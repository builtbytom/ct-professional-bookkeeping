# Connecticut Professional Bookkeeping

A professional, high-performance website for a bookkeeping firm serving New Haven County businesses. Built with Astro and featuring an "unbreakable" CMS demo using Decap CMS.

## 🚀 Features

- **Lightning Fast**: Built with Astro for exceptional performance
- **Professional Design**: Navy, gray, white, and gold color scheme that conveys trust
- **Unbreakable CMS**: Decap CMS integration for safe content editing
- **Mobile Responsive**: Looks great on all devices
- **Local SEO Optimized**: Schema markup and Connecticut-focused content
- **Lead Generation**: Multiple CTAs and resource downloads

## 🛠️ Tech Stack

- **Framework**: Astro
- **Styling**: Tailwind CSS v3
- **CMS**: Decap CMS (formerly Netlify CMS)
- **Deployment**: Optimized for Netlify

## 📁 Project Structure

```
/
├── public/
│   ├── admin/          # Decap CMS files
│   └── images/         # Static images
├── src/
│   ├── components/     # Reusable components
│   ├── content/        # CMS-managed content
│   ├── layouts/        # Page layouts
│   ├── pages/          # Route pages
│   └── styles/         # Global styles
└── package.json
```

## 🚦 Getting Started

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:4321](http://localhost:4321)

3. **Build for production**
   ```bash
   npm run build
   ```

## 📝 CMS Access

The site includes a demo CMS at `/admin`. In demo mode, you can:
- Edit all content safely (changes won't persist)
- Test the "unbreakable" editing experience
- See how easy content management can be

### Setting Up CMS for Production

1. Deploy to Netlify
2. Enable Netlify Identity in site settings
3. Update `public/admin/config.yml`:
   ```yaml
   backend:
     name: git-gateway
     branch: main
   ```
4. Invite users through Netlify Identity

## 🚀 Deployment

### Netlify (Recommended)

1. Push to GitHub
2. Connect to Netlify
3. Build settings:
   - **Build command**: `npm run build`
   - **Publish directory**: `dist`
4. Enable Netlify Identity for CMS

### Environment Variables

None required for basic setup. For production CMS:
- Enable Netlify Identity
- Configure Git Gateway

## 🎨 Customization

### Colors
Edit color palette in `tailwind.config.js`:
- Navy: Professional trust
- Gold: Premium accent
- Gray: Clean neutrals

### Content
All content is editable through the CMS:
- Homepage hero and trust signals
- Services and pricing
- Team members
- FAQs
- Resources

## 📈 Performance

- **Lighthouse Score**: 95-100
- **Page Load**: < 1 second
- **First Contentful Paint**: < 0.5s
- **Fully Static**: No JavaScript required for content

## 🔒 Security

- Static site (no server vulnerabilities)
- CMS requires authentication
- No sensitive data in codebase
- Form submissions handled by Netlify

## 📞 Support

For questions about this demo site or the Built by Tom CMS service, visit [builtbytom.com](https://builtbytom.com)

---

Built with ❤️ to showcase professional, fast, and manageable websites for service businesses.