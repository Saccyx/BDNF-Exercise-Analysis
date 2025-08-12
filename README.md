# Acute Aerobic and Anaerobic Exercise Effects on Circulating BDNF in Healthy Adults  

## Overview  
This repository contains the data, analysis scripts, and results from my research on how **aerobic** and **anaerobic** exercise acutely affect **brain-derived neurotrophic factor (BDNF)** levels in healthy adults.  
BDNF is a neurotrophin involved in **neuroplasticity, memory, and learning**. Increasing BDNF before learning activities may enhance knowledge retention and cognitive performance.  

Our work leverages **meta-analysis techniques** to compare the acute effects of the two exercise modalities on circulating BDNF concentrations.  

---

## Research Question  
> *“When taking a break, what type of exercise is most effective at increasing productivity afterward?”*  
We address this by evaluating whether aerobic or anaerobic exercise produces a significantly greater acute increase in BDNF.  

---

## Methods  
- **Dataset Source:** Dinoff, Adam, et al. (2017) meta-analysis dataset on acute exercise and BDNF.  
- **Added Data:** Supplemented anaerobic studies to improve statistical power.  
- **Statistical Tests:** Welch two-sample *t*-tests on both ΔBDNF and Cohen’s *d* (effect size).  
- **Outlier Sensitivity Check:** Removal of ±3 SD outliers to verify robustness of results.  

---

## Results Summary  
- **No statistically significant difference** between aerobic and anaerobic modalities in ΔBDNF or effect size (*p* > 0.05).  
- Both exercise types **acutely elevated BDNF**.  
- Adding 12 anaerobic studies roughly **doubled statistical power** for detecting between-group differences.  

---

## Key Takeaways  
- Exercise—regardless of modality—can be used acutely to elevate BDNF levels.  
- Overlap in energy systems (aerobic phases in anaerobic training, and vice versa) may reduce observed differences.  
- Mechanisms may involve **lactate production, catecholamine release, and increased cerebral blood flow**, but are not fully established.  

---

## Future Work  
- Expand dataset with underrepresented anaerobic protocols.  
- Explore alternative outcome measures (e.g., **BDNF mRNA expression**, **other neurotrophins**).  
- Investigate moderating variables like **age, sex, fitness level, and training status**.  
- Assess time-course changes in BDNF post-exercise.  

---

## Citation  
If using this repository or data in your work, please cite:  

Dinoff, Adam; Herrmann, Nathan; Swardfager, Walter; Lanctôt, Krista L. (2017). Dataset for: *The effect of acute exercise on blood concentrations of brain-derived neurotrophic factor (BDNF) in healthy adults: A meta-analysis*. Wiley. Dataset. https://doi.org/10.6084/m9.figshare.4980764.v1  

---

## License  
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
