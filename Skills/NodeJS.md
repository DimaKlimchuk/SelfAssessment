## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js
  - Stateful and stateless servers
  - Nonblocking I/O and slocking code: 👂 heard
  - Event loop: phases: 🎓 known
  - Event loop: microtasks and macrotasks: 🎓 known
  - Garbage collection
  - Node.js LTS schedule
  - I/O-bound, CPU-bound, memory-bound tasks
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  - CommonJS modules: 🎓 known
  - ECMAScript modules: 🎓 known
  - node:module: 🖐️ used
  - Caching in CJS and ESM: 👂 heard
  - Modules as singletons: 🖐️ used
  - Contexts and scripts node:vm: 🖐️ used
  - Dependencies: npm, node_modules: 🖐️ used
  - Dependencies: package.json and package lock: 🖐️ used
  - Module-based permissions model: 👂 heard
  - Isolation with modularity
  - Dependency injection
  - DI containers
  - Coupling and cohesion
  - Framework agnostic approach
- Environment
  - Command line arguments
  - Node.js CLI
  - Process-based permissions
  - Graceful shutdown
  - Clustering
  - Watch filesystem changes with --watch
- Internal API
  - Streams API: 🎓 known
  - Web Streams API
  - Crypto API
  - Password hashing with node:crypto.scrypt
  - Web Crypto API
  - File system API: sync and async
  - Copy folder recursively
  - Worker threads
  - Performance hooks
  - Native fetch and nodejs/undici
  - node:async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - Stream back pressure
  - SharedArrayBuffer
  - node:worker_threads
  - node:child_process
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - node:url vs new URL
  - node:assert
  - Internationalization
  - Blob, File, Buffer, node:buffer
  - Module node:zlib
- Application structure and architecture
  - Isolation between layer
  - Multilayer approach
  - Separation of concerns
  - Inversion of control
  - Dependency injection
  - GRASP
  - SOLID
  - GoF patterns
  - Distributed systems
  - Highload applications
  - Clean architecture
  - DDD
  - Message Queue
  - CQS
  - CQRS
  - Event sourcing
  - Load balancing
  - Serverless clouds
  - FaaS clouds
  - Fat controller
  - GoF for Node.js
  - Leaking abstractions
- Network
  - IP sticky sessions: 🎓 known
  - Endpoint throttling: 🎓 known
  - HTTP(S): 🎓 known
  - TCP/SSL: 🎓 known
  - UDP
  - TLS
  - Websocket: 👂 heard
  - SSE
  - HTTP/3 (QUIC)
  - Long polling
  - REST: 👂 heard
  - RPC
  - Routing: 🎓 known
  - DoS
  - DDoS: 🎓 known
  - XSS
  - Path traversal
  - CSRF
  - DNS
  - Fetch API: 🖐️ used
  - IncomingMessage
  - SQL injection: 🎓 known
  - noDelay
  - keep-alive
  - ALPN
  - SNI callback
  - SSL certificates
  - Protocol agnostic approach
- Technique and tools
  - Native test runner
  - Logging: 🖐️ used
  - Application configuring: 🎓 known
  - Testing: 🖐️ used
  - CI/CD
  - Readable
  - Writable
  - Transform
  - back pressure
  - Buffer
  - Console: 🖐️ used
  - Inspector
  - Reliability
  - Quality
  - Availability
  - Flexibility
- Data access
  - Data access layer
  - Repository
  - Active record
  - Query builder
  - Object-Relational Mapping
- Error handling and debugging
  - Error
  - error.cause
  - error.code
  - error.message
  - error.stack
  - How to avoid mixins
  - Error.captureStackTrace
  - Uncaught exceptions
  - Heap dump
  - Debugging tools
  - Flame graph
  - Memory leaks
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons
  - C and C++ addons
  - Rust addons
  - Zig addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI C and C++
  - NAPI Rust
  - NAPI Zig
  - Webassembly WAT
  - Webassembly C and C++
  - Webassembly Rust
  - Webassembly Zig
  - Webassembly AssemblyScript
  - Shared memory
  - SharedArrayBuffer
  - V8 binary serialization
