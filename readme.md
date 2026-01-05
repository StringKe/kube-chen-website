# KubChen Website

Official website for [KubChen](https://github.com/StringKe/kub-chen) - Native Kubernetes Visualization and Management Tool.

**Live Site:** [https://kubchen.app](https://kubchen.app)

## Tech Stack

- **Framework**: [Astro](https://astro.build/) 5.x
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) 4.x
- **UI Components**: React 19
- **Deployment**: Cloudflare Pages
- **i18n**: English (default) + Chinese

## Development

### Prerequisites

- Node.js 22+
- Yarn 1.22+

### Setup

```bash
# Install dependencies
yarn install

# Start development server
yarn dev

# Build for production
yarn build

# Preview production build
yarn preview
```

### Deployment

The site is automatically deployed to Cloudflare Pages on push to `main`.

For manual deployment:

```bash
yarn deploy
```

## Project Structure

```
src/
├── content/           # Markdown/MDX content
│   ├── homepage/      # Homepage content
│   ├── about/         # About page
│   ├── blog/          # Blog posts
│   ├── pages/         # Static pages (features, docs, download)
│   └── sections/      # Reusable sections
├── config/            # Site configuration
│   ├── config.json    # Main config
│   └── menu.json      # Navigation menus
├── pages/             # Astro pages
└── components/        # React/Astro components
```

## Configuration

### Environment Variables

Create a `.envrc` file (using direnv) with:

```bash
# Cloudflare (for deployment)
export CLOUDFLARE_API_TOKEN="your-api-token"
export CLOUDFLARE_ACCOUNT_ID="your-account-id"
```

### Site Configuration

Edit `src/config/config.json` for site-wide settings.

## License

MIT License - Website template based on [Astroplate](https://github.com/zeon-studio/astroplate).

KubChen application is licensed under [PolyForm Noncommercial License 1.0.0](https://github.com/StringKe/kub-chen/blob/main/LICENSE).

---

Built with Astro for the KubChen project.
