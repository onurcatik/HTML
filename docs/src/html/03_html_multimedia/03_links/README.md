# HTML Bağlantıları

- Bağlantılar neredeyse tüm web sayfalarında bulunur. Bağlantılar, kullanıcıların sayfalar arasında tıklayarak gezinebilmesini sağlar.
- HTML bağlantıları, köprülerdir.
- Bir bağlantıya tıklayarak başka bir belgeye geçiş yapabilirsiniz.
- Farenizi bir bağlantının üzerine getirdiğinizde, fare oku küçük bir el şekline dönüşecektir.
- Not: Bir bağlantının metin olması gerekmez. Bir bağlantı, bir resim veya başka herhangi bir HTML öğesi olabilir!

## HTML Bağlantıları - Söz Dizimi

- HTML `<a>` etiketi bir köprüyü tanımlar. Aşağıdaki söz dizimine sahiptir:

  ```html
  <a href="url">link metni</a>
  ```

- `<a>` etiketinin en önemli özelliği, bağlantının hedefini belirten `href` özniteliğidir.
- *Bağlantı metni*, okuyucuya görünen kısımdır.
- Bağlantı metnine tıklamak, okuyucuyu belirtilen URL adresine yönlendirecektir.

Tarayıcılarda bağlantılar varsayılan olarak şu şekilde görünür:

- Ziyaret edilmemiş bir bağlantı altı çizili ve mavidir.
- Ziyaret edilmiş bir bağlantı altı çizili ve mordur.
- Aktif bir bağlantı altı çizili ve kırmızıdır.

## HTML Bağlantıları - target Özniteliği

- Varsayılan olarak, bağlantı verilen sayfa mevcut tarayıcı penceresinde görüntülenir. Bunu değiştirmek için bağlantı için başka bir hedef belirtmelisiniz.
- `target` özniteliği, bağlantılı belgenin nerede açılacağını belirtir.
- `target` özniteliği şu değerlerden birine sahip olabilir:

  - `_self` - Varsayılan. Belgeyi tıklandığı aynı pencere/sekmede açar.
  - `_blank` - Belgeyi yeni bir pencere veya sekmede açar.
  - `_parent` - Belgeyi üst çerçevede açar.
  - `_top` - Belgeyi tarayıcı penceresinin tam gövdesinde açar.

## Bir Resmi Bağlantı Olarak Kullanma

- Bir resmi bağlantı olarak kullanmak için, `<img>` etiketini `<a>` etiketinin içine yerleştirin:

  ```html
  <a href="url">
    <img src="resim.jpg" alt="Açıklama">
  </a>
  ```

## Bir E-posta Adresine Bağlantı Verme

- Kullanıcının e-posta programını açarak yeni bir e-posta göndermesini sağlamak için `href` özniteliğine `mailto:` kullanarak bir bağlantı oluşturun:

  ```html
  <a href="mailto:ornek@mail.com">E-posta Gönder</a>
  ```

Bu eğitim, HTML bağlantıları hakkında temel bilgileri sağlamayı amaçlamaktadır. Bağlantıların farklı türlerini ve nasıl kullanılacağını öğrenmek, web geliştirme sürecinizde kritik bir rol oynar. Her zaman doğru söz dizimini kullanarak ve bağlantılarınızın kullanıcı deneyimini nasıl etkilediğini göz önünde bulundurarak daha etkili ve kullanıcı dostu web sayfaları oluşturabilirsiniz.
