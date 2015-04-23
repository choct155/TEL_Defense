---
title       : Does One Size Fit All?
subtitle    : An Analysis of Tax and Expenditure Limitations in Colorado
author      : Marvin Ward Jr.
job         : PhD Candidate, School of Public Affairs, American University
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: ["libraries/highcharts", "libraries/nvd3", "libraries/morris"]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &twocol

<style>
.title-slide {
  background-color: #23294A;
  font-color: #FFFFFF;
  background-image: url(./assets/img/CO_pic.png);
  background-repeat: no-repeat;
  background-position: 50% -30%;
  background-size: 100%;
}

.title-slide hgroup > h1{
  font-family: 'Oswald', sans-serif;
  color: #FFFFFF;
  font-color: #FFFFFF;
}

.title-slide hgroup > h2{
  font-family: 'Oswald', 'Calibri', sans-serif;
  color: #FFFFFF;
  font-color: #FFFFFF;
}

.title-slide hgroup > p{
  font-family: 'Oswald', 'Calibri', sans-serif;
  color: #FFFFFF;
}

slide:not(.segue) h2{
  color: #23294A;
}

table th {
  background: #23294A;
  color: #FFFFFF;
  text-transform: uppercase;
}

table thead {
  border-top: 1px solid #FFFFFF;
  border-bottom: 1px solid #FFFFFF;
}

table tr:nth-child(2n+1) {
  background: #FFFFFF;
}
</style>

## Thank You

*** =left width:40%

<span style='font-weight:bolder; font-size:110%'>I'd like to start by expressing my appreciation for the School of Public Affairs, Members of the Committee, friends, and family.  Most importantly, thanks to my wife for putting up with my incessant chatter about fiscal policy, high-dimensional estimators, and other narcolepsy-inducing topics.</span></br>
</br>
</br>
<span style='font-weight:bolder'>Full Disclosure</span>:  She vetoed a far more hilarious, and apparently objectionable, photo of us.

*** =right width:55%
<div style='text-align: center;'>
  <img width='600' src='./assets/img/angela_and_me2.png' />
</div>

---

## Plan of Attack

<span style='font-weight:bolder; font-size:150%'>&rarr; High-Level View</span></br>
<span style='font-weight:bolder; font-size:150%'>&rarr; Operating Context</span></br>
<span style='font-weight:bolder; font-size:150%'>&rarr; Space</span></br>
<span style='font-weight:bolder; font-size:150%'>&rarr; Why are TELs such a fixture?</span></br>
<span style='font-weight:bolder; font-size:150%'>&rarr; Q & A</span>

</br>
</br>
<span style='font-weight:bolder'>SPOILER ALERT:</span> This study does not test propositions about why TELs have become a fixture, which is only a motivating question.  It does, however, ask related questions about TEL impacts and when counties choose to opt out.

---

## Plan Status

<span style='color:red; font-size:150%; font-weight:bolder'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>High-Level View</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Operating Context</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Space</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Why are TELs such a fixture?</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Q & A</span>

<div style='text-align: center;'>
  <img width='600' src='./assets/img/TEL_bind_states_lab.png' />
</div>

---

## Tax and Expenditure Limitations

TELs provide a remarkably useful lens for viewing the intersection of rules and economic outcomes.  They are constraints, over and above the common set of rules that serve as a common denominator when we think about economic policy in the US.  Insofar as these rules vary, their impacts beg to be explored.  In much the same way as learning a second language teaches one more about one's first language, the exploration of this variance teaches us about what we have already implicitly accepted.

That was heavy. What exactly are we looking at again?
+ Do TELs successfully depress revenue?
+ Do TELs make counties change how they spend public funds?
+ How can local fiscal managers adapt?

---

## Punchline

|DOES THIS STUDY FIND THAT COTELs...|COTEL Intensity|Gallagher Ratio
|:-----------|---------------|---------------
|...increase fiscal clustering?|<span style='color:red; font-weight:bold'>NO</span>|<span style='color:green; font-weight:bold'>YES</span>
|...depress revenue yield?|<span style='color:green; font-weight:bold'>YES</span>|<span style='color:green; font-weight:bold'>YES</span>
|...depress economic capacity?|<span style='color:red; font-weight:bold'>NO</span>|<span style='color:red; font-weight:bold'>NO</span>
|...change expenditure behavior?|<span style='color:red; font-weight:bold'>NO*</span>|<span style='color:red; font-weight:bold'>NO</span>
|...increase chances of deBrucing success?**|<span style='color:red; font-weight:bold'>NO</span>|<span style='color:green; font-weight:bold'>YES</span>
</br>
*COTELs actually decrease the variation in expenditure choices within county type.
</br>
**Basic socioeconomic chacteristics are a far better predictor.
</br>

