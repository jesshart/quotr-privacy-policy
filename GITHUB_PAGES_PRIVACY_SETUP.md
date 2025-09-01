# GitHub Pages Privacy Policy Setup - Detailed Instructions

## Overview
This guide will walk through creating a GitHub repository and hosting the QUOTR privacy policy using GitHub Pages (completely free).

## Prerequisites
- GitHub account (free at https://github.com)
- The `privacy-policy.html` file (already created in this project)

## Step-by-Step Instructions

### Step 1: Create New GitHub Repository
1. Go to https://github.com and sign in
2. Click the green "New" button (or go to https://github.com/new)
3. Repository settings:
   - **Repository name**: `quotr-privacy-policy`
   - **Description**: `Privacy policy for QUOTR watchOS app`
   - **Visibility**: ✅ Public (required for GitHub Pages)
   - **Initialize**: ✅ Add a README file
4. Click "Create repository"

### Step 2: Upload Privacy Policy File
1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop the `privacy-policy.html` file from this QUOTR project
3. Or click "choose your files" and select `privacy-policy.html`
4. In the commit message box at bottom:
   - **Title**: `Add privacy policy for QUOTR app`
   - **Description**: `Privacy policy for QUOTR watchOS app submission`
5. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click the "Settings" tab (top navigation)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source":
   - Select "Deploy from a branch"
   - Branch: Select "main" (or "master")
   - Folder: Select "/ (root)"
4. Click "Save"
5. GitHub will show a message: "Your site is ready to be published at https://[username].github.io/quotr-privacy-policy/"

### Step 4: Wait and Verify (5-10 minutes)
1. Wait 5-10 minutes for GitHub to build and deploy
2. Visit your privacy policy URL: 
   ```
   https://[YOUR-GITHUB-USERNAME].github.io/quotr-privacy-policy/privacy-policy.html
   ```
3. Verify the page loads correctly with the privacy policy content

### Step 5: Test and Document
1. **Test the URL** in multiple browsers to ensure it works
2. **Save the URL** - you'll need it for App Store Connect
3. **Bookmark it** for future reference

## Expected Final URL Format
```
https://[YOUR-GITHUB-USERNAME].github.io/quotr-privacy-policy/privacy-policy.html
```

**Example**: If your GitHub username is `jessehartman`, the URL would be:
```
https://jessehartman.github.io/quotr-privacy-policy/privacy-policy.html
```

## Using the URL in App Store Connect
1. When setting up your app in App Store Connect
2. Go to "App Information" section
3. Find "Privacy Policy URL" field
4. Paste your GitHub Pages URL
5. Save changes

## Troubleshooting

### If the page shows 404 error:
- Wait longer (can take up to 10 minutes)
- Check that the file is named exactly `privacy-policy.html`
- Verify the repository is public
- Ensure GitHub Pages is enabled with "main" branch selected

### If content doesn't look right:
- Check that the HTML file uploaded correctly
- View the raw file in GitHub to verify content

### If you need to update the privacy policy later:
1. Go to your repository
2. Click on `privacy-policy.html`
3. Click the pencil icon to edit
4. Make changes and commit
5. Changes will be live in 1-2 minutes

## Security Notes
- ✅ This URL will be publicly accessible (required by Apple)
- ✅ No sensitive information in privacy policy
- ✅ GitHub Pages is secure and reliable
- ✅ Free forever for public repositories

## Timeline
- Repository setup: 2 minutes
- File upload: 1 minute  
- GitHub Pages activation: 1 minute
- Deployment wait time: 5-10 minutes
- **Total time**: ~10-15 minutes

## What to Report Back
Once complete, provide:
1. ✅ The final privacy policy URL
2. ✅ Confirmation that the URL loads the privacy policy
3. ✅ Screenshot of the privacy policy page (optional but helpful)

This URL will be needed for the App Store Connect setup in the next phase of the submission process.