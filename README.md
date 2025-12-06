# Top Rental - Property Holding System

A property reservation and holding deposit system for your rental marketplace. This site allows customers to book and hold properties by paying a $50 holding deposit.

## Features

- 📋 Complete customer information collection
- 🏠 Property address input
- 📅 Check-in/Check-out date selection
- 👥 Guest count tracking
- 💳 PayPal integration for $50 holding deposit
- ✅ Form validation
- 📱 Responsive design
- 🔒 Secure payment processing

## How It Works

1. Customers enter their personal information (name, email, phone)
2. Enter property details and dates
3. Pay the $50 holding deposit via PayPal
4. Receive confirmation for their reservation

## Deployment

This site is deployed via **GitHub Pages**.

### Setup Instructions

1. **Create a new GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Property Holding System"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/property-marketplace.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository settings
   - Select "Pages" from the left menu
   - Choose `main` branch as source
   - Save

3. **Your site will be live at:**
   `https://YOUR_USERNAME.github.io/property-marketplace/`

## Customization

- **Change payment amount:** Edit the `value: '50.00'` in the PayPal section
- **Modify colors:** Update the gradient colors in the CSS (`#667eea 0%, #764ba2 100%`)
- **Update branding:** Change "Top Rental" text throughout the page

## PayPal Integration

This site uses your PayPal Client ID. All payments go directly to your PayPal account.

## Support

For technical issues, check the browser console for error messages.
