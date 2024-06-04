# Konu 2 - **HTML Renkleri**

**👉** HTML'de, bir renk bir renk adı kullanılarak belirtilebilir:

## Arka Plan Rengi

HTML öğeleri için arka plan rengini ayarlamak, web sayfalarınızı görsel olarak daha çekici hale getirebilir. İşte bunu nasıl yapabileceğinizi gösteren bir örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Renk Örnekleri</title>
</head>
<body style="background-color: LightGray;">

    <h1 style="background-color: DodgerBlue; color: white;">Başlık 1</h1>
    <p style="background-color: Yellow; color: black;">
        Bu bir paragraf örneğidir. Arka plan rengi sarı, metin rengi ise siyah olarak ayarlanmıştır.
    </p>

</body>
</html>
```

Yukarıdaki kodda:
- `<body>` etiketi için arka plan rengi `LightGray` olarak ayarlanmıştır.
- `<h1>` etiketi için arka plan rengi `DodgerBlue`, metin rengi ise `white` olarak ayarlanmıştır.
- `<p>` etiketi için arka plan rengi `Yellow`, metin rengi ise `black` olarak ayarlanmıştır.

## Metin Rengi

HTML'de metin rengini ayarlamak, içeriklerinizin daha okunabilir ve estetik olmasını sağlar. İşte bir örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Renk Örnekleri</title>
</head>
<body>

    <h1 style="color: DodgerBlue;">Başlık 1</h1>
    <p style="color: Red;">
        Bu bir paragraf örneğidir. Metin rengi kırmızı olarak ayarlanmıştır.
    </p>

</body>
</html>
```

Yukarıdaki kodda:
- `<h1>` etiketi için metin rengi `DodgerBlue` olarak ayarlanmıştır.
- `<p>` etiketi için metin rengi `Red` olarak ayarlanmıştır.

## Sınır Rengi

HTML öğelerine sınır eklemek ve bu sınırların rengini ayarlamak, sayfa düzeninizin daha belirgin olmasını sağlar. İşte bir örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Renk Örnekleri</title>
</head>
<body>

    <h1 style="border: 2px solid DodgerBlue;">Başlık 1</h1>
    <p style="border: 2px solid Red; padding: 10px;">
        Bu bir paragraf örneğidir. Sınır rengi kırmızı olarak ayarlanmış ve içerik 10 piksel içeri itilmiştir.
    </p>

</body>
</html>
```

Yukarıdaki kodda:
- `<h1>` etiketi için sınır `2px solid DodgerBlue` olarak ayarlanmıştır.
- `<p>` etiketi için sınır `2px solid Red` olarak ayarlanmıştır ve `padding` özelliği ile içeriğin kenarlardan 10 piksel içeri itilmesi sağlanmıştır.

## Birleştirilmiş Örnek

Şimdi, yukarıdaki tüm özellikleri birleştirerek daha kapsamlı bir örnek oluşturalım:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Renk Örnekleri</title>
    <style>
        body {
            background-color: LightGray;
        }
        .header {
            background-color: DodgerBlue;
            color: white;
            border: 2px solid navy;
            padding: 10px;
            text-align: center;
        }
        .content {
            background-color: yellow;
            color: black;
            border: 2px solid green;
            padding: 10px;
            margin: 10px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Başlık 1</h1>
    </div>
    <div class="content">
        <p>
            Bu bir paragraf örneğidir. Arka plan rengi sarı, metin rengi siyah olarak ayarlanmış ve sınır rengi yeşildir.
        </p>
    </div>

</body>
</html>
```

Yukarıdaki kodda:
- `body` etiketi için arka plan rengi `LightGray` olarak ayarlanmıştır.
- `.header` sınıfı için arka plan rengi `DodgerBlue`, metin rengi `white`, sınır rengi `navy`, içeri boşluk `padding` 10 piksel ve metin hizalaması `center` olarak ayarlanmıştır.
- `.content` sınıfı için arka plan rengi `yellow`, metin rengi `black`, sınır rengi `green`, içeri boşluk `padding` 10 piksel ve kenar boşluğu `margin` 10 piksel olarak ayarlanmıştır.

Bu kapsamlı örnek, HTML'de renklerin nasıl kullanılabileceğini ve çeşitli özelliklerle nasıl kombinlenebileceğini göstermektedir. Web sayfalarının görsel çekiciliğini artırmak ve kullanıcı deneyimini iyileştirmek için renklerin doğru kullanımı önemlidir.