# System Patterns

## Architecture Overview
The application follows a single-page application (SPA) architecture with the following components:

1. **Frontend**
   - HTML5 for structure
   - CSS3 for styling and animations
   - JavaScript for interactivity and calculations
   - Chart.js for data visualization

2. **Key Components**
   - Interactive Calculator
   - Visualization Charts
   - Educational Content Sections
   - Real-time Updates

## Design Patterns

### 1. Component Organization
- Modular HTML structure
- Separated concerns (HTML/CSS/JS)
- Reusable UI components

### 2. Data Flow
- Unidirectional data flow
- Real-time updates based on user input
- Centralized calculation logic

### 3. Visualization Patterns
- Responsive charts
- Interactive data points
- Consistent color scheme
- Clear data representation

## Technical Implementation

### 1. Core Functions
```javascript
- blackScholes(S, K, T, r, sigma)
- normalCDF(x)
- erf(x)
```

### 2. Chart Implementations
- Stock Price Chart
- Strike Price Chart
- Time Decay Chart
- Interest Rate Chart
- Volatility Chart
- Probability Distribution Chart

### 3. UI Components
- Slider Controls
- Result Display
- Formula Box
- Variable Cards
- Interactive Sections

## Code Organization
1. **HTML Structure**
   - Semantic markup
   - Clear section hierarchy
   - Accessible elements

2. **CSS Architecture**
   - Modular styling
   - Responsive design
   - Consistent theming
   - Gradient effects

3. **JavaScript Organization**
   - Utility functions
   - Chart configurations
   - Event handlers
   - Calculation logic

## Performance Considerations
- Efficient calculations
- Optimized chart rendering
- Responsive updates
- Smooth animations

## Future Extensions
- Additional option types
- More complex scenarios
- Advanced visualizations
- User preferences
- Data persistence 