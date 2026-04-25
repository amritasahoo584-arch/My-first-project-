<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Yash 💖</title>

<style>
body {
    margin: 0;
    font-family: 'Comic Sans MS', cursive;
    text-align: center;
    background: linear-gradient(45deg, #ff9a9e, #a18cd1);
    color: white;
}

h1 {
    margin-top: 40px;
    font-size: 30px;
}

.cartoon {
    font-size: 80px;
    animation: bounce 2s infinite;
}

@keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-20px); }
}

button {
    padding: 12px 25px;
    margin: 10px;
    border: none;
    border-radius: 20px;
    font-size: 18px;
    cursor: pointer;
    background: white;
    color: #ff4d6d;
    transition: 0.3s;
}

button:hover {
    transform: scale(1.1);
}

#noBtn {
    position: absolute;
}

.message {
    display: none;
    font-size: 22px;
    margin-top: 20px;
}
</style>

</head>

<body>

<h1>Hey Yash 😘</h1>

<div class="cartoon">🐻💖🐻</div>
<p>Two cute teddies hugging just like us 🥺💞</p>

<h2>Do you miss me? 💕</h2>

<button onclick="showLove()">Yes 💖</button>
<button id="noBtn" onmouseover="moveButton()">No 😜</button>

<div class="message" id="loveMsg">
    <p>Yayyy 😍 I knew it!</p>
    <p>You are my favorite person in the whole world 💕</p>
    <p>I feel so lucky to have you 🥺</p>
    <p>I love you so much Yash 💖</p>

    <div class="cartoon">💋💞🤗</div>
    <p>Sending you lots of hugs and kisses 😘</p>
</div>

<script>
function showLove() {
    document.getElementById("loveMsg").style.display = "block";
}

function moveButton() {
    let x = Math.random() * window.innerWidth - 100;
    let y = Math.random() * window.innerHeight - 50;

    let btn = document.getElementById("noBtn");
    btn.style.left = x + "px";
    btn.style.top = y + "px";
}
</script>

</body>
</html>
