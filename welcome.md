# CodeIgniter 4 Giriş ve Yükleme

Codeigniter php kullanarak web arayüzü geliştiren kişiler için oluşturulmuş bir basit araç seti/framework 'dür. 

Amacı sık ihtiyaç duyulan görevler ve işlemler için sizi sürekli tekrarlı kod yazımlarından kurtararak çok daha hızlı proje geliştirmenizi sağlayan bir araç setidir. CodeIgniter belirli bir iş için gereken kod miktarını en aza indirmek geliştirilmiştir.

CodeIgniter esnek yapısı sayesinde sizi belirli bir kalıpta proje yazımından kurtararak özgürce sizi kod yazımına odaklamaktadır. Bu bilgiler ışığında özet geçmek gerekirse CodeIgniter size başta hız olmak üzere klasör yapısı, Chache, desteklediği veri tabanı yapıları ve güvenlik olmak üzere birçok konuda sıfırdan servis yazmak yerine, size bu servisleri hazır olarak sunar. Yazılıma yeni başlayan arkadaşlar için hız odaklandırkları bir konu olmayabilir fakat belirli bir sayıda proje ile uğraştıkları zaman hız konusunun ne kadar önemi hatta en önemli etken olduğunu anlayacaklardır. Sürekli tekrar eden ve artık sıkıcı olmaya başlayan yapıları tekrar tekrar yazmak sizi o projeden soğutmaya ve hatta işten soğutmaya kadar yol açar. Yani en azından benim için öyle. 

Kurulumu ve yapılandırması oldukça kolaydır. Parmak ısırtacak kadar hızlıdır ve şaşırtacak kadar da küçük bir boyuta sahiptir. 

Bu yazı genellikle CodeIgniter içeriğine odaklanıştır. Kurulumu ve yapılandırma ile ilgili çok fazla içerik olmayacaktır. Çünkü internette bu konularla ilgili birçok yazı ve video var. İngilizce bilmeyen insanlar bile sadece belirli noktalara bakarak kurulumunu ve yapılandırmayı tamamlayabilir. Codeigniter kurarken Laravel gibi Composer kullanmak zorunda değilsiniz yani en azından yazıyı yazdığım zamanlar için laravel kurabilmek için Composer zorunlu. İleriki sürümlerde bu zorunluluk kalkarsa beli linçlemeyin diye bu bilgiyide yavaşça buraya bırakayım.

CodeIgniter 4 için minimum php sürümü 7.4 dür ve CodeIgniter 4 için initl, mbstring ve json uzantılarını etkileştirmek gerekir. mbstring ve json için herhangi bir yükleme yapmanıza gerek yoktur ki bunlar php içerisinde mevcuttur. Intl için ise php.ini dosyasından ";extension=intl" bölümündeki ";" kaldırarak kaydedin ve apache yi yeniden başlatın.

CodeIgniter 4 veritabanı olarak MySQLi, Postgre, SQLite3, SQLSRV ve OCI8 destekler. 

CodeIgniter 4 yüklemek için [CodeIgniter](https://www.codeigniter.com/) offical sitesi üzerinden Download diyerek CodeIgniter 4 sürümünü indirin. İndirmenin ardından zip dosyası içerisinde CodeIgniter 4 dosyaların ve klasörlerin bulunduğu app, assets, system vb. bulunduğu tüm dosya ve klasörleri ilgili çalışma alanınıza (ilgilli php kodlarınızı yazdığınız klasör dizinine Örn: xampp için sürücü\xampp\htdocs klasörünün içerisine) kolyalayın. Bu kurulum aşaması ilgili CodeIgniter orjinal dökümanının [linki](https://www.codeigniter.com/user_guide/installation/installing_manual.html) 


