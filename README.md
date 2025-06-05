# PolySolutions.B.V. Website

Professional business website for PolySolutions.B.V. - A consultancy company specializing in strategic and tactical business development, product management, and proprietary web applications.

## 🚀 GitHub Pages Deployment Instructions

### 1. Create GitHub Repository
- Repository name: `[yourusername].github.io` 
- Make it **public** (required for free GitHub Pages)
- Upload all files from this directory

### 2. Enable GitHub Pages
- Go to repository → **Settings** → **Pages**
- Under **Source**, select **Deploy from a branch**
- Choose **main** branch and **/ (root)** folder
- Click **Save**
- GitHub will provide URL: `https://[yourusername].github.io`

### 3. Custom Domain Setup (polysolutionsbv.com)
The `CNAME` file is already configured for `polysolutionsbv.com`

**If you want a different domain:**
- Edit the `CNAME` file with your domain (e.g., `www.yourdomain.com`)

### 4. DNS Configuration
Configure these DNS records with your domain registrar:

#### For apex domain (polysolutionsbv.com):
```
Type: A
Name: @
Values: 
- 185.199.108.153
- 185.199.109.153  
- 185.199.110.153
- 185.199.111.153
```

#### For www subdomain (www.polysolutionsbv.com):
```
Type: CNAME
Name: www
Value: [yourusername].github.io
```

### 5. Enable HTTPS
- Go to **Settings** → **Pages**
- Check **"Enforce HTTPS"** (wait for SSL cert to be issued first)

### 6. Verification
- DNS propagation: 1-48 hours (usually much faster)
- SSL certificate: 5-10 minutes after DNS is working
- Test: Visit your domain and verify HTTPS works

## 📁 Files Included

- `index.html` - Main website
- `favicon.svg` - Custom favicon with "P" logo
- `CNAME` - Domain configuration for GitHub Pages
- `README.md` - This setup guide

## 🔧 Technical Features

- **Responsive Design** - Works on all devices
- **Email Protection** - Anti-spam email reveal system
- **Professional Styling** - Shoelace web components
- **SEO Optimized** - Proper meta tags and structure
- **Performance** - Lightweight static site

## 🏢 Company Information

**PolySolutions.B.V.**
- VAT: NL865437257B01
- KVK: 90744306
- Address: Klarinetstraat 6, 4462MB Goes, The Netherlands
- Services: Strategic consultancy, business development, product management, web applications

---

*Website built with modern web standards and optimized for performance and trustworthiness.* # polysolutionsbv
