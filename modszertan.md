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
		  <h5>Prediction methodology for the 2026 Hungarian election</h5> 

<br/>
<p><strong>Last updated: 26th December 2025.</strong>
<br/>
<p><strong>Input data</strong></p>

<p>The single-member constituency (OEVK) model is built from five components:</p>
<p>1. The results of the European Parliament (EP) elections projected onto single-member constituencies (OEVKs).</p>
<p>2. National party support based on data for all party voters (regularly published by Gábor Tóka on the <a href="https://www.facebook.com/valasztasi.kalauz">Vox Populi</a> Election Guide website.</p>
<p>3. The expected vote share of 13 re-running opposition candidates, based on the number of voters remaining in the redrawn districts.</p>
<p>4. A multiplier reflecting the expected regional shift in Fidesz’s vote share (between 0.98 and 1.02).</p>
<p>5. A multiplier applied to Fidesz’s "strong candidates" (between 1.01 and 1.05).</p>
<br/>

<p><strong>Detailed description</strong></p>
<p><strong>1. EP election results at the OEVK level</strong></p>
<p>At the end of 2024, due to the new district boundaries, EP election results must already be interpreted according to the new OEVK layout. Special thanks to Olivér Szabó for preparing and sharing the new district mapping with me.</p>
<p>The redistricting substantially affects Budapest and Pest County, but Fejér and Csongrád-Csanád counties were also redrawn. In the EP election results, votes cast for Fidesz are counted one-to-one, while votes cast for Tisza include both Tisza’s votes and those of other parties (excluding Mi Hazánk).</p>
<br/>
<p><strong>2. Expected national vote share</strong></p>
<p>Because data on committed party voters are based on assumed mobilization rates, they are uncertain with regard to the future. For this reason, the model is built on data for the total population, calculating national support from expected domestic vote totals.</p>
<p>The model currently assumes a uniform nationwide turnout of 72%, regardless of constituency. In addition, Fidesz is allocated 250,000 list votes, Tisza 50,000, and Mi Hazánk 10,000 from overseas postal voting (this affects only the calculation of list votes in the D’Hondt matrix).</p>
<p>Data on national vote totals will be updated periodically, and a new estimate will be published accordingly.</p>
<br/>
<p><strong>3. Re-running opposition MPs (12 Budapest seats and the Szeged 1 constituency)</strong></p>
<p>Re-running opposition candidates who previously won in single-member constituencies are expected to receive a significant number of votes in their individual districts. Since these constituencies have been redrawn, the model assumes that—depending on their local popularity and name recognition—these candidates can count on the support of 30–50% of their former voters who, under the new district boundaries, did not end up in another OEVK.</p>
<p>As a result, these opposition candidates may receive 10–30% of all votes cast in the constituency. The individual votes they receive are deducted from Tisza’s expected surplus (compensation) votes (which again affects the allocation of party list seats).</p>
<p><strong>Important:</strong> At present, this part of the model is uncertain, as there is no publicly available constituency-level polling from Budapest’s OEVKs. If such polling becomes available, it will be used to validate the model, and the percentage assumptions mentioned above may be revised.</p>
<br/>
<p><strong>4. Regional shift in Fidesz's support</strong></p>
<p>Based on lessons from previous elections, Fidesz's regional support changes continuously. Therefore, the relative change between the 2024 EP election and the 2022 parliamentary election has been incorporated as an additional multiplier applied to Fidesz's expected vote share.</p>
<p>The multipliers are as follows (for counties not listed, the multiplier is 1.00):</p>
<ul>
<li><strong>0.98 multiplier:</strong> Budapest, Pest, Győr-Moson-Sopron, and Hajdú-Bihar counties</li>
<li><strong>0.99 multiplier:</strong> Komárom-Esztergom and Bács-Kiskun counties</li>
<li><strong>1.01 multiplier:</strong> Nógrád and Szabolcs-Szatmár-Bereg counties</li>
<li><strong>1.02 multiplier:</strong> Baranya, Somogy, and Borsod-Abaúj Zemplén counties</li>
</ul>
<br/>
<p><strong>5. Multiplier for Fidesz’s "strong candidates"</strong></p>
<p>In previous elections, Fidesz received on average about 1% more votes in single-member constituencies than on the party list (roughly 25–28 thousand votes). However, this surplus was unevenly distributed. This part of the model estimates by what percentage an individual MP, who previously outperformed the Fidesz list, will exceed the party list's vote share.</p>
<p>The multipliers range between 1.01 and 1.05 and apply to a total of 30 re-running Fidesz MPs.</p>
<br/>
<p><strong>Additional notes</strong></p>
<p>The model may be further modified in the future, especially if more information becomes available about individual candidates or about the vote-transfer behavior of smaller parties (DK, Mi Hazánk, and MKKP), that is, the proportion in which their voters cast their candidate votes for Tisza or Fidesz candidates.</p>