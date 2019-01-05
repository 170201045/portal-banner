## portal-banner
Portal projesi için banner(reklam) modülü
<br>
<br>

# Bilgi #
>Bu projede tüm değişiklikler ve yüklemeler developer branch ı ile backend altında yapılmıştır
>Banner modülünün amacı siteye reklam ekleyip yönetmektir.
>Bu oluşturulan modül , model ve crud işlemleri portal-gii kullanılarak yapılmıştır.

# Kurulum
>Profilimde bulunan portal isimli reponun composer.json dosyasına kouosl'den Fork ettiğim ve değiştirdiğim portal-theme , gii generator ile oluşturduğum portal-banner eklenmiştir.Profilimdeki portal kurulumundan sonra bunlar otamatik gelecektir.
>Portal kurulumu için örnek ; https://github.com/kouosl/portal
>
> ## Migrations <br>
>Migrationsu işlemek için su yetkisiyle sanal makinede aşağıdaki kod çalıştırılmalıdır
```
php yii migrate --migrationPath=@vendor/kouosl/portal-banner/migrations --interactive=0
```
<br> 

# Erişim 
> Modül Sayfası : http://portal.kouosl/admin/banner <br>
> Model Sayfası : http://portal.kouosl/admin/banner/bannerr



