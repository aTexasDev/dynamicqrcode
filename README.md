# Dynamic QR Code

[![dynamicqrcode](og-image.png)](https://dynamicqrcode.app)


Learn about dynamic QR codes and create free static QR codes instantly. Companion educational site for QR Cheetah - explains the difference between static and dynamic QR codes.

**Live:** [dynamicqrcode.app](https://dynamicqrcode.app)

## Tech Stack

- Vanilla JavaScript
- HTML5 / CSS3
- i18n internationalization support
- SEO-optimized content pages

## Features

- Educational content on dynamic vs static QR codes
- Free static QR code generator
- SEO-optimized guides and tutorials
- Multi-language support

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/aTexasDev/dynamicqrcode-app.git
cd dynamicqrcode-app
```

2. Open `index.html` in your browser, or serve with any static file server:
```bash
npx serve .
```

## Architecture

This is the frontend application. It communicates with a serverless backend (AWS Lambda + API Gateway) for authenticated operations and data persistence.

- **Authentication:** Google OAuth 2.0
- **Payments:** Stripe Checkout
- **Hosting:** AWS S3 + CloudFront CDN
- **Backend:** AWS Lambda (not included in this repo)

## License

MIT License - see [LICENSE](LICENSE) for details.

---

Built by [T.K. Flautt](https://snapitsoftware.com) | [SnapIT Software](https://snapitsoftware.com)
