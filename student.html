<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Live Transcript Viewer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(120deg, #005f73, #0a9396, #94d2bd);
      background-size: 400% 400%;
      animation: oceanFlow 20s ease infinite;
      font-family: sans-serif;
    }

    @keyframes oceanFlow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    textarea {
      width: 90%;
      max-width: 800px;
      height: 300px;
      margin: 20px auto;
      display: block;
      padding: 15px;
      font-size: 1.1rem;
      border: 1px solid #ccc;
      border-radius: 8px;
      resize: vertical;
      background: #fff;
    }

    button {
      display: block;
      margin: 10px auto;
      padding: 10px 20px;
      font-size: 1rem;
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <marquee><h3>3MTT Potiskum — Live Transcript (Student View)</h3></marquee>
  <button onclick="downloadPDF()">Save as PDF</button>
  <textarea id="studentTranscript" readonly></textarea>

  <!-- Firebase SDKs -->
  <script src="https://www.gstatic.com/firebasejs/9.6.10/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/9.6.10/firebase-database-compat.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>

  <script>
    const transcriptArea = document.getElementById("studentTranscript");

    // ✅ Firebase config — replace with your actual values!
    const firebaseConfig = {
      apiKey: "AIzaSyBbXGnrJZd6sh48qBaMJFojs0tQR571nsE",
    authDomain: "rtvoicet.firebaseapp.com",
    databaseURL: "https://rtvoicet-default-rtdb.firebaseio.com",
    projectId: "rtvoicet",
    storageBucket: "rtvoicet.firebasestorage.app",
    messagingSenderId: "574390825166",
    appId: "1:574390825166:web:29a4368f3d7829fa01a09f",
    measurementId: "G-59M7EXW6N3"
    };

    // ✅ Initialize Firebase and database
    firebase.initializeApp(firebaseConfig);
    const db = firebase.database();

    // ✅ Listen for transcript changes
    db.ref("transcript").on("value", (snapshot) => {
      const text = snapshot.val();
      transcriptArea.value = text || "";
      transcriptArea.scrollTop = transcriptArea.scrollHeight;
    });

    // ✅ Download as PDF
    function downloadPDF() {
      const { jsPDF } = window.jspdf;
      const doc = new jsPDF();
      const content = transcriptArea.value;
      const lines = doc.splitTextToSize(content, 180);
      doc.text(lines, 10, 10);
      doc.save("lecture-transcript.pdf");
    }
  </script>
</body>
</html>
