📡 About MCP (Multi-Cursor Protocol)

The Multi-Cursor Protocol (MCP) is a lightweight and standardized protocol developed by Figma for managing real-time cursor presence across multiple users in collaborative applications.

MCP defines how clients connect, broadcast their cursor position, and disconnect in a shared space—making it easy to implement live cursors with metadata like color, name, or pointer style.

🔧 Key Concepts
• Session ID: Uniquely identifies each connected client
• Cursor Position: { x, y } coordinates of the user’s pointer
• Metadata: Optional information like username, color, or avatar
• Rooms: Logical groups to scope user visibility (optional)

MCP is simple, extensible, and designed for performance in real-time environments like collaborative editors, whiteboards, or design tools.

⚙️ Installation

- bun install

Installs all dependencies using Bun, a fast modern JavaScript runtime.

🚀 Running the Server

- bun socket

Starts the WebSocket server for real-time multi-user cursor sharing.
Make sure the server is accessible to clients via ws:// or wss:// depending on your environment.
