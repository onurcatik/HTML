# Konu 3 - **HTML Listeleri**

HTML listeleri, web geliştiricilerin ilgili öğeleri listeler halinde gruplandırmalarını sağlar.

## **👉** Sırasız HTML Listesi

- Sırasız bir liste, `<ul>` etiketi ile başlar. Her liste öğesi `<li>` etiketi ile başlar.
- Liste öğeleri varsayılan olarak küçük siyah dairelerle işaretlenir:

### Örnek:
```html
<ul>
  <li>Öğe 1</li>
  <li>Öğe 2</li>
  <li>Öğe 3</li>
</ul>
```

Bu kod, sırasız bir liste oluşturur ve her öğe bir madde işaretiyle gösterilir.

## Sıralı HTML Listesi

- Sıralı bir liste, `<ol>` etiketi ile başlar. Her liste öğesi `<li>` etiketi ile başlar.
- Liste öğeleri varsayılan olarak numaralarla işaretlenir:

### Örnek:
```html
<ol>
  <li>Öğe 1</li>
  <li>Öğe 2</li>
  <li>Öğe 3</li>
</ol>
```

Bu kod, sıralı bir liste oluşturur ve her öğe bir numara ile gösterilir.

## HTML Tanım Listeleri

- HTML ayrıca tanım listelerini de destekler.
- Bir tanım listesi, terimlerin ve her terimin açıklamasının bulunduğu bir listedir.
- `<dl>` etiketi tanım listesini tanımlar, `<dt>` etiketi terimi (adı) tanımlar ve `<dd>` etiketi her terimi açıklar:

### Örnek:
```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language: Web sayfaları oluşturmak için kullanılan standart dildir.</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets: Web sayfalarının görünümünü düzenlemek için kullanılan stil dilidir.</dd>
</dl>
```

Bu kod, bir tanım listesi oluşturur. Her terim `<dt>` etiketi ile belirtilir ve terimin açıklaması `<dd>` etiketi ile verilir. Bu tür listeler, terimlerin ve açıklamaların düzgün bir şekilde yapılandırılmasını sağlar.

### Önemli Noktalar:

1. **Kapsamlı Anlaşılır Kodlama**: Kodların anlaşılabilir ve doğru bir şekilde yazılması, HTML belgelerinin düzgün çalışmasını sağlar.
2. **Etiketlerin Doğru Kullanımı**: `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>`, ve `<dd>` etiketlerinin doğru ve yerinde kullanımı, belgelerin yapısal bütünlüğünü korur.
3. **Semantik Web**: Listelerin ve diğer HTML etiketlerinin doğru kullanımı, web sayfalarının semantik yapısını güçlendirir ve erişilebilirliğini artırır.

Bu bilgiler, HTML listelerini kullanırken dikkat edilmesi gereken temel noktaları kapsamaktadır. Geliştiriciler, bu kuralları takip ederek daha okunabilir, anlaşılır ve işlevsel web sayfaları oluşturabilirler.