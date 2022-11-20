A) Readme, Legibilidade, organização e documentação de código fonte		
B) Modularização (arquivos de corpo e cabeçalho; funções e métodos)		
D) Manipulação de arquivos		
Escrever em arquivo		
Ler de um arquivo		
E) Uso consistente de alocação de memória e de TADs		
Uso de coleções, iteradores e métodos		
Uso de algoritmo para busca por chassi		
F) Uso adequado de makefile		
G) Sobrecarga de funções e operadores; uso de templates; polimorfismo			
Sobrecarga de operadores para leitura ou escrita em arquivos		
Uso de templates e polimorfismo                		
H) Corretude, saída em conformidade com a especificação				
Criar concessionária e adicionar veículos		
listar proprietários, frota e valor		
Busca por chassi		
Listar veículos produzidos < 90 dias		
Listar média de veículos por concessionária		
I) Compilação e warnings		

12. O programa deverá permitir listar os dados de todos os veículos de uma concessionária, sobrecarregando-se o operador de inserção em stream (<<).

# Autoavaliação

- Modelagem e implementação das classes Concessionária, Veículo, Automóvel, Moto, Caminhão | **... / 10**
  - 0: sem modelagem e implementação de classes
  - 5: apenas algumas classes modeladas e implementadas; ausência de herança
  - 10: modelagem e implementação completa com uso de herança
  
- Implementação e uso do comando `create-concessionaria` | **... / 10**
  - 0: não cria concessionária via linha de comando 
  - 5: permite criar apenas uma concessionária
  - 10: permite criar mais do que uma concessionária
  
- Implementação e uso dos comandos para adicionar veículos `add-car/add-bike/add-truck` | **... / 10**
  - 0: não permite criar veículos via linha de comando
  - 5: permite criar apenas um ou outro veículo em uma única concessionária
  - 10: permite criar qualquer tipo de veículo em qualquer uma das concessionárias disponíveis

- Não permitir adicionar um veículo que já tenha sido anteriormente adicionado | **... / 10**
  - 0: não realiza o teste
  - 10: realiza o teste e indica o erro  

- Implementação e uso do comando para remover veículos `remove-vehicle` | **... / 10**
  - 0: comando não implementado
  - 10: comando implementado e funcional

- Implementação e uso do comando para busca de veículos `search-vehicle` | **... / 15 - Bônus: ...**
  - 0: não implementado
  - 15: implementado e funcional
  - bonus +5: implementado com estratégia de busca diferente da busca exaustiva
  - bonus +5: uso de métodos virtuais para impressão na tela
  - bonus +5: uso de sobrecarga de operadores para impressão na tela

- Implementação e uso do comando `list-concessionaria` | **... / 10 - Bônus: ...**
  - 0: não implementado
  - 10: implementado e funcional   
  - +5: uso de sobrecarga de operadores para impressão na tela

- Implementação e uso do comando `raise-price` | **... / 10 - Bônus: ...**
  - 0: não implementado
  - 10: implementado e funcional 
  - +5: implementado com uso de método virtual

- Implementação e uso do comando `save-concessionaria` | **... / 15**
  - 0: não implementado
  - 15: implementado e funcional 

- Implementação e uso do comando `load-concessionaria` | **... / 15**
  - 0: não implementado
  - 15: implementado e funcional  
  
- Implementação eficiente através do uso de referencias e contêineres da STL | **... / 10**
  - 0: não usou contêiner da STL nem fez uso eficiente dos recursos computacionais
  - 5: usou contêiner da STL mas não otimizou uso dos recursos computacionais
  - 10: usou contêiner da STL junto a algoritmos e práticas de bom uso de recursos computacionais
  
- Organização do código em src, include, data | **... / 5**
  - 0: não organizou o código
  - 5: organizou o código 
  
- Documentação do código | **... / 5**
  - 0: não documentou o código
  - 5: documentou o código 
  
- Implementação e documentação de arquivos e procedimentos de compilação e teste | **... / 15**
  - 0: não implementou arquivos e procedimentos de compilação e teste
  - 5: implementou alguns arquivos e procedimentos de compilação e teste (com alguma documentação) 
  - 15: Ampla implementação e documentação de arquivos e procedimentos de compilação e teste
 
 # Total
 **...** pontos (sem bônus)
 **...** pontos (com bônus)
