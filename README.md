<img width="6000" alt="Um programa em Python capaz de converter unidades de Celsius para Fahrenheit, de Milhas para Metros, de Dólar para Real, e outras  Três grandezas, um código" src="https://github.com/user-attachments/assets/a32e2202-e3cc-4ebe-a2e6-93f2a3cc91e9" />

---
**Aluno:** Luis Navarro Erbetta


**Disciplina:** PCD


**Professores Orientadores:** Daniel Roberto Cassar,
                              Leandro Nascimento Lemos,
                              James Moraes de Almeida


**Linguagem:** Python

## Resumo
Este projeto consiste no desenvolvimento de um Conversor de Medidas em Python, com interface gráfica. A aplicação permite realizar conversões em três categorias distintas: unidades de temperatura (Celsius, Fahrenheit e Kelvin), unidades de distância (metros, quilômetros, milhas, polegadas, entre outras) e taxas de câmbio entre diferentes moedas. O objetivo central foi aplicar conceitos fundamentais de programação — como funções e manipulação de entrada de dados — integrados a uma interface visual intuitiva que facilita o uso por qualquer tipo de usuário. O resultado final é uma ferramenta funcional, organizada e de fácil utilização.

## Explicação
Visão Geral da Aplicação
O projeto foi desenvolvido inteiramente em Python, aproveitando das bibliotecas disponíveis para construção de interfaces gráficas. A aplicação é dividida em três módulos principais de conversão, cada um acessível por meio de janelas separadas na interface.

## Interface Gráfica
A interface foi construída para oferecer uma experiência de uso simples e direta. O usuário insere o valor que deseja converter, seleciona a unidade de entrada e a unidade de saída por meio de botões, e obtém o resultado de forma imediata. Essa abordagem elimina a necessidade de interação via linha de comando, tornando o programa acessível a pessoas sem familiaridade com programação.

## Módulo de Temperatura
- O módulo de temperatura suporta conversões entre as três escalas termométricas mais utilizadas:
- Celsius (°C): escala padrão no Brasil e na maioria dos países.
- Fahrenheit (°F): amplamente utilizada nos Estados Unidos.
- Kelvin (K): escala adotada no contexto científico.
As fórmulas de conversão aplicadas seguem as definições matemáticas consagradas, garantindo precisão nos resultados. Por exemplo, a conversão de Celsius para Fahrenheit é dada por °F = (°C × 9/5) + 32, e de Celsius para Kelvin por K = °C + 273,15.

## Módulo de Distância
O módulo de distância permite converter entre diferentes unidades de comprimento, como metros, quilômetros, centímetros, milímetros, milhas e polegadas. Cada conversão é realizada com base em fatores de escala bem definidos, assegurando que os cálculos sejam precisos independentemente da combinação de unidades escolhida pelo usuário.

## Módulo de Câmbio
O módulo de taxas de câmbio permite ao usuário converter valores monetários entre diferentes moedas. Nele, são utilizadas taxas de conversão fixas (definidas no código). Esse módulo exemplifica a capacidade de integração do Python com serviços externos, dando uma dimensão prática e do dia a dia à aplicação.

## Lógica de Programação
Toda a lógica de cálculo foi organizada em funções específicas para cada tipo de conversão. A separação entre a camada de lógica e a camada de interface facilita a manutenção e a eventual expansão do projeto.

## Resultados
Ao final do desenvolvimento, o Conversor de Medidas apresentou os seguintes resultados:
Interface funcional e responsiva: a interface responde corretamente às entradas do usuário, exibindo os resultados de forma clara e em tempo real.
Precisão nas conversões: todos os cálculos de temperatura e distância foram validados com valores de referência conhecidos, confirmando a exatidão das fórmulas implementadas.
Cobertura das categorias propostas: as três categorias de conversão — temperatura, distância e câmbio — foram implementadas com sucesso e estão acessíveis pela interface.
Uso intuitivo da interface: a organização visual da aplicação permite que o usuário compreenda rapidamente como utilizá-la, sem necessidade de instruções adicionais.
Código estruturado e legível: a separação em funções por comentários internos resultou em um código bem organizado e de fácil leitura.

## Discussão
O desenvolvimento deste projeto permitiu consolidar uma série de competências fundamentais em programação. A construção da interface gráfica foi um dos pontos de maior aprendizado, pois exigiu compreender como conectar eventos visuais (cliques de botão e valores fornecidos pelo usuário) à lógica de cálculo implementada no código.
A organização do projeto se mostrou uma decisão acertada: ao separar cada categoria de conversão em sua própria célula, tornou-se simples adicionar novas unidades ou corrigir eventuais problemas sem impactar o restante da aplicação.
Entre os desafios enfrentados, destacam-se a programação adequada da interface e como relacioná-la com as conversões do código. 
Em síntese, o Conversor de Medidas cumpriu plenamente os objetivos propostos, entregando uma aplicação útil, funcional e bem estruturada, que demonstra de forma prática os fundamentos da programação em Python aplicados a um problema do cotidiano.

## Referências 

**Tkinter**


Tkinter no Python: Guia Completo - Crie Interfaces do Zero. Disponível em: <https://www.hashtagtreinamentos.com/tkinter-no-python?conversion=base-py-go-post&gad_source=1&gad_campaignid=15353425825&gbraid=0AAAAADLlh8-DtN5wrsZmYCnN2d62HYQnT&gclid=Cj0KCQjw3K7RBhDJARIsAKRtP5TNYPFVnxS0LcSCmRxdgE8NwulmxSPWW9LuITwgE2GqV4fYHtpLqcgaAneeEALw_wcB>. Acesso em: 22 jun. 2026.

‌PYTHON SOFTWARE FOUNDATION. tkinter — Python interface to Tcl/Tk — Python 3.7.2 documentation. Disponível em: <https://docs.python.org/3/library/tkinter.html>.

‌**Taxas de câmbio**


XE CURRENCY CONVERTER. XE: The World's Trusted Currency Authority. Disponível em: https://www.xe.com. Acesso em: 22 jun. 2026.

EXCHANGE-RATES.ORG. Exchange Rates — Currency Converter. Disponível em: https://www.exchange-rates.org. Acesso em: 22 jun. 2026.

**Programação do código**


CASSAR, Daniel R. ATP-103 A - Funções. [S. l.], 2025. 1 Jupyter Notebook (ATP-103_A_-_Funções__1_.ipynb). Disponível em: arquivo local. Acesso em: 22 jun. 2026.

CASSAR, Daniel R. ATP-103 B - Funções anônimas em Python. [S. l.], 2025. 1 Jupyter Notebook (ATP-103_B_-_Funções_anônimas_em_Python.ipynb). Disponível em: arquivo local. Acesso em: 22 jun. 2026.
