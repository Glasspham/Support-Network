# Network Tools Suite

A comprehensive web application for network administrators and engineers, featuring advanced IP address management, subnet calculations, and network analysis tools. Built with modern web technologies including HTML5, CSS3, JavaScript ES6, and Bootstrap 5.

## 🌐 Live Demo

**Try it now: [https://glasspham.github.io/Support-Network/](https://glasspham.github.io/Support-Network/)**

The application is deployed and running live on GitHub Pages. You can access all features directly in your browser without any installation.

## 📋 Project Description

The Network Tools Suite is a powerful, browser-based application designed to simplify complex networking tasks. This project provides a suite of tools for:

### 🌐 Core Features

- **VLSM (Variable Length Subnet Masking) Calculator**: Advanced subnet calculations with custom subnet sizes
- **IP Address Validation & Analysis**: Comprehensive IP address checking and validation tools
- **IP Aggregation & Supernetting**: Automatic route summarization and network aggregation
- **Binary/Decimal Conversion**: Convert between different number representations for networking
- **Subnet Planning**: Plan and optimize network topologies with intelligent subnet allocation
- **Network Range Analysis**: Analyze IP ranges, calculate usable hosts, and determine network boundaries

### 🎯 Target Users

- **Network Engineers**: Simplify daily subnet calculations and network planning
- **System Administrators**: Validate IP configurations and plan network expansions
- **Students & Educators**: Learn networking concepts with interactive tools
- **IT Professionals**: Quick reference for network troubleshooting and design

### ✨ Key Benefits

- **No Installation Required**: Browser-based tools accessible anywhere
- **Real-time Calculations**: Instant results with interactive interfaces
- **Educational Value**: Visual representations help understand networking concepts
- **Professional Grade**: Accurate calculations suitable for production environments
- **Mobile Friendly**: Responsive design works on all devices

## 🚀 Technology Stack

- **HTML5** - Modern semantic markup and structure
- **CSS3** - Advanced styling with custom properties and animations
- **JavaScript ES6+** - Modern JavaScript with modules and async/await
- **Bootstrap 5** - Responsive UI framework and components
- **Font Awesome** - Professional icon library
- **GitHub Pages** - Free static site hosting and deployment

## 📋 System Requirements

- **Modern Web Browser** (Chrome, Firefox, Safari, Edge)
- **Internet Connection** (for CDN resources)
- **No installation required** - runs entirely in the browser

## 🛠️ Installation & Setup

### Quick Start (Recommended)

Simply open the live demo: [https://glasspham.github.io/Support-Network/](https://glasspham.github.io/Support-Network/)

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/Glasspham/Support-Network.git
   cd Support-Network
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

### 6. Run Code Linting

```bash
npm run lint
```

## 🚀 Deployment

This project is automatically deployed to GitHub Pages at [https://glasspham.github.io/Support-Network/](https://glasspham.github.io/Support-Network/)

### Deploy to GitHub Pages

The project includes GitHub Actions workflow for automatic deployment:

1. **Push to main branch** - Automatically triggers deployment
2. **Build process** - Vite builds the project for production
3. **Deploy** - Files are deployed to GitHub Pages
4. **Live site** - Available at the GitHub Pages URL

### Manual Deployment

To deploy manually:

```bash
# Build the project
npm run build

# Deploy to GitHub Pages (if you have gh-pages package)
npm run deploy
```

## 📁 Project Structure

```

```

├── js/ # Core networking logic modules
│ ├── binaryMap.js # Binary/decimal conversion utilities
│ ├── ipAggregator.js # IP aggregation and supernetting logic
│ ├── ipChecker.js # IP address validation and analysis
│ ├── uiHandler.js # User interface event handlers
│ └── vlsmLogic.js # VLSM calculation algorithms
├── .github/ # GitHub Actions workflow
│ └── workflows/
│ └── deploy.yml # Automated GitHub Pages deployment
├── .gitignore # Git ignore file
├── index.html # Main HTML file with Bootstrap integration
├── README.md # Project documentation (this file)
└── style.css # Custom styles and responsive design

````

## 🌟 Key Features & Modules

### VLSM Calculator (`vlsmLogic.js`)

- Calculate optimal subnet sizes for given requirements
- Support for custom host requirements per subnet
- Automatic subnet allocation with minimal waste
- Binary and decimal representation of results

### IP Address Validator (`ipChecker.js`)

- Validate IP address format and ranges
- Check if IP is assignable within a subnet
- Identify network, broadcast, and usable IP ranges
- Support for both IPv4 validation

### IP Aggregation Tool (`ipAggregator.js`)

- Automatic route summarization
- Find longest common prefix for multiple networks
- Optimize routing tables with supernetting
- Calculate aggregate network addresses

### Binary Mapping Utilities (`binaryMap.js`)

- Convert between CIDR notation and subnet masks
- Binary to decimal and decimal to binary conversion
- Wildcard mask calculations
- Network address calculations

## 🔍 Troubleshooting

### Common Issues:

1. **Port Already in Use**: If port 5173 is occupied, Vite will automatically select another available port
2. **Module Not Found**: Run `npm install` to reinstall dependencies
3. **TypeScript Errors**: Check `tsconfig.json` configuration and ensure all type definitions are installed
4. **Build Failures**: Clear cache and reinstall dependencies

### Reset Project Dependencies:

```bash
# Remove node_modules and reinstall
rm -rf node_modules package-lock.json
npm install

# Or on Windows PowerShell
Remove-Item -Recurse -Force node_modules
Remove-Item package-lock.json
npm install
````

## 📝 Development Workflow

To start developing:

1. Open terminal in project directory
2. Run `npm run dev` to start development server
3. Open browser at `http://localhost:5173`
4. Edit files in `src/` directory for React components
5. Edit files in `js/` directory for networking logic
6. Changes will hot-reload automatically
7. Use browser developer tools for debugging

## 🧪 Testing Network Calculations

The application includes several built-in examples and test cases:

- **VLSM Scenarios**: Test with different subnet requirements
- **IP Validation**: Try various IP formats and edge cases
- **Aggregation Examples**: Practice with multiple network ranges
- **Binary Conversion**: Verify calculations with known values

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Contribution Guidelines:

- Follow TypeScript best practices
- Add comments for complex networking algorithms
- Test calculations with known correct values
- Update documentation for new features
- Maintain consistent code style with ESLint

## 🙏 Acknowledgments

- Built with modern web technologies for optimal performance
- Inspired by the need for accessible networking tools
- Thanks to the open-source community for amazing libraries
- Deployed with GitHub Pages for easy accessibility

## 🔗 Links

- **Live Application**: [https://glasspham.github.io/Support-Network/](https://glasspham.github.io/Support-Network/)
- **GitHub Repository**: [https://github.com/Glasspham/Support-Network](https://github.com/Glasspham/Support-Network)
- **Issues & Feedback**: [GitHub Issues](https://github.com/Glasspham/Support-Network/issues)

---

_Built with ❤️ using Vite + React + TypeScript for the networking community_
