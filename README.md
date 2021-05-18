
# Desafio Final Imersão Dados

**Introdução**

Olá! Nesse repositório você vai encontrar o desenvolvimento do meu projeto final da Imersão de Dados 3 realizada pela Alura. Com o objetivo de avanço no desenvolvimento de medicamentos por meio de melhorias nos algoritmos de previsão do MoA (Mecanismos de Ação), o projeto proposto foi baseado na base do Kaggle - Mechanisms of Action (MoA) Prediction criado pela The Connectivity Map, um projeto do Broad Institute of MIT e Harvard, do Laboratory for Innovation Science em Harvard (LISH). A base de dados disponibilizadas pelo Kaggle consistiu em uma competição referente à Drug Discovery, que é a descoberta de novos medicamentos através de dados do efeito de compostos sobre determinados genes e grupo celulares.

**Sobre o Projeto** 
💊

**Banco de Dados**


Esse projeto explora as bases da dados disponibilizadas pelo Kaggle com os arquivos abaixo:

dados_experimentos.zip : Dados com os valores de expressão gênica, viabilidade celular, tratamento, dose, tempo para os diferentes experimentos.
dados_resultados.csv : Dados com os valores de ativação ou não do Mecanismo de Ação.


**Estrutra do Projeto**

1. Definition
2. Data Preparation Process 
3. Exploratory Data Analysis
4. Creating ML Model
5. Model Optimization 
6. Results





O nosso objetivo é que você construa um projeto de Data Science com análise exploratória e desenvolva um modelo de machine learning para auxiliar na descoberta de novos medicamentos, aplicando todo o conhecimento que você irá adquirir na imersão e criando um projeto incrível no github, deixando-o com a sua cara. 

Se você não sabe por onde iniciar, não se preocupe! Use este documento como um guia para a construção da sua pesquisa e mergulhe fundo!

Sabemos que esse pode ser o seu primeiro projeto de Data Science. Queremos que você tenha um portfólio com um projeto mais aplicável e mais próximo do cotidiano de cientistas de dados. E, para isso, temos alguns lembretes para que você reflita quando for trabalhar. Então, mão na massa!

É importante que você olhe para o seu projeto como um todo. Desde a concepção ao entendimento do negócio, a análise de dados e ao levantamento de hipóteses. Ou seja, ao chegar na solução aplicando machine learning, se atente para que seu projeto tenha começo, meio e fim. Lembrando que ter um fim não quer dizer que os resultados precisam ser perfeitos. O nosso problema é complexo e se seus resultados não forem os melhores do mundo, não há problemas. Dentro das limitações de tempo e de conceitos aprendidos na imersão, o mais relevante é ter entendido os processos relacionados ao desenvolvimento de uma solução de Data Science, desde a análise até o desenvolvimento dos modelos de Machine Learning. 

Os critérios que utilizaremos para analisar os projetos foram divididos em duas etapas de observação, sendo elas:


## Critérios de avaliação técnicos

### Escopo do Projeto

Delimitar qual será o escopo do seu projeto e colocá-lo em prática pode ser bastante desafiador, pois é um equilíbrio entre a sua criatividade e o tempo disponível. 

Você pode se perguntar: Exploram pouco as possibilidades e tenho um estudo raso, ou explorar muitas possibilidades e não consigo fechar dentro do tempo? 

Na dúvida, pondere e priorize o que está dentro do escopo do projeto, essa é uma tarefa fundamental.  

### Estrutura do projeto

É necessário que seu estudo seja bem organizado e estruturado, apresentando uma sequência lógica da análise. 

O projeto precisa expressar e justificar qual a linha de raciocínio foi criada e seguida durante o processo de elaboração. 


### Storytelling e conclusões

Parte da entrega de um estudo é mostrar para a comunidade qual o valor do seu projeto, dessa forma, contextualizar e aproximar o(a) interlocutor(a) é vital. 

É imprescindível que você pense que seu(sua) interlocutor(a), muitas vezes, não sabe do que o estudo trata e/ou não tem familiaridade com tecnologia e programação. Por isso, o notebook precisa ser explicativo de forma que a informação seja acessível para seu público alvo.

