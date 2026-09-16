# 💳 Gerador de Cartão Virtual

[![Licença](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status do Deploy](https://img.shields.io/badge/Deploy-Online-brightgreen.svg)](https://gerador-de-cartao-virtual.onrender.com)
[![Tecnologias](https://img.shields.io/badge/HTML5-CSS3-JavaScript-orange.svg)](#-tecnologias-utilizadas)

Uma aplicação web moderna e responsiva desenvolvida para simular a emissão instantânea de cartões de crédito virtuais a partir de um cadastro simples de cliente.

🔗 **Acesse o Projeto Online:** [https://gerador-de-cartao-virtual.onrender.com](https://gerador-de-cartao-virtual.onrender.com)

---

## 📸 Previews do Projeto

<div align="center">
  <h3>1. Formulário de Cadastro</h3>
  <img src="./assets/preview2.png" alt="Tela de Cadastro" width="700px" style="border-radius: 8px;">

  <br><br>

  <h3>2. Cartão Virtual Gerado (Verde Menta)</h3>
  <img src="./assets/preview.png" alt="Cartão Virtual Gerado" width="700px" style="border-radius: 8px;">
</div>

---

## ✨ Funcionalidades

- **Formulário Completo de Cadastro:** Coleta de dados pessoais (Nome completo, CPF, Data de nascimento, Renda mensal, CEP, Endereço, Complemento e Estado Civil).
- **Escolha de Vencimento:** Seletor customizado para o dia da fatura (`05`, `15`, `20` ou `30`).
- **Geração Automática do Cartão:**
  - Número de cartão gerado de forma totalmente aleatória no formato padrão.
  - Validade calculada automaticamente para **10 anos** a partir da data de criação (Ex: `mês atual/2036`).
  - Visual em tom **Verde Menta** com chip simulado e dados do titular.
- **Interface Responsiva:** Design limpo e adaptável para celulares e computadores.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da aplicação.
- **CSS3:** Estilização com paleta em tons de verde suave/menta, variáveis e layout flexível.
- **JavaScript (ES6+):** Lógica de geração de números randômicos, manipulação do DOM e cálculo dinâmico de datas.

---

## 🚀 Como Executar Localmente

Caso queira clonar e testar o projeto na sua máquina:

1. Clone o repositório:
   ```bash
   git clone [https://github.com/AnteroVieira/gerador-de-cartao-virtual.git](https://github.com/AnteroVieira/gerador-de-cartao-virtual.git)

   Acesse a pasta do projeto digitando " cd gerador-de-cartao-virtual " no terminal.
   Abra o arquivo index.html em qualquer navegador web.