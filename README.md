# push-streak-360-day-start-day-3

## 📅 Day 3 - 12 Mei 2025  
### 🧭 Fokus: Hero Section — Pintu Gerbang yang Harus Mempesona

---

### ✨ Tujuan Hari Ini
Hari ini aku mulai membangun **Hero Section**, bagian paling atas dan krusial dari landing page. Ibaratnya ini "wajah pertama" yang bakal dilihat pengunjung saat mereka membuka website. Jadi, penting banget tampilannya rapi, informatif, dan tentu saja menarik. Aku ingin bagian ini menyampaikan value utama secara singkat, padat, dan powerful.

---

### ⚒️ Apa yang Dilakukan?

#### 1. Menyusun Struktur HTML
Aku membuat struktur HTML yang terdiri dari dua bagian besar:
- **Teks Promosi:** Headline utama, subheadline/tagline, dan tombol CTA.
- **Ilustrasi Visual:** Gambar pendukung agar tampilan lebih hidup dan profesional.

```html
<section class="hero">
  <div class="hero-content">
    <h1>Buat Web yang Ngomong Banyak Tanpa Banyak Kata.</h1>
    <p>Kami bantu kamu bangun website yang bukan cuma cantik, tapi juga konversi tinggi.</p>
    <a href="#contact" class="cta-button">Mulai Sekarang</a>
  </div>
  <div class="hero-image">
    <img src="assets/images/hero-banner.svg" alt="Gambar Hero Section">
  </div>
</section>

.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  padding: 60px 20px;
  background-color: #f9f9f9;
}

.hero-content h1 {
  font-size: 2.8rem;
  font-weight: bold;
  color: #1d1d1d;
}

.cta-button {
  display: inline-block;
  background-color: #007bff;
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  margin-top: 20px;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #0056b3;
}

