# Bayesian inference and forecast of COVID-19, code repository modified for Rwanda COVID-19 Cases.
## Used the original code to quantify effect of the government interventions


##Brief Overview Of SIR Model
![SIR model](/rwanda_plots/SIR.PNG)

The effect of non-pharmaceutical interventions are incorporated by introducing flexible change points in the spreading rate.
- Major interventions after this period include: 
i).20th April- Guidelines required everyone to wear a mask in public, and at home during the lockdown and thereafter.According to the model output below,the spread rate λ(t),decreased from λ=0.21(CI[0.10,0.40]) to λ=0.10(CI[.03,0.32]).The date of the  change point was inferred to be around April 19th,which matches the timing of the intervention.Hence this particular helped reduce the spread rate of the virus.

ii)30th April-Loosened the lockdown, while allowing free movement within each province during the day.Hotels,restaurants opened till 7pm.For this particular change point,the spread rate λ(t),increased from λ=0.10(CI[.03,0.32]) to λ=0.19(CI[.03,0.87]).Relaxing the measures previously put in place impacted the spread rate.

iii). May 4th- a gradual easing of lockdown measures was introduced  with selected businesses allowed to resume operations while adhering to health guidelines. Domestic movement restrictions were partially relaxed but strict physical distancing measures mandated in public buses. Bars remain closed, and schools will only reopen in September.
At the third change point,where the date was inferred to be around 3rd May,the spread rate λ(t),decreased from λ=0.19(CI[.03,0.87]) to λ=0.15(CI[.11,0.20]).The new interventions like physical distancing helped to decrease the spread rate.Though the decrease was not as substantial as the first one,since some interventions were also relaxed during this period. 
![Change in Spread Rate](/rwanda_plots/spread.PNG)



For the approaching week,the number of cases are expected to increases shown above in the model.
![Forecast Of SIR model](/rwanda_plots/forecast.PNG)

[![Documentation Status](https://readthedocs.org/projects/covid19-inference/badge/?version=latest)](https://covid19-inference.readthedocs.io/en/latest/doc/gettingstarted.html)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This is a Bayesian python toolbox for inference and forecast of the spread of the Coronavirus.

- [**Documentation**](https://covid19-inference.readthedocs.io/en/latest/index.html)
- [**Getting started**](https://covid19-inference.readthedocs.io/en/latest/doc/gettingstarted.html)
- [**Examples**](https://covid19-inference.readthedocs.io/en/latest/doc/examples.html)
- [**Contributing**](https://covid19-inference.readthedocs.io/en/latest/doc/contributing.html)
- [**Source code**](https://github.com/Priesemann-Group/covid19_inference)


The latest stable version is [v0.1.8](https://github.com/Priesemann-Group/covid19_inference/tree/v0.1.8)!


The research article [is available on arXiv](https://arxiv.org/abs/2004.01105) (**updated on April 13**).
The code used to produce the figures is available in the other repository [here](https://github.com/Priesemann-Group/covid19_inference_forecast)


If you are interested in our efforts and like to help us feel free to contact us. **We are looking for support** to help us with analyzing other countries and to extend to an hierarchical regional model.

### Please take notice of our [disclaimer](DISCLAIMER.md).


