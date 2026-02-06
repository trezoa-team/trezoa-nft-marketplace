# 🎨 Trezoa NFT Marketplace

<div align="center">

![Trezoa](https://img.shields.io/badge/Trezoa-NFT%20Marketplace-blue?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-15.3.2-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.2.7-38B2AC?style=for-the-badge&logo=tailwind-css)
![License](https://img.shields.io/badge/License-Commercial-green?style=for-the-badge)

**A Modern, Feature-Rich NFT Marketplace Template Built with Next.js 15 and React 19**

[Demo](#-demo-pages) • [Features](#-key-features) • [Installation](#-installation) • [Documentation](#-documentation)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Available Scripts](#-available-scripts)
- [Demo Pages](#-demo-pages)
- [Wallet Integration](#-wallet-integration)
- [Customization](#-customization)
- [Dark Mode](#-dark-mode)
- [Performance](#-performance)
- [Browser Support](#-browser-support)
- [Contributing](#-contributing)
- [License](#-license)
- [Support](#-support)

---

## 🎯 About

**Trezoa** is a premium NFT Marketplace template designed for creating modern, fast, and feature-rich blockchain applications. Built with the latest technologies including Next.js 15 App Router, React 19, and TailwindCSS, this template provides everything you need to launch your NFT marketplace quickly.

### 🌟 Perfect For

- 🖼️ NFT Marketplaces
- 🎮 Gaming Platforms
- 🎨 Digital Art Galleries
- 💎 Collectibles Platforms
- 🏦 DeFi Applications
- 🪙 Crypto Trading Platforms
- 🌐 Web3 Projects

---

## ✨ Key Features

### 🎨 **13+ Unique Home Pages**
- NFT Marketplace (Multiple Variants)
- Crypto Consultant Landing
- NFT Game Platform
- DAO Platform
- Crypto Mobile App
- Crypto Trading Platform
- ICO Landing Page
- NFT Aggregator

### 🛠️ **Core Marketplace Features**
- ✅ **Item Management**
  - Item Details Pages
  - Item Creation & Upload
  - Multiple Item Display Layouts
  - Item Properties & Levels
  - Rarity Attributes

- ✅ **Collections**
  - Collection Pages
  - Collection Details
  - Wide Sidebar Layout
  - Grid & List Views

- ✅ **User Profiles**
  - User Profile Pages
  - Edit Profile
  - User Activity Feed
  - Owned Items Display
  - Created Collections

- ✅ **Trading & Transactions**
  - Bid Functionality
  - Buy Now Option
  - Activity Timeline
  - Transaction History
  - Rankings & Leaderboards

### 🔐 **Web3 Integration**
- **MetaMask** Integration
- **Wallet Connect** Support
- Multiple Wallet Providers:
  - Coinbase Wallet
  - Bitski
  - Fortmatic
  - Torus
- Connection Status Management
- Account Display

### 🎨 **Design & UI**
- 📱 **Fully Responsive** - Mobile, Tablet, Desktop
- 🌙 **Dark/Light Mode** - Seamless theme switching
- 🎭 **Modern Animations** - Smooth transitions
- 🎨 **TailwindCSS** - Utility-first styling
- 📐 **Clean Layout** - Professional design
- ♿ **Accessibility** - WCAG compliant

### 🚀 **Performance**
- ⚡ **Next.js 15** - Latest features
- 🔥 **Turbopack** - Ultra-fast bundler
- 📦 **Code Splitting** - Optimized loading
- 🖼️ **Image Optimization** - Next.js Image
- 🎯 **SEO Optimized** - Meta tags & schema
- 📊 **Analytics Ready** - Easy integration

### 📄 **40+ Pre-built Pages**

#### Main Pages
- Multiple Home Variants (13+)
- About Us
- Contact
- Careers
- Case Studies
- Help Center
- Blog & Resources

#### NFT Pages
- Item Details
- Collections
- Create NFT
- Activity Feed
- Rankings
- User Profiles

#### Utility Pages
- Login & Authentication
- 404 Error Page
- Maintenance Mode
- Terms of Service
- Platform Status
- Newsletter Signup

---

## 🛠️ Tech Stack

### Core Technologies
```json
{
  "Framework": "Next.js 15.3.2",
  "UI Library": "React 19.1.0",
  "Styling": "TailwindCSS 3.2.7",
  "Package Manager": "npm/yarn/pnpm/bun"
}
```

### Key Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| **next** | 15.3.2 | React Framework with App Router |
| **react** | 19.1.0 | UI Library |
| **tailwindcss** | 3.2.7 | Utility-first CSS Framework |
| **metamask-react** | 2.7.0 | MetaMask Integration |
| **chart.js** | 4.4.9 | Data Visualization |
| **swiper** | 11.2.8 | Modern Slider |
| **tippy.js** | 6.3.7 | Tooltips |
| **bootstrap** | 5.3.6 | UI Components |
| **react-countdown** | 2.3.6 | Countdown Timers |

---

## 📁 Project Structure

```
trezoa-marketplace/
├── 📁 app/                          # Next.js 15 App Directory
│   ├── 📁 (homes)/                  # Home page variants
│   │   ├── home-1/                  # NFT Marketplace v1
│   │   ├── home-2/                  # NFT Marketplace v2
│   │   ├── home-7/                  # Crypto Consultant
│   │   ├── home-8/                  # NFT Game
│   │   ├── home-9/                  # DAO Platform
│   │   ├── home-10/                 # Crypto App
│   │   ├── home-11/                 # Crypto Trading
│   │   ├── home-12/                 # ICO Landing
│   │   └── home-13/                 # NFT Aggregator
│   │
│   ├── 📁 (pages)/                  # Main application pages
│   │   ├── about/                   # About page
│   │   ├── activity/                # Activity feed
│   │   ├── careers/                 # Careers page
│   │   ├── collection/[id]/         # Dynamic collection page
│   │   ├── collections/             # Collections list
│   │   ├── contact/                 # Contact page
│   │   ├── edit-profile/            # Profile editor
│   │   ├── item/[id]/               # Dynamic item details
│   │   ├── login/                   # Login page
│   │   ├── rankings/                # Rankings page
│   │   ├── user/[id]/               # User profile
│   │   └── wallet/                  # Wallet page
│   │
│   ├── 📁 (resources)/              # Resource pages
│   │   ├── blog/                    # Blog list
│   │   ├── help-center/             # Help center
│   │   ├── newsletter/              # Newsletter
│   │   ├── partners/                # Partners page
│   │   └── platform-status/         # Status page
│   │
│   ├── 📁 create/                   # NFT creation page
│   ├── layout.jsx                   # Root layout
│   ├── page.js                      # Home page
│   └── not-found.jsx                # 404 page
│
├── 📁 components/                   # React components
│   ├── 📁 common/                   # Shared components
│   │   ├── ModeChanger.jsx          # Dark/Light mode toggle
│   │   ├── ModalVideo.jsx           # Video modal
│   │   ├── Partners.jsx             # Partners section
│   │   └── Testimonials.jsx         # Testimonials
│   │
│   ├── 📁 create/                   # Creation components
│   │   ├── Create.jsx               # Main create form
│   │   └── FileUpload.jsx           # File uploader
│   │
│   ├── 📁 footer/                   # Footer components
│   │   ├── Footer1.jsx              # Main footer
│   │   ├── CompanyLinks.jsx         # Company links
│   │   ├── MarketplaceLinks.jsx     # Marketplace links
│   │   └── Socials.jsx              # Social media links
│   │
│   ├── 📁 headers/                  # Header variants
│   │   ├── Header1.jsx              # Main header
│   │   ├── Header2.jsx              # Alternative header
│   │   └── component/               # Header sub-components
│   │       ├── Nav.jsx              # Navigation
│   │       ├── Profile.jsx          # Profile dropdown
│   │       └── DarkModeToggle.jsx   # Theme switcher
│   │
│   ├── 📁 homes/                    # Home page components
│   │   ├── common/                  # Shared home components
│   │   ├── home-1/                  # Home 1 components
│   │   ├── home-7/                  # Crypto Consultant
│   │   └── ...                      # Other home variants
│   │
│   ├── 📁 metamask/                 # Web3 integration
│   │   ├── MetamarkComponent.jsx    # MetaMask handler
│   │   └── MetamaskInLogin.jsx      # Login integration
│   │
│   ├── 📁 modals/                   # Modal components
│   │   ├── BidModal.jsx             # Bidding modal
│   │   ├── BuyModal.jsx             # Purchase modal
│   │   ├── WalletModal.jsx          # Wallet selector
│   │   ├── PropertiesModal.jsx      # Properties editor
│   │   └── LevelsModal.jsx          # Levels editor
│   │
│   ├── 📁 pages/                    # Page-specific components
│   │   ├── about/                   # About components
│   │   ├── collection/              # Collection components
│   │   ├── item/                    # Item components
│   │   └── user/                    # User components
│   │
│   └── 📁 resources/                # Resource components
│       ├── Blogs.jsx                # Blog list
│       ├── NewsLetter.jsx           # Newsletter form
│       └── help-center/             # Help center components
│
├── 📁 data/                         # Static data & content
│   ├── aggregator.js                # Aggregator data
│   ├── benefits.js                  # Benefits content
│   ├── blogs.js                     # Blog posts
│   ├── careers.js                   # Career listings
│   ├── categories.js                # NFT categories
│   ├── collections.js               # Collection data
│   ├── faq.js                       # FAQ content
│   ├── feature.js                   # Feature highlights
│   ├── footerLinks.js               # Footer navigation
│   ├── item.js                      # NFT items
│   ├── menu.js                      # Navigation menu
│   ├── partnars.js                  # Partner logos
│   ├── process.js                   # Process steps
│   ├── ranking.js                   # Rankings data
│   ├── socials.js                   # Social media links
│   ├── team.js                      # Team members
│   ├── testimonials.js              # Customer testimonials
│   └── wallets.js                   # Wallet providers
│
├── 📁 public/                       # Static assets
│   ├── 📁 fonts/                    # Custom fonts
│   │   ├── CalSans-SemiBold.*       # Display font
│   │   └── DM_Sans/                 # Body font
│   │
│   ├── 📁 img/                      # Images & icons
│   │   ├── avatars/                 # User avatars
│   │   ├── collections/             # Collection images
│   │   ├── products/                # NFT product images
│   │   ├── wallets/                 # Wallet logos
│   │   ├── coins/                   # Cryptocurrency icons
│   │   └── ...                      # Other assets
│   │
│   └── 📁 styles/                   # Global styles
│       └── style.css                # Main stylesheet
│
├── 📁 utlis/                        # Utility functions
│   ├── AddClipboard.js              # Clipboard helper
│   ├── handleDarkMode.js            # Theme handler
│   └── mobileMenuToggle.js          # Mobile menu
│
├── 📄 tailwind.config.js            # Tailwind configuration
├── 📄 next.config.mjs               # Next.js configuration
├── 📄 postcss.config.js             # PostCSS configuration
├── 📄 package.json                  # Dependencies
├── 📄 jsconfig.json                 # JS configuration
└── 📄 README.md                     # Documentation
```

---

## 🚀 Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** 18.17 or higher
- **npm**, **yarn**, **pnpm**, or **bun** package manager
- **Git** for version control

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Trezoa-Team/trezoa-nft-marketplace.git
   cd trezoa-nft-marketplace/trezoa-marketplace
   ```

2. **Install dependencies**
   ```bash
   # Using npm
   npm install

   # Using yarn
   yarn install

   # Using pnpm
   pnpm install

   # Using bun
   bun install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to see the result.

### Environment Setup (Optional)

Create a `.env.local` file in the root directory for environment variables:

```env
# App Configuration
NEXT_PUBLIC_APP_NAME=Trezoa
NEXT_PUBLIC_APP_URL=http://localhost:3000

# Web3 Configuration (Optional)
NEXT_PUBLIC_CHAIN_ID=1
NEXT_PUBLIC_RPC_URL=your_rpc_url

# Analytics (Optional)
NEXT_PUBLIC_GA_ID=your_google_analytics_id
```

---

## 📜 Available Scripts

In the project directory, you can run:

### Development
```bash
npm run dev
```
Runs the app in development mode with Turbopack for ultra-fast refresh.

### Production Build
```bash
npm run build
```
Creates an optimized production build.

### Start Production Server
```bash
npm start
```
Runs the production build locally.

### Linting
```bash
npm run lint
```
Checks code for errors and style issues.

---

## 🎨 Demo Pages

### 🏠 Home Page Variants

| Page | Route | Description |
|------|-------|-------------|
| **Home 1** | `/` | Main NFT Marketplace |
| **Home 1 RTL** | `/home-1-rtl` | RTL version |
| **Home 2-6** | `/home-2` to `/home-6` | Alternative layouts |
| **Crypto Consultant** | `/home-7` | Consulting landing |
| **NFT Game** | `/home-8` | Gaming platform |
| **DAO Platform** | `/home-9` | Decentralized org |
| **Crypto App** | `/home-10` | Mobile app showcase |
| **Crypto Trading** | `/home-11` | Trading platform |
| **ICO Landing** | `/home-12` | Token sale page |
| **NFT Aggregator** | `/home-13` | Aggregator platform |

### 📄 Core Pages

| Category | Pages |
|----------|-------|
| **NFT** | Item Details, Collections, Create NFT, Rankings |
| **User** | Profile, Edit Profile, Activity Feed |
| **Info** | About, Contact, Careers, Case Studies |
| **Resources** | Blog, Help Center, Partners, Newsletter |
| **Auth** | Login, Wallet Connect |
| **Legal** | Terms of Service, Platform Status |
| **Other** | 404, Maintenance Mode |

---

## 💼 Wallet Integration

### Supported Wallets

Trezoa supports multiple Web3 wallet providers:

1. **MetaMask** 🦊
   - Browser extension integration
   - Mobile app support
   - Full transaction support

2. **Coinbase Wallet** 
   - Direct integration
   - QR code support

3. **WalletConnect** 
   - Mobile wallet bridge
   - Multi-wallet support

4. **Other Providers**
   - Bitski
   - Fortmatic
   - Torus

### Implementation Example

```javascript
import { useMetaMask } from "metamask-react";

function MyComponent() {
  const { status, connect, account } = useMetaMask();
  
  return (
    <button onClick={connect}>
      {status === "connected" ? account : "Connect Wallet"}
    </button>
  );
}
```

---

## 🎨 Customization

### Theme Configuration

Edit `tailwind.config.js` to customize colors, fonts, and breakpoints:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        'jacarta': {...},
        'accent': '#8358FF',
        // Add your custom colors
      },
      fontFamily: {
        display: ['"CalSans-SemiBold"'],
        body: ['"DM Sans"'],
      },
    },
  },
}
```

### Adding Custom Pages

1. Create a new folder in `app/(pages)/`
2. Add `page.jsx` with your content
3. Update navigation in `data/menu.js`

### Modifying Data

All content is stored in the `data/` directory:
- **NFT Items**: `data/item.js`
- **Collections**: `data/collections.js`
- **Categories**: `data/categories.js`
- **Menu**: `data/menu.js`

---

## 🌙 Dark Mode

Trezoa includes a built-in dark/light mode toggle:

### Features
- ✅ Automatic system preference detection
- ✅ Manual toggle switch
- ✅ Persistent user preference (localStorage)
- ✅ Smooth transitions
- ✅ All components optimized for both modes

### Usage

The theme is controlled by the `ModeChanger` component:

```jsx
import ModeChanger from "@/components/common/ModeChanger";

// Add to your layout
<ModeChanger />
```

### Custom Dark Mode Styles

```css
/* Light mode */
.element {
  @apply bg-white text-gray-900;
}

/* Dark mode */
.dark .element {
  @apply bg-jacarta-800 text-white;
}
```

---

## ⚡ Performance

### Optimization Features

- **Next.js Image Optimization** - Automatic image optimization
- **Code Splitting** - Automatic route-based splitting
- **Tree Shaking** - Remove unused code
- **Lazy Loading** - Components load on demand
- **Turbopack** - Ultra-fast bundler in dev mode
- **Static Generation** - Pre-render pages at build time

### Performance Tips

1. **Use Next.js Image Component**
   ```jsx
   import Image from "next/image";
   
   <Image
     src="/img/product.jpg"
     width={500}
     height={500}
     alt="Product"
   />
   ```

2. **Implement Dynamic Imports**
   ```jsx
   import dynamic from 'next/dynamic';
   
   const DynamicComponent = dynamic(() => import('./Component'));
   ```

3. **Optimize Fonts**
   - Already configured with `next/font`
   - Custom fonts preloaded

---

## 🌐 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | Last 2 versions |
| Firefox | Last 2 versions |
| Safari | Last 2 versions |
| Edge | Last 2 versions |
| Opera | Last 2 versions |

### Mobile Support
- ✅ iOS Safari 12+
- ✅ Chrome Android
- ✅ Samsung Internet

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Development Guidelines

- Follow the existing code style
- Write meaningful commit messages
- Test your changes thoroughly
- Update documentation as needed

---

## 📝 License

This project is licensed under a **Commercial License**.

- ✅ Use in commercial projects
- ✅ Modify and customize
- ❌ Redistribute or resell as a template
- ❌ Use in open-source projects without permission

For licensing inquiries, contact: **office@trezoa.com**

---

## 🆘 Support

### Documentation
- 📖 [Full Documentation](./documentation/index.html)
- 💡 [Help Center](/help-center)
- 📧 Email: office@trezoa.com

### Resources
- 🐛 [Report Issues](https://github.com/Trezoa-Team/trezoa-nft-marketplace/issues)
- 💬 [Discussions](https://github.com/Trezoa-Team/trezoa-nft-marketplace/discussions)
- 📚 [Next.js Documentation](https://nextjs.org/docs)
- 🎨 [Tailwind CSS Docs](https://tailwindcss.com/docs)

### Community
- 🌟 Star this repo if you like it!
- 🍴 Fork to create your own version
- 📢 Share with your network

---

## 🙏 Acknowledgments

Special thanks to:
- **Next.js Team** - For the amazing framework
- **Tailwind Labs** - For the utility-first CSS framework
- **MetaMask** - For Web3 integration
- **Vercel** - For hosting and deployment
- **Open Source Community** - For the incredible tools

---

## 📊 Stats

![GitHub Stars](https://img.shields.io/github/stars/Trezoa-Team/trezoa-nft-marketplace?style=social)
![GitHub Forks](https://img.shields.io/github/forks/Trezoa-Team/trezoa-nft-marketplace?style=social)
![GitHub Issues](https://img.shields.io/github/issues/Trezoa-Team/trezoa-nft-marketplace)
![GitHub Last Commit](https://img.shields.io/github/last-commit/Trezoa-Team/trezoa-nft-marketplace)

---

<div align="center">

**Built with ❤️ by the Trezoa Team**

[Website](https://trezoa.com) • [GitHub](https://github.com/Trezoa-Team) • [Twitter](https://twitter.com/trezoa)

</div>
