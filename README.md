# glips-Processador MIPS de Um Ciclo para Multiplicação de Matrizes 4x4
## Sumário
- [Descrição](#descrição)
- [Funcionalidade](#funcionalide)
- [Seções do Circuito](#seções-do-circuito)
  - [Main](#main)
  - [Memoria de Instrução](#memoria_de_instrução)
  - [Unidade de Controle](#uc)
  - [Banco de Registradores](#banco_de_registradores)
  - [ULA](#ula)
  - [RAM](#ram)
- [Utilização](#utilização)
- [Instalação](#instalação)
- [Contribuições](#contribuições)


## Descriçao
Este é um simulador de processador MIPS de um ciclo implementado no software Logisim, capaz de realizar a multiplicação de matrizes 4x4. Neste projeto, todas as instruções foram criadas pelos integrantes da equipe e são de 32 bits, e o processador executa cada instrução em um único ciclo.


## Funcionalidades:

  ### Multiplicação de Matrizes 4x4:
  O processador recebe duas matrizes 4x4 como entrada, multiplica linhas por colunas e produz a matriz resultante também 4x4 como saída.

  ### Instruções MIPS Simplificadas: 
  Implementa um conjunto simplificado de instruções MIPS, incluindo instruções de carregamento e armazenamento de memória, operações aritméticas e de controle de fluxo.

  ### Execução em Um Ciclo:
  Cada instrução é executada em um único ciclo de clock, simplificando a arquitetura do processador.

## Seções do Circuito

  ### Main
  No main ocorre a implementação de todo o circuito do processador.

  ### Memória de Instrução
  Na memória de instrução, foram colocadas todas as instruções criadas pelos colaboradores em hexadecimal após traduzirem do assembler.
  Ela manda as instruções para o Banco de Registradores, a ULA e a Unidade de Controle.

  ### Unidade de Controle
  A Unidade de Controle foi estabelecida por meio de um circuito formado a partir de uma tabela verdade. 
  Ela é responsável por receber as instruções da memória de instrução e mandar os sinais certos para executá-las.
  
  
  ### Banco de Registradores




  
