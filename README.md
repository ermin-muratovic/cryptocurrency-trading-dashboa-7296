
# Simple Crypto Hub

A modern cryptocurrency dashboard built with React, TypeScript, and Tailwind CSS. Features real-time market data, interactive charts, and a sleek dark theme interface.

## Features

- 📊 Real-time cryptocurrency market statistics
- 📈 Interactive TradingView charts
- 🌙 Modern dark theme UI
- 📱 Fully responsive design
- ⚡ Fast and lightweight

## Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, Shadcn/UI
- **Charts**: TradingView Widget, Recharts
- **State Management**: TanStack Query
- **Routing**: React Router DOM
- **Icons**: Lucide React

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 18 or higher)
- npm or yarn package manager

## Local Development Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd simple-crypto-hub
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Start Development Server

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:8080`

### 4. Build for Production

```bash
npm run build
# or
yarn build
```

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Shadcn/UI components
│   ├── CryptoChart.tsx # Trading chart component
│   └── MarketStats.tsx # Market statistics component
├── pages/              # Page components
│   └── Index.tsx       # Main dashboard page
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
└── main.tsx           # Application entry point
```

## Configuration

### Environment Variables

This project doesn't require any environment variables for basic functionality. All market data is fetched from public APIs.

### Customization

- **Colors**: Modify the color scheme in `tailwind.config.ts`
- **Charts**: Update chart symbols and settings in `CryptoChart.tsx`
- **Market Data**: Customize displayed statistics in `MarketStats.tsx`

## Deployment

### Deploy to Lovable (Recommended)

1. Click the **Publish** button in the Lovable editor
2. Your app will be deployed to a Lovable subdomain (e.g., `yourapp.lovable.app`)
3. For custom domains, upgrade to a paid Lovable plan and configure in Project Settings

### Deploy to Vercel

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Deploy with default settings (Vite preset)

```bash
# Build command
npm run build

# Output directory
dist
```

### Deploy to Netlify

1. Push your code to GitHub
2. Connect your GitHub repository to Netlify
3. Set build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`

### Deploy to GitHub Pages

1. Install gh-pages:
```bash
npm install --save-dev gh-pages
```

2. Add deploy script to `package.json`:
```json
{
  "scripts": {
    "deploy": "gh-pages -d dist"
  }
}
```

3. Build and deploy:
```bash
npm run build
npm run deploy
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

## API Dependencies

This project uses the following external services:
- **TradingView**: For interactive cryptocurrency charts
- **Public Market APIs**: For real-time market statistics

No API keys are required for basic functionality.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For support and questions:
- Check the [Lovable Documentation](https://docs.lovable.dev/)
- Join the [Lovable Discord Community](https://discord.com/channels/1119885301872070706/1280461670979993613)

---

Built with ❤️ using [Lovable](https://lovable.dev)
