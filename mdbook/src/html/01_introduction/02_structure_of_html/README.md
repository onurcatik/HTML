# HTML Yapısının Temel Öğeleri

## HTML Yapısının Yapısı

HTML (Hypertext Markup Language), web sayfalarının yapısını ve içeriğini tanımlamak için kullanılan bir işaretleme dilidir. HTML belgeleri, belirli bir yapı ve sözdizimi kullanılarak oluşturulur. Bu yapıyı ve temel öğeleri anlamak, etkili ve doğru web sayfaları oluşturmanın temelidir.

### 1. Doctype Bildirimi

HTML belgesinin başında yer alır ve belgenin HTML5 standardına uygun olduğunu belirtir. Doctype bildirimi, tarayıcılara belgenin hangi HTML sürümünü kullandığını bildirir.

```html
<!DOCTYPE html>
```

### 2. HTML Etiketi

HTML belgesinin kök öğesidir ve tüm diğer öğeleri kapsar. `<html>` etiketi, belgenin başlangıcını ve bitişini belirler.

```html
<html>
  <!-- Belgenin içeriği buraya gelir -->
</html>
```

### 3. Başlık (Head) Bölümü

`<head>` etiketi, belgenin meta verilerini içerir. Bu bölümdeki bilgiler tarayıcılar tarafından işlenir, ancak kullanıcıya doğrudan gösterilmez. `<head>` etiketi içinde sıkça kullanılan öğeler şunlardır:

- `<title>`: Web sayfasının başlık çubuğunda görünen başlık.
- `<meta>`: Belgenin karakter seti, yazar bilgisi, açıklama gibi meta bilgilerini tanımlar.
- `<link>`: Harici stil dosyalarına bağlantı verir.
- `<script>`: JavaScript kodları veya harici JavaScript dosyalarına bağlantı sağlar.

```html
<head>
  <title>HTML'ye Giriş</title>
  <meta charset="UTF-8">
</head>
```

### 4. Gövde (Body) Bölümü

`<body>` etiketi, belgenin görünür içeriğini içerir. Bu bölüm, kullanıcıların tarayıcıda gördüğü metinler, görüntüler, bağlantılar ve diğer içerikleri barındırır.

```html
<body>
  <!-- Web sayfasının görünür içeriği buraya gelir -->
</body>
```

### 5. Başlık Etiketi

Başlık etiketleri (`<h1>`'den `<h6>`'ya kadar), içerik başlıklarını tanımlar. `<h1>` etiketi en önemli başlığı, `<h6>` ise en az önemli başlığı belirtir.

```html
<h1>HTML Nedir?</h1>
```

### 6. Paragraf Etiketi

Paragraf etiketleri (`<p>`), metin paragraflarını tanımlar. Paragraf etiketi, metin bloğunu belirli bir yapıda sunar.

```html
<p>HTML, bir web sayfasının yapısını tanımlar.</p>
```

### Örnek HTML Belgesi

Aşağıda, yukarıda açıklanan tüm öğeleri içeren basit bir HTML belgesi örneği verilmiştir:

```html
<!DOCTYPE html>
<html>
<head>
  <title>HTML'ye Giriş</title>
  <meta charset="UTF-8">
</head>
<body>
  <h1>HTML Nedir?</h1>
  <p>HTML, bir web sayfasının yapısını tanımlar.</p>
</body>
</html>
```
