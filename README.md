# 🌍 Enigma - Personalized Energy Hub ⚡
Welcome to Enigma, a dynamic platform designed to educate and empower individuals, businesses, and industries in managing their energy consumption efficiently. Enigma aligns with the United Nations Sustainable Development Goal (SDG) 7, promoting access to affordable, reliable, sustainable, and modern energy for all. Our mission is to help you make informed energy decisions that enhance efficiency, reduce costs, and minimize environmental impact.

## Why choose "Enigma" as our website name? 🧩
The name "Enigma" was chosen because it reflects the complex and often mysterious nature of energy management, much like how Alan Turing cracked the Enigma code. Energy consumption and sustainability are intricate puzzles that many individuals, businesses, and organizations struggle to fully understand. Our platform, Enigma - Personalized Energy Hub , seeks to demystify these complexities and provide clear, actionable insights.
Furthermore, aligning with the United Nations' Sustainable Development Goal (SDG) 7—ensuring access to affordable, reliable, sustainable, and modern energy for all—our platform educates users about energy efficiency and conservation. Just as Turing’s work on Enigma changed the course of history, our goal is to empower users to make informed energy choices that promote sustainability and contribute to global conservation efforts.

## 🧠 Why Enigma?
With the rising global energy demands, managing energy consumption is more critical than ever. Enigma empowers users with data-driven tools that help optimize energy usage, reduce costs, and promote environmental sustainability.

## 🌟 Key Features
Here’s what Enigma has to offer:

🔹 **Energy Efficiency Tools ⚙️:** Evaluate and optimize the efficiency of your household devices or industrial equipment.

🔹 **Electricity Price Prediction 📈:** Accurately predict future energy costs based on your usage patterns, helping you plan better.

🔹 **Carbon Footprint Calculator 🌱:** Track and understand your carbon footprint with personalized insights on how to reduce your impact.

🔹 **Power Plant & Cooling System Evaluator 🔋❄️:** Tailored recommendations to optimize thermoelectric power plants and cooling systems.

🔹 **Interactive Dashboards 📉📊:**
- Household Dashboard: Monitor home energy usage and efficiency.
- Power Plants Dashboard: Insights into energy generation metrics for power plants.
- Industry Dashboard: Track global energy consumption and renewable energy usage in industries.

🔹 **Industry Energy Source Optimizer 🏭:** Compare renewable and non-renewable energy options for industries based on cost and efficiency.

🔹 **Live Trends Visualizations 📊:** View real-time energy metrics and trends, helping you make data-driven decisions.

🔹 **Chatbot 🤖:** Get instant guidance on energy-saving tips and platform navigation with our AI-powered chatbot.

🔹 **Blogs with Summary & FAQ Models 📝:** Explore informative blogs featuring auto-generated summaries and FAQs for deeper insights.

## 🔧 Models & Features Breakdown

### 1️⃣ Device Efficiency Assessment 🛠️ 

- Analyze your device's efficiency based on type, age, and usage. The model provides personalized feedback to help you reduce energy consumption.

- User Inputs: Device type, brand, usage hours, malfunction history.

- Model: Random Forest Classifier.

- Outputs: Efficiency ratings and cost savings.

### 2️⃣ Carbon Footprint Calculator 🌍 

- Estimate your carbon emissions based on lifestyle factors and energy usage, and receive actionable steps to reduce your environmental footprint.

- User Inputs: Diet, transport, energy-efficient devices, etc.

- Model: Multiple Linear Regression (MLR).

- Outputs: Carbon emissions with personalized recommendations.

### 3️⃣ Electricity Price Prediction 💡

- Get a prediction of future electricity prices to optimize your energy spending.

- User Inputs: Energy usage data.

- Model: Gradient Boost, Random Forest.

- Outputs: Predicted electricity prices with optimization tips.

### 4️⃣ Power Plant Efficiency & Cooling System Model 🔌❄️ 

- Get data-driven recommendations for optimizing power plant performance and cooling systems, ensuring efficiency in energy generation.

- User Inputs: Temperature, pressure, humidity, and exhaust vacuum.

- Model: Multiple Linear Regression (MLR).

