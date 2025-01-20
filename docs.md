---
layout: page
title: Doc Links Page!
permalink: /docs/
---
<html>
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .tab-container {
      display: flex;
      flex-direction: column;
      height: 100vh;
    }

    .tab-buttons {
      display: flex;
      justify-content: center;
      background-color: black;
      border-bottom: 3px solid darkgoldenrod; /* Divider line below tabs */
    }

    .tab-buttons button {
      flex: 1;
      padding: 15px;
      cursor: pointer;
      border: none;
      background-color: black;
      color: white;
      font-family: 'Baskerville', serif;
      font-size: 18px;
      transition: background-color 0.3s, color 0.3s, border 0.3s;
    }

    .tab-buttons button:hover {
      background-color: #333;
    }

    .tab-buttons button.active {
      background-color: #555;
      border-bottom: none; /* Ensure it blends with the divider line */
    }

    .tab-content {
      flex: 1;
      display: none;
    }

    .tab-content.active {
      display: block;
      height: calc(100% - 50px); /* Adjust based on button height */
    }

    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }
  </style>
</head>
<body>

<div class="tab-container">
  <div class="tab-buttons">
    <button onclick="showTab(0)" class="active">Meeting Summaries</button>
    <button onclick="showTab(1)">Club Guidelines</button>
    <button onclick="showTab(2)">SDP Modules</button>
    <button onclick="showTab(3)">Hackduino Guidelines</button>
    <button onclick="showTab(4)">Yantriki Guidelines</button>
    <button onclick="showTab(5)">Lab Inventory</button>
    <button onclick="showTab(6)">To-doist</button>
  </div>

  <div class="tab-content active">
    <iframe src="https://docs.google.com/document/d/1IP8ntQfjf5QhLxVHLX2f76-wcX--_r24x8cBOfMTBSQ/edit?tab=t.0#heading=h.kzz2hlswxrll" style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
  <div class="tab-content>
    <iframe src="https://docs.google.com/document/d/16IzmOx266--G4dGWAzTwblzJgr2ASmREdiw0WKHgAqY/edit?tab=t.0#heading=h.myfgyqr040oy" style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
  <div class="tab-content">
    <iframe src="https://docs.google.com/document/d/12XnCsKrZ1XnY6fS6iFndkvgZssCmXPWr8yVO1A_RVHM/edit?tab=t.0#heading=h.srafljr37n5i"
    style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
  <div class="tab-content">
    <iframe src="https://docs.google.com/document/d/1D6vZ4q5jypiS-5LfYHhKUBnX50paK6y0wyNN8pNl9HI/edit?tab=t.0#heading=h.4y31ne2jj87c"
    style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
  <div class="tab-content">
    <iframe src="https://docs.google.com/document/d/1IUk8XK8VQmLMeajj_DgWqLyulv6rckkcjCU6ixvjJdU/edit?tab=t.0#heading=h.evpa5r3szb9y"
    style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
  <div class="tab-content">
    <iframe src="https://docs.google.com/spreadsheets/d/1pfoBKhvMqNE7sys6W8qDnDz4f3RJmZvBNbLKhKVbRPM/edit?gid=0#gid=0"
    style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
  <div class="tab-content">
    <iframe src="https://app.todoist.com/app/project/rtc-and-robotics-lab-2312927392"
    style="width: 100%; height: 100%; border: none;"></iframe>
  </div>
</div>
<script>
  function showTab(index) {
    const tabs = document.querySelectorAll('.tab-content');
    const buttons = document.querySelectorAll('.tab-buttons button');

    tabs.forEach((tab, i) => {
      tab.classList.toggle('active', i === index);
    });

    buttons.forEach((button, i) => {
      button.classList.toggle('active', i === index);
    });
  }
</script>

</body>
</html>
