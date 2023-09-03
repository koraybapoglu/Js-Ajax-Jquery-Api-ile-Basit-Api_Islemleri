# Veri İşleme Uygulaması

Bu basit uygulama, bir API'den verileri çekme, veri ekleme ve veri güncelleme işlemlerini gerçekleştirir. Bu işlemler AJAX, jQuery ve bir API kullanılarak gerçekleştirilir.

## Kullanılan Teknolojiler

- AJAX
- jQuery
- RESTful API (reqres.in)

## İşlevler

### İsim Büyütme

`Buyut()` fonksiyonu, kullanıcının girdiği ismi büyük harfle dönüştürür ve sonucu ekranda gösterir.

### Verileri Çekme

`VerileriCek()` fonksiyonu, belirli bir API'den verileri çeker ve tablo halinde ekranda gösterir.

### Veri Ekleme

`VeriEkle()` fonksiyonu, kullanıcının girdiği isim ve mesleği bir API'ye gönderir ve yeni bir üye ekler.

### Veri Güncelleme

`VeriGüncelle()` fonksiyonu, belirli bir kullanıcının adını ve soyadını güncellemek için bir API'ye PUT isteği gönderir.

## Nasıl Kullanılır

1. İsim büyütme işlemi için "Lütfen İsim Giriniz" alanına bir isim yazın ve sonucu görün.

2. "Verileri Çek" düğmesine tıklayarak API'den verileri çekin ve tabloyu görüntüleyin.

3. "Üye Ekle" bölümünde "ÜyeAdınıGiriniz" ve "ÜyeMesleğiGiriniz" alanlarına bilgileri girin ve "Ekle" düğmesine tıklayarak yeni bir üye ekleyin.

4. "Üye Güncelle" bölümünde güncellenecek üyenin adını ve soyadını girin ve "Güncelle" düğmesine tıklayarak güncelleme yapın.

## Lisans

Bu proje ücretsiz bir şekilde sunulmuştur. 
