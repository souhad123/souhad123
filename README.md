##  👋 Hey, I'm CHENOUF Zahra Souhad



<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Animation texte</title>
<style>
body {
font-family: Arial, sans-serif;
font-size: 1.2em;
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
}
#animated-text {
color: #333;
font-weight: bold;
}
</style>
</head>
<body>
<div id="animated-text"></div>

<script>
const phrases = [
"🎓 Computer Science Student",
"💻 Full-stack developer with interests in DevOps",
"📊 Passionate about data science and the challenges of artificial intelligence",
"🚀 Seeking a Master’s program and a work-study opportunity to deepen my expertise"
];

let index = 0;
const textElement = document.getElementById('animated-text');

function showNextPhrase() {
textElement.textContent = phrases[index];
index = (index + 1) % phrases.length; // Recommence après la dernière phrase
}

// Affiche une nouvelle phrase toutes les 3 secondes
showNextPhrase(); // Affiche immédiatement la première phrase
setInterval(showNextPhrase, 3000);
</script>
</body>
</html>




<!--
**souhad123/souhad123** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
