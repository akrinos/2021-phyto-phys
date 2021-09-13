# Session 1
## Photosynthesis and Light Harvesting

<div class="panel panel-primary">
  <div class="panel-heading">
    <h3 class="panel-title">Papers to Read Before!</h3>
  </div>
  <div class="panel-body">
      An exploration of the light harvesting that characterizes the phytoplankton.<br>
      <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/masuda2021.pdf">Masuda 2021</a><br>
      <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider1987.pdf">Geider 1987</a>
  </div>
</div>

It seemed appropriate to begin a class on marine phytoplankton with what makes phytoplankton distinct from other planktonic organisms: the ability to use light to make new biomass.

Because this is such a complex topic, and so intricately tied to the physics of light, this first session has two papers that are more technical than the breakdown we anticipate in future sessions. We'll start class with a more structured introduction to light acquisition in the phytoplankton.

### Background: photosynthesis and light

The use of light energy is what makes phytoplankton _phytoplankton_. Phytoplankton use light in the range from 400-700 nm wavelength, all made possible by chlorophyll $\alpha$ bound to proteins. 

**Photosystem II** is the first reaction center in photosyntehsis, in which the energy from light is leveraged to make oxygen via extracting electrons from the water required for photsynthesis to happen. The water from which electrons are stripped is used to promote electrons to a higher energy level, one of the core concepts behind photosynthesis. Photosystem II uses the photons at the wavelength 680 nm (but can adapt to use higher-energy photons). 

**Photosystem I** receives electrons from photosystem II, and uses those photons of lower energy equivalence (closer to 700 nM at the lower-energy range of the total energy intenrval of photosynthesis).  The electron ends up promoted to a higher energy level in order to reduce NADP+. The reduced form of NADP+ is NADPH. Any light energy that _isn't_ involved in this water->NADPH pipeline is used to pump protons out of the stroma/cytosol (eukaryotes/prokaryotes, respectively) and into the lumen space inside the thylakoid.

From a modeler's perspective, we mostly care about the arithmetic consequences of all of these exchanges. Namely, we have the equation:

$$
9 \textrm{ photons} + 2\textrm{H}_2 \textrm{O} + 2 \textrm{NADP}^+  + 12 \textrm{H}^+ \rightarrow 2 [\textrm{NADPH +H}^+] + ^*O_2 + 12^o \textrm{H}^+
$$

And we can in general write many other equations that describe and predict the process of photosynthesis. It's important to understand how phytoplankton are shaped by light availability because this has been a key aspect of their evolution. In the global oceans, we know that light is attenuated quite exponentially based on absorption by the water itself and by scattering from the particles that are present in the water (the latter of which is known as Raman scattering). Light limitation can occur dramatically and rapidly when particles are physically entrained deep in the water column, or where phytoplankton are found below at deep chlorophyll maxima and dense particle blooms are found above. 

Maximum growth rate can depend heavily on photosynthetic potential and can also be enormously genotype-specific. What's more, photoacclimation - the generation of damaging products by photosystem II limiting the rate at which photosynthesis can occur, even when light is very readily available and the cell is growing happily - can make relationships between light and growth less straightforward.

### Paper One: Masuda 2021

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/masuda2021.pdf" type="application/pdf" width="850px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/masuda2021.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/masuda2021.pdf">Download PDF</a>.</p>
    </embed>
</object>


### Paper Two: Geider 1987

_Light and Temperature Dependence of the Carbon to Chlorophyll a Ratio in Microalgae and Cyanobacteria: Implications for Physiology and Growth of Phytoplankton_

This is our quantitative paper for the week. This paper has over 600 citations, almost all of which have to do with modeling or description of aquatic photosynthesis. 

<div class="panel panel-info">
  <div class="panel-heading">
    <h3 class="panel-title">Important Concepts</h3>
  </div>
  <div class="panel-body">
    The carbon:chlorophyll ratio (&theta;) is the essential indicator of microalgal photosynthesis and depends on (1) temperature and (2) photon flux, or how quickly packets of light are reaching each chlorophyll molecule and how warm it is in the ambient environment. <br>
    At low temperatures, the carbon:chlorophyll ratio is higher. This happens irrespective of species/taxonomic group, and indicates that more photosynthetic effort as measured by chlorophyll is required per biomass unit when light is scarce.
  </div>
</div>

One of Geider's objectives was to figure out a good value to use for the carbon to chlorophyll ratio at a given photon flux density (_I_). Geider's finding was that a single value can't adequately represent the range of $\theta$ that is observed, even when photons are constant and the only thing that changes is temperature. More recent research also suggests that the photon flux, in addition to changing the chlorophyll to carbon ratio, may also be involved in deciding the behavior of mixotrophs (e.g. [Ghyoot et al. 2017](https://2021-phyto-phys.readthedocs.io/en/latest/_static/ghyoot2017.pdf)). Under high photon flux density, the photoacclimation state of a mixotroph that's being limited by nutrients rather than light could be wonky, because it isn't actively photosynthesizing. But it turns out that even so, the mixotroph might be shuffling regenerated nutrients from the food it's eating to support its own internal photosynthesis. 

Another cool tidbit from a recent external paper is that even when photon flux density changes rapidly under mixing conditions, the chlorophyll to carbon ratio might be remarkably constant ([Brown et al. 2021](https://2021-phyto-phys.readthedocs.io/en/latest/_static/brown2021.pdf)).

#### Some initial discussion questions

- To what extent do you think the sweepingly general findings of the author are due to the species under consideration?
- How can mixotrophy impact the conclusions the author reached?
- What are some ways you might model these relationships?

<object data="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider1987.pdf" type="application/pdf" width="850px" height="700px">
    <embed src="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider1987.pdf">
        <p>Alternatively, download the PDF to view it: <a href="https://2021-phyto-phys.readthedocs.io/en/latest/_static/geider1987.pdf">Download PDF</a>.</p>
    </embed>
</object>
