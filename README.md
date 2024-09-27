# MemberProject
Adını Member verdiğim bu proje, Java dili ve Firebase kullanılarak geliştirilmiş, Android tabanlı bir mobil uygulamanın tasarımını ve geliştirilmesini kapsamaktadır.

Uygulama, kullanıcıların çeşitli aktivitelerde ilan yayınlamasını, diğer kullanıcılarla mesajlaşmasını ve takımlar oluşturabilmesini sağlamaktadır. Kullanıcılar, ilanları başlığına, kategorisine ve açıklamasına göre filtreleyerek arayabilir; mesajlaşma özelliği ile iletişime geçebilir, ilan konumuna Google Maps entegrasyonu sayesinde ulaşabilir, paylaşabilir veya ilgisini çeken ilanları kaydedebilir.

Uygulama, internet erişimine sahip kullanıcılar için öncelikle kayıt olup giriş yapmayı gerektirir. Ardından kullanıcılar, aktivite ilanları paylaşabilir, güncelleyebilir, mevcut ilanları ve kendi ilanlarını görüntüleyebilir. Ayrıca ilanları kaydedebilir ve ilan sahipleriyle iletişime geçebilirler. Kullanıcılar, ilan sahipleri ve kendi hesap bilgilerini de görüntüleyebilirler.

Kullanıcılar, ilan paylaşma ekranında kategori, başlık, açıklama, başlangıç ve bitiş tarihi, konum bilgilerini doldurmalıdırlar. Resim ekleyerek ya da resimsiz olarak ilanlarını paylaşabilir ve diğer kullanıcıların görmesini sağlayabilirler. Mevcut ilanları kategori ve başlık bilgilerine göre aratarak filtreleyebilirler.


<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/aebbf18c-8b9c-4a97-8a7f-116a608a31a2" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8fa107c7-0817-4915-b88f-2b3ec7271b81" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/fffbc5d3-4e67-4854-afdc-43b3f78a3b83" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/5117cd2e-15c5-4817-b4cc-b67b53265b24" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/93a05e14-40a4-431a-a1a0-fb166f1b3bf9" alt="Resim 5" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/e9c16b98-5ba4-4e18-9b7f-8e0de88e600d" alt="Resim 6" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/2f8351fc-c757-46ac-b844-34c917f7b734" alt="Resim 7" style="width: 190px; height: auto; margin: 10px;">
</div>


<h4>1. Splash Screen</h4>
<p>Uygulama açıldığında kullanıcıyı karşılayan bir açılış ekranı (splash screen) bulunmaktadır. Bu ekran, uygulamanın yüklenmesini ve kullanıcıya hoş bir karşılama sunar.</p>

<h4>2. Giriş Yap Ekranı</h4>
<p>Kullanıcılar, uygulamaya iki farklı yöntemle giriş yapabilirler:</p>
<ul>
    <li><strong>Hesapla Giriş:</strong> Daha önce oluşturulmuş bir hesap ile e-posta ve şifre kullanarak giriş yapılabilir.</li>
    <li><strong>Google ile Giriş:</strong> Google hesabı kullanarak hızlı bir şekilde giriş yapmak mümkündür.</li>
</ul>
<p><strong>Hesap Doğrulama:</strong> Eğer kullanıcı, uygulamaya giriş yapmak için oluşturduğu e-posta hesabını doğrulamazsa, uygulamaya giriş yapması mümkün değildir. Doğrulama e-postası, kayıt işlemi sonrasında otomatik olarak gönderilir.</p>

<h4>3. Şifremi Unuttum</h4>
<p>Kullanıcılar, "Şifremi Unuttum" seçeneğine tıklayarak e-posta adreslerini girerek şifre sıfırlama linki alabilirler. Bu link aracılığıyla, şifrelerini yenileyebilirler.</p>

<h4>4. Kayıt Ol</h4>
<p>Kayıt işlemi sırasında, kullanıcılar daha önce alınmış bir e-posta adresi veya telefon numarası ile hesap oluşturamazlar.</p>

