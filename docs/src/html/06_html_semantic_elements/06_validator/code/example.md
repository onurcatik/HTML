# Konu 6 - HTML Doğrulayıcı

## Giriş

W3C (World Wide Web Consortium) doğrulaması, bir web sitesinin kodunun biçimlendirme standartlarına uyup uymadığını kontrol etme sürecidir. HTML doğrulayıcıları, web geliştiricilerinin HTML belgelerinin doğru yapılandırıldığını ve W3C standartlarına uygun olduğunu kontrol etmelerine yardımcı olur. Bu, web sayfalarının tarayıcılarda doğru görüntülenmesini ve erişilebilirlik açısından en iyi uygulamaları takip etmesini sağlar.

## HTML Doğrulayıcı Kullanımı

Aşağıda, bir HTML doğrulayıcının nasıl kullanılacağını gösteren ayrıntılı bir örnek bulunmaktadır. Bu örnek, basit bir HTML belgesinin doğrulama sürecini kapsamaktadır.

### Adım 1: HTML Kodunu Giriş Alanına Yapıştırma

Öncelikle, doğrulamak istediğiniz HTML kodunu doğrulayıcının giriş alanına yapıştırmanız gerekmektedir. İşte basit bir HTML belgesi örneği:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Doğrulayıcı Örneği</title>
</head>
<body>
    <header>
        <h1>Hoş Geldiniz!</h1>
    </header>
    <main>
        <section>
            <h2>HTML Doğrulayıcı</h2>
            <p>W3C doğrulaması, bir web sitesinin kodunun biçimlendirme standartlarına uyup uymadığını kontrol etme sürecidir.</p>
        </section>
        <section>
            <h2>Örnek Kod</h2>
            <pre>
<code>
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Validator</title>
</head>
<body>
    <h1>HTML Validator</h1>
    <p>W3C validation is the process of checking a website's code to determine if it follows the formatting standards.</p>
</body>
</html>
</code>
            </pre>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 HTML Doğrulama Örneği</p>
    </footer>
</body>
</html>
```

Bu örnek, temel HTML etiketlerini içeren basit bir web sayfasını temsil eder.

### Adım 2: Doğrulama İşlemini Başlatma

HTML kodunu giriş alanına yapıştırdıktan sonra, doğrulama işlemini başlatmak için "Check" (Kontrol Et) düğmesine tıklayın. Bu işlem, HTML kodunuzun W3C standartlarına uygun olup olmadığını kontrol eder.

### Adım 3: Çıktıyı İnceleme

Doğrulayıcı, HTML kodunuzu analiz ettikten sonra sonuçları gösterecektir. Kodunuzda hata veya uyarı yoksa, aşağıdaki gibi bir mesaj alırsınız:

```plaintext
Document checking completed. No errors or warnings to show.
```

Bu mesaj, HTML kodunuzun W3C standartlarına uygun olduğunu ve herhangi bir sorun bulunmadığını gösterir.

Eğer kodunuzda hatalar veya uyarılar varsa, doğrulayıcı bu sorunları listeleyecek ve hataların hangi satırlarda olduğunu belirtecektir. Bu sayede, hataları düzeltmek ve kodunuzu standartlara uygun hale getirmek için gerekli adımları atabilirsiniz.

### Doğrulama Raporunun Anlamı

Doğrulama raporu, HTML kodunun doğru yapılandırıldığını ve W3C standartlarına uygun olduğunu belirten bir geri bildirim sağlar. Bu, web sayfanızın tüm tarayıcılarda tutarlı bir şekilde görüntüleneceğini ve erişilebilirlik açısından en iyi uygulamalara uyacağını garanti eder.

### Örnek Çıktı

Aşağıda, doğrulayıcıdan alınan örnek bir çıktı bulunmaktadır:

```plaintext
Document checking completed. No errors or warnings to show.

Source
1. <!DOCTYPE html>
2. <html lang="en">
3. <head>
4.     <title>HTML Validator</title>
5. </head>
6. <body>
7.     <h1>HTML Validator</h1>
8.     <p>W3C validation is the process of checking a website's code to determine if it follows the formatting standards.</p>
9. </body>
10. </html>

Used the HTML parser.
Total execution time 2 milliseconds.
```

Bu örnek çıktı, doğrulayıcı tarafından kontrol edilen HTML kodunun herhangi bir hata veya uyarı içermediğini ve standartlara uygun olduğunu göstermektedir.

## Neden W3C Doğrulaması Kullanılmalı?

W3C doğrulaması, web geliştiricilerinin ve tasarımcılarının web sayfalarının kalitesini ve uyumluluğunu sağlamalarına yardımcı olur. İşte W3C doğrulamasının bazı önemli nedenleri:

- **Uyumluluk**: Web sayfalarının farklı tarayıcılarda ve cihazlarda tutarlı bir şekilde görüntülenmesini sağlar.
- **Erişilebilirlik**: Web sayfalarının erişilebilirlik standartlarına uygun olmasını sağlar, böylece daha geniş bir kullanıcı kitlesine ulaşabilir.
- **Bakım Kolaylığı**: Doğru ve standartlara uygun kod, bakım ve güncellemeleri kolaylaştırır.
- **SEO**: Temiz ve standartlara uygun kod, arama motoru optimizasyonunu (SEO) iyileştirir.

## Sonuç

HTML doğrulayıcıları, web geliştiricilerinin ve tasarımcılarının kodlarını W3C standartlarına uygun olup olmadığını kontrol etmelerine yardımcı olan önemli araçlardır. Bu doğrulayıcılar, web sayfalarının doğru çalışmasını, erişilebilirliğini ve uyumluluğunu sağlamak için kritik bir rol oynar. Web geliştirme sürecinizde HTML doğrulayıcıları kullanarak, web sitelerinizin kalitesini ve performansını artırabilirsiniz.