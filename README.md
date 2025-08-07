# People United for Peaceful Revolution Website

This is the official website for People United for Peaceful Revolution (PUPR), a 501(c)(3) nonprofit organization incorporated in New York.

## About PUPR

People United for Peaceful Revolution encourages and enables ordinary people to participate in the democratic process by removing systemic barriers to political engagement. Through civic education, grassroots candidate empowerment, and platforms like UnitedWeRise.org, we aim to make democratic representative government more democratic and more representative.

## Hosting on GitHub Pages

To host this website on GitHub Pages:

1. Create a new repository on GitHub (e.g., `peacefulrevolutions-website`)
2. Upload these files to the repository
3. Go to Settings > Pages in your repository
4. Select "Deploy from a branch" and choose the main/master branch
5. Your site will be available at `https://yourusername.github.io/repository-name`

## Custom Domain Setup

To use the custom domain `peacefulrevolutions.org`:

1. In your repository, create a file named `CNAME` (no extension)
2. Add `peacefulrevolutions.org` as the only content in the CNAME file
3. In your domain registrar's DNS settings, create:
   - An A record pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - A CNAME record for `www` pointing to `yourusername.github.io`

## File Structure

```
├── index.html          # Main homepage
├── styles.css          # Styling and responsive design
├── README.md           # This file
└── CNAME              # Domain configuration (create when ready)
```

## Features

- Responsive design that works on desktop and mobile
- Professional styling with PUPR branding colors
- Smooth scrolling navigation
- Information about the organization's mission and status
- Links to UnitedWeRise.org platform

## Making Updates

To update the website:
1. Edit the HTML or CSS files
2. Commit and push changes to GitHub
3. Changes will automatically deploy to the live site

## Contact

For questions about this website or PUPR, visit [UnitedWeRise.org](https://unitedwerise.org).