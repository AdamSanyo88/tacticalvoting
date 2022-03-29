---
layout: page
title: Forecasting methodology
permalink: /modszertan
---

<h1 class="page-title">{{ page.title | escape }}</h1>
    
<div class="section">
    <div class="row">
          <div class="col s12">
		  <h5>Forecasting methodology for the 2022 general elections</h5> 

<br/>
<h6><strong>Summary</strong></h6>
<br/>

<p>The model calculates the national support of the united opposition and Fidesz from the projections of Gábor Tóka. Details of the current national support data are available on the <a href="https://www.facebook.com/valasztasi.kalauz">Vox Populi Facebook page</a>.</p>
<p>The model weights the results of the last three national elections (2018 parliamentary, 2019 EP, and 2019 local elections) to determine whether the joint opposition and Fidesz performed better or worse than the national average in the given constituency.</p>
<p>For example, the opposition in the Pest 1 (Érd and its surroundings) constituency outperformed the national average by 11%, so the opposition in this constituency is expected to perform 11% better than the national average in 2022.</p>
<p>In addition, the model also uses the constituency-level results of the Hungarian Two-Tailed Dog Party (MKKP) and the Our Homeland Movement (Mi Hazánk) from the 2019 EP elections to account for votes cast on these candidates.</p>
<p>The data for the three elections are weighted in the model as follows:</p>
<ul>
<li>2018 Parliamentary election: 55%</li>
<li>2019 European Parliament election: 30%</li>
<li>2019 local election: 15%</li>
</ul>
<br/>
<p>For MKKP and Our Homeland, only the data for the 2019 EP elections are used in the model. In the case of MKKP, the model assumes tactical voting of 20%-50% for the opposition candidate (50% in Budapest and close districts, 40% in cities with county rights, and 20-30% in other districts). In the case of Mi Hazánk, the model assumes tactical voting of 30% for the opposition candidate in the areas where Jobbik is running, and only 10% for other candidates.</p>

<p>The model gives 42 Fidesz candidates running again an additional 1-5% extra votes (i.e. the candidate is expected to outperform Fidesz on the list by this ammount), because these candidates did better than Fidesz on the party list in the 2014 and 2018 elections. The same modifier is not used for the strong opposition candidates (who won their seats in 2014 or 2018).</p>

<p>From January 2022, the model uses two additional modifiers to adjust Fidesz the expected vote share of Fidesz. These are the county type and constituency type.</strong></p>

<ul>
<li>Budapest: 0.97x multiplier for Fidesz</li>
<li>County seats: 0.98x multiplier</li>
<li>County seats mixed with other towns: 1.00x multiplier</li>
<li>Mixed constituencies (mid-size towns with dozens of villages): 1.04x multiplier</li>
<li>Clearly rural constituencies (one mid-size town with lots of villages): 1.06x multiplier</li>
</ul>
<br/>
<p>For the counties, the following modifiers are applied to the Fidesz vote share, ranging from 0.97 to 1.05:</p>
<ul>
<li>0.97x multiplier: Békés, Csongrád-Csanád, Pest, Komárom-Esztergom counties</li>
<li>1.02x multiplier: Zala county</li>
<li>1.03x multiplier: Heves, Nógrád, Tolna county counties</li>
<li>1.04x multiplier : Szabolcs-Szatmár-Bereg county</li>
<li>1.05x multiplier: Borsod-Abaúj-Zemplén county</li>
</ul>

<br/>
<p><strong>The following multipliers may differ depending on the constituency-level polling data (if there is available data).</strong>. The current model is based on the detailed report published by  <a href="https://hvg.hu/360/20211229_Median_Az_emberek_ketharmada_Orban_maradasara_szamit">Medián in December 2021</a>, and the survey with a larger sample size published in March 2021.</p>


<br/>
<p>The model will be improved with the following extra details as the elections approach:</p>
<ul>
<li>Demographic data (and their influence on voting behavior) by constituency</li>
<li>Constituency-level polling data</li>
</ul>


    