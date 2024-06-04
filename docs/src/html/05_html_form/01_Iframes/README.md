## HTML Iframe'ler

 Bir HTML iframe, bir web sayfasını başka bir web sayfası içinde görüntülemek için kullanılır.

### HTML Iframe Sözdizimi

- HTML `<iframe>` etiketi, mevcut HTML belgesi içinde başka bir belge yerleştirmek için kullanılır.

### Iframe - Yükseklik ve Genişlik Ayarlama

- Iframe'in boyutunu belirtmek için `height` ve `width` özniteliklerini kullanın.
- Yükseklik ve genişlik varsayılan olarak piksel cinsindendir:

```html
<!DOCTYPE html>
<html>
<body>
<h2>HTML Iframe</h2>
<iframe 
    src="https://google.com" 
    height="300" 
    width="340" 
    title="Iframe Example">
</iframe>
</body>
</html>
```

### Detaylı Açıklama ve Düzeltmeler

Bir iframe kullanarak başka bir web sayfasını kendi web sayfanızda görüntüleyebilirsiniz. Bu, özellikle harici içerikleri entegre etmek için faydalıdır. Örneğin, bir harita, bir video veya başka bir web sayfasının belirli bir bölümü iframe kullanılarak gömülebilir.

Yukarıdaki örnekte, bir iframe oluşturulmuş ve `src` özniteliği ile Google'ın ana sayfası iframe içine yerleştirilmiştir. Burada dikkat edilmesi gereken önemli noktalar vardır:

1. Güvenlik ve İçerik Politikaları: Tüm web siteleri iframe içinde görüntülenmeye izin vermez. Güvenlik politikaları nedeniyle bazı siteler iframe kullanılarak gömülemez. Bu durumda tarayıcılar içerik politikasına bağlı olarak bu içeriği engelleyebilir.
2. Boyutlandırma: Iframe'in boyutu, `height` ve `width` öznitelikleri kullanılarak ayarlanır. Bu özniteliklerin değerleri varsayılan olarak piksel (px) cinsindendir. Örneğin, yukarıdaki örnekte iframe'in yüksekliği 300 piksel, genişliği ise 340 piksel olarak ayarlanmıştır.
3. Erişilebilirlik: Iframe'ler erişilebilirlik açısından uygun şekilde kullanılmalıdır. `title` özniteliği, iframe içeriğinin ne olduğunu açıklayan bir bilgi sağlar ve ekran okuyucular tarafından kullanılabilir.
4. Yanıt Verme: Mobil cihazlar ve farklı ekran boyutlarına uyum sağlamak için iframe boyutlandırmasını duyarlı (responsive) hale getirmek önemlidir. CSS kullanarak iframe'in genişlik ve yüksekliğini esnek hale getirebilirsiniz.

### Örnek

Aşağıda, duyarlı bir iframe oluşturmak için CSS ile birlikte nasıl kullanabileceğinize dair bir örnek bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<head>
<style>
.responsive-iframe {
    position: relative;
    overflow: hidden;
    width: 100%;
    padding-top: 56.25%; /* 16:9 Aspect Ratio */
}
.responsive-iframe iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>
</head>
<body>
<h2>Responsive HTML Iframe</h2>
<div class="responsive-iframe">
    <iframe 
        src="https://google.com" 
        title="Iframe Example">
    </iframe>
</div>
</body>
</html>
```

- Bu örnekte, iframe duyarlı hale getirilmiştir ve ekran boyutuna göre boyutları otomatik olarak ayarlanır. 
- CSS `padding-top` hilesi, iframe'in en-boy oranını korumak için kullanılmıştır.
- İframe'ler web sayfalarında güçlü araçlar olabilir, ancak dikkatli ve bilinçli bir şekilde kullanılmaları önemlidir. 
- Güvenlik, erişilebilirlik ve kullanıcı deneyimi açısından iyi uygulamalara uymak gereklidir.
