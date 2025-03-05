

**Kayıt Formu (RegisterForm);**

**Amaç:** Kullanıcıların yeni bir hesap oluşturmasını sağlar.

_**Bileşenler;**_

**_E-posta:_** Kullanıcının e-posta adresini girmesi için bir metin kutusu.

**_Şifre:_** Kullanıcının şifresini girmesi için bir metin kutusu (şifre gizli).

**_Şifreyi Onayla:_** Kullanıcının şifresini onaylaması için bir metin kutusu (şifre gizli).

**_Kayıt Ol Butonu:_** Kullanıcının girdiği bilgileri doğruladıktan sonra kaydetmek için tıklayacağı buton.

**İşlevsellik:**
- _Kullanıcı, e-posta ve şifre bilgilerini girdikten sonra "Kayıt Ol" butonuna tıkladığında, şifrelerin eşleşip eşleşmediği kontrol edilir._
- _Eğer şifreler eşleşiyorsa, kullanıcı bilgileri kullanici.txt dosyasına kaydedilir._
- _Kayıt işlemi başarılı olduğunda, kullanıcıya bir mesaj gösterilir ve LoginForm açılır._

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-

**Giriş Formu (LoginForm);**

**Amaç:** Kullanıcıların mevcut hesaplarıyla giriş yapmalarını sağlar.

_**Bileşenler:**_

**_E-posta:_** Kullanıcının e-posta adresini girmesi için bir metin kutusu.

**_Şifre:_** Kullanıcının şifresini girmesi için bir metin kutusu (şifre gizli).

**_Giriş Yap Butonu:_** Kullanıcının girdiği bilgileri doğrulamak için tıklayacağı buton.

**İşlevsellik;**

_- Kullanıcı, e-posta ve şifre bilgilerini girdikten sonra "Giriş Yap" butonuna tıkladığında, uygulama kullanici.txt dosyasını kontrol eder._

_- Eğer girilen e-posta ve şifre, dosyada bulunan bilgilerle eşleşiyorsa, kullanıcıya "Giriş başarılı!" mesajı gösterilir._

_- Eğer bilgiler eşleşmiyorsa, kullanıcıya "E-posta veya şifre yanlış." mesajı gösterilir._


**Kullanım:**
Bu uygulama, kullanıcıların basit bir şekilde kayıt olmasını ve giriş yapmasını sağlamak için tasarlanmıştır. Kullanıcı bilgileri, güvenli bir şekilde bir metin dosyasında saklanır. Uygulama, kullanıcıların kimlik doğrulama işlemlerini gerçekleştirmek için temel bir örnek sunmaktadır.

