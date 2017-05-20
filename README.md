# Multiprogramação & Programação Concorrente
Conceitos de multiprogramação e programação concorrente

- Multiprogramação ou Multiprogramming 

 É a técnica de executar vários programas ao mesmo tempo usando quantização de tempo (timesharing). Ele permite que um computador execute várias coisas ao mesmo tempo. Multiprogramação cria paralelismo lógico. O conceito de multiprogramming é que o sistema operacional mantém vários postos de trabalho em memória ao mesmo tempo. O sistema operacional seleciona um trabalho a partir do pool de trabalho e inicia sua execução; quando esse trabalho precisa esperar por todas as operações I/O, CPU é transferido para um outro trabalho. Assim, a idéia principal aqui é que o CPU nunca está ocioso. 

![multiple-3](https://cloud.githubusercontent.com/assets/27031498/26278386/c93458fa-3d6f-11e7-8a82-5460e50216b6.jpg)

- Programação Concorrente

 Processamento simultaneo que não requer múltiplos processadores. Formado por unidades concorrentes, ou seja, módulos que não precisam ser executados antes ou depois de outros módulos do programa. 
 
Não-determinista
  Impõe uma ordenação parcial, pois o programa não tem total controle sobre a execução das unidades concorrentes.
  
Cada tarefa é uma unidade de execução autônoma; Tarefas podem ser totalmente independentes; Tarefas podem necessitar comunicação; Programa não controla a ordem de execução.



