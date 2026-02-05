# 👗 Tryly – Virtual Try-On & AI Fashion Assistant

Tryly is an AI-powered virtual try-on and fashion assistance platform that allows users to visualize outfits digitally, receive styling recommendations, and interact with intelligent AI models for fashion suggestions. The platform combines modern web technologies with AI models to deliver an interactive and personalized fashion experience.

---

## 📌 Overview

Tryly is designed to enhance online fashion shopping by allowing users to preview clothing and styling recommendations virtually. The platform integrates frontend UI technologies with backend AI modules that analyze fashion inputs and generate intelligent recommendations.

---

## ✨ Key Features

* 👕 Virtual outfit try-on simulation
* 🤖 AI-powered styling recommendations
* 🧠 Machine learning fashion models
* ⚡ Fast and responsive React-based interface
* 🎨 Modern UI using Tailwind CSS
* 🔄 Real-time interaction and visualization
* 📦 Modular architecture for scalability

---

## 🏗️ Project Architecture

The platform follows a multi-layer modular architecture:

### 🔹 Frontend Layer

* Built using React + Vite
* Provides interactive UI for users
* Handles user input and outfit visualization

### 🔹 Backend / Processing Layer

* Manages application logic
* Handles communication between frontend and AI modules

### 🔹 AI Models Layer

* Provides recommendation and analysis
* Processes image or styling inputs
* Generates outfit suggestions

### 🔹 Static & Public Resources

* Stores UI assets and styling resources

---

## 🧾 Project Structure

```
Tryly/
│
├── AI_models/                     # Contains AI and machine learning modules
│   ├── model_training/            # Scripts used to train ML models
│   ├── inference/                 # Model prediction and processing scripts
│   ├── preprocessing/             # Image/data preprocessing utilities
│   └── utils/                     # Helper functions for AI processing
│
├── public/                        # Static public assets
│   ├── images/                    # UI and application images
│   ├── icons/                     # Application icons and graphics
│   └── assets/                    # Other static resources
│
├── src/                           # Main React application source code
│   ├── components/                # Reusable UI components
│   │   ├── Navbar.jsx             # Navigation bar
│   │   ├── Footer.jsx             # Footer section
│   │   ├── TryOnPanel.jsx         # Virtual try-on interface
│   │   └── RecommendationCard.jsx # Displays outfit recommendations
│   │
│   ├── pages/                     # Application page-level components
│   │   ├── Home.jsx               # Landing page
│   │   ├── TryOn.jsx              # Virtual try-on page
│   │   ├── Recommendations.jsx    # Styling recommendation page
│   │   └── About.jsx              # Project information page
│   │
│   ├── services/                  # API communication and backend interaction
│   │   ├── aiService.js           # Connects frontend to AI modules
│   │   └── apiService.js          # Handles HTTP/API requests
│   │
│   ├── hooks/                     # Custom React hooks
│   │   └── useTryOn.js            # Try-on related logic
│   │
│   ├── styles/                    # Styling and Tailwind customizations
│   │   └── global.css             # Global application styles
│   │
│   ├── App.jsx                    # Root React component
│   ├── main.jsx                   # React application entry point
│   └── routes.jsx                 # Routing configuration
│
├── index.html                     # Main HTML template
├── package.json                   # Project dependencies and scripts
├── package-lock.json              # Dependency version lock
├── vite.config.js                 # Vite bundler configuration
├── tailwind.config.js             # Tailwind CSS customization
├── eslint.config.js               # Linting rules and code standards
└── README.md                      # Project documentation

```

---

## 🛠️ Technologies Used

### 🌐 Frontend

* React.js
* Vite
* JavaScript
* HTML
* Tailwind CSS

### 🤖 AI / Backend

* Python
* Machine Learning Models

### 🧰 Development Tools

* ESLint
* Node.js
* Package Management (npm)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Yashika-28/Tryly.git
cd Tryly
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Setup AI Environment (Optional)

Install Python dependencies if AI modules are used:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Start the development server:

```bash
npm run dev
```

The application will be available at:

```
http://localhost:5173
```

---

## 🧪 Running AI Models

Navigate to the AI models folder and run Python scripts if required:

```bash
cd AI_models
python main.py
```

*(Note: Adjust script names based on actual implementation.)*

---

## 🎯 Use Cases

* Virtual fashion try-on
* Personalized outfit recommendation
* Smart online clothing shopping
* AI styling assistant
* Fashion visualization and experimentation

---

## 📊 Workflow

1. User selects or uploads outfit details
2. Frontend sends request to backend
3. AI models process styling or try-on logic
4. System generates recommendation or visualization
5. Results are displayed to the user interface

---

## 🚀 Future Enhancements

* 3D outfit visualization
* Real-time camera-based try-on
* User profile & wardrobe management
* Mobile application deployment
* Integration with e-commerce platforms
* Multi-language support
* Cloud AI deployment

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Submit a pull request

---

## 📜 License

This project is open-source and available for educational and development purposes.

---

## 👩‍💻 Author

Developed by **Yashika**

---

## ⭐ Acknowledgements

* React & Vite Development Ecosystem
* Open-source AI and Machine Learning Libraries
* Tailwind CSS for UI styling
