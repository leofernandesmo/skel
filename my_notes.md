############################################
# Some of my notes about the Skel/Lapedo Project
#
# Author: Leonardo Fernandes M. de Oliveira [lfmo@cin.ufpe.br]
# Date: 06/10/2015
############################################

### REMINDER
- [SKELETONS]
    -func: é um skepeton wrapper que encapsula uma função sequencial como um streamin skeleton. Quando func é instanciado, 
     um novo processo Erlang é iniciado e executa a função sequencialmente. Ex. {func, fun f/1}

    - pipe: Modela uma composição de skeletons. Faz um pipeline das funções, que são executadas em paralelo.
      A entrada do skeleton Si é a o resultado do skeleton Si-1.

    - farm: Também conhecido como Master-Slave. 

    - cluster

    - feedback

### DOUBT
- [SESSION]
    - [TODO]

