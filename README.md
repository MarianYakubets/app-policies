# App Policies

Privacy policies and terms of service for my iOS apps.

## Hosted URL

Once GitHub Pages is enabled, policies will be available at:
- **Main page**: `https://marianyakubets.github.io/app-policies/`
- **Tip Calculator + Privacy Policy**: `https://marianyakubets.github.io/app-policies/tip-calculator-plus/privacy-policy.html`
- **Tip Calculator + Terms of Service**: `https://marianyakubets.github.io/app-policies/tip-calculator-plus/terms-of-service.html`

## Setup GitHub Pages

1. Go to repository Settings
2. Navigate to "Pages" in the sidebar
3. Under "Source", select "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Click Save
6. Wait a few minutes for deployment

## Apps

### Tip Calculator +
- `/tip-calculator-plus/privacy-policy.html` - Privacy Policy
- `/tip-calculator-plus/terms-of-service.html` - Terms of Service
- `/tip-calculator-plus/index.html` - App landing page

## Adding a New App

1. Create a new folder with the app name (lowercase, no spaces)
2. Copy the structure from `tip-calculator-plus/`:
   - `index.html` - App landing page
   - `privacy-policy.html` - Privacy policy
   - `terms-of-service.html` - Terms of service
3. Update the main `index.html` to include the new app
4. Update contact email if different

## Contact

- Email: similarswords@gmail.com

## Structure

```
app-policies/
├── README.md
├── index.html          # Main landing page
├── style.css           # Shared styles
└── tip-calculator-plus/
    ├── index.html
    ├── privacy-policy.html
    └── terms-of-service.html
```
