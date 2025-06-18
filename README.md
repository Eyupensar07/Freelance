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

Tabii! Türkçe kısmı da İngilizce kısmı gibi modern ve düzenli bir şekilde yazıyorum. Hem başlıklar hem de madde işaretleri ile aynı düzeni sağlayacağım. Aşağıda düzenlenmiş Türkçe kısmı bulabilirsin:

---

### Türkçe Sürüm (README)

---

# 🌟 Kişisel Portföy ve Freelance Hizmet Web Sitesi

Bu proje, kişisel portföyünüzü veya freelance hizmetlerinizi modern bir tasarımla sergilemenizi amaçlayan bir web sitesidir. HTML, CSS ve JavaScript kullanılarak geliştirilmiştir.

---

## 🚀 Genel Yapı ve Özellikler

- **💻 HTML ve CSS Kullanımı:** Sayfalar HTML ile oluşturulmuş, CSS ile şık bir şekilde stillendirilmiştir. Ana stil dosyası `main.css`’dir.
- **📱 Responsive Tasarım:** Site, mobilden masaüstüne kadar tüm cihazlarda kusursuz bir görünüm sunar.
- **📦 Modern Kütüphaneler:**
  - Google Fonts
  - Font Awesome
  - Animate.css
  - Owl Carousel  
Bu kütüphaneler, tipografi, ikon, animasyon ve kaydırıcı efektlerinde modern bir deneyim sağlar.

---

## 🌐 Sayfa İncelemesi

### 1️⃣ **Ana Sayfa**
- 👋 Karşılama başlığı ve kısa açıklamalar ziyaretçilere hoş geldiniz der.
- 🌐 Navigasyon menüsü ile diğer sayfalara kolay erişim sağlanır.

### 2️⃣ **Hakkımda Sayfası**
- 🧑‍💻 Kişisel bilgileriniz ve yetenekleriniz tanıtılır.
- 🛠️ “Web Development”, “Mobil Uygulama Geliştirme”, “Veri Bilimi” ve “Makine Öğrenmesi” gibi alanlarda uzmanlık seviyeleri ilerleme çubukları ile gösterilir.
- ✍️ Kısa bir biyografi ve profesyonel referanslar bulunur.

### 3️⃣ **İletişim Sayfası**
- 📬 Ad, e-posta, telefon ve mesaj alanlarından oluşan bir iletişim formu vardır.
- 📍 E-posta, telefon ve adres bilgileri ikonlarla birlikte şık biçimde sunulur.

### 4️⃣ **Projeler ve Referanslar**
- 📝 Geçmişte yapılan işler ve müşteri yorumları sergilenir.
- 🖼️ Owl Carousel ile dinamik bir kullanıcı deneyimi sunulur.

---

## 🛠️ Teknik Detaylar

### **CSS Dosyaları**
- 🎨 `main.css`: Tüm ana stilleri içerir.
- 🌟 `lightbox.min.css` ve `owl.carousel.min.css`: Harici kütüphanelerin stilleri.

### **JavaScript Kullanımı**
- 🎢 Carousel efektleri için Owl Carousel eklentisi kullanılır.
- 🛠️ Temel JavaScript işlemleri için `jquery.min.js` kullanılır.

### **Görseller**
- 📂 Tüm görseller `img/` klasöründe saklanır.

---

## 🎯 Proje Amaçları

- **💼 Kişisel Portföy Sunumu:** Freelance hizmetlerinizi profesyonelce sergilemeyi hedefler.
- **✨ Modern Web Tasarımı:** Kullanıcı dostu ve estetik bir arayüz sunar.
- **📈 SCSS Kullanımı:** Daha modüler ve sürdürülebilir stil yönetimi sağlar.

---

## 🎨 Projede SCSS’in Rolü

### 📦 **Modüler Yapı**
- SCSS dosyaları bölümlere ayrılarak daha okunabilir ve düzenli hale getirilmiştir:
  - `_variables.scss`
  - `_mixins.scss`
  - `_base.scss`

### 🎨 **Değişkenler**
- Renk paletleri ve yazı tipleri gibi tasarım ögeleri değişkenlerle tanımlanır:
  ```scss
  $primary-color: #3498db;
  $font-family: 'Roboto', sans-serif;
  ```

### 🪄 **Mixin ve Fonksiyonlar**
- Tekrar eden stil kuralları mixin’lerle modülerleştirilir:
  ```scss
  @mixin flex-center {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  ```

### 📂 **İç İçe Yapı**
- SCSS’in iç içe yazım özelliği HTML ile uyumlu stil yazmayı kolaylaştırır:
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

## 🌟 SCSS Kullanımının Avantajları

- **📋 Kolay Yönetim:** Modüler yapı sayesinde büyük projeler kolayca yönetilir.
- **🔄 Daha Az Tekrar:** Mixin ve değişkenler kod tekrarını azaltır, daha temiz CSS sunar.
- **⚡ Hızlı Değişim:** Tasarım güncellemeleri değişkenler ile hızlıca yapılabilir.
- **🎨 Profesyonel Görünüm:** Düzenli yapı sayesinde profesyonel sonuç elde edilir.

---

## 📌 Ek Geliştirme Önerileri

- **🎨 Gelişmiş Mixin’ler:** Farklı renk ve boyutlar için dinamik buton mixin’leri oluşturun.
- **🏗️ BEM Metodolojisi:** SCSS sınıflarını Block-Element-Modifier yaklaşımıyla düzenleyin.
- **🗺️ SCSS Map Kullanımı:** Renk paletleri ve tekrar eden değerler için SCSS map kullanın.
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

### 🛠️ Önerilen SCSS Dosya Yapısı
```
scss/
├── _variables.scss
├── _mixins.scss
├── _base.scss
├── _layout.scss
├── _components.scss
├── _utilities.scss
```

---

Dilersen bu kısmı README dosyana ekleyebilirsin. Eğer istersen Markdown dosyasına eklenmiş halini de gönderebilirim!