<h5>Hesap Doğrulama Bağlantısı:</h5>
<p>Kayıt ol butonuna bastıktan sonra, kullanıcıya hesabını doğrulaması için bir bağlantı içeren e-posta gönderilir. Kullanıcı, bu bağlantıyı tıklayarak hesabını aktif hale getirmelidir.</p>

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/f687e3c5-be81-4c26-91a1-142c5faf6906" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/741f73cf-2252-4578-958c-cd70db008bc5" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/524c5ce1-91f4-4295-be43-ae780f75d97f" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/f7d6897b-337e-4dd0-852e-f83e84f7f367" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/5b910adc-6f2b-4f5d-9dd4-8b82dd2961c3" alt="Resim 5" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/2e04838d-5ab7-472f-bd62-42b80c079219" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

<h5>1. İlk Giriş Ekranı</h5>
<p>Kullanıcılar uygulamaya ilk giriş yaptıklarında, kullanıcı dostu bir arayüzle karşılaşırlar. Ana ekranda, gönderileri konum tabanlı olarak filtreleme imkânı sunulmaktadır.</p>

<h5>2. Konum Tabanlı Filtreleme</h5>
<p>Kullanıcılar, 60 km bir alan içerisinde yer alan gönderileri konum bilgilerini ekleyerek filtreleyebilirler. Bu sayede, yakın çevredeki ilgilerini çeken gönderilere daha kolay ulaşabilirler.</p>

<h5>3. Gönderi Arama ve Filtreleme</h5>
<p>Gönderiler başlık, açıklama ve kategori bilgilerine göre aranıp filtrelenebilir. Bu, kullanıcıların aradıkları gönderilere daha hızlı ve kolay bir şekilde ulaşmasını sağlar.</p>

<h5>4. İlginizi Çeken Gönderiler</h5>
<p>Kullanıcılar, beğendikleri ve ilgilerini çeken gönderileri kaydedebilir veya kaydettikleri gönderileri istedikleri zaman geri alabilirler. Gönderileri daha sonra incelemek isteyen kullanıcılar kaydedilenler ekranından bunu yapabilirler</p>

<h5>5. Detaylı Gönderi Görüntüleme</h5>
<p>Bir gönderinin üzerine tıklandığında, o gönderiyle ilgili daha ayrıntılı bilgilere ulaşılabilir.</p>

<h5>6. Gönderi Oluşturma</h5>
<p>Yeni bir gönderi oluşturmak isteyen kullanıcıların telefon numaralarını doğrulamaları gerekmektedir. Telefon numarasını doğrulamayn kullanıclar sadece mevcut gönderilerle iletişime geçebilirler.</p>

Uygulama içnde internet erişimi gittiğinde internet erişimi gelene kadar progress dialog açılır. Ekrana dokunma ve geri tuşu işlevsiz kılınmıştır.


<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/c12a4b5a-8afa-4921-a28f-fac118c1c254" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/1b6da205-a593-472d-bfbb-a72c309dc335" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/bcc19040-7c5c-4ac2-873c-3655888af441" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/2c65d395-e060-4ad6-9ee4-6f1453a200b0" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/86299b38-0845-4c56-a9f3-1ba71174e545" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/dce0ea3a-8d8f-420a-84b1-5ad99de70c71" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/fc6c949e-96a8-4a2f-b651-06f4b55c7a3f" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/5967f1f5-651d-4dbe-8e55-a6dd4c527b9c" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8773e4fc-a185-4720-b26e-7686c03c75fa" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/6c7a8782-efd3-4768-b96b-51fdd8f65851" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/79e2e25c-53f5-4f09-9df2-548134d4369d" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>



<h5>Gönderi Favorilerine Eklenip Çıkarılabilir</h5>
<p>Kullanıcılar, bu ekran üzerinden de gönderileri favorilerine ekleyip çıkarabilir.</p>

<h5>Resimler Tam Ekran ve Slider Modunda Görüntülenebilir</h5>
<p>Gönderiye ait resimler slayt şeklinde tam ekranda veya normal olarak incelenebilir.</p>

