### Konu 2 - **HTML <!DOCTYPE>**

### **👉 HTML Belge Tipi**

- Tüm HTML belgeleri bir `<!DOCTYPE>` deklarasyonu ile başlamalıdır.
- Bu deklarasyon bir HTML etiketi değildir. Bu, tarayıcıya hangi belge tipinin bekleneceği hakkında bir "bilgi" sağlar.
- HTML5'te `<!DOCTYPE>` deklarasyonu basittir.

#### Detaylı Açıklama

`<!DOCTYPE>` deklarasyonu, tarayıcıların belgeyi nasıl işlemesi gerektiğini belirlemelerine yardımcı olur. HTML5'te kullanılan `<!DOCTYPE>` deklarasyonu, önceki HTML sürümlerine göre daha basit ve kısadır. 

Örneğin:
```html
<!DOCTYPE html>
```

Bu deklarasyon, tarayıcıya belgenin HTML5 standardına uygun olduğunu belirtir. HTML5'ten önceki sürümlerde kullanılan `<!DOCTYPE>` deklarasyonları daha karmaşıktı ve belge türünü daha ayrıntılı bir şekilde tanımlıyordu.

##### Neden `<!DOCTYPE>` Deklarasyonu Kullanılır?

- **Uyumluluk:** Tarayıcıların belgeyi standartlara uygun bir şekilde yorumlamasını sağlar.
- **Geçerlilik:** W3C tarafından belirlenen standartlara uygun bir HTML belgesi oluşturduğunuzdan emin olmanızı sağlar.
- **İşleme Modu:** Tarayıcılar, bir belgeyi ya "standart modda" ya da "uyumluluk modunda" (diğer adıyla "quirks mode") işler. `<!DOCTYPE>` deklarasyonu, tarayıcıların belgeyi "standart modda" işlemesini sağlar, bu da daha doğru ve tutarlı bir görüntüleme sağlar.

##### Örnekler

HTML4.01 için kullanılan `<!DOCTYPE>` deklarasyonu:
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

XHTML1.0 için kullanılan `<!DOCTYPE>` deklarasyonu:
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
```

Görüldüğü gibi, HTML5 ile gelen yeni `<!DOCTYPE>` deklarasyonu çok daha basit ve kullanımı kolaydır:
```html
<!DOCTYPE html>
```

#### Sonuç

`<!DOCTYPE>` deklarasyonu, HTML belgelerinin doğru ve tutarlı bir şekilde işlenmesini sağlamak için kritik bir öneme sahiptir. HTML5 ile birlikte bu deklarasyonun basitleştirilmiş olması, web geliştiricilerinin işini kolaylaştırmıştır. Tüm HTML belgelerinizde bu deklarasyonu kullanmak, belgelerinizin geçerli ve tarayıcılarla uyumlu olmasını sağlayacaktır.

---
