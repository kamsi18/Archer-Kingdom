
# Archer Kingdom
The Longbow Oath

A story-driven medieval archery RPG that runs in the browser. Your name will be remembered.

Gameplay

Create a hero, join a company and carry a yew longbow through a seven-part campaign across five fictional kingdoms, managing survival resources while your choices shape the story.

Features
Character creation: name (default "Aren"), gender (man, woman, non-binary) and company
Campaign: six chapters plus an epilogue, with checkpoints
Survival stats: health, stamina, hunger, arrows, money, food and medkits
Story values: trust, affection, allies and standing with the kingdoms
Chance-based archery, a day counter and an event log
Progress saved in the browser, with continue and reset options
Companies
Grey Heron Company
March Wardens
Blackthorn Spears
Starting stats
Stat	Starting value
Health	82 / 82
Stamina	70
Hunger	82
Weapon	Yew longbow
Arrows	18
Money	18
Food / Medkits	3 / 1

# visit http://localhost:8000
Saving progress

Progress is saved to the browser's localStorage. Clearing site data, private browsing or switching browsers will remove or hide your save.

Project structure
index.html   # markup, styles (CSS) and logic (vanilla JS) in one file
Tech stack
HTML5, CSS3 and vanilla JavaScript
Browser localStorage for saves
Customising
Starting stats: edit the object returned by the fresh() function.
Companies: edit the options in the company selector.
Story and chapters: edit the chapter data in the script.
