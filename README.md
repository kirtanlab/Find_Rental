# 🏡 Full-Stack Airbnb Clone – Cross-Platform GraphQL Application

This project is a **production-grade, full-stack clone of Airbnb**, designed to demonstrate deep understanding of modern web and mobile application development, scalable backend architecture, and real-time systems. The application supports both **web** and **mobile** clients with a shared codebase for business logic, validation, and API integration.

---

## 🎯 What Problem It Solves

Building scalable applications often leads to duplicated business logic across platforms, inconsistent validations, and siloed architecture. This project addresses those common challenges by:

- **Centralizing business logic** across web and mobile apps
- Using **GraphQL** for efficient data exchange
- Offering **real-time messaging** with WebSockets
- Enabling robust **authentication flows**
- Creating a responsive and modern **user experience** for web and mobile

---

## 🛠️ How It’s Built (Architecture)

The project is organized as a **monorepo** with the following packages:

### 📦 Project Structure

- `@abb/server` – GraphQL API server using PostgreSQL, Redis, TypeORM
- `@abb/controller` – Shared logic (resolvers, mutations, validation)
- `@abb/common` – Shared TypeScript utilities and validation schemas
- `@abb/app` – React Native mobile client
- `@abb/web` – React web client with Google Maps & WebSockets

---

### 🌐 Web Client Highlights (`@abb/web`)

A modern React application built with:

- **React + TypeScript**
- **Apollo Client** (GraphQL)
- **Ant Design** (UI)
- **Formik** (forms)
- **React Router**
- **Google Maps API**
- **WebSockets** (real-time messaging)

#### ✨ Key Features

- **Authentication Flow**
  - Registration with email confirmation
  - Secure login/logout
  - Password recovery
  - Protected routes with route guards

- **Listing Management**
  - Step-based listing creation
  - Google Maps integration for location
  - Amenities tagging
  - Image uploads via Dropzone

- **Real-Time Messaging**
  - WebSocket-based chat between users
  - Live message subscriptions
  - Listing-specific communication

- **User Experience**
  - Fully responsive design
  - Form validation
  - Redirection and feedback UX

#### 🧱 Component Architecture

- `Connectors` – Routing and container logic
- `Controllers` – Business logic and state management
- `Views` – Pure presentational components
- `Shared` – UI building blocks like InputField, DropzoneField, etc.

---

## ⚙️ Backend & Infrastructure

- **PostgreSQL** – Relational data storage
- **Redis** – Session management and caching
- **TypeORM** – ORM for consistent DB schema
- **GraphQL** – API interface with resolvers
- **WebSockets** – Real-time communication
- **Environment-Based Config** – Dev & Prod support

---

## 🔍 Evaluation

| Feature Area       | Highlights                                                                 |
|--------------------|---------------------------------------------------------------------------|
| **Code Reuse**      | Shared controllers and schemas across web and mobile                     |
| **Architecture**    | Monorepo with clear separation of concerns                               |
| **Type Safety**     | End-to-end TypeScript with strong validation                             |
| **UX Design**       | Responsive UI with route protection and form validation                  |
| **Real-Time Support**| Live messaging with GraphQL subscriptions and WebSockets                |
| **Scalability**     | Production-ready structure using PostgreSQL, Redis, and GraphQL          |

---

## 📄 Conclusion

This project showcases a complete, scalable Airbnb-like platform with a clean architectural vision and modern best practices in full-stack development. It demonstrates proficiency in:

- Multi-platform application development
- Real-time systems
- Type-safe GraphQL APIs
- Clean, maintainable architecture with shared logic

Ideal for recruiters or teams looking for candidates experienced in full-stack development, cross-platform architecture, GraphQL, and DevOps-readiness.

---

## 📜 License

This project is licensed under the MIT License.