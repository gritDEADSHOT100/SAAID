# Saaid's World

A static portfolio built with HTML, CSS and JavaScript. Includes the interactive island, six portfolio sections, six case-study pages, photos and CV.

## Deploy on Vercel

1. Extract this ZIP.
2. Upload the extracted contents to a GitHub repository. Keep vercel.json and the dist folder at the repository root.
3. In Vercel, create a new project and import that repository.
4. Use these settings if asked:
   - Framework Preset: Other
   - Root Directory: the repository root
   - Build Command: leave blank
   - Install Command: leave blank
   - Output Directory: dist
5. Deploy.

The included vercel.json supplies these settings. No API keys, environment variables, database or package installation are needed. Do not add a catch-all rewrite: the case studies are separate HTML files.

Official configuration references:
https://vercel.com/docs/project-configuration/vercel-json
https://vercel.com/docs/builds/configure-a-build

## Edit the site

- dist/index.html: homepage copy and structure
- dist/style.css: colours, responsive layout and typography
- dist/app.js: experience, projects, gallery and interactive map
- dist/case-studies/: individual case-study pages
- dist/assets/: photos and case-study screenshots
- dist/Saaid-CV.pdf: downloadable CV

Replace the CV with a PDF using the same filename to keep links working.

## What is included

The ZIP contains the deployable site and this guide. It does not include the ChatGPT hosting identity, repository credentials or internal review page.

The email button opens the visitor's email app. It is not a contact form. The case-study PDF buttons link to Google Drive; Google Fonts, company websites, LinkedIn and the prototype demo remain external links.

See REVIEW.md for the checks completed and remaining testing limits.
