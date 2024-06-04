# Konu 3 - HTML Başlıkları

HTML başlıkları, web sayfalarındaki içeriğin hiyerarşisini tanımlamak için kullanılır. Başlıklar, `<h1>` ile `<h6>` etiketleri arasında yer alır ve en önemliden en az önemliye doğru sıralanır. Bu etiketler, hem içeriğin kullanıcılar tarafından daha kolay anlaşılmasını sağlar hem de arama motorları tarafından içeriğin yapısını anlamada kullanılır. İşte HTML başlıklarının detaylı bir örneği:

### 1. Temel HTML Başlıkları

HTML başlık etiketleri `<h1>`'den `<h6>`'ya kadar sıralanır. Her bir başlık etiketi, metnin önem derecesine göre farklı boyut ve stil ile görüntülenir. İşte temel bir örnek:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>HTML Başlıkları Örneği</title>
</head>
<body>
    <h1>Bu bir H1 başlığıdır</h1>
    <h2>Bu bir H2 başlığıdır</h2>
    <h3>Bu bir H3 başlığıdır</h3>
    <h4>Bu bir H4 başlığıdır</h4>
    <h5>Bu bir H5 başlığıdır</h5>
    <h6>Bu bir H6 başlığıdır</h6>
</body>
</html>
```

Bu kod, tarayıcıda aşağıdaki gibi görüntülenir:

- `<h1>`: Bu bir H1 başlığıdır
- `<h2>`: Bu bir H2 başlığıdır
- `<h3>`: Bu bir H3 başlığıdır
- `<h4>`: Bu bir H4 başlığıdır
- `<h5>`: Bu bir H5 başlığıdır
- `<h6>`: Bu bir H6 başlığıdır

### 2. HTML Başlıklarının Kullanımı

HTML başlıkları, içeriğin organizasyonunu ve hiyerarşisini belirlemede kullanılır. Bir web sayfasının en üst başlığı genellikle `<h1>` etiketi ile tanımlanır ve sayfanın ana başlığını belirtir. Alt başlıklar, sırasıyla `<h2>`, `<h3>` vb. etiketleri ile tanımlanır.

### Örnek: Bir Web Sayfasının Yapılandırılması

Aşağıda, bir blog yazısı için HTML başlıklarının nasıl kullanılacağını gösteren daha karmaşık bir örnek bulunmaktadır:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>HTML Başlıkları ile Blog Yazısı</title>
</head>
<body>
    <h1>HTML Başlıkları: Kapsamlı Bir Kılavuz</h1>
    <p>Bu makale, HTML başlıklarının nasıl kullanılacağını açıklamaktadır.</p>
    
    <h2>1. Giriş</h2>
    <p>HTML başlıkları, web sayfalarının içeriğini organize etmek için kullanılır.</p>
    
    <h2>2. HTML Başlıklarının Önemi</h2>
    <p>Başlıklar, hem kullanıcı deneyimini hem de SEO'yu etkiler.</p>
    
    <h3>2.1 Kullanıcı Deneyimi</h3>
    <p>Başlıklar, içeriğin kolayca taranmasını ve anlaşılmasını sağlar.</p>
    
    <h3>2.2 SEO</h3>
    <p>Arama motorları, başlıkları içeriğin yapısını anlamak için kullanır.</p>
    
    <h2>3. HTML Başlıklarının Doğru Kullanımı</h2>
    <p>Başlıkların doğru kullanımı, içerik hiyerarşisinin doğru yansıtılmasını sağlar.</p>
    
    <h3>3.1 Sıralı Başlık Kullanımı</h3>
    <p>Başlıklar, hiyerarşik bir sırayla kullanılmalıdır.</p>
    
    <h3>3.2 Anlamlı Başlıklar</h3>
    <p>Başlıklar, içeriği doğru bir şekilde tanımlamalıdır.</p>
    
    <h2>4. Sonuç</h2>
    <p>HTML başlıkları, web geliştirme için kritik bir bileşendir.</p>
</body>
</html>
```

### Açıklama:
- `<h1>` etiketi, sayfanın ana başlığını belirtir ve genellikle sayfada bir kez kullanılır.
- `<h2>` ve alt başlıklar (`<h3>`, `<h4>`, vb.), içeriğin alt bölümlerini tanımlamak için kullanılır.
- Her başlık etiketi, metnin önem derecesini ve hiyerarşik yapısını belirtir, böylece kullanıcılar ve arama motorları içeriği daha iyi anlayabilir.

HTML başlıklarının doğru kullanımı, kullanıcı deneyimini ve arama motoru optimizasyonunu (SEO) iyileştirir. Başlıklar, web sayfasının içeriğini düzenli ve anlaşılır hale getirerek, ziyaretçilerin ve arama motorlarının sayfayı daha iyi değerlendirmesine yardımcı olur.