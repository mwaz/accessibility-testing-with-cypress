# Accessibility testing with Cypress

## Set up instructions.

### 1. Clone app and install dependencies.
```bash
# Clone repository
git clone https://github.com/mwaz/accessibility-testing-with-cypress.

# CD into the directory 
cd accessibility-testing-with-cypress

# Install dependencies 
npm install
```

### 2. Start web app server

```bash
# default application server is port :3000
npm start
```

### 3. Running tests with accessibility violations

```bash
# checkout 'main' branch using git on cloned repository
git checkout main

# run test command
npx cypress run

```

### 4. Running tests without accessibility violations

```bash
# checkout 'fix/accessibility-violations' branch using git on cloned repository

git checkout main

# run test command
npx cypress run
```
