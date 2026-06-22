---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Sample slides
#### PlaceHolderName
#### Universiti Malaysia Perlis
#### [placeholder@email.com](mailto:placeholder@email.com)

<!-- __AUDIO_INTRO_DO_NOT_TOUCH__ -->

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### PartLength: Machine Comparison
**Analysis at P=100, T=303:**

- **p-value:** 0.0000
- **Significant (α=0.05):** Yes

There is a statistically significant difference in PartLength between the machines.


Using dataset `X008..3.`
:::

::: {.column width='50%'}
<!-- Placeholder for related visual or plot -->
![](media/pics/sample.png)
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### Statistical Analysis: PartLength
**Conditions:** $P=300, T=373$

- **p-value:** 9.2773e-49
- **Significant (α=0.05):** Yes

**Conclusion:**
At these specific settings, there is a statistically significant difference in `PartLength` between Machine 1 and Machine 2.
:::

::: {.column width='50%'}
![](media/pics/sample.png)
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### Comparative Analysis: PartLength
**Conditions:** $P=100, T=303$

- **Exact p-value:** 2.7687e-43
- **Significant (α=0.05):** Yes

**Conclusion:**
At $P=100$ and $T=303$, there is a statistically significant difference in the length produced by Machine 1 vs Machine 2.
:::

::: {.column width='50%'}
![](media/pics/sample.png)
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### Machine 1: Resistance Analysis
**ANOVA Results (PartResistance):**

- **Pr(>F) for Pressure:** 0.0000
- **Is Pressure Significant?:** Yes

**Observations:**
Resistance is compared against the USL of 10. Lower values are preferred. 

Using dataset `X008..3.`
:::

::: {.column width='50%'}
<iframe data-src='media/plots/m1_res_press.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
---

:::: {.columns}
::: {.column width='50%'}
### Machine 1: Temperature Impact
**ANOVA Results (PartResistance):**

- **Pr(>F) for Temperature:** 0.4964
- **Is Temperature Significant?:** No

**Analysis:**
The resistance is evaluated against a USL of 10. We assess if varying the temperature significantly alters the product resistance.

Using dataset `X008..3.`
:::

::: {.column width='50%'}
<iframe data-src='media/plots/m1_res_temp.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::
