### HTML Metin Biçimlendirme - Detaylı Örnek

HTML'deki metin biçimlendirme elementlerini anlamak ve doğru bir şekilde kullanmak için, tüm elementlerin kullanıldığı kapsamlı bir örnek oluşturalım. Bu örnekte, her bir biçimlendirme elementinin nasıl kullanılacağını ve web sayfasında nasıl görüneceğini göstereceğiz.

Aşağıdaki HTML kodu, çeşitli biçimlendirme elementlerinin nasıl kullanıldığını ve sayfa üzerindeki etkilerini göstermektedir:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Metin Biçimlendirme Örnek</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, p {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>HTML Metin Biçimlendirme Örnek</h1>

        <p><b>Bu metin kalın olarak biçimlendirilmiştir.</b></p>
        <p><strong>Bu metin önemli olarak belirtilmiştir ve kalın görünür.</strong></p>
        <p><i>Bu metin italik olarak biçimlendirilmiştir.</i></p>
        <p><em>Bu metin vurgulanmış olarak belirtilmiştir ve italik görünür.</em></p>
        <p><mark>Bu metin işaretlenmiş ve sarı arka plan ile vurgulanmıştır.</mark></p>
        <p><small>Bu metin küçük boyutta görüntülenmektedir.</small></p>
        <p><del>Bu metin silinmiş olarak belirtilmiştir ve üzeri çizilmiştir.</del></p>
        <p><ins>Bu metin eklenmiş olarak belirtilmiştir ve altı çizilmiştir.</ins></p>
        <p>Bu metin içerisinde <sub>alt simge</sub> ve <sup>üst simge</sup> kullanılmıştır.</p>
    </div>
</body>
</html>
```

#### Açıklama:

1. **HTML Başlık ve Genel Ayarlar:**
    - `<!DOCTYPE html>`: Belge türünü tanımlar.
    - `<html lang="tr">`: HTML belgesinin dilini Türkçe olarak belirtir.
    - `<meta charset="UTF-8">`: Belgenin karakter setini UTF-8 olarak ayarlar.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sayfanın mobil uyumluluğunu sağlar.
    - `<title>`: Web sayfasının başlığını belirler.
    - `<style>`: CSS kullanarak sayfa tasarımını yapar.

2. **Gövde ve İçerik:**
    - `<body>`: Sayfa içeriğini içerir.
    - `<div class="container">`: İçerik kapsayıcısı. Arka plan, kenar boşlukları ve gölge gibi stiller uygulanmıştır.
    - `<h1>`: Ana başlık.
    - `<p>`: Paragraflar.

3. **Biçimlendirme Elementleri:**
    - `<b>`: Kalın metin için kullanılır.
    - `<strong>`: Önemli metin için kullanılır ve kalın görünür.
    - `<i>`: İtalik metin için kullanılır.
    - `<em>`: Vurgulanmış metin için kullanılır ve italik görünür.
    - `<mark>`: İşaretlenmiş metin için kullanılır ve sarı arka plan ile vurgulanır.
    - `<small>`: Küçük metin için kullanılır.
    - `<del>`: Silinmiş metin için kullanılır ve metnin üzeri çizilir.
    - `<ins>`: Eklenmiş metin için kullanılır ve metnin altı çizilir.
    - `<sub>`: Alt simge metin için kullanılır.
    - `<sup>`: Üst simge metin için kullanılır.

Bu örnek, HTML'de metin biçimlendirme elementlerinin nasıl kullanılacağını ve bu elementlerin web sayfasında nasıl görüneceğini kapsamlı bir şekilde göstermektedir. HTML ve CSS kombinasyonu, web sayfalarının daha görsel ve anlam açısından zengin olmasını sağlar.