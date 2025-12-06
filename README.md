# Seongwon Woo - Typescript Fullstack Developer

<br>

## 🙋 About Me

I’m a full-stack developer specializing in digital healthcare.
With dual majors in optometry/opticianry and computer engineering, I bring interdisciplinary expertise across both fields.

I work end-to-end—from planning and UX/design to development, deployment, and operations—taking ownership of the entire journey from problem definition to solution design to productization. 

<br>

## 🌟 Projects

### 🧿 Preznel ALY | Optical Shop CRM & AI Myopia Prediction Platform (Solo End-to-End Development)

A platform that digitizes optical shop operations, replacing manual workflows with  
a fully integrated system featuring a digital prescription chart and an AI-powered myopia prediction model.  
This project was **planned, architected, designed, developed, deployed, and operated entirely solo** (end-to-end).

#### Architecture

- TypeScript-based **monorepo (server / front / ai)** for unified management
- Flexible Node.js architecture:
  - Shifted from **3-layer (Controller–Service–Repository)** to  
    **2-layer (Controller–Service)** depending on development needs
- Improved code consistency and overall development productivity

#### Authentication & Security

- **Stateless authentication** using JWT + HttpOnly cookies
- Implemented **Two-Factor Authentication (2FA)**
- Designed **refresh-token management** for multi-device concurrent sessions

#### DevOps

- Optimized AWS **EC2 Free Tier** resource usage
- Integrated AI model training and Python ETL into the **CI/CD pipeline**
- Operated **three WAS servers** on a single EC2 instance

#### Data & AI

- Built a MongoDB → Python **ETL pipeline**
- Developed an **XGBoost-based time-series myopia prediction model**
- Provided a **FastAPI prediction API (JSON)** for real-time inference

<br>
<br>

### 🚢 EDMS | HMM Ship Regulation Management System for Ground Staff

A system designed to centralize and streamline scattered maritime regulations and  
internal rule documents, providing workflow automation and robust document lifecycle management.

#### Approval Workflow

- Designed and implemented an **electronic approval workflow** for regulation changes
- Automated approval processes to reduce manual oversight

#### Document Management

- Implemented **CKEditor-based web document editing** for complex maritime regulations
- Enabled full online creation, editing, and management of regulatory documents

#### Versioning & Comparison

- Added **new/old regulation comparison** functionality
- Designed file versioning schemas to strengthen **change-history tracking**

#### Search Performance Optimization

- Improved large-scale document search using **MongoDB Atlas + custom search algorithms**
- Achieved near real-time search response for thousands of documents

#### Refactoring

- Migrated the entire legacy JavaScript codebase to **TypeScript**
- Significantly improved maintainability and runtime stability

<br>

## 🛠️ Skills & Technologies

- **Backend**: Node.js(Express), Nest.js, Python(FastAPI)
- **Frontend**: React(Vite), Nextjs, Zustand, TanStack Query
- **Database**: MongoDB (Mongoose), PostgreSQL (with TimescaleDB)
- **DevOps**: AWS (Route53, Load Balancer, EC2, S3, CloudFront, Amplify), Git Actions, Nginx
- **AI & Data**: Pandas, Scikit-learn, XGBoost

<br>

## 🚀 Mission

**"Building a better world through efficient code."**

<br>

## 📫 Get in Touch

- [LinkedIn](https://www.linkedin.com/in/seongwon-woo-4a11092a7/)
- Email: dnqkr18@gmail.com
