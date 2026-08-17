---
layout: default
title: WindBorne
---

# WindBorne

> Application answers from Stephen Behunin. Click a section to expand it.

<details markdown="1">
<summary>Semantle Strategy</summary>

**The game:** [semantle.com](https://semantle.com/) — find the secret word using similarity and ranking scores to guide your guesses.

**How to win:** Guess the secret word correctly. Simple.

### Mechanics

- Enter a guess in the bar.
- Guesses generate a raw similarity score:
  - It can be positive or negative; high positive is better.
  - The similarity score of a few milestone words is indicated — usually the closest, 10th closest, and 1000th closest.
- The top 1000 closest words generate a rank: 1/1000 is the 999th closest word, 999/1000 is the closest word besides the secret word. All other words generate hot, cold, warm, etc.

### Tips

- Hints can be used multiple times and will give a word closer to the secret word than your current closest guess.
- There is no limit on the number of guesses.
- If you guess a word you've already guessed, it will not count against the total number of guesses.
- Variations of words matter — "dead" and "deadly" may have wildly different similarity scores. Play around with variations when stuck.
- Making worse guesses can be just as valuable information as more correct ones.

### Strategy

1. Place a variety of guesses (3–10) to find a good starting point. If you hit something with a rank (the #/1000 appears) or above 15 in similarity, stop and move to the next step.
2. Find words that are adjacent to the highest-similarity word and chase those words in meaning groupings:
   - A meaning grouping is a set of related words — {bat, baseball, glove, pitcher}, {cat, toy, pet}, {run, exercise, train}.
   - Also try levels of specificity: ball → baseball → sport; player → team → league; iron → metal → material.
3. When stuck, find the most similar known words and try one of the following tactics:
   - **Move laterally.** Find words in the same meaning group that are farther than your previous guesses. If the most similar word is currently "pill" and "pharmacy" didn't improve the score, a good lateral move might be "hospital". If it's currently "flag", try something like "anthem" — related but a leap away.
   - **Switch meaning groups.** Is the similarity score of "bat" actually because of the small fuzzy creature, or the big wood stick? Find alternate meanings of your best guesses and explore those avenues.
   - **Take a hint**, especially if you're new at it. Playing a few rounds successfully helps build the correct skills.
4. If you can't make any progress, start over: make a totally random guess and deliberately stay away from meaning groups already guessed. There are generally many paths to the word that converge as the similarity ranking grows, but lateral moves and new attempts may avoid blocks previous attempts couldn't conquer.
5. Repeat this process of chasing meaning groups and getting unstuck until you win or close your browser in shame. Your choice.

</details>

<details markdown="1">
<summary>Something I Love</summary>

For something I love I'll take books; recently my favorite has been *Dungeon Crawler Carl*. If you haven't read the series and enjoy any sci-fi or fantasy I highly recommend them. I'm also only on the fifth book so don't spoil anything for me. Please. As for why I enjoy the books, I think they have a few key traits that make for a great story series.

First, the series is broad in its scope while having specific and memorable characters. The dungeon theme with different levels and complex backstory allows for the same characters to appear naturally in a nearly infinite number of situations while maintaining a coherent story line. This also allows a scale of action and stakes that other books can't achieve within a single limited world — but still allows for emotional investment in and familiarity with the main cast.

Second, the creativity is off the charts. A cat named Princess Donut the Queen Anne Chonk that shoots lasers out of its eyes through power-enhancing sunglasses while riding a velociraptor is not something I could come up with, ever. And this level of creativity is present in every single book without fail; the material is boundless and Dinniman (the author) does things with it I don't see coming seemingly every time. Creativity this insane couples with the open world to make every book unique and interesting.

Finally, the writing is funny while having deep themes and connections between the books. Chekhov's guns and callbacks are everywhere. Themes stay persistent and are reinforced in poignant moments amid the gore, hilarious imagery, and utter absurdity. Character arcs and story throughlines are both baked into the structure of the world and carefully used for real moments of connection with the characters. I think how funny the situations are allows the author to get away with absurdity and deep meaning in shockingly close proximity to each other — and in ways that wouldn't play with any other type of story.

So, in short, I love *Dungeon Crawler Carl*. I only have three and a half books left before I will have to join the legion of other fans waiting for the next installment. I may have to start rationing pages; the next one doesn't come out until late 2027 to early 2028. Goddammit Dinniman, write faster.

</details>

---

*Code for this site: [view the repository on GitHub](https://github.com/stephen-behunin/windborne_sb).*
