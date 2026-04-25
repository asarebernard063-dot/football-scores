# football-scores.header {
    background: #00ffcc;
    color: black;
    padding: 15px;
    font-size: 20px;
    font-weight: bold;
}<div class="header">
    ⚽ Live Scores App
</div>body {
    font-family: Arial;
    background: linear-gradient(135deg, #0b0f1a, #1c2333);
    color: white;
    text-align: center;
    margin: 0;
}

h1 {
    color: #00ffcc;
    padding: 20px;
}

.match {
    background: #222a3a;
    margin: 15px auto;
    padding: 15px;
    border-radius: 12px;
    width: 80%;
    max-width: 400px;
    box-shadow: 0px 0px 10px rgba(0,255,204,0.2);
}

.teams {
    font-size: 18px;
    font-weight: bold;
}

.score {
    font-size: 30px;
    margin: 10px 0;
    color: #00ffcc;
}.match {
    transition: 0.3s;
}

.match:hover {
    transform: scale(1.03);
}
<script>
setInterval(() => {
    document.querySelectorAll(".time")[0].innerText = "46' (Live)";
}, 5000);
</script>
.time {
    font-size: 14px;
    color: #aaa;
}
