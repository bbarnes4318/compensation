# Agent Compensation Portal

A comprehensive Final Expense Agent Compensation Calculator and Portal for insurance agents and agencies.

## Features

### Agent View
- **Standard Variables**: Hourly pay, hours per week, conversion percentage
- **Advanced Variables**: Level coverage %, graded %, placement %, lapsed %, average premium
- **Commission Schedule**: Dynamic commission rates based on conversion performance
- **Real-time Calculations**: Instant updates for monthly and annual compensation
- **Independent Agent Calculator**: Modal for independent agent scenarios

### Company View (Full Version)
- **Agent Team Management**: Add, remove, and manage multiple agents
- **Revenue & Scale Metrics**: Company-wide financial overview
- **Profit Analysis**: Detailed breakdown of company profitability
- **ROI Calculations**: Return on investment metrics

## Versions

- **`final.html`**: Complete version with both Agent and Company views
- **`versions/agent-only.html`**: Simplified version with Agent view only

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/bbarnes4318/compensation.git
cd compensation
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser to `http://localhost:8080`

### Production Deployment

The application is designed for deployment on Digital Ocean App Platform:

1. Connect your GitHub repository to Digital Ocean App Platform
2. The platform will automatically detect the Node.js configuration
3. Deploy using the provided `package.json` and static file serving

## Technical Details

### Architecture
- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks)
- **Styling**: Custom CSS with CSS variables for theming
- **Responsive**: Mobile-friendly design with responsive breakpoints
- **Browser Support**: Modern browsers with ES6+ support

### Key Components
- **Commission Calculator**: Dynamic rate calculation based on performance
- **Variable Management**: Interactive sliders and inputs for all parameters
- **Real-time Updates**: Instant recalculation on any variable change
- **Data Persistence**: Browser-based data storage

### Color Scheme
- **Primary**: Navy Blue (#1E3A8A)
- **Secondary**: Red (#DC2626)
- **Professional**: Clean, corporate design with patriotic undertones

## File Structure

```
├── final.html              # Main application (Agent + Company views)
├── versions/
│   └── agent-only.html     # Agent-only version
├── public/
│   └── amben.png          # Company logo
├── package.json           # Node.js configuration
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## Usage

### For Agents
1. Adjust your standard variables (hourly pay, hours per week, conversion %)
2. Review and modify advanced variables as needed
3. View your commission schedule based on performance
4. Calculate independent agent scenarios using the "Go Independent?" link

### For Companies
1. Switch to Company View
2. Add agents to your team
3. Monitor company-wide metrics
4. Analyze profitability and ROI

## Deployment

### Digital Ocean App Platform

This application is optimized for deployment on Digital Ocean App Platform:

- **Static Site**: Served via `http-server` for optimal performance
- **Node.js**: Minimal Node.js setup for static file serving
- **Environment**: Production-ready configuration included

### Manual Deployment

For other platforms:
1. Serve the HTML files as static content
2. Ensure the `public/` directory is accessible
3. Configure proper MIME types for `.html` files

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

MIT License - see LICENSE file for details

## Support

For issues or questions, please open an issue on GitHub or contact the repository maintainer.

---

**Built for Final Expense Insurance Agents and Agencies**
