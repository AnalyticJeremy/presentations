# Thesis Project Ideas
Ideas for my self-directed data science project

---

## Games
### Minecraft Auto-Miner (Computed Path)
 - Use world seed and game libraries to compute ore locations <!-- .element: class="fragment" data-fragment-index="1" -->
 - Compute best route to efficiently gather resources <!-- .element: class="fragment" data-fragment-index="1" -->
 - Automated player to follow computed path <!-- .element: class="fragment" data-fragment-index="1" -->
 - ... but this is just analytics, not ML <!-- .element: class="fragment" data-fragment-index="2" -->

---

## Games
### Minecraft Auto-Miner (AI)
 - Use AI to interpret players environment <!-- .element: class="fragment" data-fragment-index="1" -->
 - Apply probabilities to execute branch mining <!-- .element: class="fragment" data-fragment-index="1" -->
 - <span>... but there are others already working on this: [MineRL](https://minerl.io/)</span> <!-- .element: class="fragment" data-fragment-index="2" -->

---

## Games
### Clue
 - Automated player for the board game <!-- .element: class="fragment" data-fragment-index="1" -->
 - Compute probabilities based on cards held / seen <!-- .element: class="fragment" data-fragment-index="1" -->
 - <span>*REAL* challenge is AI to read cards and interpret game board</span> <!-- .element: class="fragment" data-fragment-index="2" -->

---

## Games
### Forza Horizon 5
 - Game has a feature that lets you log data in real-time
 - Could use ML to optimize care tunes
 - *or* could use data to optimize my skills as a player <!-- .element: class="fragment" data-fragment-index="1" -->
   - *e.g.* how much caffeine do I need for peak racing <!-- .element: class="fragment" data-fragment-index="1" -->

---

## Motorcycling
### Route Prediction
 - Use OpenStreetMap data and route recommending sites to identify good riding routes

---

## Photography
### Automated Organizer
  - Use AI to analyze my library of photos and find similar images
  - ... but others (like Google) have already solved this <!-- .element: class="fragment" data-fragment-index="1" -->

---

## Photography
### Style Analyzer
 - Use AI to evaluate and cluster the various "styles" that I have employed in my photos

---

## National Park Visitors
Can I build a model to provide fine-grained predictions of how busy a national park will be?

---

## National Park Visitors
 - NPS provides number of visitors per month
   <img src="https://www.nps.gov/yell/planyourvisit/images/2018_1.jpg?maxwidth=1200&maxheight=1200&autorotate=false" alt="average visitors by year" style="width: 45%" />
 - ... but I want to know which week of the month or day of the month or hour of the day is least crowded

---

## National Park Visitors
The variables used for prediction would be fairly simple
 - park
 - calendar dimensions (month, day of week, holidays)
 - weather

---

## National Park Visitors
However, NPS doesn't publish daily numbers so we don't have "ground truth" to use as a dependent variable

But there are multiple data sources that could be used as a proxy for number of visitors
 - social media posts
 - webcams at park entrances
 - air quality sensors

---

## National Park Visitors
There are limitations to all of these data sources, but can they be synthesized to create a dependent variable?

 - study correlations between all potential sources to make see which ones agree
 - aggregate each to a monthly level and study correclation with NPS published numbers
