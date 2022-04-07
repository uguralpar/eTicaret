E-Ticaret Uygulama Tasarımı

- Kullanıcı web ve mobil uygulamalardan backend servislere istekler RESTful servislerle sağlanacaktır. İstekler api gateway üzerinden iletilecektir.
- Hesap oluşturma işlemleri için hesap oluşturma microservis uygulaması hazırlanacaktır. Kullanıcı hesap bilgileri MySql veritabanı üzerinde tutulacaktır.
- Ürün arama için ürün arama microservis uygulaması hazırlanacaktır. Arama işlemi için performansı yüksek olan elasticsearch db kullanılacaktır.
- Sepete ekleme işlemleri için sepet ekleme microservis uygulaması hazırlanacaktır. Sepetteki ürünler Rediste cache değeri olarak tutulacaktır.
- Ödeme işlemleri için ödeme microservis uygulaması hazırlanacaktır. Ödeme işlemine ait işlemlerde veritabanı kararlılığı ön planda olduğu için MySql veritabanı üzerinde tutulacaktır.
- Bilgilendirme işlemleri için bilgilendirme microservis uygulaması hazırlanacaktır. Bilgilendirme üretilip queue üzerinden tüketilecektir, bunun için rabbmitmq tercih edilmiştir. 
