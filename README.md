# Campanha Ars Magica em GURPS



*Essa campanha é uma conversão livre do sistema Ars Magica quinta edição para GURPS quarta edição. A conversão foi fundamentada no Ritual Path Magic com poucas inserções de regras da casa. Usando o sistema de verbo e substantivo foi relativamente fácil adaptar a técnica e arte do Ars Magica. Houve necessidade de criar uma tabela de conversão de custos e tempo de lançamento de magias para facilitar o jogo, caso não fosse feito o mago poderia demorar mais de 20 turnos para lançar uma simples magia em combate.* 

## Livros permitidos

* Basic Set
* Low Tech
* Ritual Path Magic * (Sob consulta) *
* Magic * (Sob consulta) *

Outros livros não estão permitidos. Não é o intuito maximizar ou focar em combate e sim em roleplay. 


## Criação de personagem

* Mago = 250 pontos com 50 de desvantagens
* Companheiro = até 125 pontos com 35 de desvantagens
* Grogs = até 63 pontos com 25 de desvantagens


# Regras

## Adaptações

Para mergulhar melhor no cenário e aproveitar o máximo que ele tem a oferecer tivemos que abrir concessão sobre algumas regras no GURPS. A matemática é realmente muito simples e, ainda para ajudar mais você pode usar essa [calculadora](https://github.com/cefasheli/Ars-Magica/tree/main/Tabelas/Calculadora%20de%20Magia) que faz todo o trabalho bruto de calcular para você.

```DIFF
- **********************************IMPORTANTE*****************************************
- **Toda regra não citada aqui segue exatamente igual conforme apresentada no GURPS 4e**
- **************************************************************************************
```

### Lançamento de Magia 

```diff
Teste simples contra NH da Forma somando ou subtraindo  os modificadores
```

### Modificadores

### Alcance

* Substituiremos as regras de alcance do GURPS 4e e agora passam a ser:*

* Pessoal - O mago é o alvo
* Toque - Onde o mago consegue tocar
* Visão - Até onde a magia do mago consegue olhar que é diferente de Olhar
* Olhar - gaze attack
```diff
! Preciso deixar isso mais claro
```
* Voz - Até onde a voz do mago  puder ser ouvida
* Conexão Arcana - O mago tem algum link arcano com o seu alvo. (Mecânica do AM)

### Alvo

* Ignore as regras de magia em área ou tamanho do alvo, lembrando que SM é outra questão paralela à isso e é vista em outra mecânica.* 

* Indivíduo - Quando o alvo é uma unidade individual, pode ser um homem, um cavalo, um rato, uma colher, uma moeda etc.
* Parte - Quando o alvo é parte de um indivíduo como a roupa de uma pessoa, os galhos de uma árvore, a mão de um homem etc.
```diff
+ reler pois isso vai ser puta confuso para algumas pessoas
```
* Grupo - Pode variar de acordo com a Forma. Um grupo contem a massa de 10 individuos

* Exemplo: Para entender o contexto vamos olhar para o rio Amazonas e seus afluentes. Um único afluente é um indivíduo enquanto todos os rios de um lado são considerados um Grupo. Como referencia um grupo possui a massa básica de 10 indivíduos.

* Sala - Quando o alvo estiver contido dentro de um ambiente e ela varia de acordo com a Forma, para corpus uma sala pode ser 33 m² ela é suficiente para acomodar 100 indivíduos
* Estrutura - Uma estrutura básica contém 10 salas básicas.
* Divisa - É uma área delimitadora de até 100 metros de diâmetro. Cada magnitude esse tamanho é multiplicado por 10 
```diff
- Não gosto dos modificadores de magnitude para divisa. Entender melhor, testar, aceitar ou arranjar solução.
```
### Resumo
MAGIAS INTELLEGO: Não são afetadas pelo Tamanho do Alvo
INDIVÍDUO BÁSICO: Determinado pela Forma
PARTE BÁSICA: Determinado pela Forma
GRUPO BÁSICO: Massa de dez Indivíduos Básicos
SALA BÁSICA: Grande o suficiente para acomodar cem Indivíduos Básicos
ESTRUTURA BÁSICA: Dez Salas Básicas
DIVISA BÁSICA: Uma área de 100 metros de diâmetro
MULTIPLICADOR DE TAMANHO: Cada magnitude adicionada multiplica o tamanho básico por dez.


### Duração

* Momentâneo - Acontece em uma fração pequena de tempo e termina
* Concentração - Enquanto o mago estiver mantendo a concentração do item 
* Diâmetro - 2 minutos (Uma área de 25 m² leva 1 Diâmetro para ser explorada)
* Sol/Círculo - A magia dura até o próximo nascer ou pôr do sol.
* Lua - A magia dura até que a próxima Lua Nova e Lua Cheia se ponham, independente de que ordem isso aconteça.
* Ano - A magia dura até o nascer do sol do quarto equinócio ou solstício a partir de sua conjuração. Apenas Rituais Mágicos podem ter Duração: Sol.

## Atividades de laboratório

* Os jogadores deverão seguir a tabela [laboratório](https://github.com/cefasheli/Ars-Magica/tree/main/Tabelas/Laborat%C3%B3rio) disponibilizado aqui para saber o quanto investir e e receber os bônus desse investimento. 
* O laboratório demora 2 estações para estar em sua capacidade total, em sua primeira estação ele está pronto mais possui um modificador negativo de -3 que é retirado após a segunda estação.
* Efeitos adicionais podem ser inclusos nesses bônus como obter um ajudante, um familiar, algo muito específico para a criação.

### Estudos Arcanos 

Os conhecimento de Taumatologia e das Artes mágicas são importantes para os magi – tão importantes, de fato, que muitos passam a vida toda enclausurados em seus laboratórios, estudando-os. É possível aumentar seu conhecimento das Artes mágicas de diversas maneiras, sendo o laboratório a principal delas.

### Fixar conexões arcanas

Um magus que tenha em mãos uma Conexão Arcana ativa  pode fixá-la de maneira permanente, utilizando uma estação de trabalho em seu laboratório e um peão de Vim Vis. A conexão tem que estar ativa ao começo da estação, mas não precisa durar até o fim dela.


```diff
- Definir como vai numericamente a conexão arcana, ler pág 121 AM.
```

### Extração de Vis

É possível extrair vis bruto de um ambiente mágico (qualquer lugar que tenha uma aura mágica), canalizando a energia mágica em um objeto físico. Para cada estação empenhada na extração de vis da aura, calcule seu Total de Laboratório Creo Vim e divida por 5, arredondando para cima para determinar a quantidade de peões de vis acumulados por estação do ano.

```diff
! Isso necessita de teste de comparativo
```

### Transferência de Vis

A transferência de vis bruto de um objeto para outro é uma atividade de laboratório simples. O mago pode fazer isso em apenas um dia enquanto faz outras coisas.

#### Uso de Vis

A quantidade máxima de vis que o mago pode manipular é Forma / 2

```diff
! Jogadores dificilmente chegarão à esse limite mas ele precisa estar aí, fazer teste de comparação.
```

### Magias formulaicas

Magias formulaicas são uma grande medida do poder de um magus, pois determinam os efeitos que podem ser realizados facilmente e com resultados  revisíveis. Há diversas maneiras de inventar novas magias formulaicas.

#### Aprendendo Magias Formulaicas

```diff
NH da Forma + Modificador do laboratório + Aura + Professor + Biblioteca = Valor Resultante dividido por 3
```

Exemplo: João quer criar uma magia formulaica de proteção contra a efeitos de água, o custo dessa magia seria 4. João tem NH 12 na Forma Aquam e seu laboratório tem bônus +1 e a aura auxilia bastante adicionando mais 1 ao processo e a tutoria de um mestre e sua ppequena biblioteca somam juntas +3 , o valor final seria 15 / 3 = 5. Logo João consegueria fazer essa magia durante uma estação facilmente com alguma sobra de tempo.

```diff
+ Ignoramos o máximo que se pode aprender com um professor segundo a regra do ars magica para apenas adicionar bonus na criação de magia. O pró é que o jogador pode criar qualquer magia que desejar o contra é a falta de controle sobre magias muito poderosas ou de caráter duvidoso. 
[] Conversar sobre isso com os jogadores
```




