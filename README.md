<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>How Well Do You Know Me? ❤️</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="card">
<h1>❤️ How Well Do You Know Me? ❤️</h1>
<p class="subtitle">Answer these few questions honestly 😊</p>

<form onsubmit="event.preventDefault();showResult();">

<label>1. Which of these describes me the best?</label>
<select required><option>Kind & Caring</option><option>Funny & Cheerful</option><option>Confident & Strong</option><option>Calm & Thoughtful</option></select>

<label>2. What do you think makes me happiest?</label>
<select required><option>Spending time with loved ones</option><option>Achieving my goals</option><option>Travelling</option><option>Listening to music</option></select>

<label>3. What would I choose for a perfect day?</label>
<select required><option>Movie & Dinner</option><option>Long Drive</option><option>Coffee & Conversations</option><option>Beach Trip</option></select>

<label>4. Which emoji do you want to give me?</label>
<select required><option>❤️Love</option><option>😘 Kiss</option><option>🤬 Hate</option><option>😎 Cool</option></select>

<label>5. How well do you think you know me?</label>
<select required><option>A little</option><option>Fairly well</option><option>Very well</option><option>Better than most</option><option>Better than anyone ❤️</option></select>

<label>6. Is there anything you've always wanted to tell me?</label>
<textarea rows="5" placeholder="Write anything you'd like..."></textarea>

<div class="final">
<h3>Ready to see your result? ❤️</h3>
<button type="submit">❤️ Yes, Show My Result</button>
<button type="button" class="secondary" onclick="alert('Thank you ❤️')">No, Maybe Later</button>
</div>

</form>

<div id="resultBox">
<h2>💖 Your Result 💖</h2>
<h1 id="stars"></h1>
<h3 id="msg"></h3>
<p>📸 If you enjoyed this quiz, please take a screenshot of this result and send it to me. ❤️</p>
<button onclick="window.print()">📸 Save / Screenshot</button>
</div>

</div>
<script src="script.js"></script>
</body>
</html>
