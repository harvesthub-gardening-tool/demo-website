# Harvest Hub - Demo Website

A modern, interactive showcase website for Harvest Hub, an innovative gardening tool system featuring smart garden nodes and monitoring hubs.

## About Harvest Hub

Harvest Hub is a comprehensive gardening solution that combines:
- **Smart Garden Nodes**: IoT sensors placed in your garden to monitor plant health
- **Harvest Hub Device**: Central hub that collects and processes data from garden nodes
- **Mobile Application**: Real-time monitoring and management of your garden

This website provides an immersive demonstration of the Harvest Hub ecosystem with interactive 3D models and detailed product information.

## Features

- 🎨 Modern, responsive design with Tailwind CSS
- 🌐 Interactive 3D product visualizations using Three.js
- 📱 Mobile-first approach
- ⚡ Built with Next.js 15 and React 19
- 🎭 Smooth animations and transitions
- 🖼️ Optimized image and asset loading

## Tech Stack

- **Framework**: Next.js 15.0.2
- **UI Library**: React 19
- **Styling**: Tailwind CSS
- **3D Graphics**: Three.js
- **Icons**: Lucide React
- **Language**: TypeScript

## Getting Started

### Prerequisites

- Node.js 20.x or higher
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/harvesthub-gardening-tool/demo-website.git
cd demo-website
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
├── src/
│   ├── app/
│   │   ├── components/     # React components
│   │   │   ├── IntroView.tsx
│   │   │   ├── GeneralView.tsx
│   │   │   ├── NodeView.tsx
│   │   │   ├── HubView.tsx
│   │   │   ├── QuadrillageView.tsx
│   │   │   └── LastView.tsx
│   │   ├── page.tsx        # Main page
│   │   ├── layout.tsx      # Root layout
│   │   └── globals.css     # Global styles
├── public/
│   ├── images/            # Image assets
│   ├── models/            # 3D model files (.obj, .mtl)
│   └── fonts/             # Custom fonts
└── Dockerfile             # Container configuration
```

## Docker Support

Build and run with Docker:

```bash
docker build -t harvest-hub-website .
docker run -p 3000:3000 harvest-hub-website
```

## License

This project is private and proprietary to Harvest Hub.

## Contact

For more information about Harvest Hub, visit our website or contact the development team.
