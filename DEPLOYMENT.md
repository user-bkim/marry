# Deployment Guide

This website can be easily deployed to various platforms. Here are the recommended options:

## Option 1: GitHub Pages (Recommended - Free)

1. Go to your repository on GitHub: https://github.com/user-bkim/marry
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/create-event-page-for-danny`)
5. Click "Save"
6. Your site will be published at: `https://user-bkim.github.io/marry/`

## Option 2: Netlify (Free)

1. Go to [Netlify](https://www.netlify.com/)
2. Sign up or log in
3. Click "Add new site" > "Import an existing project"
4. Connect to your GitHub repository
5. Select the `marry` repository
6. Click "Deploy site"
7. Your site will be live in minutes with a custom URL!

## Option 3: Vercel (Free)

1. Go to [Vercel](https://vercel.com/)
2. Sign up or log in
3. Click "Add New..." > "Project"
4. Import your GitHub repository
5. Click "Deploy"
6. Your site will be live instantly!

## Option 4: Local Viewing

To view locally without deploying:
1. Simply open `index.html` in any web browser
2. Or use a local server:
   ```bash
   # Using Python
   python3 -m http.server 8080
   
   # Then visit http://localhost:8080
   ```

## Adding Your Photos

Once deployed, you can add your own photos:

1. Create an `images` folder in the repository
2. Add your photos to the folder
3. Update the HTML files to reference your images:
   ```html
   <img src="images/your-photo.jpg" alt="Description">
   ```
4. Commit and push your changes
5. The site will automatically update!

## Customization Tips

- **Change colors**: Edit the gradient colors in `styles.css` and `valentine.css`
- **Update text**: Edit any text in the HTML files
- **Add more pages**: Create new HTML files and link them in the navigation
- **Modify animations**: Adjust the CSS animations in `valentine.css`

Happy sharing! 💕
