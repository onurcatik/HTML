### Konu 3 - HTML Girintileme

**👉** Girintileme, bir kod satırının başındaki boşlukları ifade eder. HTML belgelerinde kodu daha okunabilir ve anlaşılır hale getirmek için girintileme önemlidir. Doğru girintileme, belgelerin bakımı ve geliştirilmesi sırasında büyük kolaylık sağlar.

### Girintileme Örnekleri

Aşağıda, girintilemenin etkisini ve önemini gösteren kapsamlı bir örnek bulacaksınız. Bu örnek, karmaşık bir HTML belgesinin girintisiz ve girintili versiyonlarını içermektedir.

#### Girintileme Olmadan

```html
<!DOCTYPE html>
<html>
<head>
<title>My Web Page</title>
<link rel="stylesheet" type="text/css" href="styles.css">
<script src="script.js"></script>
</head>
<body>
<header>
<h1>Welcome to My Web Page</h1>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="about.html">About</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</nav>
</header>
<main>
<article>
<h2>About Us</h2>
<p>We are a web development company.</p>
</article>
<section>
<h2>Our Services</h2>
<ul>
<li>Web Design</li>
<li>Web Development</li>
<li>SEO Optimization</li>
</ul>
</section>
</main>
<footer>
<p>&copy; 2024 My Web Page</p>
</footer>
</body>
</html>
```

#### Girintileme ile

```html
<!DOCTYPE html>
<html>
    <head>
        <title>My Web Page</title>
        <link rel="stylesheet" type="text/css" href="styles.css">
        <script src="script.js"></script>
    </head>
    <body>
        <header>
            <h1>Welcome to My Web Page</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <article>
                <h2>About Us</h2>
                <p>We are a web development company.</p>
            </article>
            <section>
                <h2>Our Services</h2>
                <ul>
                    <li>Web Design</li>
                    <li>Web Development</li>
                    <li>SEO Optimization</li>
                </ul>
            </section>
        </main>
        <footer>
            <p>&copy; 2024 My Web Page</p>
        </footer>
    </body>
</html>
```

### Girintilemenin Önemi

Girintileme, kodun yapısını ve hiyerarşisini görsel olarak temsil etmeye yardımcı olur. Bu, özellikle karmaşık belgeler ve kod blokları ile çalışırken önemlidir. Aşağıda girintilemenin neden önemli olduğuna dair bazı ana noktalar bulunmaktadır:

1. **Okunabilirlik**: Girintileme, kodun mantıksal yapısını ortaya koyar ve okunabilirliğini artırır.
2. **Bakım Kolaylığı**: Girintili kodlar, hata ayıklamayı ve bakımı kolaylaştırır. Bir hata olduğunda veya yeni bir özellik eklenmek istendiğinde, doğru girintileme ile hangi kod bloklarının hangi işlevleri içerdiğini anlamak daha kolaydır.
3. **Standartlara Uyumluluk**: Çoğu kodlama standardı ve en iyi uygulama rehberi, girintilemenin kullanılmasını önerir.
4. **İşbirliği**: Ekip çalışması sırasında, farklı geliştiriciler aynı kod üzerinde çalıştıklarında, standart girintileme kuralları kodun tutarlılığını sağlar.

### Girintileme Kuralları

HTML'de doğru girintileme yaparken bazı temel kurallara uymak gereklidir:

- **Her Etiket İçin Girinti**: Her iç içe geçen etiket için bir girinti seviyesine ekleyin.
- **Tutarlılık**: Girintilemede tutarlılık önemlidir. Genellikle bir sekme veya iki boşluk kullanılabilir, ancak bir projede hangisi seçildiyse ona sadık kalınmalıdır.
- **Doğru Kapatma**: Açılış etiketleri ve kapanış etiketleri aynı hiyerarşi seviyesinde olmalıdır.

### Sonuç

Girintileme, HTML kodlamasında önemli bir yere sahiptir. Kodun okunabilirliği, bakım kolaylığı ve ekip çalışması gibi konularda büyük avantajlar sağlar. Yukarıdaki örnekler ve kurallar doğrultusunda, HTML belgelerinizi daha düzenli ve profesyonel hale getirebilirsiniz.

Bu makale, HTML girintilemenin önemini ve uygulanabilirliğini kapsamlı bir şekilde açıklamaktadır. Kod yazarken bu prensiplere dikkat etmek, geliştiricilerin işlerini kolaylaştırır ve daha kaliteli yazılımlar üretmelerine katkı sağlar.