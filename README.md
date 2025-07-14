# Motivation-
Motivation <!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Site de Motivation Mentalité 93</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #ff7e5f, #feb47b);
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    padding: 20px;
    text-align: center;
  }
  h1 {
    font-size: 2.8em;
    margin-bottom: 0.5em;
  }
  #citation {
    font-size: 1.8em;
    font-style: italic;
    margin: 40px 20px;
    min-height: 80px;
  }
  button {
    background-color: #fff;
    border: none;
    border-radius: 30px;
    padding: 15px 30px;
    font-size: 1.2em;
    color: #ff7e5f;
    cursor: pointer;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    transition: background-color 0.3s ease;
  }
  button:hover {
    background-color: #ffb399;
  }
</style>
</head>
<body>
  <h1>Bienvenue sur Mentalité 93</h1>
  <div id="citation">Clique sur le bouton pour une citation de motivation !</div>
  <button onclick="changerCitation()">Nouvelle citation</button>

  <script>
    const citations = [
      "Le succès appartient à ceux qui osent.",
      "N’abandonne jamais tes rêves, ils sont la clé de ton avenir.",
      "Chaque jour est une nouvelle opportunité pour avancer.",
      "La motivation te fait démarrer, la discipline te fait continuer.",
      "Crois en toi, et tout deviendra possible.",
      "Transforme tes blessures en sagesse.",
      "Le seul endroit où le succès vient avant le travail, c’est dans le dictionnaire.",
      "La peur est temporaire, le regret est éternel.",
      "Ta mentalité détermine ta réalité."
    ];

    function changerCitation() {
      const index = Math.floor(Math.random() * citations.length);
      document.getElementById('citation').textContent = citations[index];
    }
  </script>
</body>
</html>

