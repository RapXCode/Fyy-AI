# Fyy-AI - Advanced AI Chat Assistant

Fyy-AI adalah aplikasi chat AI canggih yang dikembangkan oleh **RapXCode (Rhafi Al Ghofar)** menggunakan teknologi Google Gemini AI. Aplikasi ini menyediakan pengalaman chat AI yang komprehensif dengan berbagai fitur canggih dan antarmuka yang modern.

## ✨ Fitur Utama

### 🤖 AI Chat yang Canggih
- **4 Model Gemini AI**: Gemini 2.5 Flash, 2.5 Flash Lite, 2.0 Flash, dan 2.0 Flash Lite
- **7 Mode Chat Khusus**: Umum, Coding, Matematika, Riset, Terjemahan, Analisis, dan Pemecahan Masalah
- **Respons Real-time**: Chat yang responsif dengan indikator typing
- **Riwayat Chat**: Penyimpanan dan manajemen percakapan

### 📁 Upload & Analisis File
- **Multi-format Support**: Gambar, PDF, DOC, DOCX, TXT
- **Preview File**: Tampilan preview untuk semua jenis file
- **AI Analysis**: Analisis konten file menggunakan AI
- **Drag & Drop**: Interface upload yang mudah

### 🎨 Generasi Gambar AI
- **HuggingFace Integration**: Generasi gambar berkualitas tinggi
- **Custom Prompts**: Kontrol penuh atas prompt generasi
- **Preview & Download**: Tampilan dan unduh hasil generasi

### 👤 Sistem Pengguna
- **Autentikasi Lengkap**: Login, register, dan manajemen profil
- **Mode Tamu**: Akses terbatas tanpa registrasi
- **Dashboard Pengguna**: Statistik dan manajemen akun
- **Pengaturan Kustomisasi**: Personalisasi pengalaman pengguna

### 🎯 Fitur Premium vs Tamu

#### Mode Tamu (Gratis)
- ✅ 10 pesan chat gratis
- ✅ 2 mode chat (Umum & Terjemahan)
- ✅ Upload file maksimal 5MB (2 file)
- ❌ Tanpa riwayat chat
- ❌ Tanpa input suara
- ❌ Tanpa dashboard

#### Mode Premium (Gratis dengan Registrasi)
- ✅ Pesan chat unlimited
- ✅ Semua 7 mode chat
- ✅ Upload file unlimited
- ✅ Riwayat chat tersimpan
- ✅ Input suara
- ✅ Dashboard lengkap
- ✅ Pengaturan advanced

## 🚀 Teknologi yang Digunakan

### Frontend
- **Next.js 15** - React framework dengan App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS v4** - Modern styling dengan design tokens
- **shadcn/ui** - Komponen UI yang konsisten
- **Radix UI** - Accessible UI primitives

### Backend & AI
- **Google Gemini AI** - Model AI terdepan
- **HuggingFace API** - Generasi gambar AI
- **Next.js API Routes** - Backend serverless
- **File Upload System** - Manajemen file terintegrasi

### State Management
- **React Context** - Global state management
- **Custom Hooks** - Reusable logic
- **SWR** - Data fetching dan caching

## 📦 Instalasi & Setup

### Prerequisites
- Node.js 18+ 
- npm atau yarn
- API Keys (Gemini AI, HuggingFace)

### Environment Variables
Buat file `.env.local` dengan variabel berikut:

\`\`\`env
# Google Gemini AI
GEMINI_API_KEY=your_gemini_api_key_here

# HuggingFace (untuk generasi gambar)
HUGGINGFACE_API_KEY=your_huggingface_api_key_here

# Optional: Custom base URLs
NEXT_PUBLIC_APP_URL=http://localhost:3000
\`\`\`

### Instalasi
\`\`\`bash
# Clone repository
git clone <repository-url>
cd fyy-ai

# Install dependencies
npm install

# Setup environment
cp .env.example .env.local
# Edit .env.local dengan API keys Anda

# Run development server
npm run dev
\`\`\`

### Deployment
\`\`\`bash
# Build untuk production
npm run build

# Start production server
npm start
\`\`\`

## 🎨 Design System

### Color Palette
- **Primary**: Rose/Pink gradient untuk branding utama
- **Accent**: Complementary colors untuk highlights
- **Neutral**: Grayscale untuk teks dan backgrounds
- **Semantic**: Success, warning, error colors

### Typography
- **Headings**: Geist Sans dengan berbagai weights
- **Body**: Optimized untuk readability
- **Code**: Geist Mono untuk code blocks

### Layout
- **Mobile-first**: Responsive design
- **Flexbox**: Primary layout method
- **Grid**: Complex 2D layouts
- **Spacing**: Consistent 8px grid system

## 📱 Fitur Responsif

- **Desktop**: Full sidebar dengan semua fitur
- **Tablet**: Collapsible sidebar
- **Mobile**: Overlay sidebar dengan touch gestures
- **PWA Ready**: Installable sebagai aplikasi

## 🔒 Keamanan & Privasi

- **Client-side Processing**: Data tidak disimpan di server
- **Secure API Calls**: Encrypted communication
- **Guest Mode**: Privasi maksimal tanpa registrasi
- **File Security**: Temporary file storage

## 🛠️ Struktur Proyek

\`\`\`
fyy-ai/
├── app/                    # Next.js App Router
│   ├── api/               # API routes
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── ui/               # shadcn/ui components
│   ├── auth-provider.tsx # Authentication
│   ├── chat-interface.tsx # Main chat UI
│   └── ...               # Other components
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
└── public/              # Static assets
\`\`\`

## 🎯 Roadmap

### v1.1 (Coming Soon)
- [ ] Voice input implementation
- [ ] Chat export functionality
- [ ] Advanced file analysis
- [ ] Multi-language support

### v1.2 (Future)
- [ ] Team collaboration
- [ ] API access
- [ ] Plugin system
- [ ] Advanced analytics

## 👨‍💻 Developer

**Rhafi Al Ghofar (RapXCode)**
- Full-Stack Developer & AI Enthusiast
- 5+ tahun pengalaman development
- Spesialisasi: React, Next.js, AI/ML Integration

### Contact
- GitHub: [@RapXCode](https://github.com/RapXCode)
- LinkedIn: [Rhafi Al Ghofar](https://linkedin.com/in/rhafi-al-ghofar)
- Email: contact@rapxcode.com
- Portfolio: [rapxcode.com](https://rapxcode.com)

## 📄 License

MIT License - Lihat file [LICENSE](LICENSE) untuk detail lengkap.

## 🙏 Acknowledgments

- Google Gemini AI untuk teknologi AI terdepan
- HuggingFace untuk model generasi gambar
- Vercel untuk platform deployment
- shadcn/ui untuk komponen UI yang excellent
- Komunitas open source yang luar biasa

---

**Fyy-AI** - Masa depan interaksi AI dimulai dari sini! 🚀
\`\`\`

```json file="" isHidden