<h5>Kullanıcı Profili ve İlanlara Ulaşılabilir</h5>
<p>Gönderi sahibi ile ilgili bilgilere kullanıcı profil sayfası üzerinden ulaşılabilir. Bu sayfada, kullanıcıya ait diğer ilanlar da görüntülenebilir. Böylece, kullanıcılar tek bir gönderi yerine, ilgi duydukları kişiye ait tüm ilanlara ulaşma fırsatı bulurlar.</p>

<h5>İlan Şikayet Edilebilir</h5>
<p>Eğer kullanıcı, bir gönderiyi uygunsuz veya kurallara aykırı buluyorsa, gönderi ile ilgili şikayette bulunabilir. Kullanıcı aynı gönderi için en fazla 1 şikayette bulunabiilir. Şikayetleri için kullanıcılara bilgilendirme maili gönderilir. Şikayet sayısı belli bir düzeyi geçtikten sonra da yöneticiye şikayet edilen gönderinin bilgileri ve şikayet eden kişiler gönderilir.</p>

Kullanıcya gönderilen mail bilgiendirme amaçlıdır.
Admine gönderilen mail şiaket eden kişilerin ve şikayet edilen gönderiyi kapsamaktadır.

Konum butonu ile kullanıclar gönderi konumu rotasyonunu açabilir.
Mesaj butonu ile de gönderi ssahibiyle iletişime geçebilir. Mesajlaşma gönderi ve kullanıcı eşleşmesi ile oluşturlur yani aynı kullanıcının farklı gönderileri ile olan mesajlaşma farklı sohbet kanallarından yapılır. 



<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/68e07fb5-b7de-4667-9fcb-d6670ccfccdb" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8f008d05-f4f8-4b2d-9024-18d78fd7a1c7" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/63c2dd49-b9a0-4a5c-ba7d-1be436c696b1" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/c7800bf6-f86d-4b0f-9f99-c7153282e8f7" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/f158dd80-74b1-49d5-8082-5a15c919954e" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
</div>

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/60d2292c-356b-4534-8a91-521944ca5c49" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/d7fc592e-f471-4244-b4d6-facf5fcafdb2" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8b99aa58-d000-4d97-b676-6d833abd8a64" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/32c84dbd-d40d-4ba4-a3c1-7200f70ef56e" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

Burada kullanıcı adına göre arama yaparak filtrleme yapabilir.
Mesajlaşma sırasında kişinin çevrimiçi, yazıyor, son görülme bilgileri görüntülenebilir. Mesajın teslim edilme görülme durumu ve mesajlaşma saatleri görüntülenbilir. Hatalı gönderilen bir mesaj silinerek her iki taraftan da silinmesi sağlanır. Kullanıcı profilne tıklandığında gönderi sahibine yazan kullanıcıya seçim kutusu açılarak gönderi sahibinin profilini veya gönderisini görüntüleyebilir, gönderi sahibi ise direkt olarak sadece kullanıcı profilini görüntüleyebilir. 

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/9ba59d90-d008-4fa7-a494-c77671cacac8" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/3c383c11-c8d7-42d3-9d3e-7b29be78a991" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/d6bb7c29-36af-4c5f-94e5-32f129c5bdfe" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/c0dbee00-bc35-47a5-8035-540b52a58c1b" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>





Aynı kullanının farklı gönderileri için farklı sohbetler oluşturlur.
Kulanıcının çevrimiçi olup veya çevrımdışı olduğu görüntülebeilir. 
Kullanıclar arasında son mesajlar ve son mesaj saatleri görüntülenebilir.
Teslim edilen ancak okunmayan yani görüldü durumunda olmayan mesaj sayısı görüntülenebilir.
Mevcut kullanıcı sohbeti sil dediğinde diğer kişi ile olan sohbet kanalı bu kullanıcıdan silinir. Karşı taraf da sohbeti sil derse ona ait olan sohbet kanalı da silinir ardından ikisi arasındaki tüm mesajlar silinir.

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/aad8c3cb-d487-4220-8d04-14353aa3b4ff" alt="Resim 9" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/7369a797-9826-4a10-819b-ea955fca3932" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/93485190-dcb9-42a8-9e22-00355b25af21" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/9938dc4a-a42b-494e-8a5c-ddb69011abbe" alt="Resim 8" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/c95267d2-d061-4c37-a95a-a4a67b2a5b15" alt="Resim 6" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/ffc45a9e-62e7-44c5-a86b-844989b5087f" alt="Resim 5" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/9e7ca2b3-257d-4db8-9a17-1fd3cf9725fa" alt="Resim 1" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/073c601b-c68a-422d-88c4-539f56140379" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/0956cfe9-3ff2-4917-9c12-e4a1e62ddad0" alt="Resim 7" style="width: 190px; height: auto; margin: 10px;">
</div>

