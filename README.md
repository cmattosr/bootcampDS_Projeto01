# bootcamp_Projeto01

# Projeto do Módulo 01


Projeto de conclusão do Móulo 01 do Bootcamp 02 de Data Science da Alura



Neste projeto analisaremos os dados do SUS para ter um comparativos entre os Estados. Vamos analisar os dados para entender se os gastos são proporcioanais aos atendimentos, além da taxa de mortalidade, óbitos, dias de permanência, entre outros, tudo isso relacionado à população de cada Estado para termos um entendimento da situação do Sistema Único de Saúde

Os dados do SUS foram obtidos do DATASUS em http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe%253Fsih/cnv/qi

Descrição dos dados do SUS utilizados:

Ano e mês de atendimento: Período correspondente à data de internação do paciente na unidade hospitalar.

Internações: Quantidade de AIH (Autorização de Internação Hospitalar) aprovadas no período, não considerando as de prorrogação (longa permanência). Este é um valor aproximado das internações, pois as transferências e reinternações estão aqui computadas.

Valor total: Valor referente às AIH aprovadas no período. Este valor não obrigatoriamente corresponde ao valor repassado ao estabelecimento, pois, dependendo da situação das unidades, estes recebem recursos orçamentários ou pode haver retenções e pagamentos de incentivos, não aqui apresentados. Portanto, este valor deve ser considerado como o valor aprovado da produção.

Dias de Permanência: Total de dias de internação referentes às AIH aprovadas no período. São contados os dias entre a baixa e a alta. Exemplo: internação = 15/02/2003; alta = 18/02/2003; dias de permanência = 3. Nota: este valor não pode ser utilizado para calcular a ocupação da unidade hospitalar, por incluir períodos fora do mês e os períodos em que o paciente utilizou UTI.

Óbitos: Quantidade de internações que tiveram alta por óbito, nas AIH aprovadas no período.

Taxa de Mortalidade: Razão entre a quantidade de óbitos e o número de AIH aprovadas, computadas como internações, no período, multiplicada por 100.


Os dados de população por Estado foram obtidos do IBGE: https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html

<hr>

### Explicação <br>

Olá Cientista!

Boas vindas ao Projeto do Módulo 01! Neste projeto queremos que você aplique tudo que aprendeu no curso, analisando uma outra informação referente a base de dados de produção hospitalar, seja número de internação, óbito, dias de permanência, taxa de mortalidade ou outros de sua preferência.

Utilizando mais dados, teremos mais possibilidades de análise, por exemplo, identificar se o aumento de gastos e internações estão crescendo juntos. Assim, explore o máximo que conseguir dos dados e nos conte suas hipóteses e análises através desse projeto.

Segue algumas dicas para você mandar bem no desafio final do módulo: capriche nas análises, escreva suas conclusões e hipóteses (mesmo que o resultado seja inconclusivo) e não esqueça de colocar um resumo dos pontos que julgar mais interessantes do seu projeto. Pode também utilizar outros dados como por exemplo os disponíveis no Brasil.IO para incrementar sua analise.

Temos um conjunto de dicas para este projeto. Portanto, fique de boa, use elas como um guia para a construção da sua pesquisa e mergulhe fundo!

São boas práticas de projeto:

Delimitar o escopo do projeto de acordo com o tempo e o aprendizado desse módulo;
Utilizar a base de dados sugerida;
Estruturar o projeto de maneira organizada e lógica;
Criar um notebook que tenha um enredo atraente e coerente;
Tratar e descrever seus dados quando necessário;
Fundamentar bem o cruzamento dos dados se você utilizar outras bases;
Aplicar as técnicas de configurações de gráficos para torná-los compreensíveis e para criar argumentações embasadas neles;
Se possível, fazer pesquisas para ir além do apresentado no módulo;
Fazer uma conclusão que relate as limitações do projeto, dando ideias para projetos futuros e apresentando os principais resultados da análise;
Citar e trazer as fontes de todo o conteúdo que apresentar e não for de sua autoria.
É recomendado que você utilize o Github para disponibilizar o seu projeto. Caso não tenha familiaridade com o Github, relaxa! Nós vamos disponibilizar essa semana um vídeo com o passo a passo de como criar seu repositório, colocar seus notebooks e estruturar seu README.

Aqui temos alguns exemplos de repositórios bem estruturados,com bons readme, e também de notebooks bem organizados:

https://github.com/CidSantiago/imersao-dados-desafio-final
https://github.com/gustavolq/Imersao-Dados-Alura
https://github.com/Pedro-correa-almeida/imersao-dados-desafio-final
https://colab.research.google.com/drive/1LO7paa2ArAY7I9hMzTT4Oz34l6m9K9SG?usp=sharing
https://colab.research.google.com/drive/1egYeRJpwKIlrBKtBujyj5E2KW8L5HDn8?usp=sharing
Qualquer dúvida é só nos procurar no Discord do Bootcamp! Bom mergulho!
