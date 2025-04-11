# WebSocket Communication Module

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This repository contains a Go implementation for WebSocket communications, supporting both **Push** and **Poll** messaging mechanisms. The project is a fork of the [MythicC2Profiles/websocket](https://github.com/MythicC2Profiles/websocket) repository and aims to provide a streamlined and efficient WebSocket communication framework.

## Features

- **WebSocket Push Messaging**: Real-time updates and event-driven architecture.
- **Polling Support**: Alternative messaging mechanism for cases where WebSocket is unavailable.
- **Lightweight and Fast**: Optimized for performance using Go.
- **Extensible**: Easily integrate with other applications or extend functionality.

## Getting Started

### Prerequisites

- Go 1.16+ installed on your system.
- Basic understanding of WebSocket and HTTP communication protocols.

### Installation

Clone the repository:

```bash
git clone https://github.com/nodoubtz/websocket.git
cd websocket
```

Build the project:

```bash
go build
```

Run the application:

```bash
go run main.go
```

### Usage

This module can be used as a standalone WebSocket communication server or integrated into larger systems. Below is an example of how to initialize and use this WebSocket module in your Go project:

```go
package main

import (
    "github.com/nodoubtz/websocket"
)

func main() {
    // Initialize WebSocket server
    server := websocket.NewServer()

    // Start server
    server.Start(":8080")
}
```

## Contributing

Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

1. Fork it (https://github.com/nodoubtz/websocket/fork)
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This repository is a fork of the [MythicC2Profiles/websocket](https://github.com/MythicC2Profiles/websocket) repository. Special thanks to the original authors for their foundational work.

## Contact

For any questions or concerns, please feel free to contact the repository owner at [nodoubtz](https://github.com/nodoubtz).

---
