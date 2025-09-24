# Myntra Fashion DNA

A personalized fashion engagement platform inspired by **Myntra**, designed to provide users with interactive features like **Fashion DNA profiling**, **Avatar Closet**, **Influencer Video Feed**, and **Shoppable Content**. Built using **React + Vite** with modular components for scalability.

---

## Project Structure

```
├── public/ Static assets
├── src/
│ ├── assets/ Images, fonts, videos, icons
│ ├── components/ Reusable UI components
│ │ ├── AvatarCloset/ Avatar customization
│ │ ├── Navbar/ Navigation bar
│ │ ├── Product/ Product listing
│ │ ├── ProductCard/ Individual product card
│ │ └── CartTab.jsx /Shopping cart tab
│ │
│ ├── data/ Mock data (JSON, JS)
│ │ ├── products.js
│ │ └── videos.json
│ │
│ ├── pages/Page-level views
│ │ ├── Home/Landing page
│ │ ├── Influencing/Influencer/creator section
│ │ ├── LikeTab.jsx /Likes & interactions
│ │ ├── Login/ Authentication
│ │ ├── OrderHistory/Order history
│ │ ├── ProductGrid.jsx
│ │ ├── ProfileDNA/Style DNA profile
│ │ ├── Signup/Registration
│ │ └── VideoFeed/Video-based fashion feed
│ │
│ ├── App/Root component
│ ├── index.css /Global styles
│ └── main.jsx/ Entry point
│
├── .gitignore
├── eslint.config.js/ ESLint config
├── index.html/App entry HTML
├── package.json
├── package-lock.json
├── vite.config.js /Vite config
└── README.md
```

---

## Features

### **Fashion DNA**

- Each product has a **category**: _Retro, Streetwear, Boho, etc._
- When a user purchases items, their **purchase history** is tracked using `useState`.

## **Fashion DNA %** is calculated:

**_DNA% (for a category) = (count of items bought in that category) / (total purchases) × 100_**

- DNA is displayed in:
- A **Helix visualization**
- A **Pie/Bar chart**
- A **one-line summary** describing the user’s unique style DNA.

### **Closet & Avatar Integration**

- Every purchased item is added to the **Closet**.
- The Closet integrates with the **AvatarCloset** component, letting users try outfits on their virtual avatar.
- Creates a personalized wardrobe experience.

### **Influencer Video Feed**

- Users can **post their own fashion videos**.
- Videos from influencers showcase outfits that can be **directly purchased** by viewers.
- Turns fashion content into a **shoppable social feed**.

### Other Features

- **Product Grid & Cards** → Product browsing with mock data
- **Order History** → See past purchases
- **Login / Signup** → Authentication flows
- **Gamification (DNAQuests)** → Quests and challenges to boost engagement

---

## Tech Stack

- **Frontend Framework:** React + Vite
- **Styling:** CSS (component-based modular CSS)
- **State Management:** React state & props
- **Linting:** ESLint
- **Data:** JSON/JS mock data for products, videos, posts

---

## Installation & Setup

1. **Clone the repo**

```bash
git clone https://github.com/Pritee668/myntra-fashion-dna.git
cd myntra-fashion-dna
```

## Installation & Setup

### Install dependencies

```bash
npm install
```

### License

```bash
This project is for educational/hackathon purposes. No commercial use intended.
```
