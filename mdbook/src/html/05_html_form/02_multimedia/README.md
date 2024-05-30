# HTML Multimedya

 Web'deki multimedya, ses, müzik, videolar, filmler ve animasyonlardan oluşur.

## HTML `<video>` Elemanı

- HTML `<video>` elemanı, bir web sayfasında video göstermek için kullanılır.
- HTML'de video göstermek için `<video>` elemanını kullanın:

### Ortak Video Formatları

- Birçok video formatı mevcuttur.
- HTML tarafından desteklenen formatlar MP4, WebM ve Ogg'dur.
- YouTube tarafından önerilen format MP4'tür.

## HTML `<audio>` Elemanı

- HTML'de bir ses dosyası çalmak için `<audio>` elemanını kullanın.
- HTML `<audio>` elemanı, bir web sayfasında ses dosyası çalmak için kullanılır.

### Ortak Ses Formatları

- MP3, sıkıştırılmış kaydedilmiş müzik için en iyi formattır. MP3 terimi dijital müzikle eş anlamlı hale gelmiştir.
- Web siteniz kaydedilmiş müzikle ilgiliyse, MP3 formatını tercih edin.

## HTML YouTube Videoları

- HTML'de video oynatmanın en kolay yolu YouTube'u kullanmaktır.

## HTML'de YouTube Videosu Oynatma

➪ Videonuzu bir web sayfasında oynatmak için şunları yapın:

1. Videoyu YouTube'a yükleyin.
2. Video kimliğini not edin.
3. Web sayfanızda bir `<iframe>` elemanı tanımlayın.
4. `src` özniteliğini video URL'sine yönlendirin.
5. Oynatıcının boyutlarını belirtmek için `width` ve `height` özniteliklerini kullanın.

### HTML'de Video Göstermek İçin `<video>` Elemanı Kullanımı

HTML'de bir video göstermek için aşağıdaki örneği inceleyebilirsiniz:

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Tarayıcınız video elementini desteklemiyor.
</video>
```

### HTML'de Ses Dosyası Çalmak İçin `<audio>` Elemanı Kullanımı

Bir ses dosyasını çalmak için aşağıdaki örneği kullanabilirsiniz:

```html
<audio controls>
  <source src="audiofile.mp3" type="audio/mpeg">
  Tarayıcınız audio elementini desteklemiyor.
</audio>
```

### YouTube Videolarını HTML'de Gömme

YouTube videolarını HTML'de gömmek için aşağıdaki örneği takip edin:

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```

Bu yöntemlerle, HTML kullanarak web sayfalarınıza multimedya öğeleri ekleyebilir ve ziyaretçilerinize zengin içerikler sunabilirsiniz.
