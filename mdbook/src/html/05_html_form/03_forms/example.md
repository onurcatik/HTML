# Konu 3 - HTML Formlar

## **👉** `<input>` Elemanı

- HTML `<input>` elemanı, en çok kullanılan form elemanıdır.
- `<input>` elemanı, `type` özniteliğine bağlı olarak birçok şekilde görüntülenebilir.
- İşte bazı örnekler:

### `<input>` Elemanı Türleri

#### 1. Metin Girişi (`type="text"`)

```html
<input type="text" name="isim" placeholder="Adınızı girin">
```

- Bu tür, kullanıcıdan metin girişi almak için kullanılır.
- `placeholder` özniteliği, kullanıcıya ne tür bilgi girmesi gerektiğini belirtir.

#### 2. Şifre Girişi (`type="password"`)

```html
<input type="password" name="sifre" placeholder="Şifrenizi girin">
```

- Bu tür, kullanıcıdan şifre girişi almak için kullanılır.
- Girilen metin, gizlilik amacıyla yıldız (*) veya nokta (•) ile maskelenir.

#### 3. E-posta Girişi (`type="email"`)

```html
<input type="email" name="email" placeholder="E-posta adresinizi girin">
```

- Bu tür, kullanıcıdan e-posta adresi girişi almak için kullanılır.
- Tarayıcı, e-posta formatını doğrular.

#### 4. Sayı Girişi (`type="number"`)

```html
<input type="number" name="yas" min="0" max="100">
```

- Bu tür, kullanıcıdan sayı girişi almak için kullanılır.
- `min` ve `max` öznitelikleri, girilebilecek sayı aralığını belirler.

#### 5. Tarih Girişi (`type="date"`)

```html
<input type="date" name="dogumTarihi">
```

- Bu tür, kullanıcıdan tarih girişi almak için kullanılır.
- Kullanıcıya takvim arayüzü sunulur.

## HTML Formu

Bir HTML formu, kullanıcı girdisi toplamak için kullanılır. Kullanıcı girdisi, genellikle işlenmek üzere bir sunucuya gönderilir. Bir form oluşturmak için `<form>` etiketi kullanılır. İşte bir örnek:

### Örnek HTML Formu

```html
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Örnek HTML Formu</title>
</head>
<body>
  <h2>Kullanıcı Bilgileri Formu</h2>
  <form action="/submit" method="post">
    <label for="isim">İsim:</label><br>
    <input type="text" id="isim" name="isim" placeholder="Adınızı girin"><br><br>

    <label for="sifre">Şifre:</label><br>
    <input type="password" id="sifre" name="sifre" placeholder="Şifrenizi girin"><br><br>

    <label for="email">E-posta:</label><br>
    <input type="email" id="email" name="email" placeholder="E-posta adresinizi girin"><br><br>

    <label for="yas">Yaş:</label><br>
    <input type="number" id="yas" name="yas" min="0" max="100"><br><br>

    <label for="dogumTarihi">Doğum Tarihi:</label><br>
    <input type="date" id="dogumTarihi" name="dogumTarihi"><br><br>

    <input type="submit" value="Gönder">
  </form>
</body>
</html>
```

### Form Elemanları Açıklamaları

- `<form>`: Formu tanımlar.
- `action`: Form verilerinin gönderileceği URL'yi belirtir.
- `method`: Form verilerinin gönderilme yöntemini belirtir (örn. `get` veya `post`).
- `<label>`: Form elemanları için etiket sağlar ve erişilebilirliği artırır.
- `<input>`: Kullanıcıdan bilgi almak için kullanılan çeşitli türlerde giriş elemanlarını temsil eder.
- `<input type="submit">`: Form verilerini göndermek için kullanılan butonu temsil eder.

## Bilimsel ve Teknik Değerlendirme

HTML formlarının kullanımı, web geliştirme sürecinde temel bir beceridir. Formlar, kullanıcıdan veri toplamak ve bu verileri sunucuya iletmek için önemli bir araçtır. `<input>` elemanının çeşitli türleri, farklı veri tipleri için uygun giriş yöntemleri sunar. Bu, kullanıcı deneyimini iyileştirir ve verilerin doğru formatta alınmasını sağlar.

Önemli olan, her giriş türünün amacına uygun olarak kullanılmasıdır. Örneğin, bir şifre girişi için `type="password"` kullanmak, güvenliği artırır ve kullanıcı gizliliğini korur. E-posta girişi için `type="email"` kullanmak ise, girilen verinin geçerliliğini tarayıcı düzeyinde kontrol eder ve hatalı girişleri azaltır.

Sonuç olarak, HTML formlarını doğru ve etkili bir şekilde kullanmak, hem kullanıcı deneyimini hem de veri doğruluğunu artırır. Bu nedenle, her form elemanının özelliklerini ve kullanım alanlarını iyi anlamak, profesyonel web geliştirme için kritik öneme sahiptir.