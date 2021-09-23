# Session 2
## Nutrient Acquisition in the Phytoplankton: Carbon, Nitrogen, Phosphorus & Trace

<div class="panel panel-primary">
  <div class="panel-heading">
    <h3 class="panel-title">Papers to Read Before!</h3>
  </div>
  <div class="panel-body">
      An introduction to nutrient acquisition in the phytoplankton and the Redfield ratio.<br>
      <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider2002.pdf">Geider 2002</a>: Redfield revisited and the C:N:P ratio<br>
      <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/morel2008.pdf">Morel 2008</a>: the relationship between ocean trace metals and the phytoplankton
  </div>
</div>

Phytoplankton can produce their own food through photosynthesis. But this "food" is carbon, and they need other nutrients, namely nitrogen, phosphorus, silica, and calcium, in order to function. For many phytoplankton, they need these major nutrients in pretty large quantities. Other nutrients are needed in much smaller amounts, like iron. 

### Redfield Revisited (Geider & La Roche)

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider2002.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider2002.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider2002.pdf">Download PDF</a>.</p>
    </embed>
</object>

The Redfield Ratio is key to understanding how nutrients work in the ocean. But the way to define the Redfield Ratio can make a big difference in how we interpret it. The paper introduces three different vantage points: 

1. 105:15:1 (C:N:P) - the ratio of inorganic components of total inorganic C (Broecker & Peng 1982)
2. 106:16:1 (C:N:P) - average elemental composition of living marine organisms (Goldman 1979)
3. 106:16:1 (C:N:P) - the presence of inorganic nutrients in the deep sea (Redfield)

The three ratios are really similar, but they are measured really differently. If we wanted to revise the Redfield Ratio, as scientists have recently done, we would need to know which of the three was the way to measure it. For (1), we might just analyze some total inorganic C, whereas for (3), we would do something similar, but we would need to do a more exhaustive survey of the deep sea. For (2), we would be searching for a unifying definition across measured marine organisms.

As the paper indicates, a pretty popular paradigm is that the N:P ratio is what determines nitrogen or phosphorus limitation. When N:P is less than that magic ratio of 16, N limitation is at hand; greater and we have P-limitation. This is because an N:P ratio of bigger than 16 would indicate that excess N molecules are going unused because we don't have enough P molecules to pair them with.

The reason this concept is complicated is because individual phytoplankton show a lot of variability when it comes to their own N:P ratios. One suggestion that is brought up is that it has to do with the glacial maximum of an N:P ratio of 25:1. This would indicate a lot less overall importance/necessary abundance of phosphorus for the same biomass abundance. 

![Figure 1](_images/fig1_geider_2002.png)

* Panels A & B = nutrient-replete microalgal + cyanobacterial cultures
* Panels C & D = particulate matter
* Panels E & F = how nutrients are drawn down during phytoplankton groups

Even without any duress, N:P under nutrient-replete conditions varies from 5-19 mol N:mol P, which indicates that it may be quite different from 16. As shown in Fig 1B, 16 isn't even close to the most typical value. The average is closer to 7. 

#### Nutrient-limited conditions

Under nutrient-limited conditions, the story can be quite different

- **N limitation** - C:N increases (more biomass is making use of less of that scarce nitrogen) while N:P decreases (more phosphorus taken up per precious N)
- **P limitation** - C:P increases (more biomass per P) while N:P also increases

#### The Droop model: generalizing nutrient limitation

Using the Droop model, we can potentially generalize the concept of nutrient limitation. By abstracting out the limiting nutrient as its cellular quota $Q_L$, we can reframe the current growth rate, $\mu$, relative to what it might be at maximum, $\mu'$:

$$
\mu = \mu' \frac{Q_L - \min(Q_L)}{Q_L}
$$

The tricky part with N and P is that limitation of one nutrient affects quota of the other. This is what necessitates Terry et al. (1995)'s appraisal: "the transition between P-limited and N-limited growth occurs at the point where the cell contents of both N and P simultaneously limit growth rate" - the **critical ratio**.

<div class="panel panel-info">
  <div class="panel-heading">
    <h3 class="panel-title">Experimental concepts for Redfield Ratio</h3>
  </div>
  <div class="panel-body">
    Under nutrient-replete conditions, the C:N ratio tends to be closer to Redfield than N:P, which hovers much below 16.
  </div>
</div>





