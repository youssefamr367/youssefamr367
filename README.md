# Youssef Amr

Full-stack developer working mostly on the backend — distributed services in Java and TypeScript, and the React frontends that sit on top of them.

**Open to junior and entry-level full-stack roles.**

## What I build

I like systems where correctness under failure matters: services that can be retried without double-charging anyone, events that cannot be published for a transaction that rolled back, and permission checks that hold up when a request takes an unexpected path.

A few things I have built and the problems they made me solve:

| Project | What it is | What it taught me |
| --- | --- | --- |
| **Foody** | Multi-tenant food ordering and delivery backend — two TypeScript services over Postgres, Redis and RabbitMQ | Transactional outbox, idempotent payment webhooks, RBAC across restaurants and branches, region sharding with separate live and archive databases |
| **[Flight Booking Microservices](https://github.com/youssefamr367/flight-booking-microservices)** | Spring Cloud platform: Eureka discovery, API gateway, and user, flight, booking and notification services | Service discovery and routing, event-driven notifications over RabbitMQ, command handlers, deploying the whole thing with Docker Compose and Kubernetes |
| **[AURORA](https://github.com/youssefamr367/AURORA)** | Order tracking for a furniture workshop — products, suppliers, material lookups, per-status due dates with SLA colour coding | Modelling a real business process in SQL, one codebase serving both a long-lived Express server and Vercel serverless functions |
| **[El7a2ni](https://github.com/youssefamr367/Team-Caffeine-Clinic)** | MERN virtual clinic and pharmacy for patients, doctors, pharmacists and admins | Working in a team on a large feature set: appointments, prescriptions, Stripe payments, Socket.IO chat |
| **[notes-app](https://github.com/youssefamr367/notes-app)** | Minimal note-taking app with rich-text editing and public sharing | Next.js 16 App Router, better-auth, per-user data scoping and a strict Content-Security-Policy |
| **[springboot-shop](https://github.com/youssefamr367/springboot-shop)** | Cart and order REST API with file-backed persistence | Clean layering — controller, service, repository — and generics to keep the persistence layer from repeating itself |

## Tech

**Backend** · Java 23, Spring Boot, Spring Cloud · Node.js, TypeScript, Express · REST APIs

**Frontend** · React 19, Next.js, Tailwind CSS, Vite

**Data** · PostgreSQL, MongoDB, Redis, Knex, Drizzle, Mongoose

**Infrastructure** · Docker, Docker Compose, Kubernetes, RabbitMQ, Vercel

**Practice** · Event-driven architecture, RBAC, idempotency, transactional outbox, dependency injection, OOP and design patterns

## Contact

- **Email** — [youssefamr367@gmail.com](mailto:youssefamr367@gmail.com)
- **LinkedIn** — [youssef-amr-283911226](https://www.linkedin.com/in/youssef-amr-283911226/)
