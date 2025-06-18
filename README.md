### English Version of the README

---

# 🌟 Personal Portfolio and Freelance Service Website

This project is a modernly designed website aimed at showcasing your personal portfolio or freelance services. It is built using HTML, CSS, and JavaScript.

---

## 🚀 General Structure and Features
- **💻 HTML and CSS Usage:** The pages are structured with HTML and styled with CSS. The main stylesheet file is `main.css`.
- **📱 Responsive Design:** The website offers a seamless appearance across devices, from mobile to desktop.
- **📦 Modern Libraries:**
  - Google Fonts
  - Font Awesome
  - Animate.css
  - Owl Carousel  
These libraries provide enhanced typography, icons, animations, and carousel effects.

---

## 🌐 Page Overview

### 1️⃣ **Home Page**
- 👋 A welcoming header and short descriptions greet users.
- 🌐 A navigation menu provides easy access to other pages in your portfolio.

### 2️⃣ **About Page**
- 🧑‍💻 Introduces your information and skills.
- 🛠️ Progress bars visualize expertise in areas like "Web Development," "Mobile App Development," "Data Science," and "Machine Learning."
- ✍️ Includes a brief biography and professional references.

### 3️⃣ **Contact Page**
- 📬 A contact form with fields for name, email, phone, and message.
- 📍 Stylishly presented contact details (email, phone, and address) with icons.

### 4️⃣ **Projects and References**
- 📝 Displays past work and client testimonials.
- 🖼️ Offers a dynamic user experience with Owl Carousel.

---

## 🛠️ Technical Details

### **CSS Files**
- 🎨 `main.css`: Contains all primary styling.
- 🌟 `lightbox.min.css` and `owl.carousel.min.css`: Styles from external libraries.

### **JavaScript Usage**
- 🎢 Owl Carousel plugin for carousel effects.
- 🛠️ `jquery.min.js` for basic JavaScript operations.

### **Images**
- 📂 Images are stored in the `img/` folder.

---

## 🎯 Project Goals
- **💼 Personal Portfolio Showcase:** Aims to professionally present your freelance services.
- **✨ Modern Web Design:** Delivers a user-friendly and aesthetically pleasing interface.
- **📈 SCSS Usage:** Ensures a more modular and sustainable styling approach.

---

## 🎨 Role of SCSS in the Project

### 📦 **Modular Structure**
- SCSS files are divided into sections such as:
  - `_variables.scss`
  - `_mixins.scss`
  - `_base.scss`  
This modular structure improves readability and organization.

### 🎨 **Variables**
- Design elements like color palettes and fonts are defined using variables. For example:
  ```scss
  $primary-color: #3498db;
  $font-family: 'Roboto', sans-serif;
  ```

### 🪄 **Mixins and Functions**
- Repetitive style rules are modularized using mixins:
  ```scss
  @mixin flex-center {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  ```

### 📂 **Nested Structure**
- SCSS's nesting feature mirrors the HTML structure, making it easier to manage:
  ```scss
  .navbar {
    background-color: $primary-color;

    .nav-item {
      color: white;
      &:hover {
        color: darken($primary-color, 10%);
      }
    }
  }
  ```

---

## 🌟 Advantages of Using SCSS
- **📋 Easy Management:** Modular structure makes stylesheets easier to manage as the project grows.
- **🔄 Less Repetition:** Mixins and variables minimize code repetition, creating cleaner stylesheets.
- **⚡ Quick Changes:** Design updates can be applied swiftly through variables.
- **🎨 Professional Appearance:** A structured approach ensures a polished, professional result.

---

## 📌 Further Development Suggestions
- **🎨 Advanced Mixins:** Create dynamic button mixins for different colors and sizes.
- **🏗️ BEM Methodology:** Organize SCSS classes using the Block-Element-Modifier approach for consistency.
- **🗺️ SCSS Map Usage:** Use SCSS maps for color palettes and other repetitive values.
  ```scss
  $colors: (
    primary: #3498db,
    secondary: #2ecc71,
    danger: #e74c3c
  );

  .btn {
    background-color: map-get($colors, primary);
  }
  ```

---

### 🛠️ Suggested SCSS File Structure
```
scss/
├── _variables.scss
├── _mixins.scss
├── _base.scss
├── _layout.scss
├── _components.scss
├── _utilities.scss
```

Aşağıda, istediğiniz bilgileri daha düzenli, okunabilir ve görsel olarak çekici bir hale getirilmiş şekilde sunuyorum. Bu düzenlemeyi README dosyanızda kullanabilirsiniz:

🌟 Kişisel Portföy ve Freelance Hizmet Web Sitesi
Bu proje, kişisel portföyünüzü veya freelance hizmetlerinizi tanıtmak için tasarlanmış, modern bir tasarım anlayışı sergileyen bir web sitesi projesidir. HTML, CSS ve JavaScript kullanılarak oluşturulmuştur.

