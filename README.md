# Silabus Backend Development dengan JavaScript/TypeScript (Node.js, Deno, Bun)

## 1. Dasar-dasar JavaScript dan TypeScript
### JavaScript (ES6+)
- Modern syntax: `let`, `const`, arrow functions, template literals.
- Modules (`import/export`) dan destructuring.
- Asynchronous programming:
  - Promises.
  - Async/Await.

### TypeScript
- Deklarasi tipe dasar: `string`, `number`, `array`, `enum`.
- Interface dan type alias.
- Generics.
- Integrasi TypeScript di proyek Node.js.

---

## 2. Node.js Fundamentals
### Core Concepts
- Event loop dan non-blocking I/O.
- Modules (CommonJS vs ES Modules).
- File system, Streams, Buffer.

### NPM/Yarn
- Package management.
- Menggunakan dan membuat package.

### Error Handling
- Best practices untuk menangani error (`try-catch`, async errors).

### Testing
- Unit testing dengan Jest atau Mocha.

---

## 3. API Development
### Frameworks
- **Express.js**:
  - Middleware, routing, request/response lifecycle.
- **Fastify**:
  - Alternatif cepat dengan dukungan plugin.
- **NestJS**:
  - Framework berbasis TypeScript untuk aplikasi skala besar.

### RESTful APIs
- CRUD operations, middleware, autentikasi JWT.
- Query parameters dan validation dengan libraries seperti Joi atau Zod.

### GraphQL
- Membuat server GraphQL dengan Apollo Server.
- Resolvers dan schema definition.

---

## 4. Advanced Topics in Node.js
### Asynchronous Programming
- EventEmitter.
- Worker threads dan cluster module.

### Authentication
- OAuth2, JWT, dan session-based authentication.
- Implementasi otentikasi sosial (Google, GitHub).

### Real-time Applications
- WebSocket dengan Socket.IO.
- Server-sent events (SSE).

---

## 5. Deno dan Bun
### Deno
- Dasar Deno: Keunggulan tanpa npm dan keamanan bawaan.
- Membuat API menggunakan Oak (framework mirip Express untuk Deno).
- Typescript native dan permission handling.

### Bun
- Cara menginstal dan konfigurasi Bun.
- Penggunaan sebagai bundler dan runtime alternatif.
- Kelebihan Bun untuk aplikasi ringan.

---

## 6. Database Integration
### PostgreSQL
- Dasar SQL (query, joins, indexing).
- ORM dengan TypeORM atau Prisma.
- Transaction dan connection pooling.

### NoSQL
- MongoDB dengan Mongoose.
- Redis untuk caching dan session store.

---

## 7. Deployment & Performance Optimization
### Deployment
- Containerization dengan Docker.
- Deploy ke platform seperti AWS, Vercel, atau Heroku.
- Serverless functions dengan AWS Lambda atau Deno Deploy.

### Optimization
- Monitoring dan logging dengan PM2 dan Winston.
- Caching dengan Redis.
- Load testing dengan Artillery atau k6.

---

## 8. System Design & Architecture
### Software Design Patterns
- MVC, Repository Pattern.
- Dependency Injection (NestJS).

### Microservices
- Membagi aplikasi menjadi layanan kecil.
- Komunikasi antar layanan dengan gRPC atau RabbitMQ.

### Scalability
- Horizontal scaling dengan Nginx.
- Load balancing dan clustering.

---

## 9. Proyek dan Latihan
### Proyek 1: REST API Sederhana
- Membuat CRUD sederhana (todo list) dengan autentikasi JWT.

### Proyek 2: GraphQL API
- Manajemen data pengguna dengan resolvers dan schema.

### Proyek 3: Real-time Chat App
- Membuat aplikasi chat menggunakan Socket.IO.

### Proyek 4: Aplikasi dengan Deno
- API menggunakan Oak dan TypeScript native.

### Proyek 5: Optimalisasi Performasi
- Aplikasi berbasis Bun untuk runtime dan bundling cepat.

---

Silabus ini dirancang untuk mendalam dan menyeluruh, serta fleksibel untuk memasukkan teknologi seperti Deno dan Bun. Mulailah dari dasar, lalu bangun proyek nyata untuk memperkuat pemahaman.
