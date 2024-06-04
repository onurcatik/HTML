# HTML Multimedia - Detaylı ve Kapsamlı Örnek

Web sayfalarında multimedya içeriklerini etkin bir şekilde kullanmak, kullanıcı deneyimini artırmak açısından önemlidir. Bu bölümde, HTML kullanarak video ve ses dosyalarını nasıl ekleyebileceğinizi ve YouTube videolarını nasıl yerleştirebileceğinizi detaylı bir örnekle açıklayacağız.

## HTML Video Kullanımı

Bir web sayfasında video göstermek için HTML `<video>` elemanını kullanabilirsiniz. Bu eleman, çeşitli video formatlarını destekler ve tarayıcı uyumluluğunu artırmak için birden fazla kaynak dosyası belirtebilirsiniz.

### Örnek Video HTML Kodu

Aşağıda, bir web sayfasında video göstermek için kullanılan HTML kodunu bulabilirsiniz:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Video Örneği</title>
</head>
<body>
    <h1>HTML Video Örneği</h1>
    <video width="640" height="360" controls>
        <source src="movie.mp4" type="video/mp4">
        <source src="movie.webm" type="video/webm">
        <source src="movie.ogv" type="video/ogg">
        Tarayıcınız video etiketini desteklemiyor.
    </video>
</body>
</html>
```

Bu örnekte, `<video>` elemanı kullanılarak bir video dosyası gösterilmektedir. `controls` özniteliği, video oynatma kontrollerini (oynat, duraklat, ses kontrolü vb.) sağlar. Farklı kaynak dosyaları (`movie.mp4`, `movie.webm`, `movie.ogv`) belirtilerek tarayıcı uyumluluğu artırılmıştır.

## HTML Audio Kullanımı

Bir web sayfasında ses dosyası çalmak için HTML `<audio>` elemanını kullanabilirsiniz. Bu eleman, çeşitli ses formatlarını destekler ve kullanıcıya ses kontrolleri sağlar.

### Örnek Ses HTML Kodu

Aşağıda, bir web sayfasında ses dosyası çalmak için kullanılan HTML kodunu bulabilirsiniz:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Audio Örneği</title>
</head>
<body>
    <h1>HTML Audio Örneği</h1>
    <audio controls>
        <source src="audiofile.mp3" type="audio/mpeg">
        <source src="audiofile.ogg" type="audio/ogg">
        Tarayıcınız audio etiketini desteklemiyor.
    </audio>
</body>
</html>
```

Bu örnekte, `<audio>` elemanı kullanılarak bir ses dosyası çalınmaktadır. `controls` özniteliği, ses oynatma kontrollerini (oynat, duraklat, ses kontrolü vb.) sağlar. Farklı kaynak dosyaları (`audiofile.mp3`, `audiofile.ogg`) belirtilerek tarayıcı uyumluluğu artırılmıştır.

## HTML'de YouTube Videosu Gömme

HTML kullanarak web sayfanıza YouTube videoları eklemek oldukça basittir. Bu işlem için `<iframe>` elemanını kullanabilirsiniz.

### Örnek YouTube Video Gömme HTML Kodu

Aşağıda, bir web sayfasında YouTube videosu gömmek için kullanılan HTML kodunu bulabilirsiniz:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YouTube Video Gömme Örneği</title>
</head>
<body>
    <h1>YouTube Video Gömme Örneği</h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</body>
</html>
```

Bu örnekte, `<iframe>` elemanı kullanılarak bir YouTube videosu web sayfasına eklenmiştir. `src` özniteliği, YouTube video URL'sini belirtir. `width` ve `height` öznitelikleri, oynatıcının boyutlarını belirler. `allowfullscreen` özniteliği ise videonun tam ekran modunda oynatılabilmesini sağlar.

### Özet

Bu detaylı örneklerle, HTML kullanarak web sayfalarınıza video ve ses dosyalarını nasıl ekleyebileceğinizi ve YouTube videolarını nasıl gömebileceğinizi öğrendiniz. Bu bilgiler, web sitenize zengin multimedya içerikleri eklemenizi ve kullanıcı deneyimini geliştirmenizi sağlayacaktır.