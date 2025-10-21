# EnergyShare Prototype

A smart energy trading platform prototype that connects energy sellers and consumers.

## 🌟 Features

- **Consumer Dashboard**: Browse nearby energy sellers, compare prices, track consumption
- **Seller Dashboard**: List energy for sale, set prices, monitor earnings
- **Interactive Maps**: Location-based seller discovery using Leaflet
- **Real-time Charts**: Energy consumption and pricing visualizations with ECharts
- **Responsive Design**: Mobile-first UI built with Tailwind CSS

## 🚀 Live Demo

Visit: [https://oliswee.github.io/prototypetest/](https://oliswee.github.io/prototypetest/)

## 📁 Project Structure

```
├── index.html                  # Entry point (redirects to login)
├── login.html                  # Login page
├── user-type.html             # User role selection
├── energyshare-consumer.html  # Consumer dashboard
└── energyshare-seller.html    # Seller/Prosumer dashboard
```

## 🛠️ Technologies

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Charts**: ECharts 5.4.3
- **Maps**: Leaflet 1.9.4
- **Icons**: Iconify

## 📱 Usage

1. Open the app and login
2. Select your role:
   - **Energy Buyer**: Purchase clean energy from community sellers
   - **Energy Seller**: Sell excess solar/battery power
   - **Hybrid Prosumer**: Buy and sell as needed
3. Explore the dashboard features

## 🔧 Local Development

Simply open `index.html` in a browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## 📄 License

Educational project for INFO3315 course.
