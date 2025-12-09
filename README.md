📟 Calculadora JavaScript

Uma calculadora simples desenvolvida com HTML, CSS e JavaScript, capaz de realizar operações matemáticas básicas como soma, subtração, multiplicação e divisão.

📁 Estrutura do Projeto
/Calculadora
│── CalculadoraJavaScript.html
│── CalculadoraJavaScript.css
│── CalculadoraJavaScript.js

🖥️ Funcionalidades

✔ Inserção de números e ponto decimal 

CalculadoraJavaScript


✔ Operações: +, -, *, / 

CalculadoraJavaScript


✔ Botão AC para limpar tudo 

CalculadoraJavaScript


✔ Botão DEL para apagar o último dígito 

CalculadoraJavaScript


✔ Cálculo com atualização dinâmica do visor
✔ Layout responsivo baseado em grid 

CalculadoraJavaScript

📄 Arquivos
🔹 HTML — Interface principal

Define a estrutura da calculadora, incluindo botões e display.
Trecho representativo:

Container .Calculadora com display (.output) e botões de números e operações 

CalculadoraJavaScript

🔹 CSS — Estilização

Responsável pela aparência moderna e escura (dark mode), usando CSS Grid para organizar a calculadora.

display: grid para construir o layout

Cores em tons escuros e destaques em azul 

CalculadoraJavaScript

🔹 JavaScript — Lógica da calculadora

Controla cliques, operações, exibição e cálculos.
Principais funções:

appendNumber() – adiciona números ao display atual 

CalculadoraJavaScript

chooseOperation() – define a operação e move valores entre displays 

CalculadoraJavaScript

compute() – realiza o cálculo e exibe o resultado 

CalculadoraJavaScript

Manipula botões de AC, DEL e igual

▶️ Como Executar

Baixe os três arquivos do projeto.

Coloque-os na mesma pasta.

Abra CalculadoraJavaScript.html no navegador.

A calculadora estará pronta para uso!

🛠️ Melhorias Futuras (opcionais)

Teclado numérico funcional (input por teclado)

Tema claro/escuro
Histórico de operações

Tratamento para divisão por zero
