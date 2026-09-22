# 🚀 PrepForge

### Forge Your Skills. Ace Your Interviews.

> An AI-powered Android application designed to make interview preparation
> structured, personalized, measurable, and adaptive.

 ## 📖 Overview

PrepForge is an Android application focused on helping students and developers
prepare for technical interviews through structured learning paths,
personalized roadmaps, AI-powered interview practice, and progress tracking.

The application combines a curated technical curriculum with AI-based
personalization to create a preparation experience that adapts to the user's
career goal, experience level, existing skills, preparation timeline, and
available study time.

> 🚧 PrepForge is currently under active development. Features and architecture
> described in this README represent the current implementation and planned
> product direction.

## 🎯 Problem Statement

Interview preparation is often fragmented across multiple platforms.

Students commonly have to:

- Find what topics they should study
- Decide the order in which to learn them
- Track their progress manually
- Find interview questions separately
- Evaluate their own answers
- Identify weak areas
- Decide what to revise next

This makes preparation difficult to structure and measure.

PrepForge aims to bring these activities into a single personalized
preparation workflow.

## 💡 Proposed Solution

PrepForge combines structured learning content with AI-powered personalization.

The user provides:

- Career goal
- Experience level
- Existing skills
- Preparation duration
- Daily study availability

PrepForge uses this information to create a personalized preparation journey
consisting of:

**Learn → Practice → Evaluate → Track → Improve**

The long-term goal is to make the preparation roadmap adaptive rather than
static.

## ✨ Core Features

### 🔐 Authentication
- Firebase Authentication
- Email/password registration
- Login
- Forgot password
- User profile creation

### 🧑‍💻 Personalized Onboarding
Users provide:
- Career goal
- Experience level
- Existing skills
- Preparation duration
- Daily study time

### 🗺️ Personalized Learning Roadmap
- Career-specific learning paths
- Structured phases
- Topics and subtopics
- Topic prerequisites
- Difficulty levels
- Progress tracking
- Personalized learning priorities

### 🤖 AI Interview Practice
- AI-generated interview questions
- Topic-based practice
- Difficulty-based questions
- User answer submission
- AI-generated feedback

### 📊 Progress Tracking
- Overall preparation progress
- Topic completion
- Practice history
- Performance tracking
- Skill-gap identification

### 📚 Practice History
- Previous questions
- Submitted answers
- AI feedback
- Practice timestamps
- Topic and difficulty information

## 🚧 Development Status

PrepForge is currently under active development.

### ✅ Completed

- [x] Android project setup
- [x] Kotlin configuration
- [x] View Binding
- [x] Material Design foundation
- [x] MVVM project structure
- [x] Repository layer foundation
- [x] Firebase project configuration
- [x] Firebase Authentication
- [x] Registration
- [x] Login
- [x] Forgot Password
- [x] Firestore user profile creation
- [x] Authentication-based navigation

### 🔄 In Progress

- [ ] Personalized onboarding
- [ ] Dashboard
- [ ] Roadmap data model
- [ ] Curated curriculum
- [ ] Roadmap UI

### 📋 Planned

- [ ] AI-powered roadmap personalization
- [ ] AI interview practice
- [ ] AI answer evaluation
- [ ] Skill-gap analysis
- [ ] Practice history
- [ ] Progress analytics
- [ ] Security hardening
- [ ] Testing
- [ ] Release build

## 🔄 How PrepForge Works

```text
User
  │
  ▼
Authentication
  │
  ▼
Personalized Onboarding
  │
  ├── Career Goal
  ├── Experience Level
  ├── Existing Skills
  ├── Preparation Duration
  └── Daily Availability
  │
  ▼
Curated Curriculum
  │
  ▼
AI Personalization
  │
  ▼
Personalized Roadmap
  │
  ▼
Learn Topics
  │
  ▼
AI Interview Practice
  │
  ▼
AI Answer Evaluation
  │
  ▼
Progress & Skill Analysis
  │
  ▼
Adaptive Preparation


## 🤖 AI Architecture

PrepForge follows a hybrid AI approach.

Instead of allowing AI to freely generate an entire learning curriculum,
the application uses a structured curriculum as the foundation.

### Curated Curriculum

Defines:

- Career paths
- Learning phases
- Topics
- Prerequisites
- Difficulty
- Topic ordering

### AI Personalization

AI is responsible for:

- Personalizing learning priorities
- Generating interview questions
- Evaluating user answers
- Identifying improvement areas
- Suggesting practice areas

```text
                 ┌─────────────────────┐
                 │   User Profile      │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Curated Curriculum  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ AI Personalization  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Personalized        │
                 │ Roadmap             │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Learn & Practice    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ AI Evaluation       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Progress /          │
                 │ Skill Analysis      │
                 └─────────────────────┘

```

---

## 🤖 AI Architecture

PrepForge follows a hybrid AI approach.

Instead of allowing AI to freely generate an entire learning curriculum,
the application uses a structured curriculum as the foundation.

### Curated Curriculum

Defines:

- Career paths
- Learning phases
- Topics
- Prerequisites
- Difficulty
- Topic ordering

### AI Personalization

AI is responsible for:

- Personalizing learning priorities
- Generating interview questions
- Evaluating user answers
- Identifying improvement areas
- Suggesting practice areas

```text
                 ┌─────────────────────┐
                 │   User Profile      │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Curated Curriculum  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ AI Personalization  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Personalized        │
                 │ Roadmap             │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Learn & Practice    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ AI Evaluation       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Progress /          │
                 │ Skill Analysis      │
                 └─────────────────────┘
---
```

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Kotlin | Android development |
| XML | UI development |
| View Binding | Type-safe view access |
| MVVM | Application architecture |
| Repository Pattern | Data abstraction |
| Coroutines | Asynchronous operations |
| StateFlow / LiveData | UI state management |
| Firebase Authentication | User authentication |
| Cloud Firestore | Cloud database |
| Firebase Cloud Functions | Secure backend/AI layer |
| Gemini | Generative AI |
| Git & GitHub | Version control |

## 🏗️ Architecture

PrepForge follows **MVVM + Repository Pattern**.

```text
UI
 │
 ▼
ViewModel
 │
 ▼
Repository
 │
 ├──────────────► Firebase
 │
 └──────────────► AI Service
```

## 🚧 Development Status

PrepForge is currently under active development.

### ✅ Completed

- [x] Android project setup
- [x] Kotlin configuration
- [x] View Binding
- [x] Material Design foundation
- [x] MVVM project structure
- [x] Repository layer foundation
- [x] Firebase project configuration
- [x] Firebase Authentication
- [x] Registration
- [x] Login
- [x] Forgot Password
- [x] Firestore user profile creation
- [x] Authentication-based navigation

### 🔄 In Progress

- [ ] Personalized onboarding
- [ ] Dashboard
- [ ] Roadmap data model
- [ ] Curated curriculum
- [ ] Roadmap UI

### 📋 Planned

- [ ] AI-powered roadmap personalization
- [ ] AI interview practice
- [ ] AI answer evaluation
- [ ] Skill-gap analysis
- [ ] Practice history
- [ ] Progress analytics
- [ ] Security hardening
- [ ] Testing
- [ ] Release build

## 👨‍💻 Developer

**Yash Gupta**

Android Developer | Java Backend Developer

- GitHub: [@yashgpt20](https://github.com/yashgpt20)
- LinkedIn: [Yash Gupta](https://linkedin.com/in/yashgpt)

### Development Profile

**Technex**

PrepForge is being developed as part of my Android and AI engineering
portfolio, with a focus on building production-oriented applications using
modern Android architecture and cloud technologies.
