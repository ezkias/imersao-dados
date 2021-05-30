
![imagem do banner](https://github.com/ezkias/imersao-dados-desafio-final/blob/main/imagens/19-0871-banner.png)
Imagem de: Bioradiations <https://www.bioradiations.com/artificial-intelligence-in-drug-development/>
# **Desafio Final Imersão Dados**
## Análise dos 3 mais promissores compostos a seguirem para a próxima fase do estudo.

### **INTRODUÇÃO**
Por mais que essa semana de aprendizado tenha sido uma 'baita' imersão no oceano da análise de dados e drug discovery, não tivemos como fazer um mergulho mais profundo. O processo desde a descoberta de um composto e a disponibilização de um novo medicamento para uso terapêutico é bem longo, e essa fase explorada na imersão da Alura ainda é um dos primeiros passos nesse processo.

### **OBJETIVO**
Sendo assim, meu objetivo com essa análise é identificar os 3 compostos com maiores chances de seguir para a proxima fase, considerando o seu mecanismo de ação em cada gene testado.

## **PONTOS INTERESSANTES DA ANÁLISE** 
**Observações:** foi possível coletar informações muito valiosas para a nossa pesquisa. Sabemos que o dataset possui 23814 linhas e 877 colunas, sendo elas:  

**ID:** Onde estão listadas as indentificações de cada experimento.  
**TEMPO:** Onde é informado o tempo da administração do composto.  
**DOSE:** Onde é indicado se naquele experimento foi utilizado a Dose 1 (**D1**) ou a Dose 2 (**D2**).  
Todas as outras colunas são semelhantes, já que nelas estão os resultados da resposta dos genes (**G0 - G771**) ao composto aplicado, e a viabilidade celular (**C0 - C99**).

Ao analisarmos os dados sobre o tipo de tratamento adotado, notamos que o com_droga é muito mais utilizado do que o com_controle, e isso se dá ao fato de que a analise foi feita com a administração de varias compostos mas apenas um controle (O **cacb2b860**), sendo assim o número de experimentos controle pode ser menor.

## **CONCLUSÃO**
Infelizmente por falta de tempo não fui capaz de concluir minha analise, como era o meu objetivo. Até onde pude analisar os compostos **87d714366**, **d50f18348** e **83a9ea167**, foram os que mais ativaram mecanismos de ação, juntando isso com a alta taxa de correlação entre os genes com os quais os mesmos compostos interagiram e o padrão do tempo de cada dosagem, me levam a especular que esses são os 3 compostos com maiores chances de passarem para uma próxima fase do estudo. 

## **Referências**
- [Kaggle](https://www.kaggle.com/c/lish-moa)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [SKlearn](https://scikit-learn.org/)

# **Nota de Agradecimento**
Olá você que está avaliando esse trabalho : ) ... Gostaria de agradecer a todos vocês da Alura por desenvolverem essa imersão fantastica. Sou estudante de medicina e tenho uma paixão secreta pela área da tecnologia, então, essa imersão me fez criar um grande interesse pela área da pesquisa, além de me ensinar muita coisa sobre análise de dados. Gostaria de ter tido tempo para ter finalizado o desafio, essa bolsa para o bootcamp me deixou cheio de vontade hahaha... No mais é isso, sou super grato pela oportunidade de aprender com vocês... vlw!

*****
