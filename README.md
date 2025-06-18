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

🌟 Kişisel Portföy ve Freelance Hizmet Web Sitesi
Bu proje, kişisel portföyünüzü veya freelance hizmetlerinizi modern bir tasarımla sergilemenizi amaçlayan bir web sitesidir. HTML, CSS ve JavaScript kullanılarak geliştirilmiştir.

🚀 Genel Yapı ve Özellikler
💻 HTML ve CSS Kullanımı: Sayfalar HTML ile yapılandırılmış, main.css dosyası ile şık bir görünüm kazandırılmıştır.

📱 Responsive Tasarım: Mobil, tablet ve masaüstü cihazlarda kusursuz bir kullanıcı deneyimi sunar.

📦 Kullanılan Modern Kütüphaneler:

Google Fonts

Font Awesome

Animate.css

Owl Carousel
Bu kütüphaneler sayesinde daha estetik yazı tipleri, ikonlar, animasyonlar ve kaydırıcı efektleri elde edilmiştir.

🌐 Sayfa İncelemesi
1️⃣ Ana Sayfa
👋 Karşılama başlığı ve kısa açıklamalarla ziyaretçilere hoş geldiniz mesajı sunulur.

🌐 Navigasyon menüsü sayesinde diğer sayfalara hızlı geçiş sağlanır.

2️⃣ Hakkımda Sayfası
🧑‍💻 Kişisel bilgileriniz ve yetenekleriniz tanıtılır.

🛠️ "Web Development", "Mobil Uygulama Geliştirme", "Veri Bilimi", "Makine Öğrenmesi" gibi alanlarda ilerleme çubukları ile uzmanlık seviyeleri gösterilir.

✍️ Kısa bir biyografi ve profesyonel referanslara yer verilir.

3️⃣ İletişim Sayfası
📬 Ad, e-posta, telefon ve mesaj alanlarını içeren bir iletişim formu yer alır.

📍 E-posta, telefon ve adres bilgileri ikonlarla birlikte şık bir şekilde sunulur.

4️⃣ Projeler ve Referanslar
📝 Geçmişte yapılan işler ve müşteri yorumları sergilenir.

🖼️ Owl Carousel ile etkileşimli bir proje gösterimi sağlanır.

🛠️ Teknik Detaylar
CSS Dosyaları
🎨 main.css: Tüm temel stil ayarlarını içerir.

🌟 lightbox.min.css ve owl.carousel.min.css: Harici kütüphanelere ait stiller.

JavaScript Kullanımı
🎢 Owl Carousel eklentisi, slayt ve kaydırma efektleri için kullanılır.

🛠️ jquery.min.js: Temel JavaScript işlemlerinde destek sağlar.

Görseller
📂 Tüm görseller img/ klasörü içinde saklanmaktadır.

🎯 Projenin Amacı
💼 Kişisel Portföy Sunumu: Hizmetlerinizi profesyonel bir arayüzle tanıtmayı hedefler.

✨ Modern Web Tasarımı: Estetik ve kullanıcı dostu bir görünüm sağlar.

📈 SCSS Kullanımı: Daha modüler ve sürdürülebilir bir stil yönetimi sunar.

🎨 Projede SCSS'in Rolü
📦 Modüler Yapı
SCSS dosyaları mantıklı bölümlere ayrılarak daha okunabilir ve düzenli hale getirilmiştir:

_variables.scss

_mixins.scss

_base.scss

🎨 Değişkenler (Variables)
Renk paletleri ve yazı tipleri gibi tasarım ögeleri değişkenlerle tanımlanmıştır:

scss
Copy
Edit
$primary-color: #3498db;
$font-family: 'Roboto', sans-serif;
🪄 Mixin'ler ve Fonksiyonlar
Tekrarlayan stil kurallarını yeniden kullanmak için mixin'ler oluşturulmuştur:

scss
Copy
Edit
@mixin flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
📂 İç İçe Yapı (Nesting)
SCSS’in iç içe yazım özelliği sayesinde HTML yapısı ile uyumlu stil tanımlamaları yapılır:

scss
Copy
Edit
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
📋 Kolay Yönetim: Dosyalar bölümlere ayrıldığı için büyüyen projelerde yönetim kolaylaşır.

🔄 Daha Az Tekrar: Değişken ve mixin kullanımı ile stil tekrarları azaltılır.

⚡ Hızlı Değişim: Renk veya yazı tipi gibi öğelerde değişiklikler tek yerden yapılabilir.

🎨 Profesyonel Görünüm: Düzenli yapı sayesinde daha kaliteli sonuçlar elde edilir.

📌 Ek Geliştirme Önerileri
🎨 İleri Düzey Mixin'ler: Farklı renk ve boyutlarda butonlar için mixin yapısı geliştirin.

🏗️ BEM Yaklaşımı: SCSS sınıflarını BEM (Block Element Modifier) metodolojisi ile organize edin.

🗺️ SCSS Map Kullanımı: Renk paletleri gibi değerleri SCSS map ile tanımlayın:

scss
Copy
Edit
$colors: (
  primary: #3498db,
  secondary: #2ecc71,
  danger: #e74c3c
);

.btn {
  background-color: map-get($colors, primary);
}
🛠️ Önerilen SCSS Dosya Yapısı
Copy
Edit
scss/
├── _variables.scss
├── _mixins.scss
├── _base.scss
├── _layout.scss
├── _components.scss
├── _utilities.scss
