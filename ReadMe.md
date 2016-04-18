# Bigdump v0.36
Bigdump ile büyük veritabanlarınızı kolaylıkla yükleyebilirsiniz.

#Kurulum ve Kullanımı
Yukarıdan bigdump.php dosyasını bilgisayarınıza indirin ve dosyayı Notepad++ programı yardımıyla açın ve şu alanları kendinize göre düzenleyin.

$db_server   = 'localhost'; // MySQL sunucu adresiniz, genelikle localhost'tur aynı kalsın.

$db_name     = ''; //Oluşturduğunuz yeni veritabanının ismi.

$db_username = ''; // Oluşturduğunuz yeni veritabanının kullanıcısı.

$db_password = ''; // Oluşturduğunuz yeni veritabanının şifresi.


$filename           = '';     // Eski veritabanızın adını bu bölüme yazacaksınız.


Eski veritabanızı ve bigdump.php dosyasını aynı dosyaya veya aynı dizine koymalısınız. $filename kısmına yüklemek istediğiniz veritabanı uzantısıyla birlikte yazacaksınız. Üstteki bilgiler ise yeni oluşturduğunuz veritabanı ile ilgili bilgilerdir.

#Detaylı Bilgi:
http://www.ozerov.de/bigdump
