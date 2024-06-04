### HTML <!DOCTYPE> Deklarasyonu Hakkında Kapsamlı ve Detaylı Bir Örnek

#### Giriş
HTML belgelerinin tarayıcılar tarafından doğru bir şekilde işlenmesi için `<!DOCTYPE>` deklarasyonunun nasıl kullanıldığını ve önemini anlamak, web geliştiricileri için kritik bir öneme sahiptir. Aşağıda, `<!DOCTYPE>` deklarasyonunun kullanımını gösteren kapsamlı ve detaylı bir örnek sunulmuştur.

#### Adım Adım Örnek

##### 1. Temel HTML5 Belgesi

HTML5 kullanarak basit bir web sayfası oluşturmak için, ilk olarak `<!DOCTYPE>` deklarasyonunu ekleyerek başlarız. Bu deklarasyon, tarayıcıya belgenin HTML5 standardına uygun olduğunu belirtir.

**Örnek:**
```html
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basit Bir HTML5 Belgesi</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu, HTML5 ile oluşturulmuş basit bir web sayfasıdır.</p>
</body>
</html>
```

**Açıklama:**
- `<!DOCTYPE html>`: Bu deklarasyon, tarayıcıya belgenin HTML5 standardına uygun olduğunu belirtir.
- `<html lang="tr">`: HTML belgesinin dilini belirtir. Burada dil Türkçe olarak ayarlanmıştır.
- `<meta charset="UTF-8">`: Belgenin karakter setini belirtir. UTF-8, geniş bir karakter yelpazesini destekler.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Mobil cihazlarda sayfanın düzgün görüntülenmesini sağlar.
- `<title>`: Sayfanın başlığını belirtir.
- `<body>`: Sayfanın ana içeriğini barındırır.

##### 2. Eski HTML Sürümlerinde `<!DOCTYPE>` Kullanımı

HTML5'ten önceki HTML sürümlerinde `<!DOCTYPE>` deklarasyonları daha karmaşıktı. İşte HTML4.01 ve XHTML1.0 için `<!DOCTYPE>` deklarasyonlarının nasıl kullanıldığına dair örnekler.

**HTML4.01 Strict:**
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>HTML4.01 Belgesi</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu, HTML4.01 Strict ile oluşturulmuş bir web sayfasıdır.</p>
</body>
</html>
```

**XHTML1.0 Strict:**
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="tr" lang="tr">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
    <title>XHTML1.0 Belgesi</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
    <p>Bu, XHTML1.0 Strict ile oluşturulmuş bir web sayfasıdır.</p>
</body>
</html>
```

**Açıklama:**
- HTML4.01 ve XHTML1.0 için kullanılan `<!DOCTYPE>` deklarasyonları, belgenin hangi tür olduğunu ve hangi DTD'yi (Document Type Definition) kullandığını belirler.
- XHTML belgelerinde, XML kurallarına uyulması gerektiğinden, `<html>` etiketinde ek özellikler bulunur.

##### 3. Uygulama ve Test

Yukarıdaki örnekleri tarayıcınızda açarak `<!DOCTYPE>` deklarasyonunun nasıl çalıştığını ve tarayıcının belgeyi nasıl işlediğini gözlemleyebilirsiniz. 

##### Sonuç

`<!DOCTYPE>` deklarasyonu, HTML belgelerinin doğru ve tutarlı bir şekilde işlenmesi için kritik bir bileşendir. HTML5 ile bu deklarasyonun basitleştirilmiş olması, web geliştiricileri için önemli bir avantaj sağlar. Tüm HTML belgelerinizde `<!DOCTYPE>` deklarasyonunu kullanmak, belgelerinizin geçerli ve tarayıcılarla uyumlu olmasını sağlayacaktır.

---

Bu örnek, `<!DOCTYPE>` deklarasyonunun HTML belgelerindeki kullanımını ve önemini detaylı bir şekilde açıklamaktadır. Bu bilgiler, web geliştiricileri için temel bir referans niteliği taşımaktadır.