Note that this study uses a model ensemble approach.  Some of the negative findings are due to statistically insignificant results, <span style='font-weight:bolder'>while others are due to a high degree of conflict across models.</span>

---

## Hasn't the TEL Impact Thing Been Done?

Please tell me something new is being brought to the table...

+ Counties are far from identical, why pretend they are if we don't have to?
+ “[T]he first law of geography: everything is related to everything else but near things are more related than distant things.” (Tobler 1979)
+ Overlapping policies can interact in complex ways.
+ This study views individual models as observations (hence the model ensemble approach).

---

## How Do the Pieces Fit Together?

1. TELs impose artificial barriers in the fiscal matching process.
2. Revenue growth that lags expenditure need decreases the ability to satisfy constituent preferences.
3. Failing to serve constituents is unlikely to help make a jurisdiction attractive for siting purposes.

Effective strategies for local fiscal managers require good intel.  This study scratches the surface.

---

## TEL Literature Landscape

Most of the empirical work attempts to study TELs across states, and as such, focuses on statewide definitions of TELs. Obviously this masks local variation, but perhaps more interestingly, this choice in geographic scope encourages certain types of questions. 

+ What is the impact of TELs on revenue volatility ([St. Clair 2012](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2151690))? 
+ Do TELs constrain property taxes ([Dye & McGuire 1997](http://www.sciencedirect.com/science/article/pii/S0047272797000479))? 
+ Do TELs constrain growth in employment and wages ([Poterba & Rueben 1995](http://www.jstor.org/discover/10.2307/2117953?uid=3739256&uid=2&uid=4&sid=21102688756161))?
+ Does the impact of TELs on property revenue change during recessions (Mullins & Mikesell 2013)?

Evaluating the impact of TELs with a local lens begs the question, *are some jurisdictions affected differently than others*? While St. Clair did utilize local government data, the purpose was to show a general effect.  [Mullins (2004)](http://onlinelibrary.wiley.com/doi/10.1111/j.0275-1100.2004.00350.x/abstract?deniedAccessCustomisedMessage=&userIsAuthenticated=false), by contrast, is an important example of evaluating the *differential* impact of TELs as a function of socioeconomic starting conditions.

This study seeks to extend this approach by incorporating spatial and temporal dependency.

---

## In Case We Want to Get Into the Weeds...

<span style='font-size:70%'>&diams; Strong TELs have a cumulative depressive effect on revenue (Mikesell & Mullins 2008)</span></br>
<span style='font-size:70%'>&diams; TELs degrade educational labor supply (Figlio & Rueben 2001)</span></br>
<span style='font-size:70%'>&diams; TELs may lower student performance (Downes et al 1998; Downes & Figlio 1999)</span></br>
<span style='font-size:70%'>&diams; TELs increase reliance on non-tax revenue (Joyce & Mullins 1991;Eberts & Gronberg 1981)</span></br>
<span style='font-size:70%'>&diams; TELs increase reliance on state funding for local services (Sokolow 1998; Sokolow 2000; Shadbegian 2003)</span></br>
<span style='font-size:70%'>&diams; TELs are often motivated by distrust of officials and belief in rampant waste (Cutler et al 1999)</span></br>
<span style='font-size:70%'>&diams; Residents often resent service cuts due to TELs (Cutler et al 1999)</span></br>
<span style='font-size:70%'>&diams; States with higher property taxes are more likely to pass TELs (Alm & Skidmore 1999)</span></br>
<span style='font-size:70%'>&diams; TELs depress property tax revenue (Shadbegian 1998; Rown 2000; Dye & McGuire 1997)</span></br>
<span style='font-size:70%'>&diams; Offsetting the revenue loss from TELs is more difficult with more stringent TELs (Shadbegian 1999)</span></br>
<span style='font-size:70%'>&diams; The impact of TELs varies widely across jurisdictions (Bradbury et al 2001; Rown 2000; Mullins 2004)</span></br>
<span style='font-size:70%'>&diams; TELs depress local spending (Shadbegian 1998; Bails & Tieslau 2000; Feld & Matsusaka 2003)</span></br>
<span style='font-size:70%'>&diams; TELs reduce housing stock value by limiting the extent of educational service capitalization (Bradbury et al 2001)</span></br>

---

## Plan Status

<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>High-Level View</span></br>
<span style='color:red; font-weight:bolder; font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Operating Context</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Space</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Why are TELs such a fixture?</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Q & A</span>

<div style='text-align: center;'>
  <img width='980' src='./assets/img/colorado.png' />
</div>

---

## Why Colorado?

+ Variation, variation, variation
  + Widely regarded as having one of the most restrictive TEL regimes in the country
  + Policy overlap is a significant feature
  + "DeBrucing" is a double edged sword

<div style='text-align: center;'>
  <img width='700' src='./assets/img/CO_med_inc_cty_map.png' />
</div>

---

## TABOR *and Company*

While the Taxpayer's Bill of Rights (TABOR) gets the lion's share of attention in Colorado, it is but one component of a set of four overlapping policies.  In order of enactment:

1. <span style='font-weight:bolder'>General Statewide Limit on Property Tax Revenue (SLPTR):</span>  Local property tax revenues may not increase by more than 5.5% in a given year
2. <span style='font-weight:bolder'>Gallagher Amendment (GA):</span> Assessment rates for residential property are set statewide, calculated to keep historical ratios of residential and non-residential property tax revenue consistent (with some minor space for modification)
3. <span style='font-weight:bolder'>Taxpayer Bill of Rights (TABOR):</span> Limits annual growth in revenues to inflation plus a measure of growth (new construction for local governments and enrollment for school districts)
4. <span style='font-weight:bolder'>Amendment 23 (A23):</span> Mandates minimum increases in school funding and removes a portion of revenue from the TABOR base

Yes, the interactions create modeling difficulties, but they also happen to provide <span style='font-weight:bolder'>temporal variation</span> in the restrictiveness of the TEL structure.

---

## Timeline

<span style='font-weight:bold'>1913:</span> State-level property taxes limited to 15% annual growth.</br>
<span style='font-weight:bold'>1964:</span> Local property taxes limited to 5% annual growth (<span style='color:red; font-weight:bold'>SLPTR</span>).</br>
<span style='font-weight:bold'>1976:</span> SLPTR increased to 7%.</br>
<span style='font-weight:bold'>1977:</span> State General Fund Appropriations limited to 7%, with 4% reserve required (Kadlecek Amendment).</br>
<span style='font-weight:bold'>1979:</span> Kadlecek Amendment made permanent.</br>
<span style='font-weight:bold'>1982:</span> <span style='color:red; font-weight:bold'>Gallagher Amendment</span> passed to hold constant the statewide residential share of property tax burden.</br>
<span style='font-weight:bold'>1984:</span> Kadlecek limit increased to 7% plus costs of reappraisals.</br>
<span style='font-weight:bold'>1988:</span> SLPTR limit reduced to 5.5%.</br>
<span style='font-weight:bold'>1991:</span> State General Fund Appropriations limited to lesser of 5% of growth in state income or 6% over appropriations in the preceding year (Arveshoug-Bird Limit).</br>
<span style='font-weight:bold'>1992:</span> <span style='color:red; font-weight:bold'>TABOR</span> amendment passed.</br>

---

## And De-Brucing is ...?

Local governments reserve the right to waive the requirements of both TABOR and the SLPTR.  Over the 1993-2011 period, 48 counties chose to exempt themselves from one or both restrictions.  This has provided <span style='font-weight:bolder'>cross-sectional variation</span> ... and methodological complexity. 

<div style='text-align: center;'>
  <img width='700' src='./assets/img/TEL_intensity_2009.png' />
</div>

---

## "The" Douglas Bruce

<div style='text-align: center;'>
  <img width='400' src='./assets/img/DougBruce.png' />
</div>

---

## Operationalizing COTEL Impact

An ideal intensity score would capture three characteristics of any given county at time $t$:

1. The cumulative impact of statewide legislation over time;
2. The proliferation of locally derived exemptions from TABOR and SLPTR; and,
3. The local economic dynamics that may trigger a breach in the ceilings imposed by the aforementioned legislation.

This requires abstraction to model the implications of policy rather than the policy itself.  An estimate of the gap between revenue potential and the revenue yield permitted by the policies acting on county $i$ at time $t$ satisfies these requirements with a <span style='font-weight:bolder'>continuous</span> measure.

---

## Empirical Justification for the TABOR/SLPTR Measure

<div style='text-align: center;'>
  <img height='250' src='./assets/img/TABOR_vs_SLPTR.png' />
</div>

<div style='text-align: center;'>
  <img height='250' src='./assets/img/adams_cty_intensity.png' />
</div>

---


## Assessment to Sales Ratio

<div style='text-align: center;'>
  <img height='550' src='./assets/img/med_asmt_sales_ratio.png' />
</div>

---

## Modeling the Gallagher Amendment

Insofar as it is a limit based upon statewide characteristics, the Gallagher Amendment is a different animal altogether.  It is modeled as a separate variable.

<div style='text-align: center;'>
  <img width='900' src='./assets/img/gallagher_dist.png' />
</div>


To the extent that the residential share in a given county is higher than the statewide average, that county is constrained below its property tax revenue potential.

--- &twocol

## Plan Status

*** =left width:50%

</br>
</br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>High-Level View</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Operating Context</span></br>
<span style='color:red; font-weight:bolder; font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Space</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Why are TELs such a fixture?</span></br>
<span style='font-size:150%'>&rarr; </span><span style='font-weight:bolder; font-size:150%'>Q & A</span>

*** =right width:50%

<div style='text-align: center;'>
  <img width='450' src='./assets/img/Spacetime.png' />
</div>

---

## Spatial Considerations

Industrial bases and socioeconomic conditions do not abruptly shift out of respect for the county border.  Counties can and do share similarities with their neighbors.  Spatial autocorrelation is real.  Enter Local Indicators of Spatial Association (LISAs) ([Anselin 1995](http://onlinelibrary.wiley.com/doi/10.1111/j.1538-4632.1995.tb00338.x/abstract)):

#### Local Moran's $I_i$

<div>
$$I_i=\frac{\sum_j z_i w_{i,j} z_j}{\sum_i z_i^2}=\frac{\sum_j (y_i-\bar y)w_{i,j}(y_j-\bar y)}{\sum_i(y_i-\bar y)^2}$$
</div>

#### Getis & Ord's $G_i$

<div>
$$G_i(d)=\frac{\sum_j w_{i,j} (d) y_j - W_i \bar y(i)}{s(i)\{[(n-1) S_{1i} - W_i^2]/(n-2)\}^{(1/2)}},j \neq i$$
</div>

--- 

## Spatial Autocorrelation vs. Temporal Autocorrelation

Temporal autocorrelation is often discussed in terms of process memory.  The observation in time $t$ will exhibit a given relationship with the observation in time $t-1$ because the DGP carries the latent effect of that previous observation.  It "remembers" the last value or values, and behaves in a manner consistent with that knowledge.  

<div style='text-align: center;'>
  <img width='450' src='./assets/img/space_time_memory.png' />
</div>

Spatial autocorrelation, insofar as it incorporates information about observations in the local neighborhood, is basically doing the same thing.  The difference is that temporal autocorrelation reflects uni-directional memory, while spatial autocorrelation reflects multi-dimensional memory.  

---

## Unpacking Measures of Spatial Autocorrelation

Local Moran's I and Getis & Ord's G* are complementary measures, insofar as they measure two different types of clustering.  Local Moran's I highlights pockets of similarity and disimilarity while Getis & Ord's G* highlight pockets of high and low values.

<div style='text-align: center;'>
  <img height='220' src='./assets/img/Moran_colors.svg' />
</div>
<div style='text-align: center;'>
  <img height='220' src='./assets/img/GO_colors.svg' />
</div>
---

## What is the Local Neighborhood?

Defining the local neighborhood is somewhat analagous to defining the memory structure in an autoregressive process.

>"[W]hile there have been significant advances in the spatial econometrics literature in the last 20 years, the key issue involved from the very start (the specification of the W-matrix and the form of spatial spillovers more generally) remains largely unsolved." ([Harris & Kravtsova 2009](http://www.ub.edu/sea2009.com/Papers/100.pdf))

>"...what is the theoretical and empirical basis of assumptions about the spatial reach of externalities, and how can this be enhanced?" ([Fingleton 2003](http://irx.sagepub.com/content/26/2/197.abstract))

---

## Weight Matrices

<div style='text-align: center;'>
  <img height='230' src='./assets/img/w_def.svg' />
</div>
<div style='text-align: center;'>
  <img height='350' src='./assets/img/decay_curves.svg' />
</div>

---

## REVENUE

Do TELs <span style='font-weight:bolder'>Lead to Convergence in</span> Revenue Yield and Fiscal Capacity?
+ "Ratcheting" 
+ Capital Investment Capacity

Do TELs <span style='font-weight:bolder'>Depress</span> Revenue Yield and Fiscal Capacity?
+ Growth Ceiling
+ Capital Investment Capacity (again)

---

## How Can These Concepts Be Measured?

+ <span style='font-weight:bolder'>Revenue Yield</span> (`pcrev`) captures realized county resources for each constituent; and,
+ <span style='font-weight:bolder'>Fiscal Capacity</span> (`pcap`) captures potential county resources for each constitutent.

The latter utilizes per capita annual payroll instead of per capita income because payroll is spatially contained by the county in question.  Thus, there is a more direct tie to local fiscal operations (though it is not perfect).

---

## What is Contained in the Revenue Model Ensemble?

HYPOTHESIS|ESTIMATOR|DEPENDENT|REGRESSORS|COUNT
----------|---------|---------|----------|-----
Converge|Pooled OLS|`w_*`|`tel_vars + rev_regress + pcap`|20
Depress|Pooled OLS|`pcrev`|`tel_vars + rev_regress + pcap`|1
Depress|Pooled OLS|`pcap`|`tel_vars + rev_regress`|1
Depress|Repeated SLM|`pcrev`|`tel_vars + rev_regress + pcap`|19
Depress|Repeated SLM|`pcap`|`tel_vars + rev_regress`|19
Depress|Fixed Effect|`pcrev`|`tel_vars + rev_regress + pcap`|1
Depress|Fixed Effect|`pcap`|`tel_vars + rev_regress`|1

</br>
`tel_vars=[intensity_stock,prop_ratio]`</br>
`rev_regress=[gsp,lpop_growth,st_unempr,permit_rate,all_gov_rev,cty_rev_prop]`


---

## What is the Distribution of LISA Values?

<div style='text-align: center;'>
  <img width='750' src='./assets/img/cluster_wt_dist.png' />
</div>

--- &twocol

## Do TELs Increase Fiscal Convergence?

*** =left width:75%

<div style='text-align: center;'>
  <img width='700' src='./assets/img/converge_LISAs.png' />
</div>

*** =right width:25%

COTEL intensity has no discernable impact on fiscal convergence.  That is, it does not increase or decrease the level of spatial clustering in `pcrev` or `pcap`.  The Gallagher Ratio, by contrast, increases clustering in `pcrev` amongst lower revenue counties.

--- &twocol

## Do TELs Depress Revenue Yield (`pcrev`)?

*** =left width:70%

<div style='text-align: center;'>
  <img width='500' src='./assets/img/converge_slm_rev.png' />
</div>

*** =right width:30%

COTEL intensity is statistically significant and negative in almost every year, as is the Gallagher Ratio.  This indicates that COTELs are depressing revenues, as expected. The temporal trends likely reflect a cumulative burden over time. COTEL intensity, however, acts on fewer counties as time passes.

--- &twocol

## Do TELs Depress Economic Capacity (`pcap`)?

*** =left width:70%

<div style='text-align: center;'>
  <img width='500' src='./assets/img/converge_slm_econ.png' />
</div>

*** =right width:30%

Neither COTEL intensity nor the Gallagher Ratio exerted any reliable pressure on the economic capacity measure.  Given the length of the causal chain here, perhaps that is unsurprising.

--- &twocol

## But What About the Fixed Effect Models?

*** =left width:70%

<div style='text-align: center;'>
  <img width='500' src='./assets/img/converge_fe_panel.png' />
</div>

*** =right width:30%

Once county averages have been netted out, COTEL intensity still depresses revenue, but to a much lesser degree.  Further, it is now associated with increased economic capacity! The Gallagher Ratio has lost all relevance in both cases.

---

## EXPENDITURE

Do TELs force counties to change their pattern of expenditure?

Before that can be answered, how can we identify a county's pattern of expenditure and track it over time?
+ Group expenditure functions into large expenditure categories?
+ Focus on changes in a single expenditure function?
+ Regression decomposition?
+ This study uses typification.

--- &twocol

## Defining Fiscal Space

*** =left width:40%

Suppose each county in set $S={A,B,C}$ only has two expenditure functions: Public Safety and Infrastructure.  We can place the counties in space and determine that $B$ is closer to $A$ than $C$. This concept is scaleable to $n$ dimensions.

Note that there is one non-expenditure dimension in the fiscal space definition: the proportion of all expenditures from all governments in the county that is allocated to only the county government (`cty_exp_prop`).

*** =right width:60%

<div style='text-align: center;'>
  <img width='500' src='./assets/img/fisc_pos_concept.png' />
</div>

--- &twocol

## Defining County Types

*** =left width:40%

To let the data group themselves, $k$-means clustering has been employed.

<div style='text-align: center;'>
  <img width='400' src='./assets/img/kmeans_ideal.png' />
</div>

*** =right width:60%

<div style='text-align: center;'>
  <img width='500' src='./assets/img/fisc_pos1975_k5.png' />
</div>

---

## What is Contained in the Expenditure Model Ensemble?

HYPOTHESIS|ESTIMATOR|DEPENDENT|REGRESSORS|COUNT
----------|---------|---------|----------|-----
Cluster|Repeated SLM|`dist_clust`|`tel_vars + exp_regress + sl_exp_regress`|19
Cluster|LASSO|`dist_clust`|`tel_vars + exp_regress + sl_exp_regress + ind_vars + fisc_vars`|6
Cluster|Pooled OLS|`dist_clust`|`tel_vars + exp_regress`|3
Cluster|Fixed Effect (County)|`dist_clust`|`tel_vars + exp_regress`|3
Cluster|Fixed Effect (Two-Way)|`dist_clust`|`tel_vars + exp_regress`|3

</br>
`tel_vars=[intensity_stock,prop_ratio,intensity_stock*exp_total]`</br>
`exp_regress=[exp_total,pop_growth,pcintgov,pcrev,pcap]`</br>
`sl_exp_regress=[sl_exp_total,sl_pop_growth,sl_vac_rate]`</br>
`ind_vars=`industrial data from QCEW </br>
`fisc_vars=`additional fiscal variables from CO DLA

---

## What is the Distribution of Cluster Values?

<div style='text-align: center;'>
  <img width='800' src='./assets/img/ExpDiv_Dist_Distributions.png' />
</div>

--- &twocol

## Do TELs Change Expenditure Behavior?

*** =left width:25%

Positive movement in cluster distance indicates counties moving farther from their type. In this specification, most years see a negligible effect from COTELs, and in every year the effect is not statistically separable from zero.

*** =right width:75%

<div style='text-align: center;'>
  <img width='800' src='./assets/img/ExpDiv_SLM_by_year.png' />
</div>

--- &twocol

## Does LASSO Regression Provide Insight?

*** =left width:20%

The LASSO runs suggest that both COTEL intensity and the Gallagher Ratio increase expenditure shifts, but only modestly.

Other factors like government employment and demographic dynamics matter far more.

*** =right width:80%

<div style='text-align: center;'>
  <img width='850' src='./assets/img/ExpDiv_lasso_coef_by_dist.png' />
</div>

--- &twocol

## Can Panel Analysis Further Muddy the Waters?

*** =left width:55%

Repeated SLM suggested that COTELs have no effect. LASSO suggested they had a positive (albeit modest) effect.  <span style='font-weight:bolder'>Fixed effect panel analysis flies against the hypothesis completely, and suggests that COTELs are negatively associated with changes in expenditure patterns.</span>

Specifically, using three measures of distance:

+ The county fixed effect model yields ambiguous directions across models; and,
+ The two-way (county and year) fixed effect model yields negative effects across models.

<span style='font-weight:bolder'>A high level of sensitivity to the estimator reduces confidence in any single interpretation.</span>

*** =right width:40%

<div style='text-align: center;'>
  <img width='400' src='./assets/img/econ_as_observation.png' />
</div>

---

## Finally ... LOCAL CHOICE

Are some counties more likely to exempt themselves from TABOR and/or SLPTR than others, regardless of what is contained in the specific ballot initiative?

+ Socioeconomic dynamics not only vary the impact of COTELs, but also the desire to live under them.

How do individual ballot components impact the probability of a successful exemption ("deBrucing") vote?

+ Taking the baseline propensity to deBruce as a given, some initiatives are more likely to succeed than others.

This analysis is a classic two-stage estimator, with a twist on the first stage classifier.

--- &twocol

## Selection of a Classifier

*** =left width:70%

</br>
</br>
</br>
<div style='text-align: center;'>
  <img width='600' src='./assets/img/votes_pca_view.png' />
</div>

*** =right width:30%

This analysis uses over 500 variables from the USA Counties database to predict deBrucing vote outcomes. <span style='font-weight:bolder'>Not all classifiers are created equal, particularly in high-dimensional space.</span>

Support Vector Machines are quite flexible, featuring a projection capability that is able to simulate a linear decision boundary.  More importantly, SVM outperformed all other classifiers. 

---

## What is Contained in the Local Choice Model Ensemble?

HYPOTHESIS|ESTIMATOR|DEPENDENT|REGRESSORS|COUNT
----------|---------|---------|----------|-----
Socioeconomic|SVM|`pass`|`censtat_regress`|1
Ballot Design|Probit|`pass`|`tel_vars + prob_exmpt + cty_rev_prop`|1
Ballot Design|Logit|`pass`|`tel_vars + prob_exmpt + cty_rev_prop`|1
Ballot Design|OLS|`results`|`tel_vars + prob_exmpt + cty_rev_prop`|1

</br>
`tel_vars=[intensity_stock,prop_ratio]`</br>
`censtat_regress=`over 500 variables from USA Counties</br>
`ballot_regress=` operationalized ballot components</br>

---

## Prediction from Socioeconomic Factors

Keeping in mind that SVM was the best predictor, it returned the correct result 58.3% of the time.  <span style='font-weight:bolder'>This suggests that socioeconomic factors are not the dominant predictor of voting outcomes.</span>  However, they are an important predictor.


</br>
<div style='text-align: center;'>
  <img width='800' src='./assets/img/vote_probs.png' />
</div>

---

## What of Ballot Design?

Ballots were operationalized by splitting components into three groups: revenue source, expenditure target, scope of change.

<span style='font-weight:bolder'>Key Findings:</span>

+ Baseline propensity to exempt is the dominant positive factor for predicting a successful exemption vote.  Counties with higher proportions of revenue collection by county governments were also positive, but less so.  All other substantive predictors lower the probability of passage.
+ There are a number of components that voters apparently dislike:
  1. Administrative, Public Safety, and Infrastructure spending targets
  2. Open ended spending targets
  3. Property and Sales tax revenue sources
+ COTEL intensity was not strongly predictive across all models, but higher Gallagher Ratios were associated with higher likelihood of passage.

---

## Conclusion

In general, this study does not provide precise impacts.  Rather, the goal is agreement from different angles.  In some ways, this is likely to mute the effects of policy initiatives.  That being said, the study supports the following assertions:

1. COTELs matter, but measured effects are modest when space and socioeconomic disparities are incorporated.
2. Direct linkages (e.g. to revenue yield) are persistent, but longer linkages (e.g. to economic capacity) require additional work.
3. Expenditure side effects have not been shown to be meaningful, suggesting the need for more research into how the gap is filled.
4. Prediction of exemption (deBrucing) votes remains a difficult task, but socioeconomic characteristics and ballot design both matter.

---

## Questions [https://github.com/choct155/TEL_Defense](https://github.com/choct155/TEL_Defense)

</br>
<div style='text-align: center;'>
  <img width='400' src=http://www.codeinstitute.net/wp-content/uploads/2014/10/python-logo.png />
  <img hspace='80'/>
  <img width='200' src=http://cran.us.r-project.org/Rlogo.jpg />
</div>
</br>
</br>
<div style='text-align: center;'>
  <img width='300' src=http://www.cicad.oas.org/fortalecimiento_institucional/dtca/images/au.jpg />
  <img hspace='40'/>
  <img width='210' src=http://cfo.dc.gov/sites/default/files/dc/dcgov_logo.jpg />
  <img hspace='40'/>
  <img width='170' src=http://www.cbo.gov/sites/default/files/cbofiles/images/pubs-images/49xxx/49954-40th_Logo.png />
</div>
</br>
</br>
Yes, there were three different employers during this dissertation ... why do you ask?

