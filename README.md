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





