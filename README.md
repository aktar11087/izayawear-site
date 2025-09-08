# IZAYA WEAR Website

This is the official website for IZAYA WEAR, a modern modest fashion brand based in Bangladesh.

## Setup Instructions

1. Clone this repository
2. The website will automatically deploy to GitHub Pages via the included GitHub Actions workflow
3. For custom domain setup:
   - Add your domain to the `CNAME` file
   - Configure DNS settings with your domain registrar:
     - Create a CNAME record pointing to `izayawear.github.io`
     - Or create A records pointing to GitHub Pages IP addresses:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153
   - In GitHub repository settings, go to Pages > Custom domain and enter your domain

## Repository Structure

- `index.html` - Main website file
- `CNAME` - Custom domain configuration
- `.github/workflows/deploy.yml` - GitHub Actions deployment workflow
- `README.md` - This file

## Technologies Used

- HTML5
- CSS3 with Flexbox and Grid
- JavaScript (minimal)
- GitHub Pages
- GitHub Actions
