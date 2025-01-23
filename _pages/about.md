---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Rupak Kumar Das, and I am a Ph.D. student at the College of Information Sciences and Technology at Pennsylvania State University. I am currently a trainee in the NRT LINDIV graduate traineeship program.

My research interests lie in Natural Language Processing, Machine Learning, and social media analysis. I have always been fascinated by the power of language and its ability to connect people from different backgrounds and cultures. As a graduate student, I have had the opportunity to delve deeper into these fields, and I am excited about the potential for my work to impact society positively.

I completed my Master's (2022) in Computer Science from the University of Minnesota Duluth (UMD) and my Bachelor's (2015) in Electronics and Communication Engineering at Khulna University of Engineering and Technology (KUET).

Previously, I worked as a Technology Division Specialist for Robi Axiata Limited (2017-2020) and a Former Solution Engineer at Huawei Technology Bangladesh Ltd. (2015-2017) in the Sales and Solutions Department.



## News

- **Short paper got accepted in IEEE Healthcom 2024** (September 2024)
- **[Book chapter got accepted in Springer](https://link.springer.com/chapter/10.1007/978-3-031-61290-9_10)** (August 2024)
- **[Accepted to the Linguistic Diversity, Penn State fellowship program](https://ist.psu.edu/about/news/lindiv%20fellowships)** (June 2024)
- **[Joined Bangladesh Student Association](https://sites.psu.edu/bsapsu/), Penn State, as Web coordinator** (June 2024)
- **[Journal article accepted in "Sensors"](https://www.mdpi.com/1424-8220/24/8/2509)** (April 2024)
- **Received Certificate of Appreciation from Bangladesh Student Association, PSU** (April 2024)
- **Joined [Graduate Student Association of IST](https://sites.psu.edu/istgrad/about/), Penn State, as an IT officer** (Aug 2023)
- **Passed Qualifying Exam** (May 2023)
- **Joined Penn State as a Ph.D. student in Informatics** (Aug 2022)
- **Graduated (MS in Computer Science) from the University of Minnesota Duluth** (July 2022)
- **Received the "Outstanding Teaching Assistant Award" from the Department of Computer Science, University of Minnesota-Duluth** (May 2022)
- **Joined Robi Axiata Limited as a Specialist** (June 2017)
- **Joined Huawei Technology Bangladesh Limited as a Solution Engineer** (Dec 2015)
- **Graduated (BSc in ECE) from Khulna University of Engineering and Technology** (June 2015)

<<<<<<< HEAD
=======


## Chat with Me

<div id="chat-container">
  <div id="chatbox"></div>
  <input type="text" id="user-input" placeholder="Type your question here..." />
  <button id="send-button">Send</button>
</div>

<script>
  const chatbox = document.getElementById("chatbox");
  const userInput = document.getElementById("user-input");
  const sendButton = document.getElementById("send-button");

  sendButton.addEventListener("click", async () => {
    const userMessage = userInput.value.trim();
    if (userMessage) {
      appendMessage("You", userMessage);
      userInput.value = "";

      // Simulated bot response for now (replace with API call later)
      appendMessage("Bot", "Let me think... (this will be replaced by real responses)");
    }
  });

  function appendMessage(sender, message) {
    const msgDiv = document.createElement("div");
    msgDiv.textContent = `${sender}: ${message}`;
    chatbox.appendChild(msgDiv);
    chatbox.scrollTop = chatbox.scrollHeight;
  }
</script>

<style>
  #chat-container {
    width: 100%;
    max-width: 400px;
    margin: 20px auto;
    padding: 15px;
    border: 1px solid #ccc;
    border-radius: 10px;
    background-color: #f9f9f9;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  }
  #chatbox {
    height: 300px;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    overflow-y: auto;
    background-color: #fff;
    margin-bottom: 10px;
  }
  #user-input {
    width: calc(100% - 60px);
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin-right: 5px;
  }
  #send-button {
    width: 50px;
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  #send-button:hover {
    background-color: #0056b3;
  }
</style>
>>>>>>> d9a44115029b49662c8cc80b900f23052e25188e
