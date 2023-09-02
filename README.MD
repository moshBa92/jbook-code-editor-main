# JBook - Code Editor

## Description

JBook is a code editor designed to make your coding experience smoother and more efficient. Built with TypeScript, Redux, and Hooks, it offers a robust environment for developing your projects.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Tech Stack](#tech-stack)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

Follow these steps to get JBook up and running:

### Prerequisites

- Node.js and npm installed on your machine

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/moshBa92/Jbook.git
   ```

2. **Navigate to the packages folder:**

   ```bash
   cd jbook/packages
   ```

3. **Install dependencies in the CLI, Local API, and Local Client folders:**

   ```bash
   cd cli && npm install
   cd ../local-api && npm install
   cd ../local-client && npm install --force
   ```

4. **Navigate back to the root directory:**

   ```bash
   cd ../..
   ```

5. **Install root-level dependencies:**

   ```bash
   npm install
   ```

## Usage

After all dependencies are installed, run the following command to start the JBook code editor:

```bash
lerna run start
```

## Tech Stack

- **TypeScript**: For strong typing and better maintainability.
- **Redux**: For state management.
- **Hooks**: For functional components and lifecycle features.

## Thanks for trying Jbook
