# ⚠️ Importante!!!
Você pode escolher qualquer um dos desafios para desenvolver. Sinta-se à vontade para começar pelo desafio que mais lhe interessa.

# Desafio Super Trunfo - Países - Comparação das Cartas

Bem-vindo ao desafio "Super Trunfo - Países"! Neste projeto, você desenvolverá um sistema para comparar cartas baseadas em atributos de cidades. O desafio é dividido em três níveis: Novato, Aventureiro e Mestre. Cada nível adiciona novas funcionalidades e complexidades, permitindo um aprendizado progressivo.

## 🏅 Nível Novato

No nível Novato, você começará implementando a lógica básica de comparação entre cartas utilizando estruturas de decisão `if` e `if-else`.

### 🚩 Objetivos:
- **Cadastro de Cartas:** O sistema permitirá ao usuário cadastrar cartas de cidades, incluindo informações como estado, código da carta, nome da cidade, população, área, PIB e número de pontos turísticos.
- **Comparação de Cartas:** O sistema comparará os atributos de duas cartas e determinará a vencedora com base em uma propriedade específica (população, área, PIB, etc.), escolhida no código.
- **Exibição de Resultados:** Após a comparação, o sistema exibirá qual carta venceu com base na regra: maior valor vence, exceto em densidade populacional, onde o menor valor é o vencedor.

### 📥 Entrada de Dados:
- Os dados das cartas serão inseridos manualmente via terminal.
- O sistema solicitará interativamente as informações de cada carta.

### 📤 Saída de Dados:
- Após o cadastro, as propriedades da cidade serão exibidas de forma organizada.
- O resultado da comparação será mostrado, indicando a carta vencedora.

---
*****Funcionalidades

 Cadastro de duas cartas com as seguintes informações:
  Estado
  Nome da cidade
  Código da carta
  População
  Área
  Pontos turísticos
  PIB
Cálculo de densidade populacional e PIB per capita.
Comparação das cartas baseado na **densidade populacional**.
Resultado exibido indicando a carta vencedora ou empate.

*****Como Usar

Insira os dados da Carta 1 (estado, cidade, código, população, área, pontos turísticos e PIB).

Insira os dados da Carta 2.

O programa calculará a densidade populacional e exibirá o resultado final, indicando qual carta venceu.

*****Observações

Este código é referente ao nível Novato do desafio.

Apenas um atributo (densidade populacional) é utilizado para comparação.


## 🏅 Nível Aventureiro

No nível Aventureiro, você expandirá o sistema para incluir a comparação aninhada e a criação de um menu interativo usando `switch`.

### 🆕 Diferença em relação ao Nível Novato:
- **Menu Interativo:** O usuário poderá escolher diferentes atributos para comparação através de um menu.
- **Comparação Aninhada:** Implementação de lógica de comparação mais complexa, utilizando estruturas aninhadas para tomar decisões baseadas em múltiplos atributos.

### 🚩 Novas Funcionalidades:
- **Cadastro de Cartas:** Similar ao nível Novato, com a adição de comparação de múltiplos atributos.
- **Menu Interativo:** Uso de `switch` para criar um menu que permite ao jogador escolher os atributos a serem comparados.
- **Exibição de Resultados:** O sistema exibirá o resultado da comparação, indicando qual carta venceu e qual atributo foi utilizado.

---
*****Como Usar

O programa pedirá os dados da Carta 1:

Nome do país

Área

População

Pontos turísticos

PIB

Em seguida, pedirá os dados da Carta 2 com os mesmos atributos.

Depois, você escolherá qual atributo será usado para comparar as cartas:

1. População
2. Pontos Turísticos
3. Área
4. PIB
5. Densidade


O programa exibirá:

Nomes dos países

Atributo usado na comparação

Valores do atributo para cada carta

Qual carta venceu ou se houve empate

*****Exemplo de Uso
Digite o nome do País (Carta 1): Brasil
Digite a área: 8516.0
Digite a população: 211000000
Digite pontos turísticos: 10
Digite o PIB: 1800.0

Digite o nome do País (Carta 2): Argentina
Digite a área: 2780.0
Digite a população: 45000000
Digite pontos turísticos: 8
Digite o PIB: 500.0

