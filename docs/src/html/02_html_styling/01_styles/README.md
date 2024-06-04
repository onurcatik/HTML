# HTML Stil Özellikleri

HTML `style` özelliği, bir öğeye renk, yazı tipi, boyut ve daha fazlasını eklemek için kullanılır.

## HTML Stil Özelliği

HTML öğesinin stilini ayarlamak, `style` özniteliği ile yapılabilir. HTML `style` özniteliği şu söz dizimine sahiptir:

```html
<element style="property:value;">
```

Bu öznitelik, CSS (Cascading Style Sheets) kullanılarak öğenin görünümünü değiştirmek için kullanılır. 

## Arka Plan Rengi

CSS `background-color` özelliği, bir HTML öğesi için arka plan rengini tanımlar. Örnek kullanım:

```html
<div style="background-color: yellow;">
    Bu div elemanının arka plan rengi sarıdır.
</div>
```

## Metin Rengi

CSS `color` özelliği, bir HTML öğesi için metin rengini tanımlar. Örnek kullanım:

```html
<p style="color: blue;">
    Bu paragrafın metin rengi mavidir.
</p>
```

## Yazı Tipleri

CSS `font-family` özelliği, bir HTML öğesi için kullanılacak yazı tipini tanımlar. Örnek kullanım:

```html
<h1 style="font-family: Arial, sans-serif;">
    Bu başlık Arial yazı tipini kullanır.
</h1>
```

### Önemli Notlar:

1. **Uyumluluk:** Tüm tarayıcıların tüm CSS özelliklerini desteklemediğini unutmayın. Özellikle eski tarayıcılarda bazı özellikler çalışmayabilir.
   
2. **Spesifiklik ve Kalıtım:** CSS kuralları belirli bir hiyerarşiye göre uygulanır. Bir öğeye uygulanan stil, daha spesifik veya önemli bir stil ile değiştirilebilir.
   
3. **Özellik Değerleri:** CSS özelliklerinin değerleri genellikle anahtar-değer çiftleri olarak tanımlanır. Örneğin, `color` özelliği için değer bir renk adı veya bir renk kodu olabilir.

Bu temel bilgiler, HTML öğelerine stil eklemek için kullanabileceğiniz CSS özelliklerinin nasıl kullanılacağını anlamanıza yardımcı olacaktır. Daha ayrıntılı bilgi için CSS spesifikasyonlarına ve ilgili belgelere başvurabilirsiniz.