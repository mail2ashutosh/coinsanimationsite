# Coin Animation using Pixi Particles

This project brings a burst of flipping coins to life with an eye-catching animation tailored for casino games.

## **Project Overview**

The primary goal is to deliver a smooth and optimized coin flip animation, ensuring an immersive visual experience.

## Preview Video

To download the video, click the link below and then click on the "View raw" link to save the file to your computer.

[Download Preview Video (coin-animation.mp4)](preview/scoin-animation.mp4)

### **Key Features**

- **Coin Flip Animation**: Uses a series of textures (`coin_0` to `coin_6`) to create a realistic flipping effect.
- **Configurable Particle System**: The animation behavior is fully customizable using the Pixi Particles
  Editor – [Pixi Particles Editor](https://pixijs.io/pixi-particles-editor).
- **Memory Efficient**: Ensures efficient resource cleanup to maintain performance.

### **Scope**

- **Coin Visibility**: Coins gradually appear, reach full visibility, perform a series of three vertical flips, and then
  fade out smoothly.
- **Flip Movement**: Each coin performs a simple yet dynamic vertical flip along the Y-axis.
- **Size**: Coins gradually increase in size throughout the animation, enhancing the flipping effect.
- **Positioning**: The animation starts from a central point, with coins scattering outward in all directions.

## **Animation Configuration**

The particle behavior is defined in `CoinShowerConfig.json`, allowing you to adjust:

- Visibility, scale, speed, rotation, and lifespan of each coin
- Coin texture paths
- Emission frequency and overall particle dynamics

### **Installation Steps**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mail2ashutosh/coinshowerpreviewgame.git
2. **Execute below commands on the terminal**:

- Install dependencies, run ```npm install```
- Build the project, run ```npm run build```
- Start the application, run ```npm run start```

### How to Use

- Load the game with GitHub page link or for local launch the url: http://localhost:8888/
- The game is designed to be played in mobile portrait mode (375x667) using the Chrome emulator. If you resize the
  screen, please refresh the page to ensure the game adjusts to the current screen size.
- For a more detailed overview, check out the README.md file.

## Change Logs

### 0.0.2 (2024-09-24)

#### [Added]

- Implemented coin burst and flip animations to closely match the demo video, achieving over 90% similarity.

### 0.0.1 (2024-09-23)

#### [Added]

- Initial project setup using TypeScript, PixiJS v6, Webpack & Webpack-CLI.
- Established a scalable folder structure for future enhancements.
- Configured webpack.config.ts for build processes.
- Implemented the enable/disable/press effect for the button and performed code refactoring.
