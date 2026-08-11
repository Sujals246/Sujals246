# Hi, I'm Sujal 👋

### Java Backend Developer | Spring Boot | REST APIs | AI Integration

I'm a Computer Science Engineering graduate focused on **Java backend development** with Spring Boot.

I build backend applications around **REST APIs, authentication & authorization, database persistence, payment integrations, and AI-powered services**.

My recent work includes an **Airbnb-Like Booking System** with JWT authentication, Spring Security, MySQL, JPA/Hibernate and Razorpay, along with an **AI-Powered Knowledge Assistant** built with Spring AI, RAG, embeddings, vector search and AI tool calling.

Currently focused on becoming a stronger backend engineer by building practical systems and going deeper into backend architecture, security, databases, and AI integration.

---

## 👨‍💻 About Me

* 🎓 Computer Science Engineering graduate
* ☕ Focused on **Java & Spring Boot**
* 🌐 Building **RESTful backend APIs**
* 🔐 Implementing **Spring Security & JWT authentication**
* 🗄️ Working with **MySQL, SQL, JPA & Hibernate**
* 💳 Integrated **Razorpay payment processing**
* 🤖 Building with **Spring AI & Generative AI APIs**
* 🔎 Exploring **RAG, embeddings & vector similarity search**
* 🛠️ Working with **AI tool calling & backend integrations**
* 🐳 Exploring **Docker, AWS & cloud deployment**
* 🧠 Practicing **DSA & problem solving**
* 💼 Interested in **Java Backend / Software Engineering roles**

---

## ⚡ Technical Stack

### Backend

`Java` · `Spring Boot` · `Spring MVC` · `REST APIs`

### Security

`Spring Security` · `JWT` · `Authentication` · `Authorization`

### Database & Persistence

`MySQL` · `SQL` · `JPA` · `Hibernate`

### AI Engineering

`Spring AI` · `LLM Integration` · `RAG` · `Embeddings` · `Vector Search` · `AI Tool Calling`

### Integrations

`Razorpay API` · `OpenAI APIs` · `Third-Party REST APIs`

### Development

`Git` · `GitHub` · `Postman` · `IntelliJ IDEA` · `Maven`

### Currently Exploring

`Docker` · `AWS` · `CI/CD`

---

## 🛠️ Technologies

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,spring,mysql,git,github,postman,idea,vscode,maven,docker,aws" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Razorpay-3395FF?style=flat-square&logo=razorpay&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
</p>

---

# 🚀 Featured Projects

## 🏠 Airbnb-Like Booking System

A backend-focused property booking platform inspired by Airbnb, built with **Java and Spring Boot**.

The application implements real-world backend workflows including authentication, authorization, property management, booking, database persistence and online payments.

### Key Features

* 🔐 JWT-based authentication & authorization
* 👤 User registration and login
* 🏠 Property listing and management
* 🔎 Property search and filtering
* 📅 Booking and reservation management
* 💳 **Razorpay payment integration**
* 🗄️ MySQL persistence using JPA/Hibernate
* 🛡️ Protected REST API endpoints
* ✅ Request validation
* ⚠️ Global exception handling

### Architecture

```text
Client
  │
  ▼
REST Controllers
  │
  ▼
Service Layer
  │
  ├── Business Logic
  └── Validation
  │
  ▼
Repository Layer
  │
  ▼
JPA / Hibernate
  │
  ▼
MySQL
```

### Payment Flow

```text
Booking Request
      │
      ▼
Booking Validation
      │
      ▼
Razorpay Integration
      │
      ▼
Payment Processing
      │
      ▼
Payment Confirmation
      │
      ▼
Booking Completion
```

**Stack:**
`Java` · `Spring Boot` · `Spring Security` · `JWT` · `JPA` · `Hibernate` · `MySQL` · `Razorpay API` · `REST APIs`

