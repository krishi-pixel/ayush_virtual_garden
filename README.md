# 🌿 AYUSH Herbal Garden
### Virtual Herbal Garden — 


## 🌱 About the Project

**AYUSH Herbal Garden** is an interactive, educational, and immersive virtual herbal garden that showcases the diverse range of medicinal plants used across India's five traditional healing systems — **Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy**.

The platform bridges the gap between ancient botanical knowledge and modern digital access, allowing anyone to explore, learn, and understand medicinal plants from the comfort of their home.

### Problem Being Solved

Physical herbal gardens are not accessible to everyone. Students, researchers, and the general public have limited access to comprehensive information about medicinal plants. This virtual garden provides:

- A **digital platform** to explore 258+ medicinal plants
- **Interactive isometric 3D garden view** for an immersive experience
- **AI-powered quiz system** for knowledge assessment
- **Comprehensive plant profiles** with botanical details, medicinal uses, habitat, and parts used

---

## ✨ Features

### 🌿 Virtual Garden
- Isometric 3D garden view matching real garden layout
- 258+ medicinal plants across 5 AYUSH gardens
- Drag to pan · Scroll to zoom · Click to learn
- 4 garden beds with stone pathways and realistic ground textures
- 7 plant types: tree, shrub, flower, vine, grass, succulent, herb

### 🔍 Search & Filter
- Real-time search by plant name or latin name
- Filter by medicinal use (Immunity, Fever, Skin, etc.)
- Switch between all 5 AYUSH gardens via tabs
- Pagination for large plant collections

### 📋 Plant Profiles
- Botanical name (Latin) + common name
- Medicinal uses with color-coded tags
- Parts used · Habitat · Detailed description
- Side panel with garden background art



### 🏆 Scoreboard
- Personal best stats (score, accuracy, streak, attempts)
- Global leaderboard with rank badges (🥇🥈🥉)
- Filter by garden · Sort by score / accuracy / date
- Color-coded accuracy bars per entry
- Difficulty badges per attempt

### 🔐 Authentication
- Register with name, email, password
- Secure login with JWT tokens
- Guest access option
- Session persistence via localStorage (frontend) / MongoDB (backend)

---

## 🛠 Tech Stack

### Frontend
| Technology | Purpose |
|-----------|---------|
| HTML5 | Page structure |
| CSS3 | Animations, 3D transforms, glassmorphism |
| Vanilla JavaScript | Dynamic rendering, Canvas API, localStorage |
| SVG | Plant illustrations (procedurally generated) |
| CSS 3D Transforms | Isometric garden view (`rotateX` + `rotateZ`) |
| Canvas API | Particle network background animation |
| Google Fonts | Cinzel · Raleway · DM Mono |

### Backend
| Technology | Purpose |
|-----------|---------|
| Python 3.x | Backend language |
| FastAPI | REST API framework |
| Motor | Async MongoDB driver |
| MongoDB Atlas | Cloud database (free tier) |
| JWT (python-jose) | Authentication tokens |
| Bcrypt (passlib) | Password hashing |
| Anthropic SDK | AI quiz generation (server-side) |
| Uvicorn | ASGI server |





---



---

*Built with 🌿 for Smart India Hackathon 2024*
