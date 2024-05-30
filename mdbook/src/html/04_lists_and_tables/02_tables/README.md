# HTML Tabloları

 HTML tabloları, web geliştiricilerin verileri satırlar ve sütunlar halinde düzenlemelerine olanak tanır.

## HTML Tablosunu Tanımlama

- HTML'de bir tablo, satırlar ve sütunlar içindeki tablo hücrelerinden oluşur.

## Tablo Hücreleri

- Her tablo hücresi, `<td>` ve `</td>` etiketi ile tanımlanır.
- `td` tablo verisi anlamına gelir.
- `<td>` ve `</td>` etiketleri arasındaki her şey, tablo hücresinin içeriğidir.

## Tablo Satırları

- Her tablo satırı `<tr>` etiketi ile başlar ve `</tr>` etiketi ile sona erer.
- `tr`, tablo satırı anlamına gelir.

## Tablo Başlıkları

- Bazen hücrelerin tablo başlığı hücreleri olmasını istersiniz. Bu durumlarda `<td>` etiketi yerine `<th>` etiketini kullanın:
- `th`, tablo başlığı anlamına gelir.

### Örnek Kod

Aşağıda basit bir HTML tablosu örneği bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<style>
    table,
    th,
    td {
        border: 1px solid black;
    }
</style>

<body>
    <h2>HTML tablosu</h2>

    <table style="width: 100%">
        <tr>
            <th>Sl No:</th>
            <th>First Name</th>
            <th>Last Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Casey</td>
            <td>Fred</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Ronald</td>
            <td>Franklin</td>
        </tr>
    </table>
</body>
</html>
```

### Açıklama

Yukarıdaki örnek, temel bir HTML tablosunu göstermektedir. İşte adım adım açıklaması:

1. HTML Belgesi Yapısı: `<!DOCTYPE html>` etiketi, belge türünü belirtir ve belgenin HTML5 ile uyumlu olduğunu gösterir.

2. Stil Etiketi: `<style>` etiketi içinde, tablo (`table`), başlık hücresi (`th`) ve veri hücresi (`td`) için bir kenarlık (`border`) tanımlanmıştır. Kenarlık, siyah renkte ve 1 piksel genişliğindedir.

3. Gövde Etiketi: `<body>` etiketi, belgenin ana içeriğini içerir.

4. Başlık: `<h2>` etiketi, "HTML tablosu" başlığını oluşturur.

5. Tablo: `<table>` etiketi, tablonun başlangıcını ve `<table>` etiketinin sonunu belirtir. Tablonun genişliği `%100` olarak ayarlanmıştır.

6. Tablo Satırları ve Hücreleri:
    - İlk satır (`<tr>`), tablo başlık hücrelerini (`<th>`) içerir: "Sl No:", "First Name", "Last Name".
    - İkinci satır, veri hücrelerini (`<td>`) içerir: "1", "Casey", "Fred".
    - Üçüncü satır, başka bir veri satırını içerir: "2", "Ronald", "Franklin".

### Sonuç

Bu örnek, HTML tablolarının temel yapı taşlarını ve nasıl oluşturulacaklarını göstermektedir. Daha karmaşık tablolar için ek stil ve özellikler eklenebilir, ancak temel yapı her zaman aynı kalacaktır: `table`, `tr`, `th` ve `td` etiketleri.

Tablolar, web geliştirmede verileri düzenli ve okunabilir bir formatta sunmanın temel yöntemlerinden biridir. Tablolarla çalışırken, semantik HTML kullanmak ve stil bilgilerini ayırmak, bakım ve erişilebilirlik açısından en iyi uygulamalar arasında yer alır.
