# Leads Generation Dashboard

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/leads-generation-dashboard)

A professional web application for generating and managing business leads with real-time data synchronization, advanced search capabilities, and data export features.

## Features

### Core Features
- **Modern UI**: Professional, responsive design with gradient backgrounds and smooth animations
- **Lead Generation Form**: Collect user inputs (Type, Query, Max Results, Geo Location)
- **Webhook Integration**: Send data to n8n webhook for processing
- **Real-time Data Display**: View and refresh data from Google Sheets

### Advanced Features
- **🔍 Advanced Search**: Search leads by name, address, phone, or category in real-time
- **🎯 Smart Filters**: Filter leads by rating (4+ stars), website availability, or phone availability
- **📥 CSV Export**: Export filtered or all leads to CSV with one click
- **📊 Data Analytics**: View lead counts and statistics
- **📱 Mobile Responsive**: Works perfectly on all device sizes
- **🎨 Professional Design**: Modern, clean interface with intuitive navigation

## Quick Start

### Local Development

1. Clone or download the project
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open http://localhost:3000 in your browser

### Vercel Deployment (Recommended)

This app is fully configured for Vercel deployment with:
- ✅ Optimized `vercel.json` configuration
- ✅ Security headers (X-Content-Type-Options, X-Frame-Options, X-XSS-Protection)
- ✅ Static file serving
- ✅ SPA routing support

**Deploy in 3 Steps:**

1. **Via Vercel Dashboard:**
   - Push your code to GitHub
   - Go to [vercel.com](https://vercel.com)
   - Click "Import Project" and select your repository
   - Deploy with zero configuration!

2. **Via Vercel CLI:**
   ```bash
   npm i -g vercel
   vercel --prod
   ```

3. **Via Deploy Button:**
   - Click the "Deploy with Vercel" button at the top of this README

**Post-Deployment:**
- Your app will be live at `https://your-project.vercel.app`
- SSL/HTTPS is automatically configured
- Updates are deployed automatically on every push to main branch

## Usage

### Generate Leads
1. Navigate to the "Generate Leads" tab
2. Fill in the required fields:
   - **Type**: Select the type of business (store, restaurant, service, etc.)
   - **Query**: Describe what you're looking for
   - **Max Results**: Number of results to generate (1-100)
   - **Geo Location**: Geographic location code (e.g., "in" for India)
3. Click "Generate Leads" to send the request to the webhook
4. Wait for processing and view results in the "View Data" tab

### View & Manage Data
- Navigate to the "View Results" tab to see all generated leads
- **Search**: Use the search bar to filter leads by name, address, phone, or category
- **Filter**: Click filter buttons to show:
  - All Leads
  - High Rated (4+ stars)
  - Leads with Websites
  - Leads with Phone Numbers
- **Export**: Click "Export CSV" to download filtered or all leads
- **Refresh**: Use the refresh button to get the latest data from Google Sheets

## Configuration

### Webhook URL
The application sends data to: 

### Google Sheets Integration
The app displays data from the configured Google Sheets document. For production use, you'll need to:
1. Set up Google Sheets API credentials
2. Replace the mock data with actual API calls
3. Implement proper authentication

## Technical Details

- **Frontend**: Pure HTML, CSS, JavaScript (no frameworks required)
- **Styling**: Custom CSS with modern design patterns and gradients
- **Icons**: Font Awesome 6.0
- **Fonts**: Inter from Google Fonts
- **Storage**: Local Storage for history persistence
- **Data Source**: Google Sheets (CSV export)
- **Deployment**: Optimized for Vercel static hosting with proper security headers
- **SEO**: Optimized meta tags and descriptions

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

MIT License - feel free to use and modify as needed.
