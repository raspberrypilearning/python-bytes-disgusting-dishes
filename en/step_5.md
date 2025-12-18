<h2 class="c-project-heading--task">Finish the recipe and add a warning</h2>

--- task ---

Print the last steps of your recipe and a final warning message using double quotes.

--- /task ---

<h2 class="c-project-heading--explainer">Set the scene</h2>

Your recipe is almost complete! Now add the final steps so the chef knows how to finish the dish.

Then add a warning message at the end — it's so disgusting that only zombies should eat it!  
This message uses an apostrophe in the word <code>Don't</code>, so you’ll need to use double quotes <code>" "</code> around the string.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 13
line_highlights: 13-16
---

print('3. Stir in the eyeballs until they stare back at you.')
print('4. Drizzle with slime and serve cold. ❄️')
print()
print("💀 WARNING: Don't eat this unless you're a zombie!")

--- /code ---
</div>

<div class="c-project-output">
<pre>🤢 Welcome to the DISGUSTING DISHES cookbook! 🤮

🧠 Ingredients:
 - 1 cup of toenail clippings 🦶
 - 2 rotten eggs 🥚
 - A handful of belly button fluff 🤏
 - 3 eyeballs 👁️👁️👁️
 - Green slime to taste 🧪

🧪 Instructions:
1. Mix the toenails and eggs in a dirty sock.
2. Sprinkle in the belly button fluff.
3. Stir in the eyeballs until they stare back at you.
4. Drizzle with slime and serve cold. ❄️

💀 WARNING: Don't eat this unless you're a zombie!</pre>
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

You can use single quotes <code>' '</code> for most strings, but if your text includes an apostrophe like <code>Don't</code>, you’ll need double quotes <code>" "</code> instead.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- Did you use double quotes around the warning message?<br />
- Each step should still be printed on a new line<br />
- Use <code>print()</code> for every message

</div>

<div class="c-project-callout c-project-callout--tip">

### Feedback

This is a beta projects, which means it is brand new and not widely available. If you've tested this project on your own or with your club, let us know what you think.

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
  Give feedback
</a>
</div>
