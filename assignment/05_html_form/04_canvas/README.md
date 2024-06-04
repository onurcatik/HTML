# Konu 4 - HTML Canvas

## **👉 HTML Canvas Nedir?**

- HTML `<canvas>` öğesi, grafiklerin JavaScript ile dinamik olarak çizilmesi için kullanılır.
- `<canvas>` öğesi yalnızca grafikler için bir konteynerdir. Grafikleri gerçekten çizmek için JavaScript kullanmanız gerekir.
- Canvas, yollar, kutular, daireler, metinler çizmek ve görüntüler eklemek için çeşitli yöntemlere sahiptir.
- Canvas, bir HTML sayfasında dikdörtgen bir alandır. Varsayılan olarak, bir canvas'ın sınırı ve içeriği yoktur.
- İşaretleme (markup) şu şekilde görünür:

```html
<!DOCTYPE html>
<html>
  <body>
    <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
      Tarayıcınız HTML canvas etiketini desteklemiyor.
    </canvas>
  </body>
</html>
```

Yukarıdaki HTML kodu, "myCanvas" kimliği verilen 200 piksel genişliğinde ve 100 piksel yüksekliğinde bir `<canvas>` öğesi tanımlar. Bu canvas'ın sınırları, 1 piksel genişliğinde siyah bir çizgi ile belirlenmiştir. Eğer tarayıcı canvas etiketini desteklemiyorsa, "Tarayıcınız HTML canvas etiketini desteklemiyor." mesajı görüntülenecektir.

### **JavaScript ile Çizim**

Canvas'a çizim yapmak için JavaScript kullanmamız gerekir. Aşağıdaki örnek, canvas'a bir dikdörtgen çizmeyi gösterir:

```html
<!DOCTYPE html>
<html>
  <body>
    <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
      Tarayıcınız HTML canvas etiketini desteklemiyor.
    </canvas>

    <script>
      var canvas = document.getElementById("myCanvas");
      var ctx = canvas.getContext("2d");
      ctx.fillStyle = "#FF0000";
      ctx.fillRect(0, 0, 150, 75);
    </script>
  </body>
</html>
```

Bu JavaScript kodu, "myCanvas" kimliği ile tanımlanan canvas'ı seçer ve 2D çizim bağlamını (`getContext("2d")`) alır. `fillStyle` özelliği ile dolgu rengini kırmızıya (`#FF0000`) ayarlar ve `fillRect` yöntemi ile (0, 0) koordinatlarından başlayarak 150 piksel genişliğinde ve 75 piksel yüksekliğinde bir dikdörtgen çizer.

### **Çeşitli Çizim Yöntemleri**

Canvas API, çeşitli grafik türleri oluşturmak için birçok yöntem sunar. Örneğin:

- `fillRect(x, y, width, height)`: Dolgu ile bir dikdörtgen çizer.
- `strokeRect(x, y, width, height)`: Çerçeve ile bir dikdörtgen çizer.
- `clearRect(x, y, width, height)`: Belirtilen dikdörtgen alanı temizler.
- `beginPath()`: Yeni bir yol başlatır.
- `moveTo(x, y)`: Kalemi belirli bir noktaya taşır.
- `lineTo(x, y)`: Belirtilen noktaya bir çizgi çizer.
- `arc(x, y, radius, startAngle, endAngle, anticlockwise)`: Bir yay çizer.
- `fill()`: Geçerli yolu dolgu ile kaplar.
- `stroke()`: Geçerli yolu çerçeve ile çizer.

Bu yöntemleri kullanarak, karmaşık grafikler ve şekiller oluşturabilirsiniz. Daha fazla bilgi için MDN Web Docs gibi kaynaklara başvurabilirsiniz.

### **Canvas'a Görüntü Eklemek**

Canvas'a bir görüntü eklemek de mümkündür. Aşağıdaki örnek, bir görüntüyü nasıl yükleyip canvas'a çizeceğinizi gösterir:

```html
<!DOCTYPE html>
<html>
  <body>
    <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
      Tarayıcınız HTML canvas etiketini desteklemiyor.
    </canvas>

    <script>
      var canvas = document.getElementById("myCanvas");
      var ctx = canvas.getContext("2d");
      var img = new Image();
      img.onload = function() {
        ctx.drawImage(img, 0, 0);
      };
      img.src = 'path/to/image.jpg';
    </script>
  </body>
</html>
```

Bu kod, bir görüntü dosyasını (`path/to/image.jpg`) yükler ve yükleme tamamlandığında, `drawImage` yöntemi ile canvas'a çizer. `onload` olayı, görüntünün tamamen yüklendiğini belirttiğinde çizim işlemi gerçekleştirilir.

Canvas API'nin sunduğu zengin özellik seti, web uygulamalarında dinamik ve etkileşimli grafikler oluşturmanıza olanak tanır. Bu özellikler, sadece temel şekiller ve çizimlerle sınırlı değildir; aynı zamanda oyunlar, veri görselleştirme, animasyonlar ve daha fazlası için güçlü araçlar sunar.

### **Sonuç**

HTML Canvas, web sayfalarında dinamik grafikler oluşturmak için güçlü bir araçtır. JavaScript ile birlikte kullanıldığında, etkileşimli ve görsel olarak çekici içerikler yaratmanıza imkan tanır. Temel kavramları ve yöntemleri öğrendikten sonra, Canvas ile yapabilecekleriniz sadece hayal gücünüzle sınırlıdır.