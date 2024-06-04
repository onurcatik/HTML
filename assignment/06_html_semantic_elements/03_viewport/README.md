# Konu 3 - HTML Viewport Meta Etiketi

## **👉** Viewport Ayarlama

Responsive bir web sitesi oluşturmak için, tüm web sayfalarınıza aşağıdaki `<meta>` etiketini ekleyin:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Bu, sayfanızın görünüm alanını ayarlayacak ve tarayıcıya sayfanın boyutlarını ve ölçeklendirmesini nasıl kontrol edeceği konusunda talimatlar verecektir.

## Örnekler

Viewport meta etiketi **olmayan** bir web sayfası ile viewport meta etiketi **olan** aynı web sayfasının örnekleri aşağıda verilmiştir:

### Viewport Meta Etiketi Olmadan

Viewport meta etiketi olmadan, web sayfası mobil cihazlarda düzgün bir şekilde ölçeklenmez ve masaüstü versiyonu gibi görünür. Bu, kullanıcı deneyimini olumsuz etkileyebilir, çünkü içerik mobil ekrana sığmaz ve kullanıcılar sürekli olarak yakınlaştırmak veya uzaklaştırmak zorunda kalır.

### Viewport Meta Etiketi ile

Viewport meta etiketi ile, web sayfası cihazın ekran boyutuna uygun olarak ölçeklenir. Bu, daha iyi bir kullanıcı deneyimi sağlar çünkü içerik, cihaz ekranına göre otomatik olarak uyarlanır ve kullanıcılar içeriği rahatça okuyabilir ve gezinebilir.

## Örnek Kod

Aşağıda, viewport meta etiketi eklenmiş basit bir HTML belgesi örneği bulunmaktadır:

```html
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Web Sayfası</title>
</head>
<body>
    <h2>Duyarlı Görüntü</h2>
    <img src="imglogo.jpg" style="width: 100%;">
</body>
</html>
```

Bu HTML belgesi, cihazın ekran boyutuna göre ölçeklenen ve kullanıcıya daha iyi bir deneyim sunan duyarlı bir görüntü içerir.

## Çıktı

Bu kodu tarayıcıda çalıştırdığınızda, aşağıdaki gibi bir çıktı elde edersiniz:

![Responsive Image](file-ibCyI9bUEOSwSyDvEztFEBWT)

Bu örnekte, viewport meta etiketi sayesinde görüntü, ekran boyutuna göre otomatik olarak ölçeklenir ve kullanıcının ekranına tam olarak uyum sağlar. Bu, mobil cihazlarda görüntülerin ve diğer içeriklerin doğru bir şekilde görüntülenmesini sağlar.

## Sonuç

Viewport meta etiketi, web sayfalarınızın mobil cihazlarda doğru şekilde görüntülenmesini sağlamak için kritik öneme sahiptir. Bu etiketi kullanarak, web sitenizin duyarlı olmasını ve tüm cihazlarda iyi bir kullanıcı deneyimi sunmasını sağlayabilirsiniz. Bu basit ama güçlü araç, modern web geliştirmede vazgeçilmez bir bileşendir.