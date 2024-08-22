# Test Websocket Server For Codefest2024
This repository contains a simple WebSocket test server, designed as a demo for Codefest 2024.

The server has been deployed to [Render](https://render.com/), and you can connect to it using the following WebSocket URL:
```
ws://test-websocket-server-for-codefest2024.onrender.com
```

## Connecting via Flutter
To connect to this WebSocket server using Flutter, you can use the following code snippet: 
```dart
  final _channel = IOWebSocketChannel.connect(
    Uri.parse('ws://test-websocket-server-for-codefest2024.onrender.com'),
  ); // connect to a Websocket server
```
