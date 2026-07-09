# 🧠 AI Data Lineage & ML Dataset Intelligence System

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/ml-lineage-intelligence-system)](https://github.com/vishakha2121/ml-lineage-intelligence-system/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/ml-lineage-intelligence-system)](https://github.com/vishakha2121/ml-lineage-intelligence-system/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/ml-lineage-intelligence-system)](https://github.com/vishakha2121/ml-lineage-intelligence-system/issues)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9+-3776AB.svg)](https://www.python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688.svg)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18.2+-61DAFB.svg)](https://reactjs.org)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-336791.svg)](https://www.postgresql.org)

---

## 📋 Overview

An **intelligent data lineage and ML metadata tracking system** that automatically traces dataset origins, transformations, feature usage, model dependencies, and data quality across the ML lifecycle. Built with **FastAPI**, **React**, and **PostgreSQL**, the system leverages **Google Gemini API** to generate intelligent insights and maintain a comprehensive metadata catalog.

### 🎯 Why This Project?

- **🔍 Complete Visibility**: Track every data transformation and model dependency
- **🤖 AI-Powered**: Intelligent insights using Google Gemini API
- **📊 Real-time Quality**: Monitor data quality metrics in real-time
- **🎨 Beautiful UI**: Professional dark theme with interactive visualizations
- **🚀 Production-Ready**: Scalable architecture with Docker support

---

## ✨ Key Features

### 🔍 **Data Lineage Tracking**
- Automated tracking of dataset origins and transformations
- Interactive D3.js graph visualization with zoom/pan
- Complete data pipeline DAG visualization
- Color-coded nodes (datasets, models, features)

### 🧠 **ML Dataset Intelligence**
- Automatic metadata extraction and enrichment
- Feature usage tracking across models
- Dataset versioning and history
- Data profiling and statistics

### 📊 **Model Dependency Management**
- Track model-to-dataset relationships
- Monitor model performance drift
- Maintain model version history
- Complete model dependency graph

### ✅ **Quality Monitoring**
- Real-time data quality metrics
- Automated anomaly detection
- Quality trend analysis
- Custom threshold alerts

### 🤖 **AI-Powered Features**
- Gemini API for intelligent insights
- Automatic dataset descriptions
- Smart anomaly detection
- Predictive quality alerts

### 🎨 **Modern UI/UX**
- Dark theme with neon accents
- Responsive design for all devices
- Smooth animations and transitions
- Keyboard shortcuts support

---

## 🏗️ Architecture

### Backend Stack
| Technology | Version | Purpose |
|------------|---------|---------|
| **FastAPI** | 0.100+ | Web framework |
| **Python** | 3.9+ | Programming language |
| **PostgreSQL** | 14+ | Database |
| **SQLAlchemy** | 2.0+ | ORM |
| **Alembic** | Latest | Migrations |
| **Celery** | Latest | Task queue |
| **Redis** | Latest | Caching & broker |
| **Google Gemini** | Latest | AI integration |
| **JWT** | Latest | Authentication |

### Frontend Stack
| Technology | Version | Purpose |
|------------|---------|---------|
| **React** | 18.2+ | UI framework |
| **Redux Toolkit** | Latest | State management |
| **Material-UI** | Latest | Component library |
| **Tailwind CSS** | Latest | Styling |
| **D3.js** | Latest | Data visualization |
| **React Flow** | Latest | Graph visualization |
| **Vite** | Latest | Build tool |

---

## 📁 Project Structure

---

## 🚀 Quick Start

### Prerequisites

- Python 3.9+
- Node.js 18+
- PostgreSQL 14+
- Docker (optional)
- Git

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/vishakha2121/ml-lineage-intelligence-system.git
cd ml-lineage-intelligence-system

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
pip install -r dev-requirements.txt  # For development

# Configure environment
cp .env.example .env
# Edit .env with your credentials

# Navigate to frontend
cd ../frontend

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Edit .env with your API URL