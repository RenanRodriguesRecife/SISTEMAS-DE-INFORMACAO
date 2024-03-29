# Métodos de Apoio Multicritério a Decisão


- Um problema de decisão multicritério é uma situação onde existem:

  – Pelo menos dois cursos de ação para se escolher
  
  – A decisão é realizada de modo a atender a diferentes objetivos, muitas vezes conflitantes entre si

  – É necessário racionalizar sob valores em diferentes escalas ou atributos que requerem um tratamento especial para serem comparados em conjunto
 
 ```
  Ex: Você vai comprar uma casa: existe vários critérios - se é bem localizada, se é espaçosa, o preço, se a rua é violenta...
  ```
  
- Em problemas que envolvem grande quantidade de critérios, normalmente não existe a possibilidade de se chegar a uma solução unânime e ótima, pois diferentes objetivos e preferências resultam em diferentes resultados

##### Classificação

- Problemas de decisão multicritério podem ser classificados em diferentes tipos (Roy, 1996):
  
  <img src=".assets/Multiclassi.jpg">
    
  Obs: Problemática de Portfólio (caso especial da Problemática de Escolha)

#### Métodos Multicritério

(OBS: A função do método é facilitar a nossa vida na hora de decidir, o método nunca vai decidir por você)

- Doumpos & Zopounidis (2014) distinguem entre quatro tipos de abordagens multicritério:

  – Otimização Multiobjetivo / Métodos Interativos
  
  – Teoria de Valor / Utilidade Multiatributo / Critério Único de Síntese

  – Relações de Sobreclassificação / Métodos de Sobreclassificação

  – Análises de Desagregação de Preferências


#### Otimização Multiobjetivo

- A Otimização Multiobjetivo consiste em abordagens de programação matemática envolvendo mais de um único objetivo do decisor

- É considerada uma extensão aos métodos tradicionais de otimização monobjetivo

- O campo de atuação da abordagem de otimização multiobjetivo contempla problemas complexos, podendo envolver a formulação de heurísticas e algoritmos evolucionários

- Nessa abordagem, existe uma busca por alternativas não dominadas em uma análise da fronteira de Pareto

- A otimalidade das soluções é analisada através da relação de dominância devido ao fato de que não existe uma alternativa que possua o melhor desempenho em todos os critérios ao mesmo tempo

#### Critério Único de Síntese

- Envolvem metodologias que agregam/combinam as performances de cada alternativa para os diferentes critérios de avaliação, de forma que se obtenha um valor global de performance para cada alternativa

- Esse valor é utilizado para comparações entre as diferentes alternativas do problema, e assim, para a tomada de decisão.

- Esses métodos são considerados compensatórios, pois um bom desempenho de uma alternativa para um determinado critério pode compensar um desempenho ruim para um outro critério

  – A compensação é definida pelos tradeoffs (pesos, constantes de escala) dos critérios de decisão


- Destacam-se os métodos provenientes da Teoria de Valor/Utilidade Multiatributo:

  – Modelo Aditivo

  – AHP

  – TOPSIS

  – SMARTS

  – MACBETH

  – FITradeoff


- MAUT difere de MAVT ao tratar problemas sob a perspectiva da existência de consequências probabilísticas

- Considerando-se assim uma modelagem no contexto de incerteza, enquanto MAVT trata de consequências determinísticas

- Ambas abordagens são bem definidas axiomaticamente

- Para estas duas abordagens existem testes de racionalidade que devem ser realizados para validar a adequação dos métodos ao contexto decisório

#### Métodos de Sobreclassificação

- Os métodos de sobreclassificação possuem racionalidade não-compensatória

  – Um mau desempenho de uma alternativa em um dos critérios não é compensado por um bom desempenho em um outro critério
  
- Estes métodos admitem relações de incomparabilidade entre as alternativas

- A relação de sobreclassificação indica que uma alternativa ‘a’ é pelo menos tão boa quanto uma alternativa ‘b’, se a sobreclassifica b

- Os métodos de sobreclassificação são formulados de maneira que as alternativas sejam comparadas par-a-par.

- Em modelos que utilizam métodos de sobreclassificação, a avaliação intercritério é realizada de modo que os pesos dos critérios representam o grau de importância relativa de cada critério

- Os principais métodos de sobreclassificação são:

  – ELECTRE (ELimination Et Choix Traduisant la REalité)

  – PROMETHEE (Preference Ranking Organization METHod for Enrichment of Evaluations)

- Estes métodos representam os métodos da escola francesa (franco-belga)

- Uma vez que existem algorítimos específicos para cada problemática e particularidades do contexto de decisão, é comum mencionar como família de métodos ELECTRE e PROMETHEE

#### Aplicação de Métodos Multicritério

<img src=".assets/apliMetodMulti.jpg">


#Part 2

Problema multicritério

Tem mais de uma alternativa e você vai racionalisar em escolher (função utilidade é pra 1 critério)

=====================================

Critério único -> pode fazer análise ponderado

a probabilidade demanda utilidade

=====================================

Critério único de Sintese (escola americana)

Relaçãod e sobreclassificação (escola européia) <- compensatório

Multiobjectivo (abordagem mais matemática) <- não compensatório

Processi decisório compensatório e não compensatório

(vai usar multitec no trabalho final)
