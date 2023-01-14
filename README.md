# Cartão de Crédito - Taxas de Juros e Inadimplência
Extração de dados através de API do Banco Central e Análise dos dados referente a:
<br>
* Taxa média de juros das operações de crédito com recursos livres
* Inadimplência da carteira de crédito com recursos livres
<br>
Fonte de dados:
<br>

[SGS - Sistema Gerenciador de Séries Temporais - Banco Central](https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries). 
<br>

[Sobre o Portal do Banco Central](https://dadosabertos.bcb.gov.br/pages/sobre-o-portal)

<br>
<br>
<b>Modulos utilizados:</b> Numpy, Pandas, Matplotlib, Seaborn Requests, BeautifulSoup, json.
<br>
<br>
<b>Passo a passo:</b>  
<br>
**API Banco Central**
<br>
<b>Tarefa 1:</b> Identificação de Dados.
<br>
<b>Tarefa 2:</b> Coleta de Dados.
<br>
<b>Tarefa 3:</b> Pré-processamento de dados.
<br>
<b>Tarefa 4:</b> Análise e representação dos conjuntos de dados processados.
<br>
<br>

<b>Jupyter Notebook:</b> [Cartão de Crédito - Taxas de Juros e Inadimplência](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/Taxa_M%C3%A9dia_de_Juros_das_Operac%C3%B5es_de_Cr%C3%A9dito.ipynb)
<br>
<b>LinkedIn:</b> [Oscar Monteiro](https://www.linkedin.com/in/oscarmonteiro98)
<br>
<br>
Resultados (Dados Desde 01/03/2011):
<br>
<br>
# Cartão de Crédito Rotativo
![1](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/1.png)
<br>
<br>
![2](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/2.png)
<br>
<br>
# Cartão de Crédito Total
![3](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/3.png)
<br>
<br>
![4](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/4.png)
<br>
<br>
# Cartão de Crédito Parcelado
![5](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/5.png)
<br>
<br>
![6](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/6.png)
<br>
<br>
# Taxa de Inadimplência
![7](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/7.png)
<br>
<br>
![8](https://github.com/MonteiroOscar98/Cartao-de-Credito-Juros-e-Inadimplencia/blob/main/README_files/8.png)
<br>
<br>
# Conclusão
O crédito rotativo funciona como um empréstimo pré-aprovado que tem como objetivo evitar que a fatura do cartão de crédito não seja paga. Dessa forma, o valor que fica em aberto é somado à próxima fatura, acrescido de juros.
<br>
<br>
Porém, essa é uma armadilha: as taxas de juros do rotativo estão entre as mais caras do mercado, dada a alta taxa de inadimplência (falta de cumprimento de uma obrigação). Por isso, mesmo em situações emergenciais, essa alternativa deve ser evitada.
<br>
<br>
# Correlações:
<br>
Como podemos interpretar os valores que ρ pode assumir?

* ρ = 0,9 a 1,0 (positivo ou negativo): correlação muito forte;
* ρ = 0,7 a 0,9 (positivo ou negativo): correlação forte;
* ρ = 0,5 a 0,7 (positivo ou negativo): correlação moderada;
* ρ = 0,3 a 0,5 (positivo ou negativo): correlação fraca;
* ρ = 0,0 a 0,3 (positivo ou negativo): não possui correlação.
Nos casos analisados podemos notar a correlações fortes, ou seja:
<br>
Quanto mais devedores inadimplentes, maiores as taxas de juros dos credores. 
<br>
Quanto menos devedores inadimplentes, menores as taxas de juros dos credores.
