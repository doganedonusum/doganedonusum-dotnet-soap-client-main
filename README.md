Doğan E-Dönüşüm ENTEGRASYON TEST PROJESİ

Bu proje Authentication ,e-Fatura, e-Arşiv,e-İrsaliye, Müstahsil ve Smm  ürünlerinin izibiz  web servis metodlarının testleri örnek olması için yazılmıştır.
Yalnızca test web servis sisteminde çalışmaktadır.

KURULUM

Projemizi indirdikten sonra sonra Izibiz_dotnet_soap_client projesinin altındaki Adapter klasörünün içinde bulunan BaseAdapter.cs sınıfındaki ve 
Samples projesinin altındaki Authentication klasörünün içinde bulunan AuthenticationSample.cs sınıfındaki
	 USER_NAME = "KULLANICI ADINI GIRINIZ..."
	 PASSWORD = "SIFRE GIRINIZ..."
alanlarına kullanıcı adınızı ve şifrenizi giriniz.

Projemizi build ettikten sonra Test sekmesinden Windows --> Test.explorer açılır.
Tüm testlerin çalışması için Test.explorer daki Samples üzerinde sağ tıklanılır run edilir veya hangi testi çalıştırmak istenilirse örneğin 
Authentication testini çalıştırmak için o test üzerinde sağ tıklanılır run edilir.
