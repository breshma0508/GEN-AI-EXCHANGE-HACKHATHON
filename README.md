# GEN-AI-EXCHANGE-HACKHATHON
### Team Name: SuperArtisans
### Built for: Google Cloud GenAI Exchange Hackathon
### Contact: breshma0508@email.com
### 🇮🇳 BHARAT KALASANS — A GENAI-POWERED PLATFORM FOR LOCAL ARTISANS

> **TAGLINE**: Empowering India's artisans with AI-driven storytelling, visibility, and growth.

---

## 🛑 PROBLEM STATEMENT

Many small-scale industries and local artisans in India face major challenges in showcasing their products to customers.

Even though they have excellent manufacturing skills and unique crafts, their work often remains hidden from mainstream markets.

They depend heavily on middlemen, who take a large share of the profit, leaving artisans with very little income.

As a result, artisans are unable to grow their businesses, while large-scale industries dominate with better marketing and visibility.

There is no single platform where artisans can present their products, stories, and processes directly to customers in an engaging way.

This disconnect not only reduces their earnings but also threatens the survival of India’s rich traditional heritage and small-scale industries.

---

## 💡 PROPOSED SOLUTION

We propose **BHARAT KALASANS**, a GenAI-driven digital platform that empowers artisans to:

- ✅ Create profiles showcasing their products, photos, and videos of their manufacturing process.
- 🤖 Use Generative AI to automatically generate product descriptions, multilingual bios, and storytelling content.
- 🗺️ Display artisan locations on an **interactive India map**, making discovery easy for customers.
- 📱 Promote themselves through **integrated social media links** (YouTube, Instagram) and **existing e-commerce stores** (Amazon, Flipkart, Etsy).
- 🏛️ Access simplified information about **government schemes** such as ODOP, PM Vishwakarma, KVIC, and MSME support.

This solution removes dependence on middlemen, gives artisans direct access to customers, increases their income, and helps preserve India’s cultural heritage while making it digitally visible to the world.

---

## 🔧 TECH FOCUS

Built using:

- **GOOGLE CLOUD VERTEX AI** – for GenAI-based bios, descriptions, and translations  
- **FIREBASE FIRESTORE** – for storing artisan profiles and metadata  
- **GOOGLE CLOUD STORAGE** – for hosting artisan images and videos  
- **CLOUD FUNCTIONS** – for triggering AI generation and integration  
- **LEAFLET.JS + MAPBOX** – for interactive map view of artisan locations  
- **REACT.JS** – for frontend web interface

## Flow Diagram 
flowchart TD
    A[🧑‍💻 User Lands on Website] --> B{How Do They Explore?}
    B -->|🔍 Search Bar| C[Search Profiles by Craft Type]
    B -->|🗺️ Map View| D[Explore India Map with Artisan Pins]

    C --> E[📋 List of Matching Artisan Profiles]
    D --> F[📍 Click on Artisan Map Pin]

    E --> G[👤 View Artisan Profile Page]
    F --> G

    G --> H[ℹ️ See Bio, Contact Info, Address, Social Links]
    H --> I[🛒 Click “Product Section” Button]
    I --> J[🧵 View Products with AI-Generated Descriptions]
    
## Architecture Diagram
 ### 1. Frontend (Website/App)
- Built using React (HTML/CSS/JS)
- Shows artisan profiles, map, and product sections
- Handles clicks and navigation

### 2. Backend (Firebase)
- Firestore: stores artisan data (name, craft, contact, etc.)
- Cloud Storage: stores artisan images and videos

### 3. AI Integration (Vertex AI)
- Generates bios, product descriptions, translations
- Triggered via API when user clicks “Generate Description”

### 4. Map Integration
- Uses Google Maps API / Leaflet.js
- Displays artisan pins using their location data

### 5. External Links
- Social media (YouTube, Instagram)
- E-commerce stores (Amazon, Flipkart, Etsy, personal sites)

### 6. Users
- **Customers:** Explore artisans via map or search
- **Artisans:** Showcase work, get AI-generated content

