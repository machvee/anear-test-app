Anear Test App
Testing Goals
  1. Integration test for anear-jsapi, ably.io and anear API
  2. Tests XState machine techniques (invent some simple game that multiple participants can play)
  3. Command line client interaction to send participant messages
  4. Use mock anear API from JSON files
  5. Scripted client interactions from standard-input
    - login session
    - get global zones apps
    - choose test app
    - create test app event
    - other clients join from mock QR scan
    - clients get text published on participants and private channels
    - clients publish to actions channel
    - client will timeout
  6. Tests participant behavior like active/idle for open house, and timeout for head-to-head play
  7. Event state changes e.g. Cancel, Broadcast
  8. Reloading events that were interrupted
  9. JSON only publishing.  No HTML/pug required
 10. log files capture all interactions and responses
