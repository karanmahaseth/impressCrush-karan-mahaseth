<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proposal 💕</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #ffd6e0;
      text-align: center;
      padding-top: 100px;
    }
    img {
      width: 120px;
      margin: 20px 0;
    }
    .buttons {
      margin-top: 20px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      margin: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      background-color: #ff6f91;
      color: white;
      transition: 0.3s;
    }
    button:hover {
      background-color: #ff3e68;
    }
    #noBtn {
      position: relative;
    }
  </style>
</head>
<body>

  <h2 id="message">Will you be mine forever? 🥰</h2>
  <img id="gif" src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif" alt="cute">
  
  <div class="buttons">
    <button id="yesBtn">Yes 💖</button>
    <button id="noBtn">No 😢</button>
  </div>

  <script>
    const message = document.getElementById("message");
    const gif = document.getElementById("gif");
    const noBtn = document.getElementById("noBtn");
    const yesBtn = document.getElementById("yesBtn");

    let noClicks = 0;

    const responses = [
      "Please think again! 🙄",
      "Itni jaldi mat bolo na 😢",
      "Baby man jao na! Kitna bhav khaogi 😭",
      "Bht glt baat hai yaar 😤",
      "Ab toh haan bol do 🥺"
    ];

    noBtn.addEventListener("click", () => {
      if (noClicks < responses.length) {
        message.textContent = responses[noClicks];
        noClicks++;
      } else {
        // Make the "No" button run away 😂
        noBtn.style.position = "absolute";
        noBtn.style.top = Math.random() * window.innerHeight + "px";
        noBtn.style.left = Math.random() * window.innerWidth + "px";
      }
    });

    yesBtn.addEventListener("click", () => {
      message.textContent = "Yay! I knew you'd say YES 💍🥳";
      gif.src = "https://media.giphy.com/media/5GoVLqeAOo6PK/giphy.gif";
      noBtn.style.display = "none";
      yesBtn.style.display = "none";
    });
  </script>

</body>
</html>
