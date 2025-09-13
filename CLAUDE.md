# 18XX Bank Website - Development Instructions

## Project Overview
This is the official marketing website for the 18XX Bank iOS app. It's a simple, static website designed to be hosted on GitHub Pages that provides information about the app, its features, and privacy policy.

## Website Context

### Purpose
- Marketing landing page for 18XX Bank iOS app
- Provides download link to App Store
- Houses the privacy policy required for App Store listing
- Showcases app features and supported games
- **IMPORTANT: Repository is PRIVATE - no GitHub links should be included**

### Technology Stack
- **Pure HTML/CSS** - No JavaScript required for maximum compatibility
- **Static Site** - Designed for GitHub Pages hosting
- **Responsive Design** - Works on all devices
- **No Backend** - Completely static, no server required

### File Structure
```
18xxbank-website/
├── index.html              # Main landing page
├── privacy.html            # Privacy policy (required for App Store)
├── styles.css              # All styling
├── icon.png                # App icon (1024x1024)
├── distribution_screen.png # App screenshot
├── README.md               # Deployment instructions
├── CLAUDE.md              # This file
└── development-log.md     # Development history
```

## Key Design Elements

### Visual Design
- **Color Scheme**: Railroad/train theme
  - Primary: #2c5530 (railroad green)
  - Secondary: #8b4513 (brown)
  - Accent: #d4af37 (gold)
- **iPhone Mockup**: Realistic CSS-only iPhone with app screenshot
- **App Icon**: Displayed in header for branding

### Content Sections
1. **Hero**: App description with download button
2. **Features**: 6 key capabilities in grid layout
3. **Premium**: Subscription information ($2.99/year)
4. **Games**: Showcase of 98+ supported games
5. **How It Works**: 4-step tutorial
6. **Privacy Policy**: Comprehensive privacy information

## Important Notes

### Privacy Focus
- **App tracks NO user data** - This is emphasized throughout
- Privacy policy clearly states no data collection
- All data stored locally on device
- Optional iCloud sync for user convenience

### Repository Status
- **PRIVATE repository** - Do not add GitHub links
- Website deployed via GitHub Pages
- Public can access website but not source code

## Development Guidelines

### When Making Changes
1. Maintain the simple HTML/CSS structure
2. Keep privacy-first messaging prominent
3. Update both index.html and privacy.html headers if changing navigation
4. Test responsive design on mobile devices
5. Ensure App Store link is correct
6. Keep images optimized for web

### Testing
```bash
# Test locally with Python
python3 -m http.server 8000
# Then open http://localhost:8000
```

### Deployment
1. Commit all changes
2. Push to main branch
3. GitHub Pages automatically deploys
4. Available at: https://[username].github.io/18xxbank-website/

## Maintenance Tasks

### Regular Updates
- Update app screenshots when UI changes
- Keep supported games list current
- Update privacy policy if app changes data handling
- Refresh testimonials with real user feedback

### Before App Store Submission
- Verify privacy policy is current
- Check all links work correctly
- Ensure screenshots are up-to-date
- Test on multiple devices

## GitHub Workflow
- Commit directly to main branch (small website)
- Use clear commit messages
- Update development-log.md for major changes
- Keep CLAUDE.md current with any structural changes

## Best Practices
- Always commit with clear, descriptive messages
- Test locally before pushing
- Keep the website simple and fast-loading
- Maintain privacy-first messaging
- Update development-log.md after significant changes
- Remember to commit and push changes after finishing them