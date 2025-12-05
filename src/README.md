## 1️⃣ **Desafio Classificador de nível de Herói** 🦸🏻‍♀️

Primeiro desafio proposto pela **DIO**, com o objetivo de testar os conhecimentos adquiridos durante o curso e utilizar conceitos de lógica de programação em JavaScript, como:

- Variáveis  
- Estruturas condicionais  
- Operadores  
- Laços   

A missão é classificar um herói de acordo com sua quantidade de XP, exibindo uma mensagem no console com o nome e o nível de experiência.

---

## 📌 Objetivo do Desafio

Criar uma variável para armazenar:

- **Nome do herói**
- **Quantidade de XP**

Usar estruturas de decisão para determinar o nível do herói seguindo as regras:

| XP | Nível |
|----|--------|
| Menor que 1.000 | **Ferro** |
| 1.001 – 2.000 | **Bronze** |
| 2.001 – 5.000 | **Prata** |
| 5.001 – 7.000 | **Ouro** |
| 7.001 – 8.000 | **Platina** |
| 8.001 – 9.000 | **Ascendente** |
| 9.001 – 10.000 | **Imortal** |
| Maior ou igual a 10.001 | **Radiante** |


Ao final, exibir uma mensagem, seguindo este modelo:

"O Herói de nome **{nome}** está no nível de **{nivel}**"

---

## 📂 Estrutura do Projeto

Este repositório possui somente as estruturas básicas necessárias para realizar o desafio:

---

## 🧠 Lógica Utilizada

A lógica utilizada compara o valor do XP com faixas predefinidas e atribui um nível ao herói.

---

## 💻 Código Utilizado

```javascript
let nome = "Ana"; 
let quantidadeXP = 10001;
let nivel;

if (quantidadeXP <= 1000) {
    nivel = "Ferro";
} else if (quantidadeXP <= 2000) {
    nivel = "Bronze";
} else if (quantidadeXP <= 5000) {
    nivel = "Prata";
} else if (quantidadeXP <= 7000) {
    nivel = "Ouro";
} else if (quantidadeXP <= 8000) {
    nivel = "Platina";
} else if (quantidadeXP <= 9000) {
    nivel = "Ascendente";
} else if (quantidadeXP <= 10000) {
    nivel = "Imortal";
} else {
    nivel = "Radiante";
}

console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);
```

