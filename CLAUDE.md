# Auto Tip Map Website

## Project Overview
Static website for Auto Tip Map, hosted on GitHub Pages at fullyautomatedthings.com/autotipmap/. The root domain redirects to /autotipmap/ to future-proof for additional apps.

## Structure
- `/index.html` - Root redirect to /autotipmap/
- `/autotipmap/index.html` - Main landing page
- `/autotipmap/contact.html` - Contact form (via FormSubmit to contact@fullyautomatedthings.com)
- `/autotipmap/thankyou.html` - Form submission confirmation
- `/autotipmap/style.css` - Shared stylesheet
- `/autotipmap/assets/images/` - Logos and images

## Hosting & Deployment
- GitHub repo: Cassidy-Blake/Cassidy-Blake.github.io (public)
- Domain: fullyautomatedthings.com (DNS via Wyoming Agents)
- HTTPS enabled, CNAME configured
- Push to master to deploy

## Design System (matches the app)
- **Primary color:** #4F46E5 (indigo)
- **Background:** #FAFAF9 (warm off-white)
- **Surface/Cards:** #FFFFFF
- **Text:** #0F172A (primary), #475569 (secondary)
- **Border:** #E7E5E4
- **Font:** Open Sans (400, 600, 700)
- **Tip score colors:** Great #4CAF50, Good #9ACD32, Average #FFD700, Poor #FF6B35, No Tip #FF4444
- Light mode only

## Key Decisions
- App name: Auto Tip Map by Fully Automated Things
- Target audience: Shipt shoppers specifically
- "Works with Shipt" used under nominative fair use (no logo, no implied endorsement)
- Avoid "screen reading" language - use "automatically saves orders and tips" instead
- Keep feature descriptions non-technical and easy to understand
- Screenshots section has Coming Soon blur overlay (placeholders ready for real screenshots)
- Contact form uses FormSubmit - first submission requires activation email confirmation
- passwords.txt is gitignored - stores email credentials locally only

## App Logos
- Source: e:\documents\testapp\icons\
- ATMIcon.png - Square app icon
- ATM Logo.png - Wide logo with text (has white background, use mix-blend-mode: multiply)
