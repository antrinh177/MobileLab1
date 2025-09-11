# System Specifications
-----------------------------------
Model:           MacBook Pro
CPU:             Apple M4
RAM:             32 GB
Storage:         512 GB SSD
OS:              macOS Sequoia 15.6.1
Display:         14-inch

# Software versions installed
-----------------------------------
Node.js: v24.7.0
React Native: 20.0.0
Android Studio: 2025.1.3
VS Code: 1.103.2 (Universal)

# Setup steps
-----------------------------------
**Step 1: Install Node.js and npm** (5 mins)
Verify versions: Node.js should be v18.0.0 or higher, npm should be v8.0.0 or higher
node -v
npm -v

**Step 2: Check brew** (10 mins)
time brew update
time brew upgrade --greedy
time brew cleanup --prune=all

**Step 3: Install React Native CLI** (20 mins)
npm install -g react-native-cli
npm install -g @react-native-community/cli

**Step 4: Android Development Setup** (30 mins)
- Install:
Refer to https://formulae.brew.sh/cask/android-studio#default
brew install --cask android-studio

- Setup


**Step 5: iOS Development Setup (macOS Only)** (20 mins)
- Install Xcode and install CocoaPods

**Step 6: Install Code Editor** (3 mins)
- Download from https://code.visualstudio.com/