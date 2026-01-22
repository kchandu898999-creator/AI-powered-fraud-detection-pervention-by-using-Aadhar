<h1>🛡️ RakshaUID: Identity Defense System</h1>

<p>
RakshaUID is an advanced AI-powered identity verification platform designed to detect Aadhaar fraud.
It combines Deep Learning (CNN), Optical Character Recognition (OCR), and Biometric Face Verification
into a strict 3-stage security workflow to ensure only authentic identities are verified.
</p>

<hr>

<h2>🚀 Key Features</h2>

<ul>
  <li>
    <b>🔍 3-Stage Verification Workflow:</b>
    <ol>
      <li>
        <b>Document Analysis:</b>
        Uses a trained CNN model (TensorFlow) to distinguish valid Aadhaar cards from non-Aadhaar documents.
      </li>
      <li>
        <b>Biometric Face Match:</b>
        Uses OpenCV (LBPH Face Recognizer) to match the photo on the ID card with a live webcam feed or uploaded user photo.
      </li>
      <li>
        <b>Data Extraction & QR Validation:</b>
        Extracts text using PaddleOCR and cross-references it with decoded QR Code data for consistency.
      </li>
    </ol>
  </li>

  <li>
    <b>🧠 Fraud Detection Engine:</b>
    Analyzes image forensics (tampering traces), data consistency, and ML-based fraud probability scores.
  </li>

  <li>
    <b>🗄️ Secure Database:</b>
    Stores verified records in SQLite for instant future lookups and duplicate prevention.
  </li>

  <li>
    <b>📊 Interactive Dashboard:</b>
    A modern, responsive web interface built with FastAPI and JavaScript featuring Dark/Light mode and real-time status updates.
  </li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li><b>Backend:</b> Python 3.10+, FastAPI, Uvicorn</li>
  <li><b>Deep Learning:</b> TensorFlow / Keras (CNN Classification)</li>
  <li><b>Computer Vision:</b> OpenCV (opencv-contrib-python), PaddleOCR</li>
  <li><b>Machine Learning:</b> Scikit-Learn (Random Forest for Fraud Probability)</li>
  <li><b>Database:</b> SQLite</li>
  <li><b>Frontend:</b> HTML5, CSS3, JavaScript (Fetch API)</li>
</ul>

<hr>

<p align="center">
  🔐 <i>RakshaUID ensures trust, security, and authenticity in digital identity verification.</i>
</p>
