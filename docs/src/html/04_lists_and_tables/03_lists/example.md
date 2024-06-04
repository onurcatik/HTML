# Konu 3 - **HTML Listeleri**

HTML listeleri, web geliştiricilerin ilgili öğeleri listeler halinde gruplandırmalarını sağlar. Bu bölümde, sırasız, sıralı ve tanım listelerinin nasıl oluşturulacağını ve kullanılacağını detaylı bir örnek ile inceleyeceğiz.

## **👉** Sırasız HTML Listesi

Sırasız listeler, öğelerin belirli bir sıraya ihtiyaç duymadığı durumlarda kullanılır. Bu listeler varsayılan olarak madde işaretleriyle (küçük siyah daireler) gösterilir.

### Sırasız Liste Örneği

Aşağıdaki örnekte, bir web sayfasında görüntülenmek üzere bir sırasız liste oluşturacağız. Bu liste, alışveriş yapılacak öğeleri içerecek.

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sırasız Liste Örneği</title>
</head>
<body>
    <h2>Alışveriş Listesi</h2>
    <ul>
        <li>Ekmek</li>
        <li>Süt</li>
        <li>Yumurta</li>
        <li>Meyve</li>
    </ul>
</body>
</html>
```

Bu kod parçası, bir başlık (`<h2>`) ve bir sırasız liste (`<ul>`) içerir. Her bir öğe (`<li>`) alışveriş listesinde yer alır.

## Sıralı HTML Listesi

Sıralı listeler, öğelerin belirli bir sıraya sahip olması gerektiğinde kullanılır. Bu listeler varsayılan olarak numaralarla gösterilir.

### Sıralı Liste Örneği

Aşağıdaki örnekte, bir tarifin adımlarını göstermek için sıralı bir liste oluşturacağız.

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sıralı Liste Örneği</title>
</head>
<body>
    <h2>Kek Tarifi</h2>
    <ol>
        <li>Fırını 180 dereceye ısıtın.</li>
        <li>Yumurta ve şekeri çırpın.</li>
        <li>Un ve kabartma tozunu ekleyin.</li>
        <li>Karışımı yağlanmış kalıba dökün.</li>
        <li>Fırında 35 dakika pişirin.</li>
    </ol>
</body>
</html>
```

Bu kod parçası, bir başlık (`<h2>`) ve bir sıralı liste (`<ol>`) içerir. Her bir öğe (`<li>`) kek tarifinin adımlarını sırasıyla gösterir.

## HTML Tanım Listeleri

Tanım listeleri, terimlerin ve her terimin açıklamasının bulunduğu listelerdir. Bu listeler, genellikle sözlük veya terim listeleri gibi yapılandırılmış bilgileri göstermek için kullanılır.

### Tanım Listesi Örneği

Aşağıdaki örnekte, web geliştirme terimlerini ve açıklamalarını içeren bir tanım listesi oluşturacağız.

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanım Listesi Örneği</title>
</head>
<body>
    <h2>Web Geliştirme Terimleri</h2>
    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language: Web sayfaları oluşturmak için kullanılan standart dildir.</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets: Web sayfalarının görünümünü düzenlemek için kullanılan stil dilidir.</dd>
        <dt>JavaScript</dt>
        <dd>Dinamik ve etkileşimli web içerikleri oluşturmak için kullanılan programlama dilidir.</dd>
    </dl>
</body>
</html>
```

Bu kod parçası, bir başlık (`<h2>`) ve bir tanım listesi (`<dl>`) içerir. Her terim (`<dt>`) ve açıklaması (`<dd>`) web geliştirme ile ilgili bilgileri sunar.

### Özet

HTML listeleri, sırasız (`<ul>`), sıralı (`<ol>`) ve tanım (`<dl>`) listeleri olmak üzere üç ana türde gelir. Her biri, farklı bilgi gruplarını düzenlemek için kullanılır ve uygun etiketlerle yapılandırılır. Yukarıdaki örnekler, bu listelerin nasıl oluşturulacağını ve kullanılacağını göstermektedir. Geliştiriciler, bu kuralları ve yapıları takip ederek daha düzenli ve anlaşılır web sayfaları oluşturabilirler.