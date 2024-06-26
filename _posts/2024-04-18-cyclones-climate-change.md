---
layout: post
title: "Extratropical cyclones and climate change"
subtitle: "What insights can we get from CMIP6's projections?"
full-width: false

#thumbnail-img: /assets/img/cyclones_climatology/den_ext_cycs.png
thumbnail-img: /assets/img/teste_cycden.gif
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
#tags: [test]
#comments: true
#mathjax: true
---
<div align="justify">
Extratropical cyclones play a critical role in distributing heat, moisture, and momentum across different regions of the planet. They are the main atmospheric systems driving weather patterns between the subtropics and high latitudes. For people living in these areas, the experienced changes in temperature, humidity, and weather conditions like rain, snow, wind gusts, and coastal storm surges are frequently influenced, directly or indirectly, by the passage of extratropical cyclones and their associated fronts. Therefore, it is natural to ask some questions:
</div><p></p>

* Will climate change impact these systems' frequency and current distribution? <br>
* If so, at what magnitude can we expect these changes to occur?
<p></p>

![Track densities SH](/assets/img/teste_cycden.gif){: width="900"}

<div style="text-align: justify"><i>
<sub>The animation above shows the current monthly climatological mean of the track density (number of cyclone tracks per 5° spherical cap per month) for the Southern Hemisphere.
It is very interesting how the distribution of tracks evolves into a distinct ring-like pattern around Antarctica during summer.
</sub>
</i></div><p></p>


<div align="justify">
In this research, which is part of my Ph.D. dissertation, we aim to provide some insights into these questions. By applying an automatic method for tracking extratropical cyclones across the Southern Hemisphere and using data from a ensemble of CMIP6 models and the ERA5 reanalysis, we show that there is a significant projection of a migration of the cyclones tracks towards higher latitudes in both winter and summer seasons (Fig. 1a,b), but this change is more clear and robust for the summer (Fig. 1c).
</div><p></p>

![Cyclone density](/assets/img/cyclones_climatology/den_cycs_zonalmean.png)
<sub>**Figure 1.** *(a,b) CMIP6's projected changes for track density under SSP5-8.5 scenario and (c) the zonal means of the track density for present (HIST) and future (SSP5-8.5) climate in winter (solid lines) and summer (dashed lines) seasons. Black stippling indicates statistically significant changes at the 95% confidence level.*</sub>

<div align="justify">
However, the behavior and intensity of extratropical cyclones exhibit significant variability, making it essential to evaluate how these different groups of cyclones respond to climate change. This study uses the relative vorticity at 850 hPa as a metric of cyclone intensity and suggests that moderate and strong cyclones are the ones that most contribute to the reduction in track density over the subtropical and mid-latitude regions in the SH (Fig. 2b,c,e,f). Additionally, an significant increase in the frequency of extreme cyclones (98th percentile) around Antarctica is also expected (Fig. 2d,g).
</div><p></p>

![Density by intensity](/assets/img/cyclones_climatology/trackdensity_byintensity.png)
<sub>**Figure 2.** *CMIP6's projected changes for track density by intensity category for (a,b,c,d) winter and (d,e,f,g) summer. Black stippling indicates statistically significant changes at the 95% confidence level.*</sub>

Many other results and discussions can be found in my dissertation and will soon be published as a paper.

<!-- ![Cyclone density](/assets/img/cyclones_climatology/changes2_percentiles.png)
**Figure 3.** *CMIP6's projected changes for (a) maximum relative vorticity (s⁻¹) and (b) maximum precipitation rate (mm.6hr⁻¹) throughout the cyclones lifecycle. The changes are showed in terms of percentiles. Horizontal dotted line indicates the zeroline.* -->

<br>
<div style="display: flex; justify-content: center; align-items: center;">
    <div style="flex-grow: 1; height:1px; background:black;"></div>
    <section style="margin: 0 15px; display: flex; align-items: center; justify-content: space-between;">
        <div style="width: 10px; height: 10px; background: #000000; border-radius: 50%; margin: 0 5px;"></div>
        <div style="width: 10px; height: 10px; background: #000000; border-radius: 50%; margin: 0 5px;"></div>
        <div style="width: 10px; height: 10px; background: #000000; border-radius: 50%; margin: 0 5px;"></div>
    </section>
    <div style="flex-grow: 1; height:1px; background:black;"></div>
</div>

### *Related publications*
**Souza, M. R.**, Piva, E. D., Nascimento, E. L., Gan, M. A., Anabor, V., Gozzo, L. F. Southern Hemisphere extratropical cyclones in a warming climate: climatology, characteristics and future changes. _International Journal of Climatology (in preparation)_. 2024.

**Souza, M. R.** "Extratropical cyclones and associated precipitation in Southern Hemisphere: present and future climate." Ph.D. diss., Federal University of Santa Maria, 2023. [https://repositorio.ufsm.br/handle/1/31129](https://repositorio.ufsm.br/handle/1/31129)

Reboita, M. S., Rocha, R. P., **Souza, M. R.**, and Llopart, M. Extratropical cyclones
over the southwestern South Atlantic Ocean: HadGEM2‐ES and RegCM4
projections. _International Journal of Climatology_, v. 38, p. 2866-287, 2018. [DOI: https://doi.org/10.1002/joc.5468](https://doi.org/10.1002/joc.5468)

Reboita, M. S., **Souza, M. R.**, and Rocha, R. P. Extratropical cyclones over southwestern Atlantic Ocean: present and future climates projected by RegCM4. _In: EGU General Assembly, 2017, Viena_. EGU General Assembly, 2017.

<!--
{: .box-success}
This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/tables/etc.<br/>I also encourage you to look at the [code that created this post](https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/_posts/2020-02-28-sample-markdown.md) to learn some more advanced tips about using markdown in Beautiful Jekyll.



**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

You can use [MathJax](https://www.mathjax.org/) to write LaTeX expressions. For example:
When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

-->
