html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>UNIVERSITY_PROJECTS // ARCHIVE</title>
  <style>
    /* Global Dark Y2K Background & Grid */
    body {
      background-color: #09090d;
      background-image: 
        linear-gradient(rgba(0, 255, 170, 0.06) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0, 255, 170, 0.06) 1px, transparent 1px);
      background-size: 25px 25px;
      color: #e2e8f0;
      font-family: 'Courier New', Courier, monospace;
      max-width: 750px;
      margin: 40px auto;
      padding: 20px;
    }

    /* Scrolling Retro Marquee */
    .marquee-box {
      background: #13131c;
      border: 1px solid #ff007f;
      color: #ff007f;
      padding: 6px;
      font-size: 13px;
      font-weight: bold;
      margin-bottom: 25px;
      box-shadow: 0 0 10px rgba(255, 0, 127, 0.3);
    }

    /* Classic Y2K Window Container */
    .window {
      background-color: #111118;
      border: 2px solid #00ffaa;
      box-shadow: 6px 6px 0px #ff007f;
      margin-bottom: 30px;
    }

    /* Window Top Title Bar */
    .title-bar {
      background: linear-gradient(90deg, #00ffaa, #0088ff);
      color: #09090d;
      font-weight: bold;
      padding: 6px 12px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 14px;
    }

    .window-controls {
      letter-spacing: 3px;
    }

    .window-body {
      padding: 20px;
    }

    /* Glowing Headings */
    h1 {
      color: #00ffaa;
      text-shadow: 0 0 8px rgba(0, 255, 170, 0.6);
      font-size: 26px;
      margin-top: 0;
      text-transform: uppercase;
    }

    h2 {
      color: #ff007f;
      font-size: 18px;
      border-bottom: 1px dashed #333;
      padding-bottom: 5px;
    }

    .status-badge {
      display: inline-block;
      background: #1f1f2e;
      border: 1px solid #00ffaa;
      color: #00ffaa;
      padding: 3px 8px;
      font-size: 12px;
      margin-bottom: 15px;
    }

    /* Retro 3D Pixel Button */
    a.y2k-btn {
      display: inline-block;
      background-color: #ff007f;
      color: #ffffff;
      font-weight: bold;
      text-decoration: none;
      padding: 10px 18px;
      border-top: 2px solid #ff77ba;
      border-left: 2px solid #ff77ba;
      border-right: 2px solid #800040;
      border-bottom: 2px solid #800040;
      margin-top: 10px;
      transition: 0.1s;
    }

    a.y2k-btn:hover {
      background-color: #00ffaa;
      color: #09090d;
      border-top: 2px solid #99ffdd;
      border-left: 2px solid #99ffdd;
      border-right: 2px solid #00774d;
      border-bottom: 2px solid #00774d;
      box-shadow: 0 0 12px rgba(0, 255, 170, 0.8);
    }

    footer {
      text-align: center;
      font-size: 12px;
      color: #666;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- Scrolling Status Ticker -->
  <div class="marquee-box">
    <marquee scrollamount="5">★ WELCOME TO MY UNIVERSITY ARCHIVE ★ STATUS: ONLINE ★ ALL SCHOOL REQUIREMENTS & SUBMISSIONS LOGGED BELOW ★</marquee>
  </div>

  <!-- Main Header Window -->
  <div class="window">
    <div class="title-bar">
      <span>C:\SYSTEM\PORTFOLIO.EXE</span>
      <span class="window-controls">[_][□][X]</span>
    </div>
    <div class="window-body">
      <div class="status-badge">● SYSTEM READY // 2026</div>
      <h1>University Projects</h1>
      <p>> Initializing log of all university projects and coursework for school requirements.</p>
    </div>
  </div>

  <!-- Assignment Window -->
  <div class="window">
    <div class="title-bar">
      <span>FILE_01 // ASSIGNMENT_SUBMISSION.PDF</span>
      <span class="window-controls">[_][□][X]</span>
    </div>
    <div class="window-body">
      <h2>[01] Semester Assignment</h2>
      <p><strong>Course:</strong> Enter Subject Code / Name<br>
      <strong>Format:</strong> Portable Document Format (.PDF)</p>
      <p>Click the button below to view or download the assignment document directly.</p>
      
      <!-- REPLACE 'your-file.pdf' WITH YOUR EXACT PDF FILENAME -->
      <a href="your-file.pdf" target="_blank" class="y2k-btn">► OPEN_FILE.PDF</a>
    </div>
  </div>

  <footer>
    [ HOSTED ON GITHUB PAGES // DESIGNED IN HTML & CSS ]
  </footer>

</body>
</html>
