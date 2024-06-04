## HTML Stil Özellikleri: Kapsamlı ve Detaylı Bir Örnek

HTML `style` özelliği, HTML öğelerine çeşitli stil özellikleri eklemek için kullanılır. Bu bölümde, arka plan rengi, metin rengi ve yazı tipi özelliklerini içeren kapsamlı ve detaylı bir örnek sunacağız.

### 1. HTML Dosyasının Temel Yapısı

Öncelikle, örnek HTML dosyamızın temel yapısını oluşturalım:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Stil Özellikleri Örneği</title>
</head>
<body>

    <!-- Burada örneklerimizi ekleyeceğiz -->

</body>
</html>
```

### 2. Arka Plan Rengi

CSS `background-color` özelliği, bir HTML öğesi için arka plan rengini tanımlar. İşte bir örnek:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Stil Özellikleri Örneği</title>
</head>
<body>

    <div style="background-color: lightblue;">
        Bu div elemanının arka plan rengi açık mavidir.
    </div>

</body>
</html>
```

Bu örnekte, `div` öğesi `background-color` özelliği ile stilize edilmiştir. Arka plan rengi açık mavi olarak ayarlanmıştır.

### 3. Metin Rengi

CSS `color` özelliği, bir HTML öğesi için metin rengini tanımlar. İşte bir örnek:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Stil Özellikleri Örneği</title>
</head>
<body>

    <div style="background-color: lightblue;">
        Bu div elemanının arka plan rengi açık mavidir.
    </div>
    <p style="color: red;">
        Bu paragrafın metin rengi kırmızıdır.
    </p>

</body>
</html>
```

Bu örnekte, `p` öğesi `color` özelliği ile stilize edilmiştir. Metin rengi kırmızı olarak ayarlanmıştır.

### 4. Yazı Tipleri

CSS `font-family` özelliği, bir HTML öğesi için kullanılacak yazı tipini tanımlar. İşte bir örnek:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Stil Özellikleri Örneği</title>
</head>
<body>

    <div style="background-color: lightblue;">
        Bu div elemanının arka plan rengi açık mavidir.
    </div>
    <p style="color: red;">
        Bu paragrafın metin rengi kırmızıdır.
    </p>
    <h1 style="font-family: 'Arial', sans-serif;">
        Bu başlık Arial yazı tipini kullanır.
    </h1>

</body>
</html>
```

Bu örnekte, `h1` öğesi `font-family` özelliği ile stilize edilmiştir. Yazı tipi Arial olarak ayarlanmıştır.

### 5. Birden Fazla Stil Özelliği Uygulama

Bir HTML öğesine birden fazla stil özelliği uygulamak için her özelliği noktalı virgülle ayırarak `style` özniteliğinde tanımlayabiliriz:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Stil Özellikleri Örneği</title>
</head>
<body>

    <div style="background-color: lightblue; color: white; font-family: 'Verdana', sans-serif; padding: 20px;">
        Bu div elemanı açık mavi arka plan rengi, beyaz metin rengi ve Verdana yazı tipine sahiptir. Ayrıca 20 piksel iç boşluk uygulanmıştır.
    </div>

</body>
</html>
```

Bu örnekte, `div` öğesine birden fazla stil özelliği uygulanmıştır: `background-color`, `color`, `font-family` ve `padding`.

### 6. Tamamlanmış Örnek

Son olarak, tüm stil özelliklerini tek bir örnekte birleştirelim:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Stil Özellikleri Örneği</title>
</head>
<body>

    <div style="background-color: lightblue;">
        Bu div elemanının arka plan rengi açık mavidir.
    </div>
    <p style="color: red;">
        Bu paragrafın metin rengi kırmızıdır.
    </p>
    <h1 style="font-family: 'Arial', sans-serif;">
        Bu başlık Arial yazı tipini kullanır.
    </h1>
    <div style="background-color: lightgreen; color: darkblue; font-family: 'Tahoma', sans-serif; padding: 15px;">
        Bu div elemanı açık yeşil arka plan rengi, koyu mavi metin rengi ve Tahoma yazı tipine sahiptir. Ayrıca 15 piksel iç boşluk uygulanmıştır.
    </div>

</body>
</html>
```

Bu tamamlanmış örnekte, çeşitli HTML öğelerine farklı stil özellikleri uygulanmıştır. Bu, HTML öğelerini stilize etmenin temellerini anlamanıza yardımcı olacaktır. Daha fazla stil özelliği ve gelişmiş stil teknikleri için CSS belgelerine başvurabilirsiniz.