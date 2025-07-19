# Deployment Instructions

## Quick Deployment (Recommended)

The easiest way to deploy this website is to use the pre-built files in the `dist/` folder.

### 1. Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the entire `dist/` folder onto the deployment area
3. Your site will be live in seconds with a custom URL

### 2. Vercel
1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Upload the `dist/` folder
4. Deploy with one click

### 3. GitHub Pages
1. Create a new repository on GitHub
2. Upload all files from the `dist/` folder to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### 4. Traditional Web Hosting
1. Access your web hosting control panel (cPanel, etc.)
2. Navigate to File Manager or use FTP
3. Upload all contents of the `dist/` folder to your `public_html` or `www` directory
4. Your site will be live at your domain

## Development Deployment

If you want to make changes to the website:

### Prerequisites
- Node.js 18+ installed
- npm or pnpm package manager

### Steps
1. Install dependencies:
   ```bash
   npm install
   # or
   pnpm install
   ```

2. Start development server:
   ```bash
   npm run dev
   # or
   pnpm run dev
   ```

3. Make your changes to the source files

4. Build for production:
   ```bash
   npm run build
   # or
   pnpm run build
   ```

5. Deploy the new `dist/` folder using any of the methods above

## Custom Domain Setup

### For Netlify:
1. Go to your site dashboard
2. Click "Domain settings"
3. Add your custom domain
4. Follow the DNS configuration instructions

### For Vercel:
1. Go to your project dashboard
2. Click "Domains"
3. Add your custom domain
4. Configure DNS records as instructed

### For Traditional Hosting:
- Simply upload to your existing domain's web directory

## SSL Certificate

Most modern hosting platforms (Netlify, Vercel, GitHub Pages) provide free SSL certificates automatically. For traditional hosting, you may need to configure SSL through your hosting provider.

## Performance Optimization

The built website is already optimized with:
- Minified CSS and JavaScript
- Optimized images
- Gzip compression support
- Modern browser features

## Monitoring and Analytics

To add analytics:
1. Add Google Analytics or similar tracking code to `index.html`
2. Rebuild and redeploy

## Backup

Always keep a backup of your source files and the original package for future updates or modifications.

## Troubleshooting

### Common Issues:

**White screen after deployment:**
- Ensure all files from `dist/` folder are uploaded
- Check browser console for errors
- Verify file permissions on your server

**Images not loading:**
- Ensure image files are uploaded correctly
- Check file paths are correct
- Verify image file permissions

**Fonts not loading:**
- The website uses Google Fonts which require internet connection
- Ensure your hosting allows external font loading

**Mobile display issues:**
- The website is responsive by default
- Test on actual devices or browser dev tools
- Check viewport meta tag is present

## Support

For deployment issues or questions, refer to your hosting provider's documentation or contact their support team.

