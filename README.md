git checkout main
git pull origin main

git checkout -b feature/landing-page

git add .
git commit -m "Initial landing page structure"
git tag v0.1-initial-setup

git add .
git commit -m "Add SEO and accessibility improvements"
git tag v0.2-accessibility-seo

git add .
git commit -m "Implement bachelor project landing content"
git tag v0.3-content

git add .
git commit -m "Add responsive styling and UI optimization"
git tag v1.0-landing-release

git push origin feature/landing-page --tags
