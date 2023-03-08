<h1
  id = "title";
  style="color:#4974a5; font-size:250%; text-align:left; border-bottom: 3px solid #4974a5;"
>
  A PROTEIN CLASSIFICATION PREDICTOR
</h1>

<h3
  id = "title";
  style="color:#207d06; font-size:220%; text-align:left; border-bottom: 3px solid #207d06;"
>
  Using Natural Language Processing (NLP) Machine Learning Methods on the Residue Sequences of Proteins.
</h3>

<h2
  id= "";
  style="color:#8fca6b; border-bottom: 1px solid #207d06;"
>
  Lighthouse Labs:
</h2>

<p
  id = "by-jamie-dormaar";
  style="
    font-family:JetBrains Mono;
    letter-spacing: 1px;
    color:#8fca6b;
    font-size:110%;
    text-align:left;";
>
  By Jamie Dormaar, February 16, 2023.
</p>

---

## Project/Goals

Mass Fingerprinting is a process by which protein identification is achieved by the analysis of the peptide and residue fragments from which its composed of. This remarkable and exciting technique promises to enrich widely ranging fields of research from Paleoproteomics to modern day health care and forensic analysis.

This was the inspiration for this project in which I imagined a nearly achievable rapid bio-classification system.

## Methods

Since the biological monomeric sequences of nucleic acids and amino acids are each their own type of language, Natural Language Processing (NLP) techniques seem the most appropriate choice.

When deciding the real-world processes I had to account for, I considered forensic investigators, who'd have access to gas chromatography mass spectrometers:

- a full chemical hydrolysis would quantize the protein's amino acid frequencies, not too unlike a bag of words. - which I simulated with count vectorization

I also considered:

- protease cleavage, for example in research facilities - and simulated this by using n-grams with a single character over lap, and a vectorizer accounting for the sequential order of the peptides.

## Images:

![](../images/residue_properties.png)

<!--
I can't remember how to size images in MD files.
-->
<img src="../images/residue_properties.png" alt=.missing?.png width="800"/>

### Target Variable Arrival Delay: Normalization

![](/W6MTP/Flight-Delays/Images/Arrival*delay_distn_df_usa*.png)

### Outlier management:

![](./Images/Arrival_delay_outliers_boxplot_df_usa_.png)

### XGBoost:

XGBoost hierarchy bar graph illustrating the importance of various parameters
![](./Images/xgb_params_importance.png)
![](./Images/xgboost_scatter.png)

## Challenges

## Future Goals
