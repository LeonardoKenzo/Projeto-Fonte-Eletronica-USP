# Projeto: Fonte de Tensão Ajustável (3V a 12V - 100mA)
## 📋 Instruções
   Este projeto consiste na montagem de uma fonte de tensão ajustável capaz de fornecer uma saída entre 3V e 12V com uma corrente máxima de 100mA. O objetivo é aplicar conceitos de eletrônica analógica, como regulação linear de tensão, seleção de componentes e montagem de circuitos.
   
  Os cálculos de dimensionamento, o esquema do circuito e a lista de componentes estão descritos abaixo.

## 🧰 Tabela de Componentes Utilizados
|Quantidade|Nome do Componente |Valor  | Modelo	Especificações                    |
|----------|-------------------|-------|------------------------------------------|
|1  |Transformador	           |R$00,00|12V  500mA	Entrada 127V AC, saída 12V AC |
|1	|Ponte Retificadora	       |R$00,00|KBPC ou 4 diodos 1N4007	Corrente máx: 1A  |
|1	|Capacitor Eletrolítico    |R$00,00|1000µF / 25V	                            |
|1	|CI Regulador de Tensão    |R$00,00|LM317	Regulável de 1,25V a 37V            |
|1	|Potenciômetro	           |R$00,00|5kΩ	Ajuste da tensão de saída             |
|1	|Capacitor Cerâmico	       |R$00,00|0,1µF	Estabilidade do CI                  |
|1	|Capacitor Eletrolítico    |R$00,00|1µF / 25V	Estabilidade da saída           |
|1	|Resistor	                 |R$00,00|240Ω	Definidor de tensão (LM317)         |
|1	|Dissipador de Calor	     |R$00,00|Pequeno para CI	Dissipação térmica        |

## 📝 Descrição dos Componentes
* **Transformador:** Reduz a tensão da rede elétrica (127V AC) para 12V AC, adequada para a fonte.

* **Ponte Retificadora / Diodos:** Convertem a tensão AC em DC, realizando a retificação de onda completa.

* **Capacitor de 1000µF:** Atua como filtro, reduzindo o ripple da tensão após a retificação.

* **LM317:** CI regulador ajustável que permite variar a tensão de saída entre 3V e 12V.

* **Potenciômetro:** Permite ajustar a tensão de saída de forma precisa.

* **Capacitores de 0,1µF e 1µF:** Melhoram a estabilidade da tensão de saída e previnem oscilações.

* **Resistor de 240Ω:** Trabalha junto com o potenciômetro para determinar a tensão de saída segundo a fórmula do LM317.

* **Dissipador de Calor:** Evita o superaquecimento do LM317 durante a operação.

* **Cabos:** Para realizar todas as interligações do circuito.

## 📈 Circuito do Projeto
📷 Imagem do Esquema Elétrico:
(Adicione a imagem do esquema aqui)

📷 Imagem da Montagem Física (Protoboard ou PCB):
(Adicione a imagem da montagem aqui)

## ✏️ Cálculos Utilizados
ini
Copiar código
Vout = 1.25V × (1 + (R2/R1)) + (Iadj × R2)
(Adicione os cálculos detalhados em formato de imagem ou texto)

## 👨‍🎓 Alunos Responsáveis
Leonardo Kenzo Tanaka [Github: [LeonardoKenzo](https://github.com/LeonardoKenzo)]

Pedro Teidi de Sa Yamacita [Github: [pedroYamacita](https://github.com/pedroYamacita)]

Gustavo de Faria Fernandes [Github: [Gustavo-Fernandes04](https://github.com/Gustavo-Fernandes04)]

Enzo Ferreira de Castro Lima
