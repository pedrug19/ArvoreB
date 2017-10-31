# ArvoreB+
Trabalho de Arvore B+ do Leandro

## O que fazer

- Transformação da implementação da Árvore B em Árvore B+
- Implementação de arquivos de texto para dados
- Implementação das estruturas referentes ao projeto
- Tirar 10 no trabalho

## Arvore B+

Árvore B+: Gerar uma sequência de índices
- Índice denso: aponta p/ a tupla
- Índice esparso: aponta p/ um intervalo ou conjunto de tuplas

```
char nome[40];
char telefone[8];
char ender[40];
int idade;
status(válido);
prox;
```

O bloco de dados é um TXT

## Distribuição de Tarefas

- **Dig:** Atualizar Inserção
- **Molina:** Atualizar Remoção
- **Pedren:** Manipulação dos Arquivos

## Mas, Pedren, como que usa o Git?
Ora, caro, gafanhoto! É muito simples:

### 1) **Baixar o aplicativo/programa do git no seu PC**
  Caso seja Windows: https://git-scm.com/ (Pode ser necessário a instalação do MinGW ou Cygwin, não tenho certeza!)
  Caso seja Linux Ubuntu: (Caso já não esteja instalado)
  ```
  sudo apt-get install git
  ```
### 2) **Clonar o repositório do Git no seu computador**
  Baixe o zip ou então:
  ```
  git clone https://github.com/pedrug19/ArvoreB
  ```
### 3) **Se preciso, inicializar o repositório**
  No terminal do git seria algo assim (dependendo de onde está seu arquivo):
  ```
  cd ArvoreB
  git init
  ```
### 4) **Criar um novo Branch para realizar alterações!**
  No terminal do git é só digitar:
  ```
  git branch NOMEDOMEUBRANCH
  ```
  Substituir NOMEDOMEUBRANCH por Molina ou Dig.
  
### 5) **CODIFICAR!**
  
### 6) **Ficar atento a atualizações dos seus parças!**
  Não se esqueça de sempre que puder utilizar o comando:
  ```
  git fetch
  ```
  Ou então:
  ```
  git pull
  ```
  Para receber as atualizações e estar a par com seus amiguinhos.
    
 ### 7) **Dar commits!**
  Para commitar mudanças, primeiro veja quais arquivos estão no status:
  ```
  git status
  ```
  Caso ele retorne algo como:
  ```
  On branch master
  Your branch is up-to-date with 'origin/master'.
  nothing to commit, working tree clean
  ```
  Adicione o arquivo que você quer commitar ao git:
  ```
  git add ARQUIVO.c
  ```
  Commite:
  ```
  git commit
  ```
  Escreva uma mensagem de Commit (Pode ser necessário que você tenha que usar o VIM. Aperte i para inserir uma mensagem, Esc para sair do modo de inserção, e digite :wq para salvar e sair da mensagem de commit) OBS: DIGITE UMA MENSAGEM RELEVANTE, E NÃO UM SIMPLES VAI **TOMAR NO CU, PEDREN**. Coloque o que você realmente fez.
### 8) **PUSH PARA O REPOSITÓRIO PRINCIPAL**
  Só commitar não vai mandar o arquivo. Utilize o comando:
  ```
  git push
  ```
  E suas alterações serão enviadas para o servidor do GitHub.
    
### 9) **TIRAR 10 NO TRABALHO**
Fazendo isso temos um Controle de Versão ótimo, que deixaria a Rogéria orgulhosíssima de seus pupilos de Engenharia de Software! O Leandro ia bater palmas, e o Guilherme ia ficar embasbacado porque a gente sabe usar git e ele não. (Ou será que sabe?)

## **Data de entrega: 21/11/17**