🚀 Genel Yapı ve Özellikler
💻 HTML ve CSS Kullanımı: Sayfalar, HTML ile yapılandırılmış ve CSS ile şık bir tasarım uygulanmıştır. Ana stil dosyası: main.css.
📱 Responsive Tasarım: Mobil cihazlardan masaüstü bilgisayarlara kadar her boyutta kusursuz bir görünüm sunar.
📦 Modern Kütüphaneler:
Google Fonts
Font Awesome
Animate.css
Owl Carousel
Bu kütüphaneler, gelişmiş tipografi, ikonlar ve animasyonlar sağlar.
🌐 Sayfa İncelemesi
1️⃣ Ana Sayfa (Home)
👋 Kullanıcıyı karşılayan başlık ve kısa açıklamalar.
🌐 Hızlı erişim sağlayan navigasyon menüsü.
2️⃣ Hakkımda Sayfası (About)
🧑‍💻 Kendi bilgileriniz ve yeteneklerinizin tanıtımı.
🛠️ İlerleme çubukları ile görselleştirilmiş uzmanlık seviyeleri.
✍️ Kısa biyografi ve profesyonel referanslar.
3️⃣ İletişim Sayfası (Contact)
📬 İsim, e-posta, telefon ve mesaj alanları içeren iletişim formu.
📍 Şık ikonlarla desteklenmiş iletişim bilgileri.
4️⃣ Projeler ve Referanslar (References)
📝 Geçmiş projeler ve müşteri yorumları.
🖼️ Owl Carousel ile dinamik kaydırma efekti.
🛠️ Teknik Detaylar
CSS Dosyaları
🎨 main.css: Temel stil düzenlemeleri.
🌟 lightbox.min.css ve owl.carousel.min.css: Ek kütüphane stilleri.
JavaScript Kullanımı
🎢 Owl Carousel eklentisi ile kaydırma efektleri.
🛠️ jquery.min.js dosyası ile temel işlemler.
Görseller
📂 Görseller, img/ klasöründe saklanmıştır.
🎯 Projenin Amacı
💼 Kişisel Portföy Tanıtımı: Freelance hizmetlerinizi profesyonel bir şekilde sergiler.
✨ Modern Web Tasarımı: Kullanıcı dostu ve estetik bir arayüz sunar.
📈 SCSS Kullanımı: Daha modüler ve sürdürülebilir bir stil yapısı sağlar.
🎨 SCSS'in Projedeki Rolü
📦 Modüler Yapı
SCSS dosyaları farklı bölümlere ayrılmıştır:
_variables.scss
_mixins.scss
_base.scss
Bu modüler yapı, kodun okunabilirliğini artırır.
🎨 Değişkenler (Variables)
Renk paleti, yazı tipleri vb. tasarım öğeleri değişkenlerle tanımlanmıştır. Örneğin:
$primary-color: #3498db;
$font-family: 'Roboto', sans-serif;
🪄 Mixin'ler ve Fonksiyonlar
Tekrarlayan stil kuralları için mixin'ler oluşturulmuştur:
@mixin flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
📂 Nested Yapı
SCSS'in iç içe yazım özelliği ile düzenli bir yapı sağlanmıştır:
.navbar {
  background-color: $primary-color;

  .nav-item {
    color: white;
    &:hover {
      color: darken($primary-color, 10%);
    }
  }
}
🌟 SCSS Kullanımının Avantajları
📋 Kolay Yönetim: Modüler yapı sayesinde stil dosyalarının yönetimi kolaydır.
🔄 Daha Az Tekrar: Mixin'ler ve değişkenler ile tekrarlar azaltılır.
⚡ Hızlı Değişim: Tasarım değişiklikleri, değişkenler üzerinden hızla uygulanır.
🎨 Profesyonel Görünüm: Daha düzenli bir yapı sağlanır.
📌 Ek Geliştirme Önerileri
🎨 İleri Düzey Mixin'ler: Farklı renk ve boyutlar için dinamik buton mixin'leri.
🏗️ BEM Yaklaşımı: SCSS sınıflarını BEM metodolojisi ile organize edin.
🗺️ SCSS Map Kullanımı: Renk paletleri ve diğer değerler için SCSS map yapısı.
$colors: (
  primary: #3498db,
  secondary: #2ecc71,
  danger: #e74c3c
);

.btn {
  background-color: map-get($colors, primary);
}
🛠️ Önerilen SCSS Dosya Yapısı
scss/
├── _variables.scss
├── _mixins.scss
├── _base.scss
├── _layout.scss
├── _components.scss
├── _utilities.scss
