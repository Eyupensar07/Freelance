Bu proje, kişisel portföyünüzü veya freelance hizmetlerinizi tanıtmak için tasarlanmış bir web sitesi projesidir. Proje, HTML, CSS ve JavaScript kullanılarak oluşturulmuş ve modern bir tasarım anlayışı sergilemektedir. Aşağıda, projenin önemli bölümlerini ve neler sunduğunu detaylıca açıklıyorum:

### Genel Yapı ve Özellikler
- **HTML ve CSS Kullanımı:** Sayfalar HTML ile yapılandırılmış ve CSS ile şık bir tasarım uygulanmıştır. Ana CSS dosyası `main.css` üzerinden düzenlenmiştir.
- **Responsive Tasarım:** Web sitesi, farklı cihaz boyutlarına uyum sağlayabilen bir tasarıma sahiptir. Bu, mobil cihazlarda ve masaüstü bilgisayarlarda kusursuz bir görünüm sağlar.
- **Modern Kütüphaneler:** Google Fonts, Font Awesome, Animate.css ve Owl Carousel gibi modern kütüphaneler entegre edilmiştir. Bu, tipografi, ikonlar, animasyonlar ve kaydırma özellikleri gibi gelişmiş görsel özellikler sağlar.

---

### Sayfa İncelemesi
1. **Ana Sayfa (Home):**
   - Kullanıcıyı karşılayan bir başlık ve kısa açıklamalar bulunur.
   - Portföyünüzdeki diğer sayfalara kolayca erişim sağlayan bir navigasyon menüsü içerir.

2. **Hakkımda Sayfası (About):**
   - Bu sayfa, sizinle ilgili bilgileri ve yeteneklerinizi tanıtmak için tasarlanmıştır.
   - "Web Development", "Mobile App Development", "Data Science", "Machine Learning" gibi alanlardaki uzmanlık seviyelerinizi görselleştiren ilerleme çubukları mevcuttur.
   - Hakkınızda kısa bir biyografi ve profesyonel referanslar yer alır.

3. **İletişim Sayfası (Contact):**
   - Kullanıcılar tarafından kolayca iletişim sağlanabilmesi için bir form alanı içerir.
   - Formda isim, e-posta, telefon ve mesaj gibi alanlar bulunur.
   - İletişim bilgileri (e-posta, telefon ve adres) ikonlarla birlikte şık bir şekilde gösterilir.

4. **Projeler ve Referanslar:**
   - "References" bölümü, geçmiş çalışmalarınızı ve müşteri yorumlarını sergileyebileceğiniz bir alan sunar.
   - Owl Carousel kullanılarak dinamik bir kaydırma efekti ile kullanıcı dostu bir deneyim sağlanmıştır.

---

### Teknik Detaylar
- **CSS Dosyaları:**
  - `main.css`: Tüm temel stil düzenlemeleri bu dosyada yapılmıştır.
  - `lightbox.min.css` ve `owl.carousel.min.css`: Harici kütüphanelerden gelen stiller.
- **JavaScript Kullanımı:**
  - `Owl Carousel` eklentisi ile kaydırma efektleri uygulanmıştır.
  - `jquery.min.js` dosyası, temel JavaScript işlemleri için kullanılmıştır.
- **Görseller:** Proje, `img/` klasöründeki görsellerle zenginleştirilmiştir.

---

Projenin Amacı
SCSS Kullanımı: Projede, geleneksel CSS yerine SCSS kullanılmıştır. Bu, daha modüler ve organize bir kod yapısı sağlar. SCSS'in sağladığı değişkenler, mixin'ler ve nested yapı sayesinde, stil dosyaları daha esnek ve sürdürülebilir hale getirilmiştir.
Kişisel Portföy Tanıtımı: Bu proje, freelance hizmetlerinizin profesyonel bir şekilde sergilenmesi için bir platform oluşturmayı hedefler.
Modern Web Tasarımı: Proje, kullanıcı dostu ve estetik bir arayüzle dikkat çekmeyi amaçlar.
SCSS'in Projedeki Rolü
Modüler Yapı:

SCSS dosyaları farklı bölümlere ayrılarak (örneğin _variables.scss, _mixins.scss, _base.scss), kodun okunabilirliği artırılmış ve düzenli bir yapı oluşturulmuştur.
Tasarım değişiklikleri hızlıca uygulanabilir, çünkü SCSS'in değişkenler ve mixin'ler gibi özellikleri kullanılmıştır.
Değişkenler (Variables):

Renk paleti, yazı tipleri ve diğer tasarım öğeleri SCSS değişkenleri kullanılarak tanımlanmıştır.
Örneğin, $primary-color veya $font-family gibi değişkenler sayesinde tutarlı bir tasarım sağlanmıştır.
Mixin'ler ve Fonksiyonlar:

Tekrarlayan stil kuralları mixin'ler kullanılarak modüler hale getirilmiştir.
Örneğin, @mixin ile medya sorguları veya buton tasarımları daha kolay bir şekilde yönetilebilir.
Nested (İç İçe Yazım):

SCSS'in iç içe yazım özelliği sayesinde HTML yapısıyla birebir eşleşen bir stil yapısı oluşturulmuştur.
Bu, hem kodun okunabilirliğini artırır, hem de stil dosyalarının yönetimini kolaylaştırır.
Projenin SCSS ile Geliştirilmesinin Avantajları
Kolay Yönetim: Proje büyüdükçe SCSS'in sağladığı modüler yapı sayesinde stil dosyalarının yönetimi kolaylaşır.
Daha Az Tekrar: Mixin'ler ve değişkenler, kod tekrarını minimuma indirerek daha temiz bir stil dosyası oluşturur.
Hızlı Değişim: Tasarımda yapılacak değişiklikler, SCSS değişkenleri üzerinden kolayca uygulanabilir.
Profesyonel Görünüm: SCSS ile oluşturulan düzenli yapı, projenin profesyonelliğini artırır.
Eğer SCSS yapısını daha da geliştirmek isterseniz, şu adımları düşünebilirsiniz:

Daha İleri Düzey Mixin'ler: Örneğin, butonlar için farklı renk ve boyut seçeneklerini tek bir mixin ile dinamik hale getirebilirsiniz.
BEM (Block Element Modifier) Yaklaşımı: SCSS sınıflarını BEM metodolojisiyle organize ederek daha tutarlı bir yapıya ulaşabilirsiniz.
SCSS Map Kullanımı: Renk paletleri veya diğer tekrarlayan değerler için SCSS map yapısını kullanabilirsiniz.
