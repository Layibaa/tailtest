# PentAi Landing Page - Next.js Implementation

A pixel-perfect Next.js + Tailwind CSS implementation of the PentAi landing page, directly exported from Figma with exact specifications.

## 🎯 Features

- **Pixel-Perfect Design**: Matches Figma design specifications 1:1
- **Next.js 14+ App Router**: Modern React framework with optimal performance
- **Tailwind CSS**: Utility-first CSS with custom configurations
- **Responsive Layout**: Desktop-first approach with exact spacing and sizing
- **Custom Fonts**: DM Sans and Roboto with proper variation settings
- **SVG Graphics**: All decorative elements and icons imported directly from Figma
- **Gradient Effects**: Complex angular gradients and visual effects
- **Image Assets**: Optimized Figma assets with proper aspect ratios

## 📁 Project Structure

```
/
├── App.tsx                         # Main application entry point
├── imports/
│   ├── LandingPage.tsx            # Complete landing page component (Figma export)
│   └── svg-177rqpx4gr.ts          # SVG path definitions
├── components/
│   ├── figma/
│   │   └── ImageWithFallback.tsx  # Image component with fallback
│   └── ui/                         # UI component library
├── styles/
│   └── globals.css                 # Global styles and theme
└── README.md                       # This file
```

## 🎨 Design System

### Colors
- **Background**: `#1c1c1c` (Primary dark)
- **Card Background**: `#232323`, `#282828`
- **Text Primary**: `#ecedee`
- **Text Muted**: `#9ba1a6`, `#a0a0a0`
- **Accent Purple**: `#8e4ec8`
- **Gradient Start**: `#301a3a` (rgb(48, 26, 58))
- **Gradient End**: `#7938b2` (rgb(121, 56, 178))

### Typography
- **Primary Font**: DM Sans (SemiBold, Bold, Medium, Regular)
- **Secondary Font**: Roboto (Bold)
- **Font Variation Settings**: `'opsz' 14`, `'wdth' 100`

### Spacing Scale
- Follows exact Figma measurements in pixels
- Common gaps: 8px, 10px, 12px, 16px, 24px, 30px, 36px, 40px, 48px, 64px, 80px

## 🏗️ Page Sections

### 1. Navigation Header
- Sticky header with backdrop blur
- Logo with gradient accent
- Navigation menu (Home, SecrtChat, GenPen, Contact)
- CTA button (Dashboard)

### 2. Hero Section
- Large gradient headline
- Subtitle with description
- Primary CTA button
- Decorative angular gradients and grid background

### 3. Supporters Section
- Centered supporter logos
- Clean layout with proper spacing

### 4. Dashboard Showcase
- Large dashboard preview image
- Gradient headline
- Supporting copy

### 5. Statistics Section (23%)
- Three identical stat cards
- Large percentage display with gradient
- Backdrop blur effects
- Border and shadow styling

### 6. Features Section 1
- Left content area with title and bullet points
- Right visual area with security icons
- Multiple floating card elements with icons:
  - Lock Laminated
  - Wall
  - Shield Check
  - Fingerprint
  - Security Camera
  - Shield Warning

### 7. Features Section 2
- Alternating layout (content left/right)
- Dashboard preview images
- Feature descriptions with checkmarks
- Star decorations

### 8. Feature Tabs
- Tab selector interface
- Dashboard preview
- Active state styling

### 9. Testimonials Section
- Grid layout with 8 testimonial cards
- User avatars
- Gradient fog overlay at bottom
- Staggered card positions

### 10. CTA Section
- Large gradient headline
- Supporting text
- Book a demo button
- Union pattern background

### 11. Footer
- Logo and copyright
- Social media icons (Facebook, Instagram, X/Twitter, LinkedIn, YouTube)
- Footer links (Privacy Policy, Terms of Service)
- Credits section

## 🖼️ Assets

### Images (figma:asset)
- `img24`: Logo accent icon
- `imgDashboard`: Main dashboard screenshot
- `imgLockFront`: 3D lock illustration
- `imgEllipse1-8`: User avatars for testimonials

### SVG Icons
All SVG paths are defined in `svg-177rqpx4gr.ts` including:
- Star decorations (multiple sizes and opacities)
- Social media icons
- Security icons (shield, lock, fingerprint, etc.)
- Check marks
- Union patterns

## 🚀 Getting Started

The application is ready to run. The main component is already set up in `/App.tsx` which imports the complete landing page.

### Development
```bash
# Application runs automatically in the Figma Make environment
# All assets and components are pre-configured
```

## 📐 Technical Details

### Exact Measurements
- Page width: 1440px
- Content max-width: 1280px
- Card border radius: 16px, 24px
- Button border radius: 9999px (fully rounded)
- Header height: 64px

### Effects
- Backdrop blur: 2px, 2.617px, 43.25px
- Box shadows: Multiple layered shadows with rgba values
- Gradients: Linear and angular gradients with multiple stops
- Filters: Gaussian blur for glow effects

### Layout
- Flexbox-based layouts with exact gap values
- Absolute positioning for decorative elements
- Overflow handling for image containers
- Z-index layering for complex compositions

## 🎯 Best Practices

1. **Pixel Perfect**: All measurements from Figma are preserved
2. **Semantic HTML**: Proper use of semantic elements
3. **Accessibility**: ARIA labels and semantic structure
4. **Performance**: Optimized images and SVGs
5. **Maintainability**: Clean component structure

## 📝 Notes

- The design uses custom font variation settings for DM Sans
- Multiple gradient overlays create the signature dark theme
- Star decorations use varying opacities (0.1, 0.3, 1.0)
- Dashboard images are positioned with precise negative margins
- Testimonial cards use absolute positioning in a grid container

## 🔧 Customization

To modify the landing page:
1. Edit `/imports/LandingPage.tsx` for component changes
2. Update `/imports/svg-177rqpx4gr.ts` for SVG modifications
3. Adjust `/styles/globals.css` for global theme changes

---

Built with ❤️ using Figma Make
