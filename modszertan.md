---
layout: page
title: Módszertan
permalink: /modszertan
---
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-45281172-4');
</script>
<h1 class="page-title">{{ page.title | escape }}</h1>
    
<div class="section">
    <div class="row">
          <div class="col s12">
		  <h5>Prediction model used for the 2024 EP and local elections</h5> 

<br/>
<h6><strong>Summary</strong></h6>
<br/>

<p>The model is based on the total expected vote share of each party calculated by Gábor Tóka's polling averages. Detailed summary of the current national polling averages are available on the <a href="https://www.facebook.com/valasztasi.kalauz">Vox Populi  Facebook page</a>.</p>
<p>The current model uses Medián's polling data that was gathered between 26-30 April 2024. This polling data is used to calculate the vote share of each party by settlement type. The detailed article on this polling data is available (to HVG360 subscribers) <a href="https://hvg.hu/360/20240508_hvg-median-magyar-peter-tisza-orban-viktor-fidesz-ellenzek-dobrev-klara">in this article</a>.</p>
<p>The current model does not expect any substantial changes in the turnout by settlement type meaning that the expected number of votes and relative vote shares by settlement type is not changed in the calculation.</p>
<br/>
<p>Vote share multipliers by parties (strongest and weakest settlement types by parties):</p>
<ul>
<li><strong>Fidesz:</strong> 0.75 (Budapest) - 1.2 (Villages)</li>
<li><strong>MSZP-DK-Párbeszéd:</strong> 0.75 (Villages) - 1.3 (Budapest)</li>
<li><strong>Tisza Párt:</strong> 0.8 (Villages) - 1.15 (County seats and major cities)</li>
<li><strong>Mi Hazánk:</strong> 0.7 (Budapest) - 1.1 (Villages)</li>
</ul>

<br/>
<p>The model does not calculate any additional mobilization by any parties as there is not enough data to count for that.</p>
<p>The model assumes 5 percentage point uplfit to LMP's Budapest Assembly list and a 4 percentage point to the Párbeszéd-DK-MSZP's joint Budapest Assembly list due to their strong candidates in the Lord Mayor race (this assumption is supported by Medián's latest Budapest-based polling conducted between 17-22 May).</p>

<br/>
<h6><strong>Election of the Lord Mayor of Budapest</strong></h6>
<br/>
<p>After Alexandra Szentkirályi withdrew from the race, the model assumes the following voting behavior based on what voters choose on the Budapest Assembly ballot:</p>
<ul>
<li><strong>Fidesz:</strong> Vitézy 98% - Karácsony 2%</li>
<li><strong>MSZP-DK-Párbeszéd:</strong>Vitézy 2% - Karácsony 98%</li>
<li><strong>Tisza Párt:</strong>Vitézy 37% - Karácsony 63%</li>
<li><strong>Momentum:</strong>Vitézy 15% - Karácsony 85%</li>
<li><strong>LMP:</strong>Vitézy 90% - Karácsony 10%</li>
<li><strong>MKKP:</strong>Vitézy 25% - Karácsony 75%</li>
</ul>

<p>Note that there was only one public polling published on the secondary preferences of voters (and the polling only covered Tisza Párt in detail), there is a lot of uncertainty about this prediction.</p>


    