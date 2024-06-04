### Konu 4 - HTML - Bir PDF'yi Gömme

**👉** Bir PDF'yi bir HTML belgesine gömmek için üç yöntem vardır: `embed` etiketi, `iframe` etiketi ve `object` etiketi kullanmak.

### 1. Embed Etiketi Kullanarak Bir PDF'yi Gömme

HTML belgesine bir PDF dosyası gömmek için en yaygın kullanılan yöntemlerden biri `embed` etiketini kullanmaktır. `embed` etiketi, bir dış kaynağı (genellikle medya dosyaları) bir web sayfasına yerleştirmek için kullanılır.

#### Örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Embed Etiketi ile PDF Gömmek</title>
</head>
<body>
    <h1>Bir PDF'yi embed etiketi ile gömme</h1>
    <embed src="example.pdf" width="600" height="400" type="application/pdf">
</body>
</html>
```

**Açıklama:**
- `src` özniteliği gömülecek PDF dosyasının yolunu belirtir.
- `width` ve `height` öznitelikleri, gömülü PDF'nin boyutlarını ayarlamak için kullanılır.
- `type` özniteliği ise dosyanın türünü belirtir; bu durumda `application/pdf` kullanılır.

### 2. iframe Etiketi Kullanarak Bir PDF'yi Gömme

Bir başka yaygın yöntem de `iframe` etiketini kullanmaktır. `iframe` etiketi, bir web sayfası içinde başka bir web sayfasını gömmek için kullanılır, ancak PDF dosyalarını gömmek için de kullanılabilir.

#### Örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <title>iframe Etiketi ile PDF Gömmek</title>
</head>
<body>
    <h1>Bir PDF'yi iframe etiketi ile gömme</h1>
    <iframe src="example.pdf" width="600" height="400"></iframe>
</body>
</html>
```

**Açıklama:**
- `src` özniteliği yine gömülecek PDF dosyasının yolunu belirtir.
- `width` ve `height` öznitelikleri, iframe'in boyutlarını ayarlamak için kullanılır.

### 3. object Etiketi Kullanarak Bir PDF'yi Gömme

PDF dosyalarını gömmek için kullanılabilecek bir başka HTML etiketi `object` etiketidir. `object` etiketi, bir HTML belgesine dış bir kaynağı (genellikle medya dosyaları) yerleştirmek için kullanılır.

#### Örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <title>object Etiketi ile PDF Gömmek</title>
</head>
<body>
    <h1>Bir PDF'yi object etiketi ile gömme</h1>
    <object data="example.pdf" type="application/pdf" width="600" height="400">
        <p>PDF görüntüleyici yüklenemedi. PDF dosyasını <a href="example.pdf">buradan indiriniz</a>.</p>
    </object>
</body>
</html>
```

**Açıklama:**
- `data` özniteliği gömülecek PDF dosyasının yolunu belirtir.
- `type` özniteliği, dosyanın türünü belirtir.
- `width` ve `height` öznitelikleri object etiketinin boyutlarını ayarlamak için kullanılır.

### Sonuç

Bir PDF dosyasını bir HTML belgesine gömmek için üç ana yöntem bulunmaktadır: `embed`, `iframe` ve `object` etiketleri. Her bir yöntem farklı durumlar için uygun olabilir ve ihtiyaçlarınıza en uygun yöntemi seçerek kullanabilirsiniz. Bu yöntemlerle web sayfanızda kullanıcılarınıza PDF dosyalarını kolayca gösterebilirsiniz.

#### Detaylı Örnek

Aşağıda, üç yöntemi de içeren kapsamlı bir HTML örneği verilmiştir:

```html
<!DOCTYPE html>
<html>
<head>
    <title>PDF Gömmek İçin Yöntemler</title>
</head>
<body>
    <h1>PDF Gömmek İçin Üç Yöntem</h1>

    <h2>Embed Etiketi</h2>
    <embed src="example.pdf" width="600" height="400" type="application/pdf">

    <h2>iframe Etiketi</h2>
    <iframe src="example.pdf" width="600" height="400"></iframe>

    <h2>object Etiketi</h2>
    <object data="example.pdf" type="application/pdf" width="600" height="400">
        <p>PDF görüntüleyici yüklenemedi. PDF dosyasını <a href="example.pdf">buradan indiriniz</a>.</p>
    </object>
</body>
</html>
```

Bu örnek, her üç yöntemi de kullanarak bir PDF dosyasını HTML belgesine gömme işlemini göstermektedir. Bu yöntemlerden hangisinin kullanılacağı, uygulama gereksinimlerinize ve kullanıcı deneyimine bağlı olarak değişebilir.