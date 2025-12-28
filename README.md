# Faysal Ahammad's Portfolio Website

A modern, responsive portfolio website built with Next.js, React, and Tailwind CSS.

## Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Dark/Light Theme**: Toggle between themes with smooth transitions
- **Modern UI**: Clean, professional design with smooth animations
- **SEO Optimized**: Meta tags, Open Graph, and Twitter Card support
- **Performance**: Built with Next.js for optimal loading speeds
- **Contact Form**: Functional contact form with validation
- **Blog Section**: Ready for content management
- **Project Showcase**: Interactive project gallery with modals

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Forms**: React Hook Form
- **Icons**: Lucide React
- **Deployment**: Vercel

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.local.example .env.local
   ```
   Edit `.env.local` with your configuration.

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy automatically on every push

### Environment Variables

For production deployment, set these environment variables:

- `SENDGRID_API_KEY`: Your SendGrid API key for contact form
- `FROM_EMAIL`: Email address for sending contact form submissions
- `TO_EMAIL`: Your email address to receive contact form submissions

## Customization

### Personal Information

Update the following files with your information:

- `app/layout.tsx`: Meta tags and site title
- `components/Hero.tsx`: Name, role, and introduction
- `components/Footer.tsx`: Social media links
- `components/Navbar.tsx`: Profile picture (add `public/profile.jpg`)
- `app/about/page.tsx`: Bio, skills, and experience
- `app/projects/page.tsx`: Your projects
- `app/blog/page.tsx`: Your blog posts

### Styling

- Colors: Modify `tailwind.config.js`
- Fonts: Update `app/layout.tsx`
- Components: Edit individual component files

### Content

- **Projects**: Update the projects array in `app/projects/page.tsx`
- **Blog Posts**: Update the blogPosts array in `app/blog/page.tsx`
- **Experience**: Update the experience array in `app/about/page.tsx`
- **Skills**: Update the skills array in `app/about/page.tsx`

## Project Structure

```
├── app/                    # Next.js app directory
│   ├── about/             # About page
│   ├── blog/              # Blog page
│   ├── contact/           # Contact page
│   ├── projects/          # Projects page
│   ├── api/               # API routes
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
├── lib/                   # Utility functions
├── types/                 # TypeScript type definitions
└── public/               # Static assets
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Adding Your Profile Picture

To add your profile picture to the header:

1. **Replace the placeholder**: Add your profile photo as `public/profile.jpg`
2. **Image requirements**: 
   - Square aspect ratio (e.g., 400x400px)
   - JPG format recommended
   - Professional headshot with good lighting
   - File size under 500KB for optimal performance

The navbar will automatically use your photo. If the image fails to load, it will fallback to the SVG placeholder with your initials.

## Contact

- Email: faysal@example.com
- LinkedIn: [linkedin.com/in/faysal](https://linkedin.com/in/faysal)
- GitHub: [github.com/faysal](https://github.com/faysal)