As conclusões parciais e a conclusão final são ótimos momentos para que a informação que você extraiu dos dados seja facilmente entregue ao(à) leitor(a). Ademais, você pode adicionar na conclusão as limitações do seu projeto, bem como as ideias para projetos futuros.   

### Pesquisas externas e cruzamento de dados

Do ponto de vista do estudo, é importante que outras fontes de informações sejam utilizadas para colaborar na construção da argumentação do projeto. E, do ponto de vista técnico, isso mostra adaptabilidade e antecipação, pois o cruzamento de informações é um passo muito fundamental no seu amadurecimento enquanto Data Scientist.

Porém, é preciso tomar bastante cuidado ao fazer essa junção: será avaliado o valor agregado à pesquisa, não somente as informações extras. 

Um exemplo: você pode pesquisar na literatura científica artigos que falam sobre drug discovery, com informações que você julgue relevantes, e utilizar esses dados e informações na sua argumentação e no desenvolvimento do seu storytelling.

## Critério de avaliação práticos

Os critérios práticos são bastante objetivos e nítidos, cientista. Use esses critérios como lembretes sobre o conteúdo que deve produzir.

- Os dados estão dentro do escopo? (É obrigatório o uso da base de dados usado na imersão de dados, que são inspirados no desafio proposto no Kaggle). 
- Quando necessário, as variáveis foram tratadas?
- Se houve criação de variáveis, as mesmas foram descritas? 
- Ficou claro qual foi o modelo final escolhido e o que motivou a escolha?
- O notebook tem uma narrativa convincente e coerente?
- O projeto contém meios para visualizar dados (gráficos ou tabelas) que ajudam na argumentação dos pontos principais do cientista?
- A bibliografia e fontes de dados alternativas foram citadas?
- O projeto é inédito e houve cuidado para evitar plágio? 

## Como iniciar seu projeto

Para começar seu projeto, você deve criar um **Fork** do repositório pois dentro dele, contém toda a estrutura de pastas recomendada e também um arquivo README.md, no qual você deve reescrever, adicionando uma apresentação do seu projeto.

### Como fazer um Fork:

Primeiro, clicamos na opção Fork que fica no canto superior direito.

