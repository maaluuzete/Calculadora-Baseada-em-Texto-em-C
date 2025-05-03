# Calculadora Baseada em Texto em C
Feita com base no exercício [Calculadora Baseada em Texto em C](https://neps.academy/br/course/introducao-a-programacao/lesson/calculadora-baseada-em-texto-em-c), do [Neps Academy](https://neps.academy/).
Uma calculadora simples desenvolvida em linguagem C que permite realizar operações matemáticas básicas diretamente pelo terminal. 
Quando executado, o software pode realizar as quatro operações básicas (i.e. soma, subtração, multiplicação e divisão) ou sair. 
## Demonstração
![menu.calculadorac](https://github.com/user-attachments/assets/8528d8a5-1508-4ac0-a9d0-23d0be2a0431)

O usuário deve escolher a operação desejada (1 a 5). Se a opção escolhida seja uma operação, o programa pede o primeiro e segundo número que o usuário deseja que seja operados. Com o resultado obtido, o programa pergunta se deseja fazer uma nova operação. Caso o usuário queira, ele deve responder com s, e ele será redirecionado para o menu, ou, n para sair do programa e voltar ao terminal.

## Instalação e Pré-requisitos
Para compilar e executar a calculadora em C, é necessário ter o compilador GCC (GNU Compiler Collection) instalado em seu sistema. Abaixo, estão as instruções resumidas para os principais sistemas operacionais:
- **Windows**
  - Baixe o MinGW-w64:
  Acesse a página oficial do MinGW-w64 e baixe o instalador apropriado para o seu sistema: [MinGW-w64](https://www.mingw-w64.org)
  Abra o prompt de comando e digite `gcc --version` para verificar se o compilador GCC está instalado corretamente.
- **Linux**
  - Abra um terminal e execute os seguintes comandos:
```
// Para Debian/Ubuntu, com o apt:
sudo apt-get update
sudo apt-get install gcc

// Para Arch Linux:
sudo pacman -S gcc
```
## Uso e Exemplos
![exemplodeoperacaocalculadorac.png](https://github.com/user-attachments/assets/45d62899-fdfd-4cdf-b6d2-b6798096df5b)

No exemplo acima, realizamos as instruções mencionadas no tópico *Demonstração*, para realizar a operação 2 + 5.

![exemplodeoperacao2calculadorac.png](https://github.com/user-attachments/assets/78588db3-a815-4aa0-ba35-1b4fff73851c)

A calculadora também suporta operações com números decimais. Importante: utilize o ponto final `.` como separador decimal, conforme o padrão da linguagem C. Por exemplo, insira `2.5` em vez de `2,5`.

## Estrutura do Projeto
Este projeto possui a seguinte estrutura:   

```
    Calculadoraemc/  
    │── Calculadora.c  
    │── LICENSE 
    │── README.md  
    │── images/  
    │   └── menu.calculadorac.png
    │   └── exemplodeoperacaocalculadorac.png
    │   └── exemplodeoperacao2calculadorac.png
    
```
* `Calculadora.c ` contém todo o código fonte da calculadora.
* `images` contém todos os arquivos de mídia ou de informação usados no projeto.
* Este arquivo é o próprio `README.md`. Ele tem informações sobre o projeto.
* `LICENSE` contém toda a licença do projeto.
## Licença
Esse projeto está licenciado sob a licença MIT. Para mais detalhes, acesse o arquivo [LICENSE](https://github.com/maaluuzete/Calculadora-Baseada-em-Texto-em-C/blob/main/LICENSE) desse repositório.