[View Repository →](https://github.com/YOUR_GITHUB_USERNAME/YOUR_BOOKING_REPOSITORY)

---

## 🤖 AI-Powered Knowledge Assistant

An AI-powered backend application built with **Java, Spring Boot and Spring AI**, combining LLM interaction with **Retrieval-Augmented Generation (RAG)** and AI tool calling.

The application demonstrates how AI capabilities can be integrated into a conventional Spring Boot backend.

### AI Capabilities

* 🧠 **LLM Integration** using OpenAI through Spring AI
* 🔎 **Retrieval-Augmented Generation (RAG)**
* 🧬 **Text embeddings** using OpenAI embedding models
* 📐 **Vector similarity search** using `VectorStore`
* 📚 Domain-specific knowledge retrieval
* 🛠️ **AI Tool Calling** using Spring AI `@Tool`
* 📦 **Structured AI output** mapped into Java objects
* 📝 Context-aware prompt construction

### RAG Pipeline

```text
User Question
      │
      ▼
Query Embedding
      │
      ▼
Vector Similarity Search
      │
      ▼
Relevant Context
      │
      ▼
Context-Aware Prompt
      │
      ▼
OpenAI LLM
      │
      ▼
Generated Answer
```

### AI Tool Calling

```text
                 User
                   │
                   ▼
              ChatClient
                   │
                   ▼
                  LLM
                   │
          ┌────────┴────────┐
          │                 │
    Normal Response     Tool Required
                            │
                            ▼
                     Java @Tool Method
                            │
                            ▼
                       Tool Result
                            │
                            ▼
                           LLM
                            │
                            ▼
                      Final Response
```

### Implemented Tools

* 🌦️ Weather information tool
* 🍽️ Food/menu interaction tool

### Backend Structure

```text
src/main/java
│
└── com.logic
    │
    ├── config
    │   └── AIConfig
    │
    ├── controller
    │   └── ChatController
    │
    ├── service
    │   ├── AIService
    │   └── RAGService
    │
    ├── dto
    │   └── Joke
    │
    └── tool
        ├── WeatherService
        └── FoodService
```

**Stack:**
`Java 17` · `Spring Boot` · `Spring AI` · `OpenAI` · `RAG` · `Embeddings` · `VectorStore` · `Tool Calling` · `REST APIs` · `Maven`

[View Repository →](https://github.com/YOUR_GITHUB_USERNAME/YOUR_AI_REPOSITORY)

---

# 🧠 Backend + AI

My main technical interest is at the intersection of **backend engineering and practical AI integration**.

```text
                    Backend Engineering
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
      Spring Boot       Databases        Security
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                     REST APIs
                           │
                           ▼
                    AI Integration
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
         LLM              RAG          Tool Calling
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                    AI Applications
```

The goal is to build systems where AI is integrated as a practical backend capability rather than simply wrapping an LLM in a chat interface.

---

# 📚 Currently Learning

### Backend

`Spring Boot` · `Spring Security` · `JPA/Hibernate` · `REST API Design`

### Data & Architecture

`SQL` · `Database Design` · `API Design` · `Testing` · `System Design`

### AI

`RAG` · `Vector Databases` · `AI Application Architecture` · `LLM Integration`

### Infrastructure

`Docker` · `AWS` · `CI/CD`

### Problem Solving

`Data Structures & Algorithms` · `Problem Solving`

---

# 📊 GitHub Activity

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&theme=transparent&rank_icon=github"
  />

<img
 height="170"
 src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&hide_border=true&theme=transparent"
/>

</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&theme=transparent&hide_border=true"
  />
</p>

---

# 🎯 Career Focus

I'm looking for opportunities where I can contribute to **real-world backend systems**, learn production engineering practices, and grow as a software engineer.

### Interested In

`Java Backend` · `Spring Boot` · `REST APIs` · `SQL` · `Backend Architecture` · `AI Integration`

---

# 📫 Let's Connect

<p align="left">

<a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:YOUR_EMAIL@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
</a>

<a href="https://leetcode.com/YOUR_LEETCODE_USERNAME/">
<img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=flat-square&logo=leetcode&logoColor=111111"/>
</a>

<a href="https://github.com/YOUR_GITHUB_USERNAME">
<img src="https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</p>

---

<p align="center">
  <sub>Java · Spring Boot · Backend Engineering · AI Integration</sub>
</p>





