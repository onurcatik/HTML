# Kişisel Web Sayfası Örneği

Aşağıda verilen HTML kodu, başlık, paragraf, liste, resim ve bağlantı öğelerini içeren basit bir kişisel web sayfasını göstermektedir.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Kişisel Web Sayfam</title>
  <meta charset="UTF-8">
  <meta name="description" content="Kişisel web sayfam, biyografi ve hobilerim hakkında bilgiler içerir.">
  <meta name="author" content="Adınız">
</head>
<body>
  <h1>Hoşgeldiniz!</h1>
  <p>Merhaba, benim adım [Adınız]. Bu benim kişisel web sayfam. Burada kendim hakkında bilgiler ve hobilerimi bulabilirsiniz.</p>
  
  <h2>Hakkımda</h2>
  <p>Şu an [Şehir] şehrinde yaşıyorum ve [Meslek] olarak çalışıyorum. Boş zamanlarımda çeşitli hobilerim var.</p>
  
  <h2>Hobilerim</h2>
  <ul>
    <li>Kitap okumak</li>
    <li>Yazılım geliştirmek</li>
    <li>Doğa yürüyüşleri</li>
  </ul>
  
  <h2>İletişim</h2>
  <p>Bana ulaşmak için <a href="mailto:email@ornek.com">email@ornek.com</a> adresine e-posta gönderebilirsiniz.</p>
  
  <h2>Favori Resmim</h2>
  <img src="https://via.placeholder.com/150" alt="Örnek Resim">
</body>
</html>
```

### Açıklamalar

- **Doctype Bildirimi**: `<!DOCTYPE html>` etiketi, belgenin HTML5 standardına uygun olduğunu belirtir.
- **HTML Etiketi**: `<html>` etiketi, belgenin başlangıcını ve bitişini tanımlar.
- **Başlık (Head) Bölümü**: `<head>` etiketi, meta bilgiler ve belge başlığını içerir.
  - `<title>` etiketi, tarayıcı sekmesinde görünen başlığı tanımlar.
  - `<meta charset="UTF-8">`, belgenin karakter setini tanımlar.
  - `<meta name="description" content="...">` ve `<meta name="author" content="...">` etiketleri, arama motorları ve tarayıcılar için ek bilgiler sağlar.
- **Gövde (Body) Bölümü**: `<body>` etiketi, sayfanın görünür içeriğini içerir.
  - `<h1>`, `<h2>` gibi başlık etiketleri, içeriğin başlıklarını belirtir.
  - `<p>` etiketi, paragrafları tanımlar.
  - `<ul>` ve `<li>` etiketleri, sırasız listeleri tanımlar.
  - `<a>` etiketi, bağlantıları tanımlar.
  - `<img>` etiketi, resimleri sayfaya ekler.

Bu örnek, temel HTML yapısını ve öğelerini kullanarak kişisel bir web sayfasının nasıl oluşturulabileceğini göstermektedir. HTML etiketlerinin doğru kullanımı, sayfanın yapısını belirler ve kullanıcıların bilgiyi kolayca bulmasını sağlar.
