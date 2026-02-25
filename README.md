<h1>🌍 Language Detection and Translation</h1>

This is a Flask-based web application that detects the language of input text and translates it into a selected target language.
<ul>
The application uses:
<li>
  langdetect for language detection
</li>
  
<li>
  googletrans for translation
</li>
<li>
Flask for backend</li>
<li>
HTML, CSS for frontend styling</li>

</ul>
<h2>🚀 Features</h2>

<ul>
  <li>Detects the language of entered text</li>
  <li>Translates text into selected target language</li>
  <li>Dynamic language dropdown using googletrans.LANGUAGES</li>
  <li>Clean and responsive Bootstrap UI</li>
  <li>Real-time translation via web interface</li>
</ul>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li>Python</li>
  <li>Flask</li>
  <li>langdetect</li>
  <li>googletrans</li>
  <li>HTML5</li>
  <li>Bootstrap 4</li>
</ul>

<h2>⚙️ Installation & Setup</h2>

<ol>
  <li>
    <strong>Clone the Repository</strong>
    <pre>
git clone https://github.com/SherylFernandes/multiple-disease-detection.git
cd multiple-disease-detection
    </pre>
  </li>

  <li>
    <strong>Create Virtual Environment</strong>
    <pre>
python -m venv .venv
    </pre>
    <p><strong>Activate it:</strong></p>
    <p><strong>Windows:</strong></p>
    <pre>
.venv\Scripts\activate
    </pre>
  </li>
</ol>

<h3>3️⃣ Install Dependencies</h3>

<p>Run the following command:</p>

<pre>
pip install -r requirements.txt
</pre>

<p>If you don’t have a <code>requirements.txt</code> file, install manually:</p>

<pre>
pip install flask langdetect googletrans==4.0.0-rc1
</pre>

<h3>4️⃣ Run the Application</h3>

<p>Start the Flask application using:</p>

<pre>
python app.py
</pre>

<p>Then open your browser and go to:</p>

<pre>
http://127.0.0.1:5000
</pre>

<h2>📌 How It Works</h2>

<ul>
  <li>User enters text</li>
  <li>langdetect detects the source language</li>
  <li>googletrans translates the text into selected language</li>
  <li>Result is displayed on the webpage</li>
</ul>

<h2>🧠 Example</h2>

<h3>Input:</h3>
<pre>
Bonjour tout le monde
</pre>

<h3>Output:</h3>
<pre>
Detected Language: French
Translation (English): Hello everyone
</pre>
