# Wallet Generator

![Wallet Generator Banner](path-to-your-banner-image.png)

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Ensure you have the following installed on your machine:

- **Node.js** (v14 or later)
- **npm** (v6 or later) or **yarn**

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/lcodepanda/web3wallet.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd Web3-Wallet
   ```

3. **Install Dependencies**

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

### Running the Application

After installing the dependencies, you can start the development server.

Using npm:

```bash
npm start
```

Or using yarn:

```bash
yarn start
```

The application will run at `http://localhost:3000`. Open this URL in your browser to view the Wallet Generator.

## Project Structure
**Note:** This structure is alterable.

```
Web3-Wallet/
├── node_modules/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── SolanaWallet.js
│   │   ├── EthWallet.js
│   │   └── MnemonicContainer.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── ...
```

- **public/**: Contains the public assets and the main HTML file.
- **src/**: Contains the source code of the application.
  - **components/**: Reusable React components.
  - **App.js**: The main application component.
  - **index.js**: Entry point of the React application.
- **package.json**: Lists project dependencies and scripts.
- **README.md**: Documentation of the project.


## Technologies Used

- **React**: Front-end JavaScript library for building user interfaces.
- **BIP39**: Bitcoin Improvement Proposal for mnemonic seed phrases.
- **Vercel Analytics**: Real-time analytics for monitoring application performance.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **JavaScript (ES6+)**: Programming language used for building the application.
- **Git & GitHub**: Version control and repository hosting.

