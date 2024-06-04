# Konu 5 - HTML Emojileri

## **👉** Emojiler Nedir?

- Emojiler resim veya ikon gibi görünse de, aslında öyle değiller.
- UTF-8 (Unicode) karakter setinin harfleridirler (karakterler).
- Emojiler, UTF-8 karakter setinden gelen karakterlerdir: 😄 😍 💗
- Bu emojileri HTML'de görüntülemek isterseniz, ondalık (dec) veya onaltılık (hex) referansları kullanabilirsiniz.

### HTML'de Emoji Kullanımı

HTML belgelerinde emojileri kullanmak oldukça basittir. Emojiler, Unicode karakter setinin bir parçasıdır ve herhangi bir HTML belgesinde doğru karakter referansları kullanılarak görüntülenebilirler. İşte adım adım HTML'de emoji kullanımı hakkında detaylı bir açıklama:

#### 1. HTML Belgesi Oluşturma

Öncelikle, emojileri içeren bir HTML belgesi oluşturmalısınız. Aşağıda basit bir HTML belgesi örneği verilmiştir:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h2>HTML Emojileri</h2>
    &#128519; &#128522; &#128525; &#128521;
</body>
</html>
```

Bu kod, basit bir HTML belgesini temsil eder ve içinde birkaç emoji karakteri içerir. `&#128519;`, `&#128522;`, `&#128525;` ve `&#128521;` karakter referansları ile emojiler temsil edilmiştir.

#### 2. Karakter Referansları Kullanma

HTML'de emojileri görüntülemek için Unicode karakterlerinin ondalık veya onaltılık referanslarını kullanabilirsiniz. Örneğin:

- `&#128519;` ondalık (decimal) referans kullanır ve bu 😇 emojisini temsil eder.
- `&#x1F60A;` onaltılık (hexadecimal) referans kullanır ve bu 😊 emojisini temsil eder.

Bu referansları HTML içinde kullanarak istediğiniz emojiyi görüntüleyebilirsiniz. İşte başka bir örnek:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h2>HTML Emojileri</h2>
    &#128513; <!-- 😀 Gülümseyen yüz -->
    &#x1F609; <!-- 😉 Göz kırpan yüz -->
</body>
</html>
```

#### 3. UTF-8 Karakter Seti

HTML belgelerinde emojilerin doğru görüntülenebilmesi için belgenin UTF-8 karakter seti ile kodlanması gereklidir. Bu nedenle, HTML belgesinin `<head>` bölümüne aşağıdaki meta etiketi eklenmelidir:

```html
<meta charset="UTF-8">
```

Bu etiket, belgenin UTF-8 karakter seti kullanarak kodlandığını belirtir ve emojilerin doğru bir şekilde görüntülenmesini sağlar.

### Sonuç

Emojiler, HTML belgelerinde kolayca kullanılabilir ve metin içeriğine renk katabilir. Unicode karakter seti sayesinde, herhangi bir emoji, doğru karakter referansları kullanılarak HTML'de görüntülenebilir. Bu basit adımları takip ederek, HTML belgelerinize emojiler ekleyebilir ve kullanıcı deneyimini zenginleştirebilirsiniz.