# HTML Görselleri

- Görseller, bir web sayfasının tasarımını ve görünümünü iyileştirebilir.

## HTML Görselleri Söz Dizimi

- HTML `<img>` etiketi, bir web sayfasına görsel yerleştirmek için kullanılır.
- Görseller teknik olarak bir web sayfasına eklenmez; görseller web sayfalarına bağlanır. `<img>` etiketi, referans verilen görsel için bir yer tutucu oluşturur.
- `<img>` etiketi boştur, yalnızca nitelikleri içerir ve kapanış etiketi yoktur.
- `<img>` etiketinin iki zorunlu niteliği vardır:
  - src - Görselin yolunu belirtir
  - alt - Görsel için alternatif metin belirtir

### src Niteliği

- Zorunlu olan `src` niteliği, görselin yolunu (URL) belirtir.
- Bir görselin genişliğini ve yüksekliğini belirtmek için `style` niteliğini kullanabilirsiniz.

### alt Niteliği

- Zorunlu olan `alt` niteliği, kullanıcının görseli herhangi bir nedenle görüntüleyememesi durumunda (yavaş bağlantı, src niteliğinde hata veya ekran okuyucu kullanılması gibi) alternatif bir metin sağlar.
- `alt` niteliğinin değeri görseli tanımlamalıdır:
  - Bir tarayıcı görseli bulamazsa, `alt` niteliğinin değerini görüntüler.

Bu bilgiler, HTML kullanarak görsellerin nasıl yerleştirileceğini ve uygun niteliklerin nasıl kullanılacağını anlamak için temel bir rehber sunmaktadır. HTML standartları, kullanıcı deneyimini ve erişilebilirliği artırmak için bu niteliklerin doğru kullanımını teşvik etmektedir. Görsellerin web sayfalarına doğru şekilde eklenmesi, hem sayfa yüklenme hızını hem de erişilebilirliği olumlu yönde etkiler.