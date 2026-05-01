# 🚢 Titanic Data Analysis: "Mulheres e Crianças Primeiro"?

Este projeto realiza uma análise exploratória de dados (EDA) sobre o trágico naufrágio do RMS Titanic. O objetivo central é validar, através de dados históricos, se a famosa máxima "mulheres e crianças primeiro" foi aplicada na prática durante a evacuação do navio.

## 📌 Visão Geral
O Titanic foi um dos maiores navios de sua época. Hoje, com os dados dos passageiros disponíveis, podemos cruzar informações como **Classe (Pclass)**, **Gênero** e **Sobrevivência** para entender o perfil de quem conseguiu chegar aos botes salvatérios.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas para manipulação de dados e análise estatística.

## 📊 Resultados da Análise

> Dataset com 1045 pessoas

Os dados revelam uma disparidade clara tanto em relação ao gênero quanto à classe social dos passageiros.

### 👩‍🦰 Perfil Feminino
A frase "mulheres primeiro" encontra forte eco nos dados, especialmente nas classes mais altas:
* **Sobreviventes:** 324 mulheres (Destaque para a **1ª Classe** com 130 sobreviventes).
* **Vítimas:** 64 mulheres (A maioria, 55, pertencentes à **3ª Classe**).

### 🧔 Perfil Masculino
Os homens registraram as maiores taxas de mortalidade em todas as categorias:
* **Sobreviventes:** Apenas 93 homens conseguiram sobreviver.
* **Vítimas:** 565 homens faleceram (Sendo 311 apenas na **3ª Classe**).

### 👶 Perfil Infantil (Crianças)
A análise dos dados das crianças revela que, embora houvesse uma tentativa de priorização, o fator gênero também se manifestou desde cedo:

| Gênero | Sobreviventes | Vítimas |
| :---  | :---: | :---: |
| **Meminas** | 31 | 13 |
| **Meninos** | 21 | 29 |

### 📉 Resumo por Classe e Gênero

| Gênero | Classe | Sobreviventes | Vítimas |
| :--- | :---: | :---: | :---: |
| **Mulheres** | 1ª | 130 | 3 |
| **Mulheres** | 2ª | 97 | 6 |
| **Mulheres** | 3ª | 97 | 55 |
| **Homens** | 1ª | 40 | 111 |
| **Homens** | 2ª | 15 | 143 |
| **Homens** | 3ª | 38 | 311 |

## 💡 Conclusão
A análise confirma que o gênero foi um fator determinante para a sobrevivência, corroborando a política de prioridade feminina. No entanto, os dados também revelam um recorte social profundo: uma mulher na 3ª classe tinha uma probabilidade de morte superior a uma mulher na 1ª classe, enquanto homens da 3ª classe formaram o grupo com o maior número absoluto de vítimas.


### Observações
1. Os barcos de emergência estavam no convés (último andar).
2. As classes eram divididas entre 3ª, 2ª e 1ª, sendo a 1ª com acesso direto ao convés.
3. As pessoas da 3ª classe subiram para o último andar.
4. Tripulação oficial: 2.224.
5. Os dados estão incompletos.
6. 1045 pessoas fazem parte da análise.

---
*Projeto desenvolvido como parte dos meus estudos em Ciência de Dados.*



> Fonte: https://www.kaggle.com/c/titanic/data

