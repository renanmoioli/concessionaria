# Concessionaria

### Table of Contents
1. [Problema](#1-problema)
2. [Orientações](#2-orientações)
3. [Entrega](#3-entrega)
4. [Avaliação](#4-avaliação)

# Motivação

## Create/Read/Update/Delete - Crud
O termo CRUD refere-se às principais manipulações sobre os dados que modelam a aplicação. Entender como modelar os dados e como realizar atividades de crud é um conhecimento muito importante em diversas áreas, mais especificamente na área de serviços web e distribuídos, sobretudo em aplicações de backend. Normalmente, a especificação do problema já indica o conjunto de dados a ser manipulado, e o trabalho de programação está em modelar classes que representam os dados e realizar as ações sobre os dados como especificado pela aplicação. Nesta atividade iremos praticar algumas operações comuns em aplicações que envolvem CRUD.

# 1. Problema

Implemente um programa em C++ que atenda aos seguintes critérios:

1. Uma `Concessionária` pode comercializar diversos tipos de `Veículos`: `Automóveis`, `Motos` e `Caminhões`. Cada Concessionária possui um `nome`, `CNPJ` e número de veículos no `estoque`.

2. Todo `Veículo` possui os seguintes campos: `marca`, `preço`, número do `chassi` e ano de `fabricação`. Apenas `Automóveis` possuem um atributo relativo ao `tipo de motor` (gasolina ou elétrico); apenas `Motos` possuem um atributo relativo ao `modelo` (clássico ou esportivo); apenas `Caminhões` possuem um atributo relativo ao `tipo de carga` (comum ou perigosa).

3. O programa deverá permitir criar uma `Concessionária`. Exemplo:
```
$ create-concessionaria IMD_SA 11.111.111/0001-11 0
```
4. O programa deverá permitir que se adicione um veículo, seja ele um automóvel, moto ou caminhão, a uma concessionária. Exemplo: 
```
$ add-car IMD_SA Toyota 100000 9BRBLWHEXG0107721 2019 gasolina
$ add-truck IMD_SA Scania 700000 7BRBLQHEXG0208811 2010 perigosa
```

5. O programa não deve permitir adicionar um veículo que já tenha sido anteriormente adicionado, sendo neste caso exibida uma mensagem de erro. Exemplo:
```
$ add-car IMD_SA Toyota 100000 9BRBLWHEXG0107721 2019 gasolina
ERRO - Veículo 9BRBLWHEXG0107721 já adicionado à concessionária IMD_SA
```

6. Os veículos de uma concessionária deverão ser mantidos em um único _array_, _vector_ ou _list_, ou ainda alguma outra estrutura de dados que você considere conveniente. 

7. A concessionária deve possuir um atributo para o registro de todos os chassis dos seus veículos.

8. O programa deve permitir que se realize uma busca por número de chassi. Caso o veículo pertença à uma concessionária, o programa deve exibir na tela seus atributos. Caso contrário, deve ser exibida uma mensagem indicando a busca sem sucesso. Exemplo:
```
$ search-car 9BRBLWHEXG0107721
Marca: Toyota
Preço: R$ 100000 
Chassi: 9BRBLWHEXG0107721 
Ano:2019
Tipo de motor: gasolina
```

9. O programa deverá permitir escrever em um arquivo de texto todo o estoque de uma concessionária, incluindo os atributos comuns e particulares de cada veículo. Exemplo:
```
$ save-concessionaria IMD_SA
Arquivo IMD_SA.txt criado com sucesso
```

10. O programa deverá permitir criar/recuperar os dados de uma concessionária à partir de um arquivo de texto no formato descrito no item anterior. Exemplo:
```
$ load-concessionaria IMD_SA.txt
Concessionaria IMD_SA criada com sucesso
```

11. O programa deve possuir uma função para listar a frota total de cada tipo de veículo e o valor total dos veículos de uma dada concessionária.
Exemplo:
```
$ list-concessionaria IMD_SA
Concessionaria IMD_SA
Total de Carros: 1; Valor total: R$ 100000
Total de Motos: 0; Valor total: R$ 0
Total de Caminhões: 1; Valor total: R$ 700000
Valor Total da frota: R$ 800000
```

13. O programa deverá permitir que seja dado um aumento de X% ao preço de todos os veículos de uma determinada concessionária. Exemplo:
```
$ raise-price IMD_SA 10
Aumento de 10% nos preços de veículos da Concessionária IMD_SA realizado
```

14. O programa deverá ser finalizado pelo comando `quit`. Exemplo:
```
$ quit
Saindo...
```

# 2. Orientações

- Utilize estritamente recursos da linguagem C++.
- Durante a compilação do seu código fonte, você deverá habilitar a exibição de mensagens de aviso (warnings).
- Aplique boas práticas de programação. Codifique o programa de maneira legível (com indentação de código fonte, nomes consistentes, etc.). Modularize e comente seu código.
- Garanta que seu programa funcione de forma correta e eficiente. Pense também nas possíveis entradas que poderão ser utilizadas para testar apropriadamente o seu programa e trate adequadamente possíveis entradas consideradas inválidas.
- A resolução da questão deve conter um arquivo makefile responsável pela compilação e ligação. 
- Quando não especificado, a modelagem das classes é livre, ou seja, inclua os atributos que você considerar importantes para resolver a questão. 

# 3. Entrega
 
Seu arquivo compactado deverá incluir também um arquivo texto README contendo: a identificação completa do aluno; a descrição de como compilar e rodar o programa, incluindo um roteiro de entradas e comandos que destaquem as funcionalidades (a)-(n); a descrição das limitações (caso existam) do programa e  quaisquer dificuldades encontradas. 

## 3.1 blablabla

# 4. Avaliação

O trabalho será avaliado sob os seguintes critérios: (i) utilização correta e abrangente dos conteúdos vistos anteriormente e nas aulas presenciais da disciplina; (ii) a corretude da execução do programa implementado, que deve apresentar saída em conformidade com a especificação e as entradas de dados fornecidas, e (iii) a aplicação correta de boas práticas de programação, incluindo legibilidade, organização e documentação de código fonte. A presença de mensagens de aviso (warnings) ou de erros de compilação e/ou de execução, a modularização inapropriada e a ausência de documentação são faltas que serão penalizadas. 

## Authorship

**Original problem: Silvio Sampaio**
**Code Snippets: Julio Melo, [julio@imd.ufrn.br](mailto:julio@imd.ufrn.br)**
**Current adaptation: Renan Moioli, [renan.moioli@imd.ufrn.br](mailto:renan.moioli@imd.ufrn.br)**


