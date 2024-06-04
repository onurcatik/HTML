## Konu 1 - HTML'ye Giriş

### HTML Nedir?

- HTML, İngilizce "Hyper Text Markup Language" ifadesinin kısaltmasıdır.
- HTML, bir web sayfasının yapısını tanımlar.
- HTML öğeleri, tarayıcıya içeriği nasıl görüntüleyeceğini söyler.

### HTML Öğesi Nedir?

- Bir HTML öğesi, bir başlangıç etiketi, içerik ve bir bitiş etiketi ile tanımlanır:
- Öğeler, başlık etiketleri, resim etiketleri, paragraf etiketleri, bağlantı etiketleri vb. olabilir.

Örnek:

```html
<h1>Bu bir başlıktır</h1>
<p>Bu bir paragraftır</p>
<a href="https://www.example.com">Bu bir bağlantıdır</a>
```

### HTML Öznitelikleri

- Tüm HTML öğeleri **özniteliklere** sahip olabilir.
- Öznitelikler, öğeler hakkında **ek bilgi** sağlar.
- Öznitelikler her zaman **başlangıç etiketinde** belirtilir.
- Öznitelikler genellikle ad/değer çiftleri şeklindedir: **ad="değer"**

Örnek:

```html
<a href="https://www.example.com" title="Example">Bu bir bağlantıdır</a>
<img src="image.jpg" alt="Örnek Resim">
```

### Açıklamalı Kod Örnekleri

**1. Basit HTML Yapısı**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Örnek HTML Sayfası</title>
</head>
<body>
    <h1>Hoş Geldiniz!</h1>
    <p>Bu bir örnek HTML sayfasıdır.</p>
</body>
</html>
```

Bu kod, basit bir HTML sayfasının temel yapısını göstermektedir. Doctype, HTML5 kullanıldığını belirtir. `head` bölümü sayfanın başlık bilgisini içerir. `body` bölümü ise sayfanın asıl içeriğini barındırır.

**2. Özniteliklerin Kullanımı**

```html
<img src="image.jpg" alt="Açıklama Metni" width="500" height="600">
<a href="https://www.example.com" target="_blank">Example Sitesine Git</a>
```

Bu örneklerde, `img` etiketi bir resim ekler ve `alt`, `width`, `height` öznitelikleri ile resim hakkında ek bilgiler sağlar. `a` etiketi ise bir bağlantı oluşturur ve `href` özniteliği ile bağlantının adresini, `target` özniteliği ile bağlantının yeni bir sekmede açılmasını belirtir.

### Bilimsel ve Teknik Açıklamalar

HTML (Hyper Text Markup Language), web sayfalarının temel yapı taşıdır. Her HTML belgesi, bir dizi öğeden oluşur. Bu öğeler, tarayıcıya içerik parçalarını nasıl düzenlemesi gerektiğini bildirir. Örneğin, `<h1>` ile `<h6>` etiketleri başlıkları belirtir ve içerik hiyerarşisini oluşturur. `<p>` etiketi paragrafları tanımlar ve metni düzenler.

Öznitelikler, öğelerin işlevselliğini ve görünümünü daha spesifik hale getirir. Örneğin, `href` özniteliği bir bağlantının hedef URL'sini belirtir, `src` özniteliği ise bir resim dosyasının yolunu gösterir. Bu tür öznitelikler, HTML belgesinin etkileşimli ve kullanıcı dostu olmasını sağlar.

### Kritik İnceleme

HTML'nin doğru kullanımı, web sayfalarının erişilebilir ve etkili olmasını sağlar. Yanlış yapılandırılmış HTML, kullanıcı deneyimini olumsuz etkileyebilir ve arama motoru optimizasyonunu (SEO) düşürebilir. Ayrıca, HTML standartlarına uygun olmayan kodlar, tarayıcılar arasında uyumsuzluklara yol açabilir.

Bu nedenle, HTML yazarken dikkat edilmesi gereken en önemli noktalar:

- Etiketlerin doğru şekilde kapatılması,
- Uygun özniteliklerin kullanılması,
- HTML5 standartlarına uyulmasıdır.

HTML, web geliştirme sürecinin temelini oluşturur ve diğer teknolojiler (CSS, JavaScript) ile birlikte kullanıldığında güçlü ve dinamik web sayfaları oluşturmayı mümkün kılar.
