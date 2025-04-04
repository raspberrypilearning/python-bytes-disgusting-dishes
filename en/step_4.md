<h2 class="c-project-heading--task">Add an apostrophe</h2>
--- task ---
Make your story use a word with an apostrophe, like “it’s” or “don’t”.
--- /task ---

<h2 class="c-project-heading--explainer">Using apostrophes in speech</h2>

When your text includes an apostrophe `'`{:.language-python}, like in the word `"don’t"` or `"it’s"`, you should use **double quotes** around your whole message.

For example:

<div class="c-project-code">
--- code ---
---
language: python
filename: example.py
line_numbers: false
---
print("It's time to go!")
--- /code ---
</div>

If you use single quotes for both the message and the apostrophe, Python gets confused.

Now let’s add a line to your story with an apostrophe:

<div class="c-project-code">
--- code ---
---
language: python
filename: story.py
line_numbers: true
line_number_start: 4
line_highlights: 4
---
print("One kid shouted, That's not my broccoli! 🤢")
--- /code ---
</div>

<div class="c-project-output">
One kid shouted, That's not my broccoli! 🤢
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

Try using a different reaction and emoji! Some ideas:  
- "That’s disgusting! 🤮"  
- "Eww, what's that? 👃"  
- "It's coming for us... run 🏃💨"

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If you see an error like *SyntaxError: invalid syntax*, check that:
- You used double quotes around the whole sentence: `"That's weird"`{:.language-python}
- You didn’t accidentally use single quotes and an apostrophe, like `'That's bad'`{:.language-python} (this breaks your code)

</div>
