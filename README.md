## 🇹🇷 Beni Hatırlayınız — Siluet Mask
Bu proje, HTML5 Canvas, JavaScript ve CSS kullanılarak hazırlanmış animasyonlu bir siluet efektidir.
Bir siluet görseli (örneğin siluet.png) üzerine, “Beni hatırlayınız.” metni akıcı bir şekilde akarak yalnızca siluet içinde görünür.
Yazı, siluet maskesiyle birleştirilerek ışıltılı bir akış efekti oluşturur.
## 🖼️ Özellikler
Dinamik mask oluşturma: Siyah siluet pikselleri otomatik olarak maske haline getirilir.
Akıcı yazı animasyonu: Metin sürekli akar ve siluet içinde görünür.
Responsive yapı: Ekran boyutuna göre otomatik ölçeklenir.
Renk geçişli (gradient) metin: Kırmızıdan beyaza geçiş yapan zarif bir görünüm.
Google Fonts (Italianno) ile estetik yazı tipi desteği.
## 🧩 Kullanım
Bu dosyayı index.html olarak kaydedin.
Aynı klasöre bir siluet.png dosyası ekleyin. (Siyah siluet, beyaz arka plan veya şeffaf alanlar olabilir.)
Tarayıcınızda index.html dosyasını açın.
Ekranda siluet içinde akarak beliren “Beni hatırlayınız.” yazısını göreceksiniz.
## ⚙️ Özelleştirme
Aşağıdaki parametrelerle oynayarak görünümü değiştirebilirsiniz:
Parametre	Açıklama	Varsayılan
text	Görünen metin	"Beni hatırlayınız. "
speed	Yazının akış hızı	2.5
lineHeight	Satırlar arası mesafe	13
fontSize	Yazı boyutu	14
threshold	Maske oluştururken kullanılan eşik değeri (0–255)	200
## 📚 Çalışma Prensibi
**Siluet Yükleme:** siluet.png dosyası yüklendiğinde bir maske oluşturulur.
**Maskeleme:** Sadece siyah bölgeler (siluet) opak hale getirilir.
**Metin Döşeme:** “Beni hatırlayınız.” metni satır satır akıcı biçimde textCanvas üzerine yazılır.
**Mask Uygulama:** Metin ve maske birleştirilerek yalnızca siluet içinde yazı görünür.
**Render:** Sonuç, ana canvas üzerine ölçeklenerek çizilir.
## 🎨 Örnek Görsel
(Projede siluet.png dosyası sizin tasarımınıza göre değişmelidir.)
Örnek: Karanlık fonda yüz veya profil silueti, içinde hareket eden “Beni hatırlayınız.” yazısı.
## 🧠 Teknolojiler
HTML5 Canvas API
Vanilla JavaScript
CSS3
Google Fonts
## 💡 Fikir
Bu proje, Atatürk’ü anmak ve 10 Kasım’ı hatırlamak amacıyla hazırlanmıştır.
“Beni hatırlayınız.” metni, 10. Yıl Nutku’nda Atatürk’ün üstünü çizdiği, söylemekten vazgeçtiği sözden ilham alınarak seçilmiştir.
Siluet maskesi, yazının yalnızca belirli bir çerçevede görünmesini sağlayarak, hatırlama ve saygı temasını görsel olarak vurgular.
Animasyon, sessiz ama akıcı bir anma deneyimi sunmayı amaçlar.
