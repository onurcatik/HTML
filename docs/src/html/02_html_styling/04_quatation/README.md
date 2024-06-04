# HTML Alıntılar

## **HTML `<q>` Kısa Alıntılar İçin**

- HTML `<q>` etiketi, kısa bir alıntıyı tanımlar.
- Tarayıcılar genellikle alıntının etrafına tırnak işaretleri ekler.

HTML `<q>` etiketi, kısa ve satır içi alıntılar için kullanılır. Bu etiket, alıntının kaynağını belirtmek için kullanışlıdır. Tarayıcılar bu etiketi kullanarak, alıntının etrafına otomatik olarak tırnak işaretleri ekler, bu da alıntının metin içerisinde daha belirgin olmasını sağlar.

Örnek:

```html
<p>Albert Einstein bir keresinde <q>Hayal gücü bilgiden daha önemlidir</q> demiştir.</p>
```

Yukarıdaki örnekte, `<q>` etiketi kullanılarak Einstein'a ait bir alıntı belirtilmiştir.

## **HTML `<blockquote>` Alıntılar İçin**

- HTML `<blockquote>` elementi, başka bir kaynaktan alıntılanan bir bölümü tanımlar.
- Tarayıcılar genellikle `<blockquote>` elementlerini girintili olarak gösterir.

HTML `<blockquote>` etiketi, daha uzun ve blok halinde alıntılar için kullanılır. Bu etiket, genellikle bir paragraf veya daha uzun metin bölümleri için kullanılır ve tarayıcılar bu etiketi kullanarak alıntıyı sayfanın geri kalanından ayırmak için girinti ekler.

Örnek:

```html
<blockquote cite="https://www.example.com/einstein">
    <p>Hayal gücü bilgiden daha önemlidir. Bilgi sınırlıdır. Hayal gücü ise tüm dünyayı kapsar.</p>
</blockquote>
```

Yukarıdaki örnekte, bir alıntı `<blockquote>` etiketi içinde belirtilmiştir ve `cite` özelliği kullanılarak alıntının kaynağı verilmiştir.

## **HTML `<abbr>` Kısaltmalar İçin**

- HTML `<abbr>` etiketi, bir kısaltma veya akronimi tanımlar, örneğin "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
- Kısaltmaların işaretlenmesi, tarayıcılar, çeviri sistemleri ve arama motorları için faydalı bilgiler sağlayabilir.

HTML `<abbr>` etiketi, metin içerisinde geçen kısaltmaların veya akronimlerin tanımlanması için kullanılır. Bu etiket, kullanıcıya veya makineye kısaltmanın anlamını belirtmek için kullanılır ve bu sayede tarayıcılar, çeviri sistemleri ve arama motorları bu bilgiyi daha iyi anlayabilir.

Örnek:

```html
<p><abbr title="Hypertext Markup Language">HTML</abbr> bir belge işaretleme dilidir.</p>
```

Yukarıdaki örnekte, `<abbr>` etiketi kullanılarak "HTML" kısaltmasının açılımı belirtilmiştir. `title` özelliği, kısaltmanın tam anlamını vermek için kullanılır ve kullanıcı fareyi kısaltmanın üzerine getirdiğinde bu bilgi görüntülenir.

Bu etiketlerin doğru ve etkili kullanımı, web sayfalarının anlaşılabilirliğini ve erişilebilirliğini artırır. Bu nedenle, HTML belgeleri oluştururken bu etiketlerin doğru kullanımına özen göstermek önemlidir.
