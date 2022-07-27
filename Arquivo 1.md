
# Incremental Strategy for Applying Mutation OperatorsEmphasizing Faults Difficult to be Detected by Automated Static Analyser

Silva, Vinícius Barcelos; Araujo, Cláudio Antonio;   Spoto,Edmundo Sérgio;
Vincenzi,Auri. 2017. Incremental Strategy for Applying Mutation
Operators Emphasizing Faults Difficult to be Detected by Automated Static
Analyser. In Proceedings of SBES’17, Fortaleza, CE, Brasil, 20-22 set. 2017, 10 págs.

 Acesso em: 26 abr. 2021. doi: [10.1145/3131151.3131169](https://dl.acm.org/doi/10.1145/3131151.3131169)

## 1. Fichamento de Conteúdo
Afim de produzir softwares mais robustos e de baixo custo, são utilizadas diversas técnicas, critérios de teste e uso de analisadores estáticos. Uma das principais é o teste de mutação, todavia é também uma técnica muito custosa devido ao seu alto custo de execução computacional. Uma alternativa seria ferramentas de análise estática automatizadas, entretanto mesmo com custo menor, ainda existe resistência ao utilizar este tipo de ferramenta, dado a escassez de evidências de sua efetividade na construção de softwares de qualidade. Tendo isto em vista o artigo tem por objetivo. evidênciar e dar continuidade ao estudo feito por Araujo, este que trata-se da investigação a correlação entre mutantes e avisos oriundos de ferramentas de análise estática automatizada. Com intuito de expandir a pesquisa através da realização de um estudo experimental para avaliar a eficácia da estratégia incremental em questão, em vista das outras estratégias discutidas pelo artigo. O autor utilizou-se de comparações, cujos os seus critérios levaram em consideração aspectos presentes no escore de mutação, o custo de acordo com o número de mutantes gerados e também o custo no que se refere a quantidade de mutantes equivalentes que foram gerados pelas estratégias, fazendo uso de tabelas, analises afins, fatores que facilitam a compreensão do leitor sendo  um ponto muito positivo. Para isto, as diversas comparações das estratégias foram realizadas, mais precisamente comparando a estratégia STAT com dois conjuntos de operadores de mutação essenciais, gerados pelos experimentos E27 e E5, baseados respectivamente em um editor de texto e utilitarios do unix. Dessarte o artigo conclui que o uso da estratégia STAT não existe diferença entre o E5 e E27 no que se refere ao escore de mutação e redução de custos pelo número de mutantes gerados, todavia o autor chega à conclusão de ainda sim o STAT possui a vantagem pois utiliza operadores que conseguem trabalhar com defeitos mais difíceis de serem encontrados por meio de análise estática, isto é, esta estratégia é capaz de aplicar com menor sobreposição operadores de mutação com os tipos de defeitos detectáveis pelo analisador estático investigado no artigo, chegando a conclusão de sua viabiliade neste aspecto.

## 2. Fichamento Bibliográfico 

* Correspondência Direta por Linha (CDL) trata-se da quantidade de *avisos gerados no mutante e que não estão contidos no programa original (página 4).

* ORRN(Relational Operator Mutation) trata-se de um operador capaz de substituir ocorrências de um operador relacional existente no programa original por todo outro qualquer operador relacional, na linguagem C (página 2).

* SSDL (Statement Deletion)  é um operador que remove um comando por vez do programa original, para assim dar origem aos mutantes (página 2).

* TM(0k) trata-se da quantia total de mutantes concebidos pelo operador 0k (página 4).


## 3. Fichamento de Citações 

* "Um dos problemas do Teste de Mutação é o alto custo computacional devido ao grande número de mutantes gerados, que demandam tempo para a execução, e posterior análise de mutantes vivos para identificação de mutantes equivalentes. "

* "Apesar do interesse acadêmico e industrial no uso das ferramentas de análise estática automatizadas, principalmente devido ao seu baixo custo de utilização, ainda existe uma resistência devido à falta de evidências das contribuições reais que tais ferramentas agregam na produção de um software de qualidade ."

* "Observou-se que existem algumas categorias de defeitos, representadas pelos operadores de mutação, que
são mais facilmente detectáveis pelos analisadores estáticos automatizados, enquanto há outras categorias de defeitos que são quase
imperceptíveis por tais analisadores, evidenciando o aspecto complementar da análise estática e dinâmica"

