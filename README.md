# 🛠️ Milestone 3: Data Flow & System Behavior
> **QA Assistant System & Smart AI-Powered Bug Triage**  
> **Team:** Bug Busters1 | **Academic Year:** 2026–2027  
> **Author:** Abd Elrahman Esmat (QA Engineer)

---

## 📌 Table of Contents
1. [Overview](#1-overview)
2. [Data Flow Diagrams (DFD)](#2-data-flow-diagrams-dfd)
3. [Class Diagram](#3-class-diagram)
4. [Sequence Diagram](#4-sequence-diagram)
5. [Activity Diagram](#5-activity-diagram)
6. [State Diagram (Bug Lifecycle)](#6-state-diagram-bug-lifecycle)
7. [System Data Interface & Architecture (SDI)](#7-system-data-interface--architecture-sdi)

---

## 1. Overview
This document specifies the system flow, structural architecture, and behavioral dynamics for the **QA Assistant System & Smart AI-Powered Bug Triage**. It demonstrates how data flows between client components, the FastAPI backend, PostgreSQL storage, and the external AI Engine.

---

## 2. Data Flow Diagrams (DFD)

### 2.1 DFD Level 0 (Context Diagram)
The Context Diagram represents the overall system boundary and interactions with external entities.

![DFD Level 0](./AI%20Bug%20Triage%20Platform-2026-11-10-152817.jpg)

### 2.2 DFD Level 1 (Detailed Data Flow)
Detailed breakdown of internal processes, data stores, and message flows.

![DFD Level 1](./AI%20Bug%20Triage%20Platform-2026-11-10-152841.jpg)

---

## 3. Class Diagram
Object-oriented class structure detailing domain models and service interactions.

![Class Diagram](./AI%20Bug%20Triage%20Platform-2026-11-10-153025.jpg)

---

## 4. Sequence Diagram
Timeline of messages exchanged between the Frontend, FastAPI Backend, PostgreSQL DB, and External AI Service.

![Sequence Diagram](./AI%20Bug%20Triage%20Platform-2026-11-10-153025.jpg)

---

## 5. Activity Diagram
Workflow execution logic including input validation, duplicate threshold checking, and human verification steps.

![Activity Diagram](./AI%20Bug%20Triage%20Platform-2026-11-10-153202.jpg)

---

## 6. State Diagram (Bug Lifecycle)
Finite state transitions for defect management.

![State Diagram](./AI%20Bug%20Triage%20Platform-2026-11-10-153239.jpg)

---

## 7. System Data Interface & Architecture (SDI)
Three-tier architecture diagram showing boundary components and API interfaces.

![System Data Interface](./Untitled%20diagram-2026-11-10-153429.jpg)
