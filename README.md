# 📝 SwiftNote Studio

Modern ve dinamik bir not defteri web uygulaması. Notlarınızı kategorize edin, etiketleyin, arayın ve organize edin.


## ✨ Özellikler

- 🎨 **Modern Tasarım**: Glass morphism efektleri ve smooth animasyonlar
- 📁 **Kategori Sistemi**: Notlarınızı kategorilere ayırın
- 🏷️ **Etiket Sistemi**: Notlarınıza etiketler ekleyin
- 🔍 **Güçlü Arama**: Başlık, içerik ve etiketlerde arama yapın
- ⭐ **Favoriler**: Önemli notlarınızı favorilere ekleyin
- 💾 **Otomatik Kaydetme**: Verileriniz güvenle saklanır
- 📱 **Responsive Tasarım**: Tüm cihazlarda mükemmel çalışır
- ⚡ **Hızlı Performance**: Instant arama ve smooth geçişler

## 🛠️ Teknolojiler

### Frontend
- **React 18** - Modern UI framework
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **Zustand** - State management
- **Lucide Icons** - Beautiful icon set
- **date-fns** - Date formatting
- **Vite** - Fast build tool

### Backend & Database
- **Supabase** - Backend as a Service
- **PostgreSQL** - Robust database
- **Real-time subscriptions** - Live updates

## 🖼️ Proje Görselleri

### Ana Sayfa Arayüzü
![SwiftNote Studio Arayüzü]()



## 🚀 Kurulum

### Gereksinimler
- Node.js 18+ 
- npm veya yarn

### Adımlar

1. **Projeyi klonlayın**
```bash
git clone https://github.com/Can-Ozan/swiftnote-studio.git
cd swiftnote-studio
```

2. **Bağımlılıkları yükleyin**
```bash
npm install
# veya
yarn install
```

3. **Development server'ı başlatın**
```bash
npm run dev
# veya
yarn dev
```

4. **Tarayıcınızda açın**
```
http://localhost:8080
```

## 📖 Kullanım

### Not Oluşturma
1. **"Yeni Not"** butonuna tıklayın
2. Başlık ve içerik ekleyin
3. Kategori seçin
4. Etiketler ekleyin (opsiyonel)
5. **"Kaydet"** butonuna tıklayın

### Not Düzenleme
1. Düzenlemek istediğiniz nota tıklayın
2. **"Düzenle"** butonuna tıklayın
3. Değişikliklerinizi yapın
4. **"Kaydet"** ile kaydedin

### Arama ve Filtreleme
- **Arama çubuğu**: Notlarınızda hızlı arama yapın
- **Kategoriler**: Soldaki kategorilerden filtreleme yapın
- **Favoriler**: Favori notlarınızı görüntüleyin

### Klavye Kısayolları
- `Ctrl + Enter`: Notu kaydet
- `Esc`: Düzenlemeyi iptal et

## 🏗️ Proje Yapısı

```
src/
├── components/          # React bileşenleri
│   ├── ui/             # Shadcn/ui bileşenleri
│   ├── Header.tsx      # Üst başlık ve arama
│   ├── Sidebar.tsx     # Kategori navigasyonu
│   ├── NoteList.tsx    # Not listesi
│   └── NoteEditor.tsx  # Not editörü
├── store/              # Zustand store
│   └── noteStore.ts    # Not state yönetimi
├── types/              # TypeScript tip tanımları
│   └── note.ts         # Not tipleri
├── pages/              # Sayfa bileşenleri
│   └── Index.tsx       # Ana sayfa
└── lib/                # Yardımcı fonksiyonlar
    └── utils.ts        # Utility fonksiyonları
```

## 🎨 Tasarım Sistemi

### Renkler
- **Primary**: Deep Purple (`#7c3aed`)
- **Accent**: Cyan Blue (`#06b6d4`)
- **Background**: Dark theme with gradients
- **Glass Effects**: Backdrop blur ile modern görünüm

### Animasyonlar
- **Fade In**: Sayfa yüklenirken
- **Slide Up**: Liste elemanları için
- **Scale In**: Modal ve popup'lar için
- **Hover Effects**: Interactive elemanlar için

## 🔧 Geliştirme

### Available Scripts

```bash
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint

# Type check
npm run type-check
```

### Code Style
- **ESLint** ile kod kalitesi kontrolü
- **Prettier** ile kod formatlaması
- **TypeScript** ile tip güvenliği

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

## 📞 İletişim

- **Email**: yusufcanozan9@gmail.com
- **GitHub**: https://github.com/Can-Ozan/swiftnote-studio.git


---

**SwiftNote Studio** ile notlarınızı modern ve etkili bir şekilde yönetin! ✨
