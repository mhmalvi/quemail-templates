# QueMail Templates

A curated collection of production-ready HTML email templates designed for use with the QueMail email marketing platform. Each template is fully responsive, cross-client compatible, and ready for campaign deployment.

## Templates

| Template | Version | Description |
|----------|---------|-------------|
| **ITEC** | v1.0, v1.1 | Corporate/technology-focused template with portfolio showcase, service highlights, and team sections |
| **NTA** | v1.0, v1.1 | Professional business template with project galleries, feature cards, and call-to-action blocks |
| **UCT** | v1.0, v1.1 | Clean modern template with hero banners, icon-based feature sections, and social media integration |
| **ATR** | v1.4 | Advanced template package (archived release) |

## Features

- **Cross-Client Compatibility** — Tested rendering across Gmail, Outlook, Apple Mail, and Yahoo Mail
- **Responsive Design** — Mobile-friendly layouts that adapt to all screen sizes
- **Inline CSS** — All styles inlined for maximum email client support
- **Image Assets Included** — Complete image sets for backgrounds, icons, and content placeholders
- **Table-Based Layout** — Reliable table structure for consistent rendering across email clients
- **Social Media Integration** — Pre-built social icon sections (Facebook, Twitter, Instagram, LinkedIn, YouTube, Pinterest)
- **Versioned Releases** — Both editable HTML (v1.0) and packaged RAR archives (v1.1+)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mhmalvi/quemail-templates.git
cd quemail-templates
```

### 2. Browse Templates

Each template is organized in its own directory:

```
quemail-templates/
├── itec_email_template_v1.0/
│   ├── index.html              # Main template file
│   └── images/                 # Template image assets
├── itec_email_template_v1.1.rar
├── nta_email_tempalte_v1.0/
│   ├── index.html
│   └── images/
├── nta_email_template_v1.1.rar
├── uct_email_tempalte_v1.0/
│   ├── index.html
│   └── images/
├── uct_email_template_v1.1.rar
└── atr_email_template_v1.4.rar
```

### 3. Customize a Template

1. Open the desired `index.html` file in a code editor
2. Replace placeholder text and images with your content
3. Update brand colors in the inline styles
4. Host images on your server and update `src` attributes
5. Test the template using an email testing service

### 4. Use with QueMail

Import the HTML template into the QueMail platform through the template management interface in the [quemail-client](https://github.com/mhmalvi/quemail-client) dashboard.

## Template Structure

Each template follows a consistent section layout:

- **Header** — Logo and navigation links
- **Hero Section** — Full-width banner with headline and CTA
- **Feature Cards** — Icon-based service or feature highlights
- **Content Sections** — Image and text blocks for detailed information
- **Portfolio/Gallery** — Project or product showcase grid
- **Footer** — Contact information, social links, and unsubscribe

## Related Projects

- [quemail-client](https://github.com/mhmalvi/quemail-client) — Email campaign management frontend (Next.js)
- [quemail-server](https://github.com/mhmalvi/quemail-server) — Email marketing backend API (Laravel)

## License

This project is open source and available under the [MIT License](LICENSE).
