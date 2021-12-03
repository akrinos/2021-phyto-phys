<!-- #region -->
# Session 3
## Common Phytoplankton Models & The Spring Bloom

<div class="panel panel-primary">
  <div class="panel-heading">
    <h3 class="panel-title">Papers to Read Before!</h3>
  </div>
  <div class="panel-body">
      A primer on phytoplankton modeling!<br>
      <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/riley1946.pdf">Riley 1946</a>: a classic model for phytoplankton ecology<br>
      <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/siegel2002.pdf">Siegel 2002</a>: evaluating Sverdrup's critical depth hypothesis & the North Atlantic spring bloom<br>
  </div>
</div>

## The Spring Bloom

The beautiful phenomenon of the North Atlantic spring bloom is a "greening" of the surface of the ocean that corresponds to rapid growth of phytoplankton as temperatures warm too match rising nutrient concentrations as winter stratification disappears. As noted by Siegel et al. (2002), this "greening" can move as quickly as 20 km/day.

### Sverdrup's Critical Depth Hypothesis

The defining equation for Sverdrup's critical depth hypothesis is:

$$
P(z) = \textrm{ primary production } = \alpha I(z) = \alpha I_0 e^{-Kz} = P_0 e^{-Kz} \\
R(z) = R_0
$$

Where $P(z)$ is a measure of primary productivity and $I(z)$ is a measure of irradiance at some depth. $\alpha$ is some slope that quantifies the linear dependence of primary productivity on irradiance, and $I_0$ is the irradiance (or photosynthetically active radiation, PAR) at the surface. $K$ is the "diffuse attenuation coefficient" of PAR, or in simple terms, how much PAR is reduced by the accumulation of overhead water with depth. $R(z)$ is the loss processes at a given depth $z$.

The reason this defines the critical depth hypothesis (CDH) is because the _critical depth_ is where the **integrated** rates of photosynthesis and respiration are equal. We know that we will have more production than respiration whenever $P(z) > R_0$ ("net production"). This defines the **compensation depth** ($Z_C = \frac{1}{K} \textrm{ln} \left( \frac{P_0}{R_0} \right)$). The _critical depth_, by contrast, happens whenever across all depths, we have balanced all of the effects of higher production at the surface and comparatively high respiration at depth ($Z_{CR}$).

$$
Z_{CR} = \frac{1}{KZ_{CR}}\left( 1-e^{-KZ_{CR}}\right) = \frac{R_0}{P_0} = \frac{I_C}{I_0}
$$

#### Sverdrup's assumptions

Sverdrup assumed a compensation depth $I_C = 0.6$ mol photons m$^{-2}$ day$^{-1}$. We know that culture experiments are different than the real deal, and based on real-world estimates, this assumption is probably six times too small.

### Community Composition Irradiance as a Metric

The tricky part about assessing Sverdrup's hypothesis is that our metrics are imperfect. The spring bloom progresses northward, which means that as it travel,s the irradiance at the surface will be different relative to the commmunity composition irradiance, which is where the respiration use equals the production help. Functionally in this paper, the critical depth was later taken as the depth of the mixed layer **when the bloom happens**. This is troublesome because _when the bloom happens_ is biased towards the local niche & temperature conditions...and because we don't always have a reliable mixed layer depth at the time that the bloom happens.

### The Sum Total from Siegel's Analysis

Siegel et al. found that there's a sharp division of the section of the North Atlantic basin that _does_ react the way that Sverdrup predicted - north of around 40 degrees of latitude - and the section of the North Atlantic that is south of this latitude and doesn't behave as Sverdrup expected. 

This is because the year-long warm water conditions south of 40N mean that nutrient limitation is a lot more important, which means that spring mixing is the real culprit for the bloom starting. Even though irradiance plays a role, it's not the real trigger for the bloom. There's too much light throughout the year for this to be the case!

<div class="panel panel-primary">
  <div class="panel-heading">
    <h3 class="panel-title">Siegel's Bottom Line</h3>
  </div>
  <div class="panel-body">
      According to Siegel, north of 40 degrees of latitude, Sverdrup's light-dominated critical depth prescribes the spring bloom, whereas the spring bloom starts in the south as soon as nutrients are entrained by mixing.
  </div>
</div>

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/siegel2002.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/siegel2002.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/siegel2002.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Phytoplankton Mathematical Modeling

Our main required reading of this session is a seminal work of distinguished biological oceanographer Dr. Gordon A. Riley. In order to connect to how important and lasting this work was to be for marine ecosystem modeling, you can check out this perspective from Thomas Anderson (2012):

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/anderson2012.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/anderson2012.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/anderson2012.pdf">Download PDF</a>.</p>
    </embed>
</object>

### Classical Models

Because much of this class will be focused on quantitative approaches to assessing phytoplankton physiology and community ecology, we'll need a discussion of a cousple of classical models that have applications far beyond the phytoplankton world. 

#### Lotka-Volterra

Classically known as the predator-prey model, Lotka-Volterra is applicable even to phytoplankton. Papers have been published just this year that leverage classical Lotka-Volterra dynamics to explain phytoplankton ecology. 
<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/hofmann2021.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/hofmann2021.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/hofmann2021.pdf">Download PDF</a>.</p>
    </embed>
</object>

[Github Link to PDF](https://github.com/akrinos/2021-phyto-phys/tree/main/_literature/session1/hofmann2021.pdf)

### Michaelis-Menten


### Monod

### Droop

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/sommer1990.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/sommer1990.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/sommer1990.pdf">Download PDF</a>.</p>
    </embed>
</object>

### Contemporary Challenges

### Trait-Based Modeling
#### Connection to Michaelis-Menten

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/fiksen2013.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/fiksen2013.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/fiksen2013.pdf">Download PDF</a>.</p>
    </embed>
</object>

<!-- #endregion -->
