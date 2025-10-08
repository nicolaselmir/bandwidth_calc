# 🏆 Sport Streaming Bandwidth Calculator

A comprehensive bandwidth calculator for sport streaming platforms to calculate yearly bandwidth consumption and plan infrastructure needs.

## Features

- **Yearly Bandwidth Planning**: Calculate total bandwidth consumption for an entire year
- **Real-time Calculations**: Instant updates when changing parameters
- **Multiple Quality Options**: Support for 480p to 4K streaming
- **Comprehensive Results**: Peak bandwidth, total data transfer, and monthly breakdowns
- **Dark Theme**: Modern, professional interface
- **Responsive Design**: Works on desktop and mobile devices

## Input Parameters

- Average Concurrent Viewers
- Video Quality (480p to 4K)
- Audio Quality (64 kbps to 320 kbps)
- Streams per Week
- Average Stream Duration
- Weeks Active per Year

## Results

- Total Streams per Year
- Total Streaming Hours
- Peak Bandwidth Needed
- Total Data Transfer (Year)
- Monthly Data Transfer
- Recommended Server Bandwidth

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. Push your code to a GitHub repository
2. Connect your GitHub account to Vercel
3. Import your repository in Vercel dashboard
4. Deploy automatically

### Option 3: Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Drag and drop your project folder
3. Deploy instantly

## Local Development

To run locally:

```bash
npm install
npm run dev
```

## File Structure

```
bandwidth_calc/
├── index.html          # Main application file
├── vercel.json         # Vercel configuration
├── package.json        # Project dependencies
└── README.md          # This file
```

## Technologies Used

- HTML5
- CSS3 (with modern features like backdrop-filter)
- Vanilla JavaScript
- Vercel for deployment

## License

MIT License
