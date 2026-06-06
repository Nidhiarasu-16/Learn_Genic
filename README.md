# LearnGenic AI – Your AI Study Partner

## Project Overview :

LearnGenic AI is an intelligent study assistant powered by Google's Gemini AI. The application generates personalized study guides on any topic, helping students learn concepts quickly and effectively. Users can enter a topic of interest and instantly receive a structured lesson containing explanations, key study points, and multiple-choice questions for self-assessment.

The platform also provides downloadable PDF study guides, making it a convenient tool for revision and offline learning.

---

## Objective :

* To simplify learning through AI-generated educational content
* To provide concise and structured study materials on demand
* To enhance self-learning through interactive quizzes
* To enable easy access to downloadable study resources

---

## Features :

* AI-powered lesson generation using Gemini AI
* Simple and intuitive user interface
* Topic-based personalized study guides
* Easy-to-understand explanations with analogies
* Key study points for quick revision
* Multiple-choice questions for self-assessment
* Answer key generation
* PDF export functionality
* Responsive web application using Streamlit

---

## Technologies & Tools Used :

* Python
* Streamlit
* Google Gemini API
* FPDF
* HTML & CSS (Custom Styling)

---

## Project Architecture :

```
User Input
     │
     ▼
Streamlit Interface
     │
     ▼
Gemini AI API
     │
     ▼
Lesson Generation
     │
     ├── Explanation
     ├── Key Study Points
     ├── MCQs
     └── Answer Key
     │
     ▼
PDF Generator
     │
     ▼
Downloadable Study Guide
```

---

## How It Works :

1. The user enters a topic they want to learn.
2. The application sends the topic to Google's Gemini AI model.
3. Gemini generates:

   * A simplified explanation
   * An analogy-based understanding
   * Five key study points
   * Three multiple-choice questions
   * Answer keys
4. The generated content is displayed within the application.
5. Users can review answers using the expandable answer section.
6. The complete study guide can be downloaded as a PDF.

---

## Installation :

### Clone the Repository :

```bash
git clone https://github.com/yourusername/learngenic-ai.git
cd learngenic-ai
```

### Install Dependencies :

```bash
pip install streamlit google-genai fpdf
```

### Configure API Key :

Create a `.streamlit/secrets.toml` file:

```toml
GEMINI_API_KEY = "YOUR_API_KEY"
```

Alternatively, enter the API key through the application's sidebar.

---

## Running the Application :

```bash
streamlit run app.py
```

---

## User Interface Components :

* Topic Input Field
* Generate Lesson Button
* AI-Generated Study Material
* Expandable Answer Section
* PDF Download Button

---

## Key Benefits :

* Instant learning assistance
* Personalized educational content
* Reduced study preparation time
* Interactive self-assessment
* Offline study through PDF downloads

---

## Applications :

* School and college students
* Competitive exam preparation
* Quick concept revision
* Self-paced learning
* Educational assistance platforms

---

## Future Enhancements :

* Voice-based learning assistant
* Multi-language support
* Flashcard generation
* Personalized learning paths
* Difficulty-level customization
* Progress tracking dashboard
* User authentication and cloud storage
* Quiz score analytics

---

## Outcome :

LearnGenic AI demonstrates the practical integration of Generative AI into education by transforming simple topic queries into structured learning experiences. The application provides an efficient and engaging way for students to learn, revise, and test their understanding of various subjects.

---

## License :

This project is intended for educational, research, and portfolio purposes.
