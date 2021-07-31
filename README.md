# KopenotIA
> Resumo: A doença Diabetes Mellitus atinge pelo menos 425 milhões de pessoas em todo mundo, incluindo indígenas que residem em áreas protegidas. Para obter mais informações sobre esta doença, o objetivo deste estudo foi utilizar a aprendizagem de  máquina, com amostras composta por dados de indígenas residentes na aldeia Aldeia Limão Verde em Aquidauana/MS. Foi utilizado um questionário para a coleta das informações, depois utilizou-se desta base de dados para o algoritmo de Árvore de Decisão, revelando 93% de precisão na previsão de diabetes, também verificou que a taxa glicêmica acima de 127 mg/dl é um dos fatores determinantes da diabetes, junto com, a pré-existência de outras doenças do paciente e o sedentarismo.

## 1. Sobre o projeto:
### Desenvolvedores:
> Projeto desenvolvido pelos alunos Geovana Figueiredo Silva e Kauê Malacrida Dias sob orientação da Prof Doutora Márcia Ferreira Cristaldo.
> O projeto foi utilizado como Trabalho de Conclusão de Curso no curso Ensino Médio Técnico Integrado em Informática pelo IFMS - Campus Aquidauana.  
### Linhas de pesquisa: 
> Ciências Exatas da Terra e Ciências da Saúde 
> Sub-áreas: Aprendizado de Máquina/Inteligência Artificial e Saúde Coletiva

## 2. Objetivos:
> Visando atender a carência de profissionais da saúde em aldeias de difícil acesso, o projeto pretende reconhecer os padrões na incidência de Diabetes Mellitus na aldeia Limão Verde em Aquidauana/MS, ajudando a evitar complicações e facilitando o gerenciamento da doença na região. Para isso, foram utilizadas técnicas de Inteligência Artificial e conceitos de aprendizado de máquina.

## 3. Tecnologias utilizadas:
 1. Estudo bibliográfico.
    > Periódicos científicos como: SCIELO, GoogleAcadêmico e CAPES.
 2. Base de dados.
    > Base construída a partir de coleta de dados realizada pelos pesquisadores.
 3. Minaração de Dados:
    > Plataforma WEKA 3.8 e algoritmo Correlation-based Feature Selection (CFS). 
    > Configuração do algoritmo: [ weka.attributeSelection.CfsSubsetEval -P 1 -E 1] 
    > Método de busca: [weka.attributeSelection.BestFirst -D 1 -N 5]
 4. Aplicaçao na Árvore de Decisão:
    > Plataforma WEKA 3.8 e algoritmo J48 com a Árvore C4.5
    > Aplicação do método [Percentage split] com 70/30.
    > Configuração do Algoritmo: [weka.classifiers.trees.J48 -C 0.25 -M 2]
 5. Análise de Dados:
    > Curva de ROC (Receiver Operating Characteristic).
    > TP - taxa de verdadeiros positivos.
    > Estatística de Kappa.
    > MAE (Erro Absoluto Médio).
 
 ## 4. Apresentações em Feiras e/ou Eventos de Pesquisa:
 1. FECIAQ - Feira de Ciência e Técnologia de Aquidauana
    > Área: Ciências Exatas e da Terra
 2. FBJC - Feira Brasileira de Jovens Cientistas
    > Área: Ciências da Saúde - Saúde Coletiva

## Anexos: 
1. ArtigoFinal.pdf
    > Artigo completo aprovado pela banca do curso.
2. Diabete_BD.arff
    > Base de dados utilizada no projeto.
3. Selected_Atri.arff
    > Atributos selecionados pelo método de pesquisa CFS.
4. arvoreJ48.png
    > Árvore gerada pelo Algoritmo J48.