![imagem mostrando no canto superior direito a opção Fork](https://user-images.githubusercontent.com/50880764/117156939-8c90d880-ad94-11eb-922e-8773b3c13bc6.png)

Agora está tudo pronto, você terá uma cópia do repositório para iniciar o seu projeto. Conforme a imagem, abaixo, no canto superior esquerdo aparecerá o seu nome seguido do nome do repositório do projeto.

![imagem mostrando repositório copiado para um novo usuário](https://user-images.githubusercontent.com/50880764/117156978-94507d00-ad94-11eb-8fe3-ffb33a645197.png)


## Dicas

### Organização de diretórios

Nós já propomos uma estrutura de diretórios, com duas pastas separando os dados das análises: 


- **Pasta Dados:** Onde ficarão os arquivos dos dados usados no projeto.
- **Pasta Notebooks:** Onde ficarão os notebooks com suas análises.

Na imagem abaixo, temos um highligth da pastas **Dados** e **Notebook**. Essa estrutura é uma sugestão você pode ficar a vontade em reorganizar conforme considerar o ideal para seu projeto. 

![imagem mostrando a estrutura de pastas padrão do projeto no GitHub](https://user-images.githubusercontent.com/50880764/117161359-3756c600-ad98-11eb-98df-f56e35e6ea96.png)


Ao realizar o **fork** deste repositório, o arquivo README.md é uma cópia deste arquivo que você está lendo agora. Para deixar o seu projeto com cara de portfólio você precisa modificar o arquivo README.md adicionando a motivação e detalhamento do seu projeto. Aqui vai algumas dicas para você editar o README.md no repositório que foi criado em sua conta do github.

* Primeiro, vamos clicar na opção "editar esse arquivo" que fica no canto superior direito.
![imagem indicando no canto superior direito a opção "editar esse arquivo"](https://user-images.githubusercontent.com/26041581/117192503-3170dd00-adb8-11eb-864f-988a8c9c0f55.png)

* Depois podemos escrever o conteudo do readme na caixa Edit file
![imagem indicando a caixa onde podemos editar o conteúdo do arquivo README](https://user-images.githubusercontent.com/26041581/117192548-3d5c9f00-adb8-11eb-8402-75af1dc5daab.png)

* Quando terminarmos as alterações vamos para o final na página e procuramos pelo campo Commit changes onde podemos descrever nossas alterações e depois clicar na opção Commit changes.
![imagem indicando campo no final da página onde podemos descrever nossas alterações e salvar nossas alterações](https://user-images.githubusercontent.com/26041581/117192564-42215300-adb8-11eb-83b0-d9f6887b8bd1.png)

* Finalmente teremos um novo README agora com as nossas alterações
![imagem indicando que nossas alterações foram salvas no README](https://user-images.githubusercontent.com/26041581/117192571-464d7080-adb8-11eb-9a70-2cef826ed24e.png)
Como escrever um bom README:

- Insira uma imagem;
- Coloque o nome do projeto;
- Descreva o projeto;
- Apresente o objetivo do projeto;
- Evidencie as particularidades do projeto;
- Explique sobre a estrutura dos dados;
- Exiba os links utilizados para a conclusão do projeto

Links úteis:

Materiais sobre **biologia** para você embasar seu projeto:

- [Drug discovery: passado, presente e futuro](https://docs.google.com/document/d/10EhrQBChlyYIcff3to7PrCQi5HcNk2r-zd2ZCKPtcz8/edit?usp=sharing)
- [Expressão gênica: o caminho da informação biológica](https://drive.google.com/file/d/1VNP08ffCiGD8cqaBkdHATWSX8Yxfm3dj/view?usp=sharing)

Materiais para auxiliar o desenvolvimento do **README**:

- [Criando anotações com Markdown](https://www.alura.com.br/artigos/criando-anotacoes-com-markdown)\

- [Projeto de Data Science criado no Bootcamp](https://github.com/souzajvp/data_science_bootcamp/tree/main/modulo_final)

Alguns projetos incrível dos nosso alunos para você se inspirar:

- [Daiane Klein](https://colab.research.google.com/drive/1EwueEMQC_vLXf_oxN3w60itrvsHjrw8B?usp=sharing)

- [Conrado Bittencourt](https://colab.research.google.com/drive/1QCRMnF-9cFRuOO_PrWpzj-UAclQuIomB?usp=sharing)

- [Matheus Leite Llorente](https://colab.research.google.com/drive/1eca1wG-pkGT0IiPv4-vcpjur3tJjj-6e?usp=sharing)


## Premiação

Serão 10 bolsas de estudos integrais para o **Bootcamp de Data Science Aplicada Alura** , que começa dia **18 de maio de 2021**. O prêmio não poderá ser dividido ou revertido em dinheiro.

### Quem pode participar?

A premiação é exclusiva para participantes inscritos na #ImersãoDados 3° Edição. Participantes do Bootcamp de DataScience aplicada (Primeira edição) e premiados com bolsas nas imersões dados anteriores, não serão elegíveis a premiação. Mas estão convidados a enviar seus projetos para serem analisados.  

### Prazo

A submissão final deve ser feita até o dia 09/05/2021 (Domingo) 23h59 horário de Brasília.

### Sobre o envio do Desafio

Você deve submeter o link do seu repositório [neste Google Forms](https://docs.google.com/forms/d/e/1FAIpQLSfcuvhSoXlbggZeRG3Y28Vb9xwCs3MDNFLjSh3WyS96slRsZA/viewform?usp=sf_link).  O repositório de submissão precisa estar público para que seja possível analisar seu projeto.


### Regras para envio do desafio

- É necessário informar o mesmo e-mail que foi utilizado no cadastrado da #imersãoDados.
- O resultado será divulgado dia 10/05/2021 na Live de encerramento da #imersãoDados.
- O repositório deve conter os topics #alura e #imersaoDados.
- Não altere o repositório, após o horário de encerramento do desafio.
- Qualquer alteração após esse horário será desconsiderada na avaliação.
- Seja gentil :). Não somos especializados em competições e estamos fazendo esse desafio para te motivar e incentivar a comunidade de Data Science, espero que goste e se divirta.



**Mergulhe fundo, é apenas o primeiro passo!**
