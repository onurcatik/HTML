### Örnek: Basit Bir HTML Sayfası Oluşturma

Bu örnekte, HTML'nin temel yapısını ve özniteliklerin kullanımını gösteren basit bir web sayfası oluşturacağız. Bu sayfa, bir başlık, bir paragraf, bir resim ve bir bağlantı içerecektir.

#### Adım 1: HTML Belgesinin Temel Yapısı

```html
<!DOCTYPE html>
<html>
<head>
    <title>Basit HTML Sayfası</title>
    <meta charset="UTF-8">
    <meta name="description" content="Bu, basit bir HTML sayfası örneğidir.">
    <meta name="keywords" content="HTML, örnek, başlangıç">
    <meta name="author" content="Frontend Web Geliştirici">
</head>
<body>
    <h1>Hoş Geldiniz!</h1>
    <p>Bu, HTML öğrenmeye başlayanlar için basit bir örnektir.</p>
    <img src="example.jpg" alt="Örnek Resim" width="400" height="300">
    <p>Daha fazla bilgi için <a href="https://www.example.com" target="_blank" title="Example Sitesi">bu bağlantıyı</a> ziyaret edin.</p>
</body>
</html>
```

#### Kod Açıklamaları

- **`<!DOCTYPE html>`**: HTML5 belgesini tanımlar.
- **`<html>`**: HTML belgesinin kök öğesi.
- **`<head>`**: Belge hakkındaki meta bilgileri içerir. Başlık (`<title>`), karakter seti (`<meta charset="UTF-8">`), sayfa açıklaması (`<meta name="description">`), anahtar kelimeler (`<meta name="keywords">`), ve yazar bilgisi (`<meta name="author">`) içerir.
- **`<body>`**: Web sayfasının görünen içeriğini barındırır.

#### Öğeler ve Öznitelikler

1. **Başlık ve Paragraf**

```html
<h1>Hoş Geldiniz!</h1>
<p>Bu, HTML öğrenmeye başlayanlar için basit bir örnektir.</p>
```

- **`<h1>`**: Birinci seviye başlık, sayfanın ana başlığını belirtir.
- **`<p>`**: Paragraf, metin içeriği içerir.

2. **Resim Ekleme**

```html
<img src="example.jpg" alt="Örnek Resim" width="400" height="300">
```

- **`<img>`**: Resim öğesi, `src` özniteliği ile resim dosyasının yolunu, `alt` özniteliği ile resim için alternatif metni, `width` ve `height` öznitelikleri ile resmin boyutlarını belirtir.

3. **Bağlantı Oluşturma**

```html
<p>Daha fazla bilgi için <a href="https://www.example.com" target="_blank" title="Example Sitesi">bu bağlantıyı</a> ziyaret edin.</p>
```

- **`<a>`**: Bağlantı öğesi, `href` özniteliği ile bağlantı adresini, `target` özniteliği ile bağlantının yeni bir sekmede açılmasını, `title` özniteliği ile bağlantı hakkında ek bilgi sağlar.

Bu örnek, HTML'nin temel yapı taşlarını ve özniteliklerin nasıl kullanıldığını göstermektedir. Bu temel bilgileri kavramak, daha karmaşık web sayfaları oluşturmak için önemli bir adımdır. HTML, web geliştirme sürecinde CSS ve JavaScript gibi teknolojilerle birlikte kullanılarak zengin ve etkileşimli kullanıcı deneyimleri yaratır.
