<h1 align="center">Hey, I'm Calli</h1>
<h3 align="center">Engineering Student · Backend & AI Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=BB86FC&center=true&vCenter=true&width=600&lines=Building+backend+systems+with+Python+%2B+FastAPI;Working+on+LiDAR+%2F+3D+Perception+pipelines;Learning+DSA+in+C%2B%2B%2C+one+pattern+at+a+time;Aiming+to+ship+AI-integrated+backend+products" alt="Typing SVG" />
</p>

---

### About Me

I'm an engineering student at **Thapar Institute of Engineering & Technology**, focused on backend engineering, AI-powered applications, and 3D computer vision. My background started in C, and I'm now building toward a Python-first stack for backend and AI systems :)

- Currently building a Foveated Semantic 2.5D LiDAR Mapping pipeline for Smart India Hackathon
- Currently deepening Python, FastAPI, DSA in C++, and Operating Systems
- Long-term goal: AI engineering + backend development, with LLM APIs, RAG pipelines, and agent frameworks

---

## Featured Project

### Foveated Semantic 2.5D LiDAR Mapping — Smart India Hackathon

Building a real-time Foveated Semantic 2.5D LiDAR Mapping pipeline as part of a 6-person Smart India Hackathon team.

**[View the repo →](https://github.com/CallidusK/SIH26053)**

**My role — Data & Pose Subsystem**

| Responsibility | Details |
|---|---|
| Data loading | Raw SemanticKITTI LiDAR `.bin` point clouds |
| Calibration | Parsing sensor calibration & coordinate transforms |
| Motion estimation | Computing relative LiDAR motion between consecutive scans |
| Loader design | Dynamic multi-frame `SemanticKITTILoader` |
| Semantic remapping | 20-class → 4-class semantic remapping |
| Performance | Vectorized NumPy lookup tables |
| Verification | 7-stage subsystem verification suite |
| In progress | Spherical range-image projection for the NN pipeline |

**Pipeline overview:**

```text
Raw LiDAR + Poses + Calibration
              │
              ▼
       Data & Pose Layer            ← my subsystem
              │
              ▼
    Range Image Projection
              │
              ▼
        SalsaNext
     Semantic Segmentation
              │
              ▼
      Unprojection &
     Semantic Remapping
              │
              ▼
       2.5D Elevation Grid
```

**Stack:** Python · NumPy · SemanticKITTI · LiDAR · 3D Point Clouds · Computer Vision · SalsaNext
**Status:** Work in progress

---

## Tech Stack

<p>
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

**AI / Computer Vision:** Artificial Intelligence · Machine Learning · Computer Vision · 3D Point Clouds · LiDAR Processing · Open3D · SemanticKITTI · SalsaNext

**Backend:** FastAPI · REST APIs · PostgreSQL (learning) · JWT Auth (learning) · Docker (learning)

---

## Current Learning Map

```text
Python
  │
  ├── Backend Track
  │       ├── FastAPI
  │       ├── REST APIs
  │       ├── PostgreSQL & JWT auth
  │       └── Async patterns + Docker
  │
  └── AI Track
          ├── LLM APIs & RAG pipelines
          ├── Agent frameworks (LangGraph, Pydantic AI)
          ├── Computer Vision
          └── 3D / LiDAR Perception

C++
  │
  └── Data Structures & Algorithms
          ├── Arrays & Two-Pointer patterns
          ├── Sorting
          ├── Linked Lists, Stacks, Queues
          ├── Trees
          └── Time & Space Complexity

Systems
  │
  └── Operating Systems
          ├── System Structures
          ├── Process Management
          └── Concurrency
```

---

## Connect

<p>
<a href="mailto:kushalbulandi01@gmail.com"><img src="https://img.shields.io/badge/Email-kushalbulandi01%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

<p align="center"><i>Building, learning, and improving one project at a time :)</i></p>
