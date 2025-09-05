# CryptoCourses.in

## Overview

CryptoCourses.in is a static educational website focused on cryptocurrency and blockchain technology education. The platform serves as a comprehensive resource hub providing technical articles, learning materials, and educational content about cryptography, digital assets, and blockchain fundamentals. Built as a pure HTML/CSS static site, it emphasizes fast loading, accessibility, and SEO optimization to deliver technical education to users interested in understanding cryptocurrency from a foundational perspective.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Pure HTML5 and CSS3 implementation without frameworks or build tools
- **Responsive Design**: Mobile-first approach using CSS Grid and Flexbox for layout management
- **Design System**: CSS custom properties (variables) for consistent theming and maintainability
- **Dark Mode Support**: Automatic dark mode detection using `@media (prefers-color-scheme: dark)`

### Content Structure
- **Static Page Architecture**: Multi-page structure with semantic HTML5 markup
- **Blog System**: Static blog posts organized in dedicated `/blog/` directory
- **Content Categories**: Organized into main sections (Home, Blog, Resources, About, FAQ, Contact)
- **SEO Optimization**: Comprehensive meta tags, Open Graph, Twitter Cards, and Schema.org JSON-LD markup on all pages

### Accessibility Implementation
- **WCAG AA Compliance**: Semantic landmarks, proper heading hierarchy, and sufficient color contrast
- **Navigation**: Skip links, ARIA labels, and keyboard navigation support
- **Screen Reader Support**: Proper semantic markup and descriptive alt text for all images

### Performance Optimization
- **Static Asset Strategy**: Minimal external dependencies with preloaded critical resources
- **CSS Architecture**: Single stylesheet with utility classes and component-based organization
- **Image Management**: Placeholder system for assets with proper aspect ratios

### Legal and Privacy Framework
- **Privacy Policy**: Basic privacy policy for educational content site
- **Terms of Service**: Educational disclaimer and usage terms
- **Contact System**: Mailto-based contact forms for simplicity

## External Dependencies

### Content Delivery
- **No External Frameworks**: Self-contained CSS and HTML without external libraries
- **Font System**: System font stack for optimal performance and consistency
- **Icon System**: SVG-based icons for scalability and performance

### SEO and Analytics
- **Schema.org Markup**: Structured data for Organization, Article, and BreadcrumbList entities
- **Social Media Integration**: Open Graph and Twitter Card meta tags for social sharing
- **Search Engine Optimization**: Canonical URLs, proper meta descriptions, and semantic markup

### Multimedia Integration
- **Video Placeholders**: YouTube embed preparation for educational content
- **Image Assets**: Organized asset structure for blog images and branding materials

### Contact and Communication
- **Email Integration**: Mailto-based contact forms for direct communication
- **Newsletter System**: Placeholder for future email list integration (Formspree or similar)
- **Social Media**: Placeholder social media icon integration

The architecture prioritizes simplicity, performance, and educational content delivery while maintaining professional web standards and accessibility guidelines.