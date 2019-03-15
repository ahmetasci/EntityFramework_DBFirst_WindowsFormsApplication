# EntityFramework_DBFirst_WindowsFormsApplication
    Siparişler MenuStrip'inde Sipariş Girişe tıkladığımız zaman FormGiris form sayfası açılacak.
    Bu açılan sayfada sıfırdan bir Order oluşturulabilecek.
    Sipariş Düzeltme/Görüntüleme dediğimizde flowLayoutPanel1 içinde label,button ve textbox belirecek. Buradan var olan bir sipariş numarası girilip 
    Siparişi aç butonuna tıklandığında eğer sipariş numarası veritabanında yoksa "BULUNAMADI" diye mesaj verecek, varsa FormOrderHeaderDetail form sayfası açılacak.
    Açılan bu form sayfasında girilen OrderID'ye göre ilgili comboBoxlar ve TextBoxlara sipariş bilgileri dolacak ve sipariş bilgileri bir tablo halinde 
    alttaki dataGridView1'de görünecek.
    Burada panelin üzerinde sipariş için silme ve güncelleme işlemleri, panelin altında da o siparişe ait detay bilgileri için silme, güncelleme ve ekleme
    işlemleri yapılacak.
