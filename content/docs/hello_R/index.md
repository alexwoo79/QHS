---
title: ggplot2 demo
author: Norah Jones
date: '2021-05-21'
format: hugo-md
---


## Air Quality

<a href="#fig-airquality" class="quarto-xref">Figure 1</a> further explores the impact of temperature on ozone level.

<details class="code-fold">
<summary>Code</summary>

``` r
library(ggplot2)
ggplot(airquality, aes(Temp, Ozone)) + 
  geom_point() + 
  geom_smooth(method = "loess")
```

</details>
<img
src="index.markdown_strict_files/figure-markdown_strict/fig-airquality-1.png"
id="fig-airquality" alt="Figure 1: Temperature and ozone level." />
