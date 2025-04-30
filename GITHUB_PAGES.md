# Deploying to GitHub Pages

Follow these steps to deploy this application to GitHub Pages:

## 1. Create a GitHub Repository

If you haven't already, create a new GitHub repository to host your project.

## 2. Update Repository Information

Before pushing your code, make sure to update:

- The GitHub URLs in the footer of `index.html`
- Your GitHub username in the README.md file

## 3. Push Your Code

Push your code to your GitHub repository:

```bash
# Initialize a git repository (if not already done)
git init

# Add all files to git
git add .

# Commit the files
git commit -m "Initial commit"

# Add your GitHub repository as the origin
git remote add origin https://github.com/yourusername/openai-image-compare.git

# Push to GitHub
git push -u origin main
```

## 4. Enable GitHub Pages

1. Go to your GitHub repository in a web browser
2. Click on "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"

## 5. Access Your Site

Your site will be published at:
`https://yourusername.github.io/openai-image-compare`

It may take a few minutes for your site to be published.

## 6. Update Repository Information (Optional)

You can add the website URL to your repository description for easy access:

1. Go to your repository main page
2. Click the "Edit" button on the right side of the About section
3. Add your GitHub Pages URL to the "Website" field
4. Click "Save"
