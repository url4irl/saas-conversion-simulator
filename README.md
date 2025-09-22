# saas-conversion-simulator

Simple, interactive SaaS Conversion Simulator. It allows you to model and visualize the financial and user metrics for a SaaS business based on customizable parameters.

## Features

- **Market & Demographic Selection:** Choose from predefined markets (Europe, North America, Latin America, Asia, Global) and demographic segments (Tech Savvy Young Adults, Gen Z, Business Professionals, General Adults, Seniors).
- **Custom User Input:** Option to manually set the number of monthly active users for custom scenarios.
- **Conversion & Pricing Controls:** Adjust conversion rate, cost per user, basic and premium tier prices, and the percentage split between tiers.
- **Real-Time Results:** Instantly see user breakdown, financial performance, unit economics, and market analysis as you change inputs.
- **Strategic Scenarios:** Explore preset scenarios (Conservative Start, Viral Growth, Market Leader) to understand different growth and profit outcomes.
- **Modern UI:** Uses Tailwind CSS for a clean, responsive, and visually appealing interface.

## Usage

1. **Open `index.html` in your browser or navigate to [saas-converter-simulator.url4irl.com](https://saas-converter-simulator.url4irl.com).**
2. Adjust the controls in the top section to model your SaaS business:
	- Select a market and demographic, or choose "Custom Users" to enter your own user count.
	- Set conversion rate, cost per user, pricing for basic and premium tiers, and the premium tier split.
3. View the results and strategic scenarios below the controls. All calculations update in real time.

## Customization

- You can modify the market sizes, demographic multipliers, and scenario presets directly in the JavaScript section of `index.html`.
- The UI theme and colors are defined using CSS variables and Tailwind configuration in the `<head>` section.

## How It Works

The simulator calculates:

- **User Breakdown:** Total, free, and paying users, split by tier.
- **Financial Performance:** Revenue, costs, profit, and profit margin.
- **Unit Economics:** Revenue/cost/net per user, payback ratio.
- **Market Analysis:** Market size, penetration, growth potential, and estimated market cap.

All logic is contained in the HTML file—no backend or build tools required.

## License

This project is open source and free to use for educational and business modeling purposes.
