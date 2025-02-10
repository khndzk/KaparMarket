Proje Açılırken,
ilk olarak kapar market ana app solution açılmalıdır.

package manager konsoluna update-database komudu yazıldıktan sonra veritabanına manager eklenip tam erişim verilmelidir (permission = 2)

sonra ana app açılmalıdır.

giriş yaptıktan sonra kategoriler ve markalar oluşturulmalıdır.
sonra ürünler oluşturulmalıdır
sonra yan bayi oluşturulmalı ve kullanmak istediğiniz isim verilmelidir.

XML sayfasından XML güncellenmeli,
(XML'ler,Ürün Fotoğrafları ve Tedarikçi Siparişleri C:\KaparMarketData klasörünün içindedir)
sonra e-commerce app solution açılmalıdır.

konsola update-database yazdıktan sonra veritabanına manager eklenmeli ve 
E-Commerce App/Areas/ManagerPanel/Data/Methods/XmlUpdater konumundaki DealerName Değişkenini uygulamanın hangi tedarikçi olmasını istediğiniz adla eşleştirilmelidir.

daha sonra e-commerce app açılabilir.

ana bayiden ürün sipariş etmek için,
ilk olarak banka uygulamam KirazBankAPI açık tutulmalıdır.
bayi siparişlerinden sipariş eklenmelidir.
daha sonra bu veri ana apptan alınabilir.
son olarak yan bayinin kartından ana bayinin hesabına para geçişi olur.
ana bayide eklenen her ürün,kategori,marka yan bayide otomatik olarak görülecektir.
