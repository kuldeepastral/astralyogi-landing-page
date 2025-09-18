# AstralYogi Landing Page

A beautiful, responsive landing page for AstralYogi - an AI-powered astrology app and WhatsApp chatbot designed for the Indian market.

## Features

- **Modern, Responsive Design**: Beautiful UI optimized for all devices
- **Indian Astrology Focus**: Tailored for Vedic astrology and Indian cultural preferences
- **WhatsApp Integration**: Direct integration with WhatsApp chatbot
- **AI-Powered Services**: Showcases AI-driven astrology features
- **Interactive Elements**: Smooth animations and engaging user experience

## Services Highlighted

- 🔮 **Birth Chart Analysis** - Complete Kundli generation and analysis
- 📅 **Daily Horoscope** - Personalized daily predictions
- 💍 **Marriage Matching** - Traditional Guna Milan compatibility
- 💼 **Career Guidance** - Professional direction based on planetary positions
- 💎 **Gemstone Recommendations** - Personalized remedy suggestions
- ⏰ **Muhurat Selection** - Auspicious timing for important events

## WhatsApp Chatbot Features

- 24/7 availability
- Instant birth chart generation
- Daily horoscope updates
- Multi-language support (Hindi & English)
- Personalized predictions and remedies

## Getting Started

### Prerequisites

- Node.js (for development server)
- Modern web browser

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd astralyogi-landing-page
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

### Alternative: Simple HTTP Server

You can also run a simple HTTP server:
```bash
npm start
```

## Project Structure

```
astralyogi-landing-page/
├── index.html          # Main landing page
├── package.json        # Project configuration
├── README.md          # This file
└── index.js           # Original placeholder (can be removed)
```

## Customization

### Colors and Branding

The design uses CSS custom properties (variables) for easy customization:

```css
:root {
    --primary-color: #FF6B35;     /* Orange - main brand color */
    --secondary-color: #1B263B;   /* Dark blue - text and backgrounds */
    --accent-color: #FFD23F;      /* Yellow - highlights and accents */
    --text-dark: #2C3E50;         /* Dark text */
    --text-light: #7F8C8D;        /* Light text */
}
```

### WhatsApp Integration

Update the WhatsApp number in the JavaScript section:

```javascript
const phoneNumber = '1234567890'; // Replace with actual WhatsApp number
```

### Content Updates

- **Hero Section**: Update main headline and description
- **Features**: Modify the feature cards in the features section
- **Services**: Update service offerings
- **Testimonials**: Replace with real customer testimonials
- **Contact Information**: Update footer contact details

## Responsive Design

The landing page is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## Performance Features

- **Optimized Images**: Uses CSS gradients and icons instead of heavy images
- **Smooth Animations**: CSS animations with hardware acceleration
- **Fast Loading**: Minimal external dependencies
- **SEO Friendly**: Semantic HTML structure

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid, Flexbox, and animations
- **JavaScript**: Interactive features and smooth scrolling
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Poppins & Playfair Display)

## Deployment

This is a static website that can be deployed to any web hosting service:

1. **GitHub Pages**: Push to GitHub and enable Pages
2. **Netlify**: Drag and drop the files or connect to Git
3. **Vercel**: Deploy directly from Git repository
4. **Traditional Hosting**: Upload files to any web server

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test responsiveness and functionality
5. Submit a pull request

## License

This project is licensed under the ISC License - see the package.json file for details.

## Support

For support and questions:
- Email: support@astralyogi.com
- WhatsApp: +91 98765 43210

---

Made with ❤️ for the Indian astrology community
