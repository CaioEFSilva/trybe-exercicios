# Módulo 1 - Dia 1.1: Unix & Shell

> Data: 16/03/2023
Hoje trabalhamos os conceitos básicos sobre arquitetura de computadores e aprofundamos falando sobre sistemas Unix-Like e o Kernel Linux. 

Quanto à Arquitetura de Computadores, foi abordado sobre o modelo de sub-divisões do computador em camadas, as quais são: 
* o Hardware; 
* o Sistema Operacional; e
* os Softwares. 

Dentro dessas camadas, o Sistema Operacional pode ser sub-dividido em novas camadas, sendo elas: 

* o Kernel; 
* os Shells; e 
* os Aplicativos do Sistema.

Desta forma, temos que o Kernel é o "cérebro" do Sistema Operacional, o qual é responsável em se comunicar diretamente com o Hardware. Os Shells são considerados interfaces de comunicação, ou seja, eles funcionam como uma espécie de "janela", que envolve o Kernel e faz uma ponte para que as aplicações e o usuário possam interagir com ele. Um conceito muito importante dessa interação são os dados de entrada e saída, onde o Shell irá enviar para o Kernel dados de entrada (comandos e parâmetros) e receber possíveis dados de saída devolvidos do Kernel, passando-os para o usuário final.

Além desses conceitos, aprendemos sobre o funcionamento do Bash e como executar os principais comandos de navegação e manipulação de arquivos/diretórios no terminal, como:

> cd, ls, mkdir, touch, cat, less, head, tail, rm, rmdir, etc