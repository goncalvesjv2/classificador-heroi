# Classificador de Nível de Herói  

Desafio proposto pela Digital Innovation One (DIO)

Desenvolvi este projeto para reforçar minha prática em lógica de programação, condicionais e manipulação de variáveis em JavaScript, como parte do meu processo contínuo de aprendizado.  
Este repositório contém a solução para o desafio **Classificador de Nível de Herói**, realizado durante a formação de Lógica de Programação da [DIO](https://www.dio.me).  
O objetivo é treinar conceitos fundamentais de programação utilizando JavaScript.

## Objetivo do Desafio

Criar um programa que:

- Receba o nome de um herói  
- Receba sua quantidade de experiência (XP)  
- Classifique o herói em um nível baseado na quantidade de XP  

## Tabela de Classificação

A classificação deve seguir esta lógica:

| XP | Nível |
|----|--------|
| < 1000 | Ferro |
| 1001 – 2000 | Bronze |
| 2001 – 5000 | Prata |
| 5001 – 7000 | Ouro |
| 7001 – 8000 | Platina |
| 8001 – 9000 | Ascendente |
| 9001 – 10000 | Imortal |
| ≥ 10001 | Radiante |

## Lógica Utilizada

O programa utiliza uma estrutura condicional (`if`, `else if` e `else`) para identificar em qual faixa o XP informado se encaixa.  
Quando a condição correta é atendida, o nível correspondente é atribuído à variável `nivel`.

## Como executar o projeto localmente

### 1. Clone o repositório
Abra o terminal e digite:
```bash
git clone https://github.com/goncalvesjv2/classificador-heroi.git
```

### 2. Acesse a pasta do projeto
```bash
cd classificador-heroi
```

### 3. Abrir no VS Code 
```bash
code .
```

### 4. Verifique se o Node está instalado
```bash
node -v
```

### 5. Se o Node estiver instalado execute o arquivo
```bash
node index.js
```

### 6. Caso o Node não estiver instalado
Baixe e instale pelo site oficial: https://nodejs.org/

### 7. Execute novamente o código
Após instalar o Node, rode:
```bash
node index.js
```