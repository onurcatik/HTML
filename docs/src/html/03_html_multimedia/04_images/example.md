# HTML Görselleri Kullanımı: Detaylı Örnek

## Örnek 1: Temel Görsel Ekleme

Aşağıdaki HTML kodu, temel bir web sayfasına görsel eklemenin nasıl yapılacağını göstermektedir. Bu örnekte, bir görselin nasıl doğru bir şekilde yerleştirileceği ve gerekli niteliklerin nasıl kullanılacağı açıklanmaktadır.

### HTML Kodu:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Görsel Ekleme Örneği</title>
</head>
<body>
    <h1>HTML Görsel Örneği</h1>
    <img src="https://www.example.com/path/to/image.jpg" alt="Açıklayıcı Görsel" style="width:500px;height:auto;">
    <p>Yukarıdaki görsel, HTML kullanılarak eklenmiştir.</p>
</body>
</html>
```

### Açıklama:

- `<img src="https://www.example.com/path/to/image.jpg" alt="Açıklayıcı Görsel" style="width:500px;height:auto;">`: Bu satır, bir görselin HTML sayfasına eklenmesini sağlar.
  - `src` niteliği, görselin URL'sini belirtir.
  - `alt` niteliği, görselin yüklenememesi durumunda gösterilecek alternatif metni sağlar. Ayrıca ekran okuyucuları için görseli tanımlar.
  - `style` niteliği, görselin genişliğini ve yüksekliğini ayarlamak için kullanılır. Bu örnekte genişlik 500 piksel olarak ayarlanmış ve yükseklik otomatik olarak belirlenmiştir.

## Örnek 2: Yerel Bir Görsel Ekleme

Aşağıdaki örnek, yerel bir görsel dosyasının web sayfasına nasıl ekleneceğini göstermektedir. Bu tür görseller genellikle web sunucusunda barındırılır.

### HTML Kodu:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yerel Görsel Ekleme Örneği</title>
</head>
<body>
    <h1>Yerel HTML Görsel Örneği</h1>
    <img src="images/local-image.jpg" alt="Yerel Açıklayıcı Görsel" style="width:300px;height:200px;">
    <p>Yukarıdaki görsel, yerel bir dosya olarak eklenmiştir.</p>
</body>
</html>
```

### Açıklama:

- `<img src="images/local-image.jpg" alt="Yerel Açıklayıcı Görsel" style="width:300px;height:200px;">`: Bu satır, yerel bir görsel dosyasının HTML sayfasına eklenmesini sağlar.
  - `src` niteliği, yerel dosyanın yolunu belirtir.
  - `alt` niteliği, görselin yüklenememesi durumunda gösterilecek alternatif metni sağlar.
  - `style` niteliği, görselin genişliğini ve yüksekliğini ayarlamak için kullanılır. Bu örnekte genişlik 300 piksel ve yükseklik 200 piksel olarak ayarlanmıştır.

## Örnek 3: Görselin Erişilebilirliğini Artırma

Görsellerin erişilebilirliğini artırmak için, alt metinlerin anlamlı ve açıklayıcı olması önemlidir. Aşağıdaki örnek, bir grafik veya diyagram gibi daha karmaşık görseller için ayrıntılı alt metin kullanımını göstermektedir.

### HTML Kodu:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erişilebilir Görsel Örneği</title>
</head>
<body>
    <h1>Erişilebilir HTML Görsel Örneği</h1>
    <img src="images/complex-diagram.png" alt="Bu diyagram, şirketin yıllık gelir dağılımını gösterir ve dört ana bölüme ayrılmıştır: Satış, Pazarlama, Ar-Ge ve Yönetim. Satış bölümü en büyük payı %40 ile alırken, Yönetim en küçük payı %10 ile alıyor." style="width:600px;height:auto;">
    <p>Yukarıdaki görsel, erişilebilirliği artırılmış bir alt metin ile eklenmiştir.</p>
</body>
</html>
```

### Açıklama:

- `alt` niteliği, görselin içeriğini ve amacını tam olarak açıklayan ayrıntılı bir metin içerir. Bu, özellikle görselin içerdiği bilgi veya verilerin kullanıcı tarafından anlaşılmasını sağlar.

Bu örnekler, HTML kullanarak görsellerin web sayfalarına nasıl ekleneceğini ve uygun niteliklerin nasıl kullanılacağını detaylı bir şekilde açıklamaktadır. Doğru kullanım, hem kullanıcı deneyimini iyileştirir hem de web sayfalarının erişilebilirliğini artırır.