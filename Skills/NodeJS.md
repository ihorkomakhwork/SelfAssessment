## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js k
  - Stateful and stateless servers k
  - Nonblocking I/O and blocking code u
  - Event loop phases c
  - Event loop microtasks and macrotasks  
  - Garbage collection k
  - Node.js LTS schedule k
  - I/O-bound, CPU-bound, memory-bound tasks k
  - Interactive applications (close to real-time) h
- Modularity, layers and dependencies
  - CommonJS modules u
  - ECMAScript modules u
  - Module `node:module` h
  - Caching in CJS and ESM k 
  - Modules as singletons h
  - Contexts and scripts module `node:vm` u
  - Dependencies: `npm`, `node_modules` u
  - Files `package.json`, `package-lock.json` u
  - Module-based permissions model h
  - Isolation with modularity 
  - Dependency injection u
  - DI containers u
  - Coupling and cohesion k
  - Framework agnostic approach u
- Environment
  - Command line arguments u
  - Node.js CLI u
  - Process-based permissions 
  - Graceful shutdown k
  - Clustering h
  - Watch filesystem changes with --watch u
- Internal API
  - Streams API k
  - Web Streams API 
  - Crypto API u
  - Password hashing with crypto.scrypt u
  - Web Crypto API
  - File system API (sync and async) u
  - Copy folder recursively h
  - Worker threads k
  - Performance hooks 
  - Native fetch and nodejs/undici u
  - async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - SharedArrayBuffer k
  - Module `node:worker_threads` u
  - Module `node:child_process`
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - Module `node:url` vs `new URL`
  - Module `node:assert`
  - Internationalization 
  - Blob, File, Buffer, module `node:buffer` u
  - Module `node:zlib` h
- Network
  - Endpoint throttling
  - ALPN
  - SNI callback
  - SSL certificates h
  - Protocol agnostic approach u
  - Fetch API u
  - IncomingMessage h
  - HTTP(S) k
  - TCP/SSL h
  - UDP
  - TLS
  - Websocket u
  - SSE 
  - HTTP/3 (QUIC) h
  - Long polling h
  - REST u
  - RPC u
  - Routing c
  - DoS
  - DDoS u
  - XSS h
  - Path traversal
  - CSRF
  - DNS
  - SQL injection h
  - noDelay 
  - keep-alive
  - IP sticky sessions
- Technique and tools
  - Native test runner u
  - Logging u
  - Application configuring u
  - Testing u
  - CI/CD u
  - Readable k
  - Writable k
  - Transform k
  - Back pressure
  - Buffer u
  - Console u
  - Inspector u
- Data access
  - Data access layer u
  - Repository u
  - Active record
  - Query builder u
  - Object-Relational Mapping u
  - CRUD u
  - DTO u
- Error handling and debugging
  - `Error` u
  - `error.cause` u
  - `error.code` u
  - `error.message` u
  - `error.stack` u
  - `Error.captureStackTrace` h
  - How to avoid mixins u
  - Uncaught exceptions u
  - Heap dump 
  - Debugging tools u
  - Flame graph 
  - Memory leaks k
  - Resource leaks k
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
