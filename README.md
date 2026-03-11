chatbot link:  https://fridge-farewell-bot.lovable.app
Kitchen Alchemist: AI-Powered Culinary Sustainability
Project Overview
Kitchen Alchemist is a conversational AI platform integrated into the BiteBack ecosystem. The project aims to mitigate domestic food waste by leveraging Generative AI to transform surplus or near-expiry ingredients into actionable recipes. By providing a low-friction interface for ingredient management, the application reduces the volume of organic waste sent to landfills and promotes sustainable consumption habits.

Key Features
Conversational Logic: A natural language processing interface that parses unstructured user input to identify available pantry items.

Dynamic Recipe Generation: Integration with the Gemini API to provide customized cooking instructions based on specific user constraints.

Sustainability Metrics: A tracking system that calculates the approximate volume of food waste diverted and the associated reduction in carbon footprint.

Interactive Progress Stepper: A state-managed cooking guide that allows users to navigate through recipe instructions sequentially.

Community Integration: A global "Karma" system that syncs with the BiteBack database to reward users for sustainable behavior.

Technical Architecture
Frontend: Built with React and Tailwind CSS, utilizing a mobile-first responsive design and modular component structure.

Backend: Developed using Java (Spring Boot) to handle API routing, user authentication, and data persistence.

AI Integration: Utilizes Google Gemini Pro for natural language understanding and recipe synthesis.

Data Management: Employs a NoSQL database (MongoDB/Firebase) for real-time synchronization of user impact data and recipe history.

Installation and Setup
Prerequisites
Node.js (v18 or higher)

Java Development Kit (JDK 17 or higher)

Maven

Frontend Setup
Clone the repository.

Navigate to the /frontend directory.

Run npm install to install dependencies.

Run npm run dev to launch the development server.

Backend Setup
Navigate to the /backend directory.

Configure your application.properties with your API keys and database credentials.

Run mvn clean install.

Run mvn spring-boot:run to start the backend service.

Project Significance
In 2026, food waste remains a critical driver of global environmental degradation. Kitchen Alchemist addresses this by providing technical solutions at the individual level, fostering a community-driven approach to zero-waste living through the BiteBack network.
