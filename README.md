# Comparative Analysis of Techniques for Forecasting Time Series in Financial Markets
![Python 3.6](https://img.shields.io/badge/Python-3-blue.svg)
![License](https://img.shields.io/badge/Code%20License-MIT-blue.svg)
![UFSC](https://img.shields.io/badge/UFSC-TCC-blue.svg)


<img src="reports/images/lstm_model.png" align="right" height=auto width=50%/>

## Title
- En: Comparative Analysis of Techniques for Forecasting Time Series in Financial Markets
- Pt-br: Análise Comparativa de Técnicas para a Previsão de Séries Temporais no Contexto de Mercados Financeiros

## Presentation
[2020/2](https://github.com/brunocampos01/forecast-of-time-series-with-stock-data/blob/master/reports/tcc-apresentacao.pdf)

## Publication
[Biblioteca UFSC](https://repositorio.ufsc.br/handle/123456789/223843)

### General Goals
Compare the main prediction techniques for ST in the financial market context.

### Specific Goals
1. Conduct a qualitative analysis of the state of the art on TS (time series) prediction and theories in financial markets;
2. Define data collection and preparation processes;
3. Define the most appropriate algorithms to be implemented targeting the econometric, Machine Learning, and Deep Learning areas;
4. Create computational models for the techniques chosen in the previous item;
5. Train the chosen models;
6. Perform a comparative analysis of the results of the predictors;
7. Develop a repository and make it available on the internet, to make all the results of this research widely reproducible.

### Some Results

#### AR
<img src='reports/images/ar_model.png' align="center" height=auto width=80%>

<br/>

#### ARIMA
<img src='reports/images/arima_model.png' align="center" height=auto width=80%>

<br/>

#### SARIMA
<img src='reports/images/sarima_model.png' align="center" height=auto width=80%>

<br/>

#### Floresta Aleatória
<img src='reports/images/floresta_aleatoria.png' align="center" height=auto width=80%>

<br/>

#### SVR
<img src='reports/images/svr_model.png' align="center" height=auto width=80%>

<br/>

#### LSTM
<img src='reports/images/lstm_model.png' align="center" height=auto width=80%>

<br/>

## Requirements
| Requisite      | Version  |
|----------------|----------|
| Python         | 3.9.7    |
| Pip            | 21.2.4   |

#### How to Install Libraries
```
pip install --require-hashes -r requirements.txt
```

<br/>

## References
Patel, J., Shah, S., Thakkar, P., & Kotecha, K. (2015) Predicting stock and stock price index movement using trend deterministic data preparation and machine learn- ing techniques. Expert Systems with Applications, 42, 259-268. Disponível em: https://www.sciencedirect.com/science/article/pii/S0957417414004473

Sampaio e Mancini, 2007.  Estudos De Revisão Sistemática: Um Guia Para Síntese Criteriosa Da Evidência Científica. Universidade Federal de Minas Gerais, Belo Horizonte, MG. Disponível em : https://www.scielo.br/pdf/rbfis/v11n1/12.pdf  

Lo, Andrew W. (2004) The Adaptive Markets Hypothesis: Market Efficiency from an  Evolutionary Perspective. Journal of Portfolio Management, Forthcoming. Disponível em: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=602222

Kaushik, Manav, e A. K. Giri. (2020), Forecasting Foreign Exchange Rate: A Multivariate Comparative Analysis between Traditional Econometric, Contemporary Machine Learning & Deep Learning Techniques. arXiv preprint arXiv:2002.10247. Disponível em: https://arxiv.org/abs/2002.10247

Luger, George F. (2013), Inteligência Artificial. 6 ed. São Paulo, Brasil. Pearson Education

BUSSAB, Wilton de Oliveira e MORETTIN, Pedro Alberto (2010), Estatística básica. 6 ed. São Paulo, Brasil. Editora Saraiva

Cao, L., Tay, F. (2001) Financial Forecasting Using Support Vector Machines. Neural Comput & Applic 10, 184–192. Disponível em: https://link.springer.com/article/10.1007/s005210170010

Parmezan, Antonio Rafael Sabino. Predição de séries temporais por similaridade. 2016. Dissertação (Mestrado em Ciências de Computação e Matemática Computacional) - Instituto de Ciências Matemáticas e de Computação, Universidade de São Paulo, São Carlos, 2016. doi:10.11606/D.55.2016. tde-21112016-150659.  Disponível em: https://www.teses.usp.br/teses/disponiveis/55/55134/tde-21112016-150659/pt-br.php

BOX, G. E. P.; JENKINS, G. M.; REINSEL, G. C.; LJUNG, G. M. Time series analysis: Forecasting and control. 5. ed. New Jersey, United States of America: Wiley, 2015. (Wiley Series in Probability and Statistics).

Junior, Salomon and Pamplona. ARIMA: An Applied Time Series Forecasting Model for the Bovespa Stock Index. Applied Mathematics, 2014, 5, 3383-3391 Published Online December 2014 in SciRes. Disponível em:  https://www.researchgate.net/publication/275214476

Kaastra, M. Boyd. Designing a neural network for forecasting financial and economic time series. Neurocomputing, 10 (3) (1996), pp. 215-236. 1996 Disponível em: https://www.sciencedirect.com/science/article/pii/0925231295000399/pdf?md5=85cce437dd80a9cc55ebaa8a43455327&pid=1-s2.0-0925231295000399-main.pdf  

Daniel, Fabrice. Financial Time Series Data Processing for Machine Learning. arXiv preprint arXiv:1907.03010, 2019 - arxiv.org. 2019. Disponível em: https://arxiv.org/pdf/1907.03010.pdf

Sergio, Anderson Tenório. Seleção dinâmica de combinadores de previsão de séries temporais. Dissertação de Doutorado em Ciências de Computação - Centro de Informática, Universidade Federal de Pernambuco, Recife, 2017. Disponível em: https://repositorio.ufpe.br/bitstream/123456789/25449/1/TESE%20Anderson%20Ten%C3%B3rio%20Sergio.pdf 

Cowpertwait, P. S. P.; Metcalfe, A. V. Introductory time series with R. Springer Science & Business Media, 2009.

Vapnik, V. N.  An overview of statistical learning theory. IEEE Transactions on Neural Networks, 10, 988–999 1999. Disponível em : https://ieeexplore.ieee.org/document/788640 

PYTHON SOFTWARE FOUNDATION. Python Language Site: Documentation, 2021. Página de documentação. Disponível em: https://www.python.org/doc/

GIL, A. C. Como elaborar projetos de pesquisa, 2010. 4 ed. São Paulo, Brasil. Editora Atlas.

Bueno, R. L. Econometria de Séries Temporais, 2011. 2 ed. São Paulo, Brasil. Editora Cengage Learning.

---

<p  align="left">
    <br/>
	<a href="mailto:brunocampos01@gmail.com" target="_blank"><img src="https://github.com/brunocampos01/brunocampos01/blob/main/images/email.png" width="30">
	</a>
	<a href="https://stackoverflow.com/users/8329698/bruno-campos" target="_blank"><img src="https://github.com/brunocampos01/brunocampos01/blob/main/images/stackoverflow.png" width="30">
	</a>
	<a href="https://www.linkedin.com/in/brunocampos01" target="_blank"><img src="https://github.com/brunocampos01/brunocampos01/blob/main/images/linkedin.png" width="30">
	</a>
	<a href="https://github.com/brunocampos01" target="_blank"><img src="https://github.com/brunocampos01/brunocampos01/blob/main/images/github.png" width="30"></a>
	<a href="https://medium.com/@brunocampos01" target="_blank"><img src="https://github.com/brunocampos01/brunocampos01/blob/main/images/medium.png" width="30">
	</a>
    <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png",  align="right" />
    </a>
    <br/>
</p>

