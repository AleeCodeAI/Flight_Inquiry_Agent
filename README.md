<!DOCTYPE html>
<html lang="en">
<body>

<h1>Aero Assistant</h1>
<p>A smart flight-intelligence agent that understands natural language queries and retrieves accurate flight information from a structured database.</p>

<hr>

<h2>Overview</h2>
<p>
Aero Assistant is an intelligent flight-search agent that takes natural language queries and retrieves the most relevant results from a SQLite database. 
It was built as part of an AI learning journey and demonstrates how LLMs, memory, and tool-calling can be combined to solve real-world problems.
</p>
<p>
This project is suitable for anyone learning how to build agents that interact with structured data. It can be used as a reference or as a starting point for creating your own flight search agent.
</p>

<hr>

<h2>Features</h2>
<ul>
  <li>Understands natural language flight queries, including airlines, dates, routes, prices, stops, and more.</li>
  <li>Converts user queries into structured tags and searches a SQLite database.</li>
  <li>Supports flexible filtering across multiple flight attributes.</li>
  <li>Uses Large Language Models for intent extraction and understanding.</li>
  <li>Tool-calling for database interactions.</li>
  <li>Conversation memory for multi-turn interactions.</li>
  <li>Fast and optimized search performance.</li>
  <li>Streamlit-based interface for interacting with the agent.</li>
  <li>Beginner-friendly architecture demonstrating LangChain agent design.</li>
</ul>

<hr>

<h2>Tech Stack</h2>

<h3>Language</h3>
<ul>
  <li>Python</li>
</ul>

<h3>Frameworks and Tools</h3>
<ul>
  <li>LangChain</li>
  <li>Streamlit</li>
  <li>OpenRouter (model switching)</li>
  <li>VS Code</li>
</ul>

<h3>Models Used</h3>
<ul>
  <li>Google Gemini</li>
  <li>DeepSeek models</li>
</ul>

<h3>Database</h3>
<ul>
  <li>SQLite</li>
</ul>

<h3>Other</h3>
<ul>
  <li>Standard Python libraries such as sqlite3 and dotenv</li>
</ul>

<hr>

<h2>Project Structure</h2>

<pre>
1_Flight_Search_Agent/
│
├── app.py                     # Main Streamlit application
├── main.py                    # Core agent logic
├── extract_flight_info.py     # Functions for analyzing and extracting flight details
├── search_functions.py        # Tool functions for database queries
├── flights_dataset.csv        # Raw flight dataset
├── flights.db                 # SQLite database
├── experimentations.ipynb     # Notebook for experimentation
└── __pycache__/               # Auto-generated cache
</pre>

<hr>

<h2>Conclusion</h2>
<p>
Aero Assistant demonstrates a practical example of combining LLMs, tool-calling mechanisms, memory components, and structured databases to build an intelligent search system. 
It serves as a clear, hands-on learning resource for anyone exploring agent design or building AI-powered applications.
</p>
<p>
You are encouraged to extend it, modify it, and adapt it into more advanced or production-ready versions.
</p>

<hr>

<h2>Support</h2>
<p>If you found this project useful, consider starring the repository and sharing your feedback.</p>

</body>
</html>
