# Package Manager Demo Project

This project demonstrates package management using npm (Node.js), showing how to install and manage production and development dependencies.

## Project Structure

```
package-manager-demo/
├── package.json          # Node.js dependencies and scripts
├── composer.json         # PHP dependencies and autoloading
├── node_modules/         # Installed npm packages
├── screenshots/          # Installation evidence screenshots
├── README.md            # This file
└── INSTALLATION_SUMMARY.md  # Detailed package information
```

## Dependencies

### Production Dependencies
- **express** (^5.2.1) - Fast, minimalist web framework for Node.js
- **lodash** (^4.17.23) - Modern JavaScript utility library for data manipulation

### Development Dependencies
- **eslint** (^10.0.2) - Pluggable JavaScript linter for code quality and consistency
- **jest** (^30.2.0) - JavaScript testing framework with zero configuration setup
- **prettier** (^3.8.1) - Opinionated code formatter for consistent code style

## Installation

### Install All Dependencies
```bash
npm install
```

### Install Only Production Dependencies
```bash
npm install --production
```

### Install a New Production Dependency
```bash
npm install <package-name>
```

### Install a New Development Dependency
```bash
npm install --save-dev <package-name>
```

## Usage

### Running Tests
```bash
npm test
```

### Code Quality
```bash
# JavaScript linting
npx eslint .

# JavaScript formatting
npx prettier --write .
```

## Package Management Best Practices

1. **Separate production and development dependencies** - Only install what's needed for production
2. **Use semantic versioning** - Pin versions appropriately for stability
3. **Regular updates** - Keep dependencies updated for security and performance
4. **Security auditing** - Regularly check for vulnerabilities
5. **Lock files** - Commit `package-lock.json` for reproducible builds

## Evidence

This project includes screenshots in `screenshots/` folder demonstrating:
- Production dependencies installation
- Development dependencies installation
- package.json configuration
- Overall project structure

## Scripts

- `npm test` - Run JavaScript tests
- `npm run lint` - Run ESLint (add to package.json)
- `npm run format` - Run Prettier (add to package.json)

## Licence

ISC Licence
