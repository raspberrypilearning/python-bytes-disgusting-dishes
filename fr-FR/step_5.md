<h2 class="c-project-heading--task">Terminer la recette et ajouter un avertissement</h2>

--- task ---

Affiche les dernières étapes de ta recette et un message d'avertissement final entre guillemets.

--- /task ---

<h2 class="c-project-heading--explainer">Planter le décor</h2>

Ta recette est presque terminée ! Ajoute maintenant les étapes finales pour que le/la chef·fe sache comment terminer le plat.

Ajoute ensuite un message d'avertissement à la fin : c'est tellement dégoûtant que seuls les zombies devraient en manger !  
Ce message utilise une apostrophe dans le mot <code>Ne</code>, tu devras donc utiliser des guillemets doubles <code>" "</code> autour de la chaîne.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 13
line_highlights: 13-16
---

print('3. Incorporez les globes oculaires jusqu'à ce qu'ils vous fixent du regard.')
print('4. Arrosez de slime et servez froid. ❄️')
print()
print("💀 ATTENTION : ne mangez pas ça à moins que vous soyez un zombie !")

--- /code ---
</div>

<div class="c-project-output">
<pre>🤢 Bienvenue dans le livre de recettes PLATS DÉGOÛTANTS ! 🤮

🧠 Ingrédients :

- 1 tasse d'ongles d'orteils 🦶
- 2 œufs pourris 🥚
- Une poignée de peluches de nombril 🤏
- 3 globes oculaires 👁️👁️👁️
- Slime vert à déguster 🧪

🧪 Instructions :

1. Mélangez les ongles d'orteils et les œufs dans une chaussette sale.
2. Saupoudrez de peluches de nombril.
3. Incorporez les globes oculaires jusqu'à ce qu'ils vous fixent du regard.
4. Arrosez de slime et servez froid. ❄️

💀 ATTENTION : ne mangez pas ça à moins d'être un zombie !</pre>

</div>

<div class="c-project-callout c-project-callout--tip">

### Astuce

Tu peux utiliser des guillemets simples <code>' '</code> pour la plupart des chaînes, mais si ton texte inclut une apostrophe comme <code>N'</code>, tu auras besoin de guillemets doubles <code>" "</code> à la place.

</div>

<div class="c-project-callout c-project-callout--debug">

### Déboguer

- As-tu utilisé des guillemets autour du message d'avertissement ?<br />
- Chaque étape doit toujours être imprimée sur une nouvelle ligne<br />
- Utilise <code>print()</code> pour chaque message

</div>

<div class="c-project-callout c-project-callout--tip">

### Avis

Il s'agit d'un projet bêta, ce qui signifie qu'il est tout nouveau et pas encore largement disponible. Si tu as testé ce projet individuellement ou avec ton club, n'hésite pas à nous faire part de ton avis.

<a href="https://form.raspberrypi.org/4874054?tfa_6933=python-bytes-disgusting-dishes" style="
display: inline-block;
padding: 10px 20px;
border: 2px solid black;
border-radius: 999px;
font-weight: bold;
font-size: 16px;
background-color: white;
color: black;
text-align: center;
text-decoration: none;
transition: background-color 0.2s;
" onmouseover="this.style.backgroundColor='#f0f0f0';" onmouseout="this.style.backgroundColor='white';">
Donner ton avis </a>

</div>

***

Ce projet a été traduit par des bénévoles:

Jonathan Vannieuwkerke

Michel Arnols

Grâce aux bénévoles, nous pouvons donner aux gens du monde entier la chance d'apprendre dans leur propre langue. Vous pouvez nous aider à atteindre plus de personnes en vous portant volontaire pour la traduction - plus d'informations sur [rpf.io/translate](https://rpf.io/translate).
