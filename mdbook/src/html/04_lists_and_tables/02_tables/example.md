# HTML Tabloları: Kapsamlı Bir Örnek

Bu bölümde, HTML tablolarının nasıl oluşturulacağı ve çeşitli özelliklerinin nasıl kullanılacağı hakkında kapsamlı bir örnek sunulacaktır. Bu örnek, HTML tablolarının temel yapı taşlarını, stil uygulamalarını ve gelişmiş özellikleri içermektedir.

## 1. HTML Temel Tablo Yapısı

Öncelikle, temel bir HTML tablosu oluşturalım.

### Temel Tablo

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

<h2>Öğrenci Bilgileri</h2>

<table>
    <tr>
        <th>Öğrenci No</th>
        <th>Adı</th>
        <th>Soyadı</th>
        <th>Not Ortalaması</th>
    </tr>
    <tr>
        <td>1</td>
        <td>Ali</td>
        <td>Yılmaz</td>
        <td>85</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Ayşe</td>
        <td>Kaya</td>
        <td>90</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Mehmet</td>
        <td>Demir</td>
        <td>78</td>
    </tr>
</table>

</body>
</html>
```

### Açıklama

- **HTML Belgesi Yapısı**: `<!DOCTYPE html>` etiketi, belge türünü belirtir ve belgenin HTML5 ile uyumlu olduğunu gösterir.
- **Stil Etiketi**: `<style>` etiketi içinde, tablo (`table`), başlık hücresi (`th`) ve veri hücresi (`td`) için stil tanımlamaları yapılmıştır.
  - `border-collapse: collapse;` özelliği, bitişik hücrelerin kenarlıklarını birleştirir.
  - `padding: 8px;` özelliği, hücre içi boşlukları tanımlar.
  - `background-color: #f2f2f2;` özelliği, başlık hücrelerinin arka plan rengini ayarlar.
- **Başlık**: `<h2>` etiketi, "Öğrenci Bilgileri" başlığını oluşturur.
- **Tablo**: `<table>` etiketi, tablonun başlangıcını ve bitişini belirtir.
  - **Tablo Satırları ve Hücreleri**:
    - İlk satır (`<tr>`), tablo başlık hücrelerini (`<th>`) içerir: "Öğrenci No", "Adı", "Soyadı", "Not Ortalaması".
    - Diğer satırlar, veri hücrelerini (`<td>`) içerir ve her biri bir öğrencinin bilgilerini temsil eder.

## 2. Gelişmiş Tablo Özellikleri

Şimdi, tabloya daha gelişmiş özellikler ekleyelim: hücre birleştirme (`colspan`, `rowspan`), stil iyileştirmeleri ve responsif tasarım.

### Gelişmiş Tablo

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .highlight {
            background-color: #d9edf7;
        }
        @media screen and (max-width: 600px) {
            table, thead, tbody, th, td, tr {
                display: block;
            }
            th {
                display: none;
            }
            tr {
                margin-bottom: 10px;
            }
            td {
                border: none;
                border-bottom: 1px solid #ddd;
                position: relative;
                padding-left: 50%;
            }
            td:before {
                position: absolute;
                top: 0;
                left: 6px;
                width: 45%;
                padding-right: 10px;
                white-space: nowrap;
            }
            td:nth-of-type(1):before { content: "Öğrenci No"; }
            td:nth-of-type(2):before { content: "Adı"; }
            td:nth-of-type(3):before { content: "Soyadı"; }
            td:nth-of-type(4):before { content: "Not Ortalaması"; }
        }
    </style>
</head>
<body>

<h2>Gelişmiş Öğrenci Bilgileri Tablosu</h2>

<table>
    <tr>
        <th>Öğrenci No</th>
        <th>Adı</th>
        <th>Soyadı</th>
        <th>Not Ortalaması</th>
    </tr>
    <tr class="highlight">
        <td>1</td>
        <td>Ali</td>
        <td>Yılmaz</td>
        <td>85</td>
    </tr>
    <tr>
        <td rowspan="2">2</td>
        <td>Ayşe</td>
        <td>Kaya</td>
        <td>90</td>
    </tr>
    <tr>
        <td colspan="2">Birleştirilmiş Hücre</td>
        <td>85</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Mehmet</td>
        <td>Demir</td>
        <td>78</td>
    </tr>
</table>

</body>
</html>
```

### Açıklama

- **Gelişmiş Stil Etiketi**:
  - `font-family: Arial, sans-serif;` özelliği, tablo metninin yazı tipini belirler.
  - `.highlight` sınıfı, belirli satırları vurgulamak için kullanılır.
  - **Medya Sorguları**: `@media screen and (max-width: 600px)` bloğu, ekran genişliği 600 pikselden az olduğunda tabloyu daha mobil uyumlu hale getirir.
    - Tablonun ve alt elemanlarının `display: block;` özelliği ile blok elemanlarına dönüştürülmesi sağlanır.
    - `th` etiketlerinin gizlenmesi (`display: none;`).
    - `td` etiketlerinin içeriklerinin önüne ilgili başlıkların eklenmesi (`content`).

- **Hücre Birleştirme**:
  - `rowspan="2"`: İkinci satırdaki "Öğrenci No" hücresi iki satır boyunca birleşir.
  - `colspan="2"`: Üçüncü satırdaki "Adı" ve "Soyadı" hücreleri iki sütun boyunca birleşir.

Bu örnek, HTML tablolarının temel ve gelişmiş kullanımını kapsamlı bir şekilde göstermektedir. Tabloları stilize etmek ve mobil uyumlu hale getirmek için CSS kullanımı önemli bir adımdır. Hücre birleştirme gibi özellikler, tabloların daha esnek ve kullanıcı dostu olmasını sağlar.