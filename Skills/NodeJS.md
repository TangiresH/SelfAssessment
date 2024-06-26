## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js 🖐️ used
  - Stateful and stateless servers
  - Nonblocking I/O and blocking code
  - Event loop phases 👂 heard
  - Event loop microtasks and macrotasks 
  - Garbage collection
  - Node.js LTS schedule 👂 heard
  - I/O-bound, CPU-bound, memory-bound tasks
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  - CommonJS modules 🖐️ used
  - ECMAScript modules 🖐️ used
  - Module `node:module` 🖐️ used
  - Caching in CJS and ESM
  - Modules as singletons
  - Contexts and scripts module `node:vm`
  - Dependencies: `npm`, `node_modules` 🖐️ used
  - Files `package.json`, `package-lock.json` 🖐️ used
  - Module-based permissions model 👂 heard
  - Isolation with modularity
  - Dependency injection 👂 heard
  - DI containers 
  - Coupling and cohesion 🖐️ used
  - Framework agnostic approach
- Environment
  - Command line arguments 👂 heard
  - Node.js CLI
  - Process-based permissions
  - Graceful shutdown
  - Clustering 👂 heard
  - Watch filesystem changes with --watch
- Internal API
  - Streams API 👂 heard
  - Web Streams API 👂 heard
  - Crypto API 👂 heard
  - Password hashing with crypto.scrypt
  - Web Crypto API
  - File system API (sync and async)
  - Copy folder recursively
  - Worker threads
  - Performance hooks
  - Native fetch and nodejs/undici
  - async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - SharedArrayBuffer
  - Module `node:worker_threads`
  - Module `node:child_process`
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - Module `node:url` vs `new URL` 👂 heard
  - Module `node:assert` 👂 heard
  - Internationalization
  - Blob, File, Buffer, module `node:buffer`
  - Module `node:zlib`
- Network
  - Endpoint throttling
  - ALPN
  - SNI callback
  - SSL certificates
  - Protocol agnostic approach
  - Fetch API
  - IncomingMessage
  - HTTP(S) 👂 heard
  - TCP/SSL 👂 heard
  - UDP 👂 heard
  - TLS 👂 heard
  - Websocket 👂 heard
  - SSE
  - HTTP/3 (QUIC)
  - Long polling
  - REST
  - RPC
  - Routing 👂 heard
  - DoS 👂 heard
  - DDoS 👂 heard
  - XSS
  - Path traversal
  - CSRF
  - DNS 👂 heard
  - SQL injection
  - noDelay
  - keep-alive
  - IP sticky sessions
- Technique and tools
  - Native test runner
  - Logging 👂 heard
  - Application configuring 👂 heard
  - Testing 👂 heard
  - CI/CD 🖐️ used
  - Readable 🖐️ used
  - Writable 🖐️ used
  - Transform 🖐️ used
  - Back pressure 
  - Buffer👂 heard
  - Console 👂 heard
  - Inspector
- Data access
  - Data access layer
  - Repository 👂 heard
  - Active record
  - Query builder
  - Object-Relational Mapping
  - CRUD 👂 heard
  - DTO
- Error handling and debugging
  - `Error` 👂 heard
  - `error.cause`
  - `error.code`
  - `error.message` 👂 heard
  - `error.stack`
  - `Error.captureStackTrace`
  - How to avoid mixins
  - Uncaught exceptions
  - Heap dump
  - Debugging tools
  - Flame graph
  - Memory leaks
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons
  - `C` and `C++` addons
  - `Rust` addons
  - `Zig` addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI `C` and `C++`
  - NAPI `Rust`
  - NAPI `Zig`
  - Webassembly `WAT`
  - Webassembly `C` and `C++`
  - Webassembly `Rust`
  - Webassembly `Zig`
  - Webassembly `AssemblyScript`
  - Shared memory
  - V8 binary serialization
