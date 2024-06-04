# HTML Favicon

- Bir favicon, tarayıcı sekmesinde sayfa başlığının yanında görüntülenen küçük bir resimdir.

## Adım 1: HTML Dosyasını Hazırlama

Öncelikle, favicon'u tanımlayacağımız HTML dosyasını oluşturmamız gerekiyor. İşte temel bir HTML şablonu:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Favicon</title>
    <link rel="icon" type="image/jpg" href="img.jpg" />
</head>
<body>
    <h1>Onur Çatık</h1>
</body>
</html>
```

Bu kod parçasında dikkat edilmesi gereken önemli noktalar:

1. DOCTYPE Deklarasyonu: Bu, HTML5 dokümanı olduğunu belirten bir bildiridir.
2. `<html lang="en">`: HTML dilini belirtir. `en` İngilizce için kullanılır.
3. Meta Etiketleri: Karakter seti (`charset="UTF-8"`) ve görüntüleme özelliklerini (`viewport`) belirler.
4. Başlık (`<title>`): Tarayıcı sekmesinde görünecek sayfa başlığını tanımlar.
5. Favicon Etiketi (`<link rel="icon">`): Favicon dosyasının yolunu ve türünü belirtir.

## Adım 2: Favicon Dosyasını Eklemek

Favicon dosyanızı projenizin kök dizinine yerleştirin. Yukarıdaki örnekte, `img.jpg` dosyasını kullanıyoruz. Favicon dosyanızın uzantısı `ico`, `png`, `jpg`, veya `svg` olabilir.

## Favicon Türleri ve Tarayıcı Uyumluluğu

Farklı tarayıcılar farklı favicon türlerini destekleyebilir. Genellikle `.ico` dosya türü en yaygın olarak kabul edilir, ancak modern tarayıcılar `png`, `jpg`, ve `svg` türlerini de desteklemektedir. İşte çeşitli favicon türlerinin nasıl ekleneceği:

```html
<!-- ICO formatı -->
<link rel="icon" type="image/x-icon" href="favicon.ico" />

<!-- PNG formatı -->
<link rel="icon" type="image/png" href="favicon.png" />

<!-- SVG formatı -->
<link rel="icon" type="image/svg+xml" href="favicon.svg" />
```

## Favicon Dosyasının Optimizasyonu

Favicon dosyanızın boyutunu optimize etmek, web sitenizin yükleme süresini azaltmak için önemlidir. Genellikle, favicon boyutları 16x16 piksel veya 32x32 piksel olur.

## Test Etme ve Sonuç

- HTML dosyanızı kaydedin ve bir tarayıcıda açarak favicon'un doğru şekilde görüntülendiğinden emin olun.
- Tarayıcınızda sayfa başlığının yanında küçük bir resim olarak favicon'unuzu görebilmelisiniz.
- Bu adımları izleyerek web sitenize başarılı bir şekilde favicon ekleyebilirsiniz.
- Faviconlar, kullanıcı deneyimini iyileştirir ve sitenizin tanınabilirliğini artırır.