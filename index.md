---
layout: default
title: WindBorne
---

# WindBorne

> Answers from Stephen Behunin. Click a section to expand it.

<details markdown="1">
<summary>Thing I Love</summary>

Write about the thing you love here. Normal markdown works — paragraphs, **bold**, `inline code`, lists, everything.

To include an image, upload it to the `images` folder of this repository, then reference it like this (delete this example until you have a real image):

![Description of the image](images/example.png)

</details>

<details markdown="1">
<summary>Semantle Strategy</summary>

Write your Semantle strategy here.

Code blocks get dark styling and syntax highlighting automatically:

```python
def next_guess(scores):
    # pick the word closest to the hottest region so far
    return max(candidates, key=lambda w: expected_gain(w, scores))
```

Tables work too:

| Guess | Similarity | Rank |
|---|---|---|
| ocean | 42.11 | — |
| water | 61.87 | 979 |

</details>

---

*Code for this site: [view the repository on GitHub](https://github.com/stephen-behunin/windborne_sb).*
