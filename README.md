# NER-Sarthi

**AI-Powered Logistics & Accessibility Intelligence for North East India**

🔗 **Live demo:** [saarthi-ner.vercel.app](https://saarthi-ner.vercel.app)

NER-Sarthi is a web dashboard that helps visualise logistics routes and accessibility across the North Eastern Region (NER) of India, combining interactive maps with data charts in a clean, responsive interface.

---

## ✨ Features

- 🗺️ **Interactive maps** powered by Leaflet / React-Leaflet
- 📊 **Data visualisation** with Recharts (trends, comparisons, insights)
- 🧭 **Multi-page navigation** with React Router
- 📱 **Responsive UI** styled with Tailwind CSS
- ⚡ **Fast dev and build** experience via Vite

<!-- Add or edit the list above to match the exact pages/modules in src/ -->

---

## 🛠️ Tech Stack

| Area | Tools |
| --- | --- |
| Framework | React 18, TypeScript |
| Build tool | Vite 5 |
| Styling | Tailwind CSS 3, PostCSS, Autoprefixer, clsx, tailwind-merge |
| Maps | Leaflet, React-Leaflet |
| Charts | Recharts |
| Routing | React Router DOM 6 |
| Icons | Lucide React |
| Deployment | Vercel |

---

## 📁 Project Structure

```
saarthi-NER/
├── dist/                 # Production build output
├── src/                  # Application source code
├── index.html            # App entry HTML
├── package.json          # Dependencies and scripts
├── tailwind.config.js    # Tailwind configuration
├── postcss.config.js     # PostCSS configuration
├── tsconfig*.json        # TypeScript configuration
└── vite.config.ts        # Vite configuration
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18 or later
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/KrishnaAsati16/saarthi-NER.git
cd saarthi-NER

# Install dependencies
npm install
```

### Run locally

```bash
npm run dev
```

Then open the URL shown in your terminal (usually `http://localhost:5173`).

### Build for production

```bash
npm run build
npm run preview   # preview the production build locally
```

### Lint

```bash
npm run lint
```

---

## 📜 Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Type-check and build for production |
| `npm run preview` | Serve the production build locally |
| `npm run lint` | Run ESLint |

---

## ☁️ Deployment

The app is deployed on [Vercel](https://vercel.com). To deploy your own copy:

1. Push the repo to your GitHub account.
2. Import it in Vercel.
3. Use the defaults: **Build command** `npm run build`, **Output directory** `dist`.

---

## 🤝 Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 🙏 Acknowledgements

- Original project by [rishabbhhh-w](https://github.com/rishabbhhh-w/saarthi-NER)
- Map data by [OpenStreetMap](https://www.openstreetmap.org/) contributors

## 📄 License

Add a license of your choice (e.g. MIT) and update this section.
