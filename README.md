# Yemeni Coffee Heritage Survey - Luxury Website

A highly elegant, niche-focused survey website for assessing interest in Yemeni Green Coffee Specialty Coffee Shops in Norway. This website features sophisticated design, responsive layout, and premium user experience.

## Features

- **Elegant Design**: Luxury coffee-themed design with sophisticated color palette
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Interactive Survey**: 5 comprehensive sections covering all aspects of coffee sourcing
- **Progress Tracking**: Visual progress bar with section indicators
- **Data Persistence**: Local storage saves progress automatically
- **Premium UX**: Smooth animations, transitions, and micro-interactions
- **Professional Typography**: Custom Google Fonts (Playfair Display, Crimson Text, Inter, Dancing Script)

## Survey Sections

1. **Demographics & Business Role** - Understanding business characteristics and roles
2. **Decision-Making Criteria** - Factors influencing green coffee sourcing decisions
3. **Yemeni Coffee Perception** - Familiarity and interest in Yemeni coffee
4. **Market Trends** - Customer preferences and market demands
5. **Logistics & Expectations** - Practical partnership aspects

## Incentives for Participants

- **10% Welcome Privilege** - Exclusive discount on first order
- **Priority Access** - First access to rarest Yemeni micro-lots

## Technical Stack

- **Frontend**: React 18 with Vite
- **Styling**: Tailwind CSS with custom luxury theme
- **Icons**: Lucide React
- **Fonts**: Google Fonts (Playfair Display, Crimson Text, Inter, Dancing Script)
- **Build Tool**: Vite
- **Package Manager**: pnpm

## Deployment Options

### Option 1: Static Hosting (Recommended)
The `dist/` folder contains the built static files ready for deployment to any static hosting service:

- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Deploy the `dist` folder
- **GitHub Pages**: Upload `dist` contents to your repository
- **AWS S3**: Upload `dist` contents to S3 bucket with static website hosting
- **Any Web Server**: Upload `dist` contents to your web server

### Option 2: Development Server
For local development or testing:

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

3. Build for production:
   ```bash
   npm run build
   # or
   pnpm run build
   ```

## File Structure

```
yemeni-coffee-survey/
├── dist/                          # Built production files (ready to deploy)
├── src/
│   ├── assets/                    # Images and static assets
│   │   ├── coffee-logo.png        # Coffee bean logo
│   │   ├── heritage-timeline.png  # 500 years heritage timeline
│   │   └── yemen-coffee-map.png   # Yemen coffee map illustration
│   ├── components/                # React components
│   │   ├── WelcomeSection.jsx     # Landing/welcome screen
│   │   ├── ProgressBar.jsx        # Survey progress indicator
│   │   ├── SurveySection.jsx      # Section wrapper component
│   │   ├── FormElements.jsx       # Reusable form components
│   │   ├── Section1Demographics.jsx
│   │   ├── Section2DecisionMaking.jsx
│   │   ├── Section3YemeniCoffee.jsx
│   │   ├── Section4MarketTrends.jsx
│   │   ├── Section5Logistics.jsx
│   │   └── ThankYouSection.jsx    # Completion screen
│   ├── App.jsx                    # Main application component
│   ├── App.css                    # Custom luxury styling
│   └── main.jsx                   # Application entry point
├── index.html                     # HTML template
├── package.json                   # Dependencies and scripts
└── README.md                      # This file
```

## Design Features

### Color Palette
- **Primary**: Rich coffee browns (#3C2415, #5D4037, #8D6E63)
- **Secondary**: Warm golds (#D4AF37, #F4E4BC, #FFF8DC)
- **Accent**: Deep burgundy (#722F37) and cream (#F5F5DC)
- **Background**: Soft ivory (#FEFEFE) with subtle texture overlays

### Typography
- **Headlines**: Playfair Display (elegant serif)
- **Subheadings**: Crimson Text (modern serif)
- **Body Text**: Inter (clean sans-serif)
- **Accent Text**: Dancing Script (calligraphic)

### Interactive Elements
- Smooth hover effects on buttons and form elements
- Animated progress bar with coffee bean patterns
- Fade-in animations for content sections
- Responsive touch-friendly design for mobile

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Android Chrome)

## Data Collection

Survey responses are stored in the browser's local storage and logged to the console upon completion. For production use, you may want to integrate with a backend service to collect and store responses.

## Customization

The website can be easily customized by modifying:

- **Colors**: Update CSS custom properties in `src/App.css`
- **Content**: Modify survey questions in the respective section components
- **Images**: Replace images in `src/assets/` folder
- **Styling**: Adjust Tailwind classes and custom CSS

## Support

For technical support or customization requests, please contact the development team.

---

**Created with attention to luxury design and premium user experience.**