Escolha o atributo para comparação: 1
Resultado:
País 1: Brasil | País 2: Argentina
Atributo: População
População carta 1: 211000000 | População carta 2: 45000000
Resultado: Carta 1 venceu!

*****Observações

Para densidade populacional, vence o país com menor densidade.

O programa trata entradas inválidas com mensagem de "Opção inválida!".

Todas as comparações seguem a regra: maior valor vence, exceto densidade.

## 🏅 Nível Mestre

No nível Mestre, o desafio se intensifica com a adição de funcionalidades avançadas, como menus dinâmicos e lógica de decisão complexa com operadores ternários.

### 🆕 Diferença em relação ao Nível Aventureiro:
- **Escolha de Dois Atributos:** O usuário poderá escolher dois atributos para comparação entre as cartas.
- **Lógica de Decisão Complexa:** Implementação de estruturas de decisão aninhadas e encadeadas, além do uso de operadores ternários para determinar a carta vencedora.
- **Menus Dinâmicos:** Os menus serão dinâmicos, permitindo uma navegação fluida entre as opções de comparação.

### 🚩 Novas Funcionalidades:
- **Comparação de Dois Atributos:** O sistema comparará dois atributos simultaneamente para determinar a carta vencedora.
- **Lógica Avançada:** Uso de operadores ternários e lógica aninhada para lidar com comparações complexas.
- **Empates:** O sistema será capaz de lidar com empates, exibindo mensagens apropriadas.
- **Exibição de Resultados:** Exibição dos resultados das comparações de forma clara e interativa.

---

## 📋 Requisitos Funcionais Comuns
- **Cadastro de Cartas:** O sistema deve permitir o cadastro de cartas com as informações necessárias.
- **Comparação:** O sistema deve comparar as cartas e determinar a vencedora com base nas regras estabelecidas.
- **Exibição de Resultados:** Os resultados devem ser exibidos de forma clara, indicando a carta vencedora.

## 📌 Requisitos Não Funcionais Comuns
- **Usabilidade:** A interface do usuário deve ser simples e intuitiva.
- **Performance:** O sistema deve executar operações sem atrasos perceptíveis.
- **Manutenibilidade:** O código deve ser bem estruturado e documentado.
- **Confiabilidade:** O sistema deve ser robusto e capaz de lidar com entradas inválidas de forma adequada.

---

Boa sorte no desenvolvimento deste desafio e aproveite para aprender e se divertir enquanto progride pelos níveis!

Equipe de Ensino - MateCheck


Objetivo do Projeto

Criar um sistema que permita:
Cadastrar duas cartas com informações de países.
Escolher dois atributos para comparar.
Calcular e exibir o resultado final com clareza, mostrando:
Nome dos países
Atributos usados
Valores comparados
Soma total de cada carta
Qual carta venceu

Opções que iram aparecer no compilador

Digite as informações da Carta 1:
Nome do país
Área
População
Pontos turísticos
PIB 

Digite as informações da Carta 2 com os mesmos dados.

O programa calcula automaticamente a densidade populacional de ambos os países.

Em seguida, escolha dois atributos diferentes para comparar:

1. População
2. Pontos Turísticos
3. Área
4. PIB
5. Densidade

O resultado exibirá:

Os nomes dos países 
Os dois atributos escolhidos
Os valores comparados
A soma final de cada carta
E o vencedor 🎉

Exemplo de saída 

*****RESULTADO FINAL*****

Nome do País vencedor: Brasil
População: Brasil = 211000000 | Argentina = 45000000
PIB: Brasil = 1800.00 | Argentina = 500.00
Soma: Carta 1 = 212800000.00 | Carta 2 = 45450000.00

🏆 Brasil venceu
PARABÉNS🎉🎉🎉🎉🎉

Observações Importantes

O programa impede que o usuário escolha o mesmo atributo duas vezes.
Todos os cálculos de soma e comparação são feitos automaticamente.
Mensagens com emojis deixam o resultado mais amigável 🌟
O código tem alguns comentários para facilitar a compreensão.