Gönderiler resimli veya resimsiz olarak paylaşılabilir.
Resim eklemek için diyalog ekranından Kamera veya Galeri seçilebilir. Galeri için depolama izni istenir. Kamera için kamera ve depolama izni istenir çünkü resimler kaydedilir. Galeriden seçilen resimler çoklu veya tek tek seçilebilir. En fazla 10 resim yüklenebilir. eklenen resimler kaldıralbilir tam ekranda görüntülenip slider içinde gezilebilir.
çıkış yapmak istendiğinde eğer gönderi paylaşılmamış ile uyarı diyaloğu açılır, gönderi paylaşılmış ise de direkt oalrak bir önceki sayfaya geçilir.
İlan paylaşmak için bütün metin alanları doldurulmak zorundadır.
Konum girişi içim tıklandığında uygulama içinde map açılır ve konum izni istenir. Konum izni verilerek veya verilmeyerek konum seçilebilir. Arama yolu ile konum belirnebilir veya konum butonuna tıklandığında eğer konum bilgisi açık ise mevcut konumu seçer, açık değil ise konumu açmanızı hatırlatır. Konum haritadan manuel oalrak dokunarak da seçilebilir. Seçilen konum allta gözükür.

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8d5c0da5-2966-440e-b411-159f9eab2f9d" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/69acb12c-1fc9-474d-bf9e-140876157e79" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8c507443-5ba1-4c78-bc2d-0a8d6fb4ea81" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/067d52ee-a770-46d5-9b54-71e23f985e67" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

Kullanıcı kendi gönderilerini anasayfasında görüntüleyemez bunun yerine gönderilerim kısmında görebilir.
Kendi gönderilerini favorilere ekleyemez ancak gönderilerini silebilir veya düzenleyebilir. Kullanıc kendi gönderisinde mesaj gönder, kullanıcı profili ve şiaket et bölümlerini de göremez. Konum bilgisini görebilir ve kontrol edebilir.
Diğer kullanıclara ait kaydettiği gönderilere de bu ekranda ulaşır burada hepsi toplu olarak görebilir favorilerden kaldırabilir.
Gönderiler ve kaydedilenler ksımında gönderileri başlık,kategori,açıklama bilgiisne göre fitreleybilir.


<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/5647c7f2-6e34-4abd-8547-2a776e18f322" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/a4292d6c-c6af-48ff-921b-40a0aa0ec733" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/50723d69-acab-45b1-bb2d-9a77cdcf5a6a" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/1bab8de0-3019-4aeb-b523-7a1e5bf7dd54" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/aa8ec979-eda5-4c54-8682-13c5b050af18" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/a53865e5-7a4a-49a8-b7b2-9b267ed18116" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

Gönderi Düzenleme
kullanıcı 1. seanryoda databsede oaln gönderi resimlerini silip güncelleyebilir.
2. senaryoda önce databasede olan gönderi resimlerini silip sonra yeni resimler ekleyerek güncelleyebilir.
3. senaryoda önce yeni resimler ekleyip sonra databasede olan resimleri silebilir. 
4. senaroyda databse  resimlerini silmeyerek yeni resimler ekleyerek güncelleyebilir.
5. senaryo da resimlerleri ilk 4. senaryoda istediğini yapıp metin kısımlarını değiştirebilir veya sadece metin ksımını değiştirip güncelleyebilir.
Kullanıcı databseden gelen ve yeni eklenen resimleri tam ekranda sliderda görüntüleybilir. 
Bu adımda yanlıkla gerı tusuna bastııgnda uyarı diyalogu acılır.

