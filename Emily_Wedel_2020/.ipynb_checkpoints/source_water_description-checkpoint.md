# Source water use of trees and grasses using a PCA approach

**Name:** Emily Wedel<br>
**Semester:** Spring 2020 <br>
**Project Area:** Stable Isotope Ecology

This python script compares the source water use of grass and tree samples inferred from the stable isotopes of water using a PCA approach. In addition, this script compares source water use between trees with their aboveground biomass repeatedly removed and uncut control trees. I used data from a 2 year study investigating how repeated cutting affects the water use of the resprouting tree *Colophospermum mopane* (mopane or turpentine tree) in lowveld savanna.

## Questions <br>
1. Do trees uptake water from deeper sources than grasses?
2. How does repeated cutting alter the source water use of trees?

## Background and Rationale <br>
Plants tend to obtain water from the surface layer (top 30cm of soil) when water is available. Trees often have deeper functional roots than grasses and can access deeper water when water is limiting (CITE). In Southern Africa, *C. mopane* is a dominant deep-rooted tree that resprouts after disturbance. In addition to differences in source water between mopane and grasses, this script tests if repeated cutting of mopane causes a shift in water use to deeper soil layers to reduce competition with grasses. 

The stable isotopes of water ($\delta {^1}{^8}{O}$ and $\delta D$) can be used as a natural tracer to understand the source water use of plants (shallow vs. deep soil water). Typically, stable isotope mixing models are used to determine source water use. However, this method relies on all isotope samples falling within sampled end members. Often trees take up water from deeper sources than the soil depth sampled. The PCA approach is gaining popoularity in stable isotope analysis to distinguish differences in source water use when end members are missing or haven't been sampled (Holdo & Nippert 2015, Holdo et al. 2018). The purpose of this approach is to collapse $\delta {^1}{^8}{O}$ and $\delta D$ isotopic values into a single axis to infer depth of water uptake.

## Outcomes <br>
1. Single isotope scatterplots to visualize how soil $\delta {^1}{^8}{O}$ and $\delta D$ vary with soil depth.

2. Double isotope scatterplot to visualize how soil, grass, and tree samples align with the meteoric water line.

3. PCA to collapse $\delta {^1}{^8}{O}$ and $\delta D$ into one axis to infer differences in source water  using a single variable (eg PC1).

4. Use PC1 as the response variable to test for differences in source water between trees and grasses and cut and uncut trees using regression and ANOVA.

<br>

## Sketch of the Process
<img src="sketch.png" width="800" />