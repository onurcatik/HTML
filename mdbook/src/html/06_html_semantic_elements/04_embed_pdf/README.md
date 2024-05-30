# HTML - Bir PDF'yi Gömme

Bir PDF'yi bir HTML belgesine gömmek için üç yöntem vardır.

1. Embed etiketi kullanarak.

### 1. Embed Etiketi Kullanarak Bir PDF'yi Gömme

HTML belgesine bir PDF dosyası gömmek için en yaygın kullanılan yöntemlerden biri `embed` etiketini kullanmaktır. `embed` etiketi, bir dış kaynağı (genellikle medya dosyaları) bir web sayfasına yerleştirmek için kullanılır.

Aşağıda, bir PDF dosyasını `embed` etiketi kullanarak HTML belgesine nasıl gömebileceğinizi gösteren bir örnek bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<body>
    <h1>Bir PDF'yi embed etiketi ile gömme</h1>
    <embed src="dosya.pdf" width="600" height="400" type="application/pdf">
</body>
</html>
```

Bu örnekte, `src` özniteliği gömülecek PDF dosyasının yolunu belirtir. `width` ve `height` öznitelikleri, gömülü PDF'nin boyutlarını ayarlamak için kullanılır. `type` özniteliği ise dosyanın türünü belirtir; bu durumda `application/pdf` kullanılır.

### 2. iframe Etiketi Kullanarak Bir PDF'yi Gömme

Bir başka yaygın yöntem de `iframe` etiketini kullanmaktır. `iframe` etiketi, bir web sayfası içinde başka bir web sayfasını gömmek için kullanılır, ancak PDF dosyalarını gömmek için de kullanılabilir.

Aşağıda, bir PDF dosyasını `iframe` etiketi kullanarak HTML belgesine nasıl gömebileceğinizi gösteren bir örnek bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<body>
    <h1>Bir PDF'yi iframe etiketi ile gömme</h1>
    <iframe src="dosya.pdf" width="600" height="400"></iframe>
</body>
</html>
```

Bu örnekte, `src` özniteliği yine gömülecek PDF dosyasının yolunu belirtir. `width` ve `height` öznitelikleri, iframe'in boyutlarını ayarlamak için kullanılır.

### 3. object Etiketi Kullanarak Bir PDF'yi Gömme

PDF dosyalarını gömmek için kullanılabilecek bir başka HTML etiketi `object` etiketidir. `object` etiketi, bir HTML belgesine dış bir kaynağı (genellikle medya dosyaları) yerleştirmek için kullanılır.

Aşağıda, bir PDF dosyasını `object` etiketi kullanarak HTML belgesine nasıl gömebileceğinizi gösteren bir örnek bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<body>
    <h1>Bir PDF'yi object etiketi ile gömme</h1>
    <object data="dosya.pdf" type="application/pdf" width="600" height="400">
        <p>PDF görüntüleyici yüklenemedi. PDF dosyasını <a href="dosya.pdf">buradan indiriniz</a>.</p>
    </object>
</body>
</html>
```

Bu örnekte, `data` özniteliği gömülecek PDF dosyasının yolunu belirtir. `type` özniteliği, dosyanın türünü belirtir. `width` ve `height` öznitelikleri ise object etiketinin boyutlarını ayarlamak için kullanılır.

### Sonuç

Bir PDF dosyasını bir HTML belgesine gömmek için üç ana yöntem bulunmaktadır: `embed`, `iframe` ve `object` etiketleri. Her bir yöntem farklı durumlar için uygun olabilir ve ihtiyaçlarınıza en uygun yöntemi seçerek kullanabilirsiniz. Bu yöntemlerle web sayfanızda kullanıcılarınıza PDF dosyalarını kolayca gösterebilirsiniz.
