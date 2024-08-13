# Local Development Setup for Drupal with Bootstrap and React

This guide will help you set up a local development environment for a Drupal site using Bootstrap and React.

## Initial Setup

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   ```
   
2. **Start the Local Environment:**
   ```bash
   ddev start
   ```

3. **Install Composer Dependencies:**
   ```bash
   ddev composer install
   ```

4. **Complete Drupal Setup:**
   Follow the Drupal installation instructions provided in your project or visit `https://drupalreact.ddev.site/` to complete the setup through the web interface.

## Setting Up React

1. **Navigate to the React Directory:**
   ```bash
   cd web/themes/custom/bootstrap_react/
   ```

2. **Install Node.js Dependencies:**
   ```bash
   npm install
   ```

3. **React Code Location:**
   Your React code should be located in the `js/src` folder.

4. **Main Entry Point:**
   The `index.jsx` file serves as the entry point for your React application. This is where you will import and render your components.

5. **JSX Compilation:**
   We use Babel to compile JSX code. Ensure you have Babel configured correctly in your project.

6. **Build for Development:**
   Run the following command to compile the code for development:
   ```bash
   npm run build:dev
   ```

7. **Build for Production:**
   When you're ready to compile your code for production, use:
   ```bash
   npm run build
   ```

   This will generate optimized output for production use.

## Additional Notes

- Ensure you have Node.js and npm installed on your local machine.
- For any issues with dependencies or setup, consult the documentation for Drupal, Bootstrap, and React.
- Regularly update your dependencies to keep your project secure and compatible with the latest versions.
