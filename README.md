# Third-Week-Homework
1- Şirket Playground Yazılımının Xcode ile projelendirilmesi yapılacaktır. 
# Özet
Proje xcode 13 ile geliştirilmiştir.

![](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-habipyesilyurt17/blob/main/FirstQuestion/ScreenShots/companyDashboard.png)

Proje açılış ekranında company bilgileri yer almaktadır. Buradaki değerler company oluşturulurken static olarak set edildi.
- Yukarıdaki resimde Revenue ve Outgoing değerlerinin yanlarında bulunan (+, -) butonlar yardımı ile açılan alert içerisine set edilen değeri companynin revenue(gelir) ve outgoing(gider) değerlerine ekliyorum. Ve budget(bütçe) değerini güncelliyorum.

- Yukarıdaki resimde navigationın en sağ kısımda yer alan ( + ) butonu ile çalışan ekleme ekranına gidilmektedir. Burada çalışan eklendikten sonra company dashboard da yer alan Employee değeri güncelleniyor. Burayı şirkette kaç çalışan olduğunu göstermek için kullandım. İlk başta hiç çalışanı yokmuş gibi düşündüm, o yüzde 0 değerini set ettim.

![](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-habipyesilyurt17/blob/main/FirstQuestion/ScreenShots/employeeForm.png)

- ( $ ) butonu ile bütün çalışanların maaşları toplanıp açılan alert ekranına arka planda set ediliyor. Payment denildiğinde bu değer company'nin outgoing(giderler) değerine eklenip budget(bütçe) değeri güncelleniyor.

![](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-habipyesilyurt17/blob/main/FirstQuestion/ScreenShots/paymentEmployess.png)

- En solda yer alan list.dash butonuna tıklandığında ise çalışanlar listesine gidiyorum. Burada çalışanların bilgileri gösteriliyor. Çalışan oluşturma formunda yer almayan salary bilgiside formda değerler girildikten sonra arka planda hesaplanıp salary propertysine set ediliyor.

![](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-habipyesilyurt17/blob/main/FirstQuestion/ScreenShots/employeeList.png)

- Çalışanlar listesinde isme göre search işlemi yapabiliyorum.

![](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-habipyesilyurt17/blob/main/FirstQuestion/ScreenShots/employeeListSearch.png)


2- Hayvanat bahçesi Playground yazılımının Xcode ile projelendirilmesi yapılacaktır. Aşağıdaki Özelliklerin bulunması gerekmektedir:
# Özet
Bu soruyu yetiştiremedim. Eksik olan kısımlar hayvanların ve bakıcıların listelenme ekranları ve berarberindeki işlemler.

3- https://programming-quotes-api.herokuapp.com/index.html üzerinden random endpointi kullanılarak aşağıdaki özellikler sağlanacaktır.
# Özet
Burada şöyle bir sıkıntı var request attığımda dönen response'un  bekleme süresi var. Burada bir indicator gösterebilirdim. Onun dışında 1 ile 100 arasında rastgele bir sayı üretiyorum. Daha sonra da 1 ile bu ürettiğim sayı arasında yine rastgale bir sayı üretiyorum. birinci sayıyı bana dönecek olan quotes sayısını vermesi için ikincisini ise index olarak kullandım.
- ilk proje ayağa kalktığında request atıyorum. Sonrasında her change butona tıklandığında yine request atıyorum.