- Outputs: Efficiency ratings and tailored cooling system suggestions.

### 5️⃣ Industry Energy Source Optimizer 🏭

- Designed for industries, this model helps optimize energy consumption by comparing renewable and non-renewable sources based on costs, location, and energy efficiency.

- User Inputs: Energy consumption data, renewable vs. non-renewable usage.

- Model: Genetic Algorithm (DEAP).

- Outputs: Optimal energy solutions, cost-saving insights, and environmental impact assessments.

### 6️⃣ Chatbot 💬

- Our AI-powered chatbot offers real-time guidance on energy-saving tips, FAQs, and general platform navigation.

- Capabilities: Symptom logging, real-time interactions, energy tips.

### 7️⃣ Live Trends & Interactive Dashboards 📊

- Monitor real-time data across various sectors—household, power plants, and industries. The dashboards provide a dynamic and user-friendly interface to track energy consumption, efficiency, and trends.

- Tools: Charts.js, Tableau.

- Outputs: Live trend visualizations with interactive insights on energy consumption.

### 8️⃣ Blogs with Summary & FAQ Models 📖

- Access well-researched articles on energy topics. Auto-generated summaries and FAQ models make it easy to extract key information quickly.

- Model: LLaMA 3 for summarization and FAQ generation.

- Features: Summarize key points and access FAQs for quicker insights.

## 🛠️ System Design Overview
Here’s a detailed breakdown of the technologies powering Enigma:

### **Frontend Technologies:**

- _HTML 🏷️:_ The backbone of our web content, ensuring structured, accessible, and SEO-friendly information. Proper HTML tags make sure the site is easy to navigate and search engine optimized.

- _CSS & SCSS 🎨:_ Ensures consistent and responsive styling across all devices—desktops, tablets, and smartphones. SCSS allows for easier management of complex styles, enhancing the overall design.

- _Bootstrap CSS & Bootstrap JS 🖼️:_ We leverage Bootstrap to create a responsive, mobile-first design. The ready-made components and grid system ensure a consistent and professional look throughout the site, while Bootstrap JS adds interactive elements like modals and carousels.

- _JavaScript 🌐:_ JavaScript enables dynamic interactions on the site, updating content in real-time without requiring a page reload. This smoothens the user experience, making the platform highly interactive.

### **Backend Technologies:**

- _Flask (Python Framework) 🐍:_ Our backend is built using Flask, a lightweight and flexible Python framework. Flask is essential for handling API requests, routing, and database interactions, ensuring seamless communication between the frontend and backend.

- _SQLAlchemy🛢️:_ This Object-Relational Mapping (ORM) tool simplifies our database interactions by allowing us to manipulate the database using Python objects rather than raw SQL queries. This speeds up development and reduces errors.

- _MySQL 🏠:_ We use MySQL for structured data storage. It manages vast amounts of user data, energy metrics, and transactions, ensuring reliable and secure data storage.

### **Data Visualization & Real-Time Trends:**
- _Charts.js 📊:_ This JavaScript library powers our real-time energy trend visualizations, offering interactive charts that allow users to track and analyze their energy consumption, usage patterns, and pricing trends easily.

- _Tableau 📈:_ For advanced data analysis, especially in industrial and power plant dashboards, we use Tableau. It helps visualize large datasets, offering detailed insights into energy metrics across various sectors.

### **Chatbot & Interaction:**

- _RAG (Retrieval-Augmented Generation) 🤖_: Our chatbot utilizes RAG to enhance user interactions. It retrieves relevant information and generates personalized responses based on user queries, ensuring accurate and context-sensitive answers.

- _LLM (Large Language Models) 🧠:_ The chatbot is built using an advanced LLM (e.g., LLaMA 3), which powers the FAQ and Summary functionalities. Users can read blog posts with auto-generated Summaries or explore frequently asked questions (FAQs) for quick insights into energy-related topics.

## 🗃️ Documentation
For further details about the models, algorithms, and technologies used in Enigma, you can check our comprehensive project report linked below:

## ❤️ Made with Dedication by:
👤 Diyotrim Maitra

👤 Jiss Sabu Varghese

👤 Shreya Ghosh
