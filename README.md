# React Native CLI

- Install Homebrew:
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Confirm if Homebrew is installed:
```sh
brew --version
```

- Install CocoaPods:
```sh
brew install cocoapods
```

Confirm if CocoaPods is installed:
```sh
pod --version
```

- Install [VS Code](https://code.visualstudio.com)
- Install nvm (Node Version Manager):
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
```

- Install [Node.js](https://nodejs.org/en/download/package-manager) using nvm:
```sh
nvm install 22
```

- Confirm if Node.js is installed:
```sh
node -v
```

- Confirm if npm is installed:
```sh
npm -v
```

- Install pnpm:
```sh
npm install -g pnpm
```

- Confirm if npm is installed:
```sh
pnpm -v
```

Create the project:
```sh
npx react-native init myskills
```

## [Adding TypeScript to an Existing Project](https://reactnative.dev/docs/typescript)

Add TypeScript, types, and ESLint plugins to your project.:
```sh
npm install -D @tsconfig/react-native @types/jest @types/react @types/react-test-renderer typescript
```