Certainly! Below is a comprehensive and detailed tutorial based on the provided text, translated into Turkish. This tutorial focuses on the topic of HTML Semantic Elements.

---

# Konu 1 - **HTML Anlamsal Öğeler**

## **👉** Anlamsal Öğeler Öncesi

HTML Anlamsal Öğeler

**👉** Pek çok web sitesi, gezinme, üstbilgi ve altbilgiyi belirtmek için <div id="nav">, <div class="header">, <div id="footer"> gibi HTML kodları içerir.

**👉** HTML'de, bir web sayfasının farklı bölümlerini tanımlamak için kullanılabilecek bazı anlamsal öğeler vardır:

---

HTML'in anlamsal öğeleri, bir web sayfasının yapısını ve anlamını daha açık hale getiren belirli etiketlerdir. Anlamsal HTML, tarayıcıların ve geliştiricilerin içeriğin anlamını daha iyi anlamalarını sağlar. Bu, hem SEO (Arama Motoru Optimizasyonu) hem de erişilebilirlik açısından önemlidir. 

HTML5 ile birlikte gelen bazı önemli anlamsal öğeler şunlardır:

- `<header>`: Bir belgenin veya bir bölümün üst bilgisini tanımlar. Genellikle başlıklar, logolar, gezinme bağlantıları içerir.
- `<nav>`: Belgedeki bir gezinme bağlantıları kümesini tanımlar.
- `<section>`: Belgedeki tematik içerik bölümlerini tanımlar. Her bölüm genellikle kendi başlığına sahiptir.
- `<article>`: Bağımsız, kendine yeten içerik parçalarını tanımlar. Bir blog yazısı, haber makalesi veya forum gönderisi olabilir.
- `<aside>`: Ana içeriğe dolaylı olarak ilişkili içerik parçalarını tanımlar. Yan bilgiler, yan notlar veya reklamlar içerebilir.
- `<footer>`: Bir belgenin veya bir bölümün alt bilgisini tanımlar. Genellikle yazar bilgileri, yasal bilgiler veya iletişim bilgileri içerir.

Bu anlamsal öğeler, sayfanın yapısını daha anlamlı hale getirir ve hem insanlar hem de makineler tarafından daha iyi anlaşılmasını sağlar. Örneğin, arama motorları bu öğeleri kullanarak sayfanızın içeriğini daha iyi analiz edebilir ve sıralayabilir.

### Anlamsal Olmayan Kodlara Örnek

```html
<!DOCTYPE html>
<html>
  <body>
    <div id="nav">Gezinme</div>
    <div class="header">Üstbilgi</div>
    <div id="footer">Altbilgi</div>
  </body>
</html>
```

### Anlamsal Kodlara Örnek

```html
<!DOCTYPE html>
<html>
  <body>
    <header>Üstbilgi</header>
    <nav>Gezinme</nav>
    <section>
      <h1>HTML</h1>
      <p>HTML, Hyper Text Markup Language'ın kısaltmasıdır. HTML, Web sayfaları oluşturmak için standart biçimlendirme dilidir.</p>
    </section>
    <section>
      <h1>CSS</h1>
      <p>CSS, belge yazımında HTML veya XML ile kullanılan bir stil sayfası dilidir.</p>
    </section>
    <footer>Altbilgi</footer>
  </body>
</html>
```

Yukarıdaki örnekte, anlamsal etiketler kullanılarak bir belgenin farklı bölümleri açıkça tanımlanmıştır. Bu, belgenin okunabilirliğini ve anlamını büyük ölçüde artırır.

---

Bu eğitimde, HTML anlamsal öğelerinin önemini ve bunların nasıl kullanılacağını öğrendik. Anlamsal HTML kullanımı, web sayfalarınızın daha iyi yapılandırılmasını ve erişilebilirliğini sağlar. Gelecekteki projelerinizde bu öğeleri kullanarak daha anlamlı ve düzenli kodlar yazabilirsiniz.