Gönderi Silme

Kullanıcı gönderisi silmek istediğinde uyarı ekranında onaylamsı gerekir.
Gönderisini sildiğinde anlık olarak diğer kullanıcılar için de ulaşılamaz olur. Sildiği gönderisini favorilere ekleyen tüm kullanıcalrdan kaldırlır. Göndersi için olan sohbet her iki taraf içinde tamamen silinir.


<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/a0475390-7e21-4536-b6b3-c5ef86453661" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/22241c0c-bcbf-4a39-8949-ba2e8af6c9cd" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/bbc60607-4440-4b5b-a901-1022967c20f0" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/8e344de6-38c0-47d8-8162-b3f8cef1e2c0" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/addae71b-c980-4d0f-888f-9bc2b4824d4f" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

Kullanıcının gönderi paylaşması için telefon doğrulamsı gerekir bu doğrulama için de profil bilgileri eksiksiz doldurulmalıdır.
Kullanıcı resmini galeriden veya kamerdan seçebilir ve yükleyebilir.
Kullanıcı bilgilerini güncelleyebilir.
Telefon numarası için ülke kodunu seçmesi gerekir varsayılan oalrak tr dir. Uygulamaya ilk kaydolduğunda telefon numarası bilgisini girmesi gerekir ardından da gönderi paylaşamk için doğrulama yapması gerekir. Doğrulama sonrası telefon numarasını değiştirmek isterse yeni numarasını da doğrulamsı gerekir.
Profil resmi ve kullanıcı adı gönderilerde, ve sohbette gözüktüğü için güncellendiği zaman databsede de guncellenerek buralrda doğru gozukmesı saglanır.

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/86ec542a-97e5-43da-9110-ce8374cd513a" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/d28d6398-eb6c-4301-8a7f-3a9afcefeab1" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/329d318f-076c-47cc-9e00-7b5f1f620947" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/091ef92f-cada-4dae-aac7-7437373a7ef0" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/55269718-9425-4b68-8887-e895b408c806" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

Uygulama içinden şifreyi değiştrimek istediğinde eski şifresini doğrulayark yeni şifre belirlenebilir.
Telefon doğrulamsı için telefona sms gönderilir. 6 haneli kod girildikten sonra eğer doğru ise doğrulama başarılı şekilde tamamlanır. Kod gelmemesi duurmunda yeni kod talep edileibilir. telefon doğrulandıktan sonra telefon doğrula bölümü gizlenir. telefon değişikliği durumunda yine görünür olur.

<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/86ec542a-97e5-43da-9110-ce8374cd513a" alt="Resim 4" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/f9046a57-9303-4f71-a8f8-fddc949a44b6" alt="Resim 3" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/3d40e2ef-e13c-468b-909b-b5acb5f7e2e8" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/b0774f87-49c4-43af-b396-bf712a654161" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
    <img src="https://github.com/user-attachments/assets/1c092707-723e-4ba2-8da0-c9e2accf29e9" alt="Resim 2" style="width: 190px; height: auto; margin: 10px;">
</div>

Hesaptan çıkış yapılmak istendiğinde uyarı diyaloğu açılır onayaldığı zaman da giriş yap ekranına erişilir. Çıkış yapılmadığı sürece giriş ekranına yönlendirilmeden direkt oalrak uygulama başlar.
HEsabı silmek istediğinde eğer google ile giriş yapmış ise google hesabını doğrulamsı gerekir, e posta ile kayıt olmus ise şifresini doğru bir sekilde tekrar girmesi ve uyarı dıylogunu onaylması gerekir.
kullanıcı hesabını sildiğinde tüm gönderileri silinir, gönderilerini favorilere ekleyen her kullanıcdan bu göndeiler kaldrılır. Tüm gönderileri için olan sohbetleri hem kendisininden hem de iletişim kurduğu kişiden silinir. Ve giriş yap ekranına yönlendirlir.
















