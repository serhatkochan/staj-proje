# 🎬 React TV Guide

## Proje Açıklaması

Bu proje, **TV Maze API** kullanarak popüler TV şovlarını listeleyen, detaylarını görüntüleyen ve favorilere ekleme gibi özellikler sunan bir React uygulamasıdır. Kullanıcılar istedikleri dizi veya programı arayabilir, detaylarını inceleyebilir ve favori listelerine ekleyebilirler.

---

## 📌 Yapılacaklar Listesi

### 1. **Ana Sayfa (TV Şovları Listesi)**

- Ana sayfada popüler TV şovları listelenecek.
- Her şov için **isim, afiş ve "Detayları Gör" butonu** yer alacak.
- Kullanıcı bir şovu arayabilecek ve sonuçlar dinamik olarak filtrelenecek.
- **Tailwind CSS ile şık bir tasarım uygulanacak.**

### 2. **Şov Detay Sayfası**

- Kullanıcı bir şovun detaylarını görmek için "Detayları Gör" butonuna tıklayacak.
- Şovun **adı, afişi, açıklaması, yayın tarihi ve oyuncuları** gösterilecek.
- Kullanıcı şovu **favorilerine ekleyip çıkarabilecek** (Redux Toolkit kullanılacak).
- "Geri Dön" butonu ile ana sayfaya yönlendirme yapılacak.

### 3. **Favoriler Sayfası**

- Kullanıcı **favorilerine eklediği şovları bu sayfada görebilecek**.
- Favorilere eklenen şovlar **Redux Toolkit ile state yönetimi kullanılarak saklanacak**.
- Kullanıcı favori listesinden şovları kaldırabilecek.

### 4. **Ekstra Sayfalar**

- Kullanılabilir diğer API'leri analiz ederek, uygulamana entegre edebileceğin zengin listeleme ve detay sayfaları oluşturabilirsin.

### 5. **Ek Özellikler**

- **Pagination:** API'den çektiğin veriler çok fazla ise sayfalama ekle.
- **Detaylı Arama Filtreleri:** Tür, yayın yılı gibi filtreleme seçenekleri ekleyerek aramayı detaylandır.
- **Responsive Tasarım:** Tailwind CSS kullanarak, uygulamanın tüm cihazlarda uyumlu çalışmasını sağla.

---

## 🎯 Öğreneceklerin

✅ **React Router** kullanarak sayfa yönlendirme yapma.\
✅ **fetch API ile dış veri kaynaklarına bağlanma.**\
✅ **Redux Toolkit ile state yönetimi yapma.**\
✅ **Tailwind CSS kullanarak modern bir arayüz tasarlama.**\
✅ **TypeScript ile güvenli ve ölçeklenebilir bir React uygulaması geliştirme.**\
✅ **JavaScript Array Metodları (filter, find vb.) ile veri işlemleri yapma.**

---

## 🚀 Proje Kurulumu

Projeyi **Vite** kullanarak oluşturabilirsin. Eğer daha önce yapmadıysan, şu komutları çalıştırarak hızlıca başlatabilirsin:

```sh
npm create vite@latest react-tv-guide --template react-ts
cd react-tv-guide
npm install
npm run dev
```

Ayrıca, **React Router, Redux Toolkit ve TypeScript destekli paketleri** projeye eklemelisin:

```sh
npm install react-router-dom @reduxjs/toolkit react-redux
```

### 📌 Dokümantasyonlar

- 🔗 [Vite Dokümantasyonu](https://vitejs.dev/guide/)
- 🔗 [React Dokümantasyonu](https://react.dev/)
- 🔗 [React Router Dokümantasyonu](https://reactrouter.com/en/main)
- 🔗 [Redux Toolkit Dokümantasyonu](https://redux-toolkit.js.org/)
- 🔗 [Tailwind CSS Dokümantasyonu](https://tailwindcss.com/docs/installation)

Bu projeyi tamamladıktan sonra, **state yönetimi, API ile veri çekme, TypeScript kullanımı ve sayfa yönlendirme** konularında kendini geliştirmiş olacaksın! 🎬✨

**Bol şans! 🎥🍿**

