# Hello World in Swift

A minimal "Hello, World!" implementation in Swift. Swift is a modern programming language that was originally developed by Apple for iOS and macOS development, and is now open source.

## Installation

### macOS
Swift comes pre-installed on macOS.

### Linux
Ubuntu/Debian:
```bash
# Add Swift repository and install
wget -q https://download.swift.org/swift-stable/ubuntu/SwiftKey.gpg
sudo gpg --dearmor SwiftKey.gpg -o /usr/share/keyrings/SwiftKey.gpg
echo "deb [signed-by=/usr/share/keyrings/SwiftKey.gpg] https://download.swift.org/swift-stable/ubuntu swift-stable main" | sudo tee /etc/apt/sources.list.d/swift.list
sudo apt-get update
sudo apt-get install swift
```

For other platforms, download from [Swift.org](https://swift.org/download/).

## Building and Running

Run directly:
```bash
swift main.swift
```

Or compile and run:
```bash
swiftc main.swift -o hello
./hello
```

## Code Explanation

The program consists of a single line that prints "Hello, World!" to standard output. Swift programs don't require an explicit main function - the code is executed from top to bottom.
