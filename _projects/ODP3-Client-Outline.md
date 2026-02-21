<!--
Compile to PDF (example):
  pandoc O3_ClientOutline_example_submission.md -o O3_ClientOutline.pdf
-->


---
fontsize: 11pt
geometry: margin=1in
papersize: letter
pagestyle: empty
header-includes:
  - \pagenumbering{gobble}
---


# Your Project Title


**Team:** Spotted... then Stopped
**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape  


## Problem statement (most important)


New York vineyard owners are trying to maximize yield in their vineyards, but Spotted Lanternflies are infesting vines and contaminating harvests, leading to decreased yield.


What challenge currently makes obvious solutions difficult to implement?
Add enough detail to narrow down the scope to the part of the problem you want to focus on.


One of the most thought of solutions would be to shake the plant enough for the bugs to fall, but there is the concern that the grapes would be lost as well. Although insecticides are normally used to control pests, this is not the most desirable solution in this case as they are both expensive and require continuous use, thus not as useful in the long term. Additionally, one issue is the vast amount of land that needs to be protected. New York state hosts approximately 35,000 acres of vineyards, all of which may be exposed to lantern flies. Another challenge is that lanternflies killed while on the vines may fall into the harvester and get mixed into the produce, which cannot be filtered due to concerns for texture and flavor. A joint study conducted by Cornell and Penn State found that 60% of lantern flies on vines wound up in the harvest bins. Current health standards require the product to be rejected if even 1-2 adults are found in a sample of 1 kilogram.


## Impact
Give context for why solving this sub-problem addresses the client's user needs.
Reducing contamination during the harvesting process leads to less wasted product and maximizes yield.


## Proposed direction(s)
Our main idea is to have a machine attached to the front of the harvester that would get rid of the flies right before the grapes are collected. 


### Concept A (primary): <Spinning Brushes>


**What it is:** An attachment to the front of the vehicle that has rotating brushes aimed at only the vine. The brushes would be located on a rotating rod (almost like a car wash brush) so as to scrape the flies off the vine without disturbing the grapes too much.  
**How it would be used:**
- Attach rotating rods to the harvester at correct height
- Turn them on to spin
- Drive the harvester through to collect grapes
**Why it’s better than the status quo:** <2–3 bullets.>  
- Flies would be knocked off vines before reaching harvester
- Brushes below grapes to protect harvest
- Don’t need to worry about separating grapes vs flies
**End-of-semester proof-of-concept:** <what you can realistically build/test in MAE 2250.> A large, slowly spinning, brush attached to a rod.


### Concepts B, C, etc.


<Only include if you want the client to compare two directions. Keep short.>


## Key risks / unknowns


- <Damage to vines> — Could reduce yield in the long run if the vine is scraped: We could test the bristles on a vine and see how it's damaged.  
- <Knocking off grapes prematurely> — This could get rid of some of the harvest that we want: We could test to make sure to find the right height to direct the bristles at to avoid hitting grapes.
- <Gaps between brushes may leave some flies on vines> — This might leave some contamination still: We could test this by running a prototype on a model of the vine with attachments of similar grip strength, and seeing what is not removed.


## Questions for the client
Focus on questions they can answer from lived experience.
1. **<Can we get a blueprint/design for the harvesters used?>**  
   *Decision affected:* <Affects how the brush would connect to the harvester, and the design considerations that come with that.>
2. **<What is the average height/length of the vine?>**  
   *Decision affected:* <Affects the dimensions of the brushes needed.>
3. **<What is the durability of the vine?>**  
   *Decision affected:* <Affects the amount of force we can put on the vine and the material used for the bristles.>
4. **<Question 4 (optional)>**  
   *Decision affected:* <what choice this answer changes for your team.>


\newpage


# Optional page 2 — References and/or one figure


## References


- <https://wineamerica.org/wp-content/uploads/2025/05/2025-WineAmerica-Methodology-4-28-25-Final.pdf>
- <Source 2 (URL or citation)>


## Figure
test
<!-- ![<One-line caption. No full sentences.>](figures/<your_figure_filename>.png) -->
