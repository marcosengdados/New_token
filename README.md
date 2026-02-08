# 🚀 NANOToken — Projeto Acadêmico de Blockchain (ERC‑20)

![Solidity](https://img.shields.io/badge/Solidity-0.4.24-blue)
![ERC20](https://img.shields.io/badge/Standard-ERC20-success)
![Blockchain](https://img.shields.io/badge/Blockchain-Ethereum-informational)
![Academic](https://img.shields.io/badge/Project-Acad%C3%AAmico-orange)

---

## 📌 Visão Geral

O **NANOToken (FIAPNANO Coin)** é um **smart contract ERC‑20** desenvolvido em **Solidity**, criado como **atividade prática acadêmica** no contexto de um **curso de Blockchain**.

O objetivo do projeto é **demonstrar na prática**:

* A criação de um token fungível
* O uso do padrão **ERC‑20**
* A interação com carteiras (**MetaMask**)
* O deploy e testes em ambiente de desenvolvimento (**Remix IDE**)

---

## 🎯 Objetivos do Projeto

✔️ Compreender a arquitetura de um token ERC‑20
✔️ Aplicar conceitos de **SafeMath** para segurança aritmética
✔️ Testar transações em ambiente de blockchain
✔️ Simular emissão e transferência de tokens
✔️ Integrar contrato inteligente com carteira digital

---

## 🧠 Contexto Acadêmico

Este projeto faz parte das atividades práticas de um **curso de Blockchain**, abordando conceitos como:

* Blockchain pública vs privada
* Tokens fungíveis e não fungíveis
* Smart Contracts
* ERC‑20
* Segurança em contratos inteligentes
* Uso do Remix IDE e MetaMask

> ⚠️ **Aviso:** Este contrato foi desenvolvido **exclusivamente para fins educacionais**.

---

## 🛠️ Tecnologias Utilizadas

* **Solidity ^0.4.24**
* **Ethereum (ambiente de testes)**
* **Remix IDE**
* **MetaMask**
* **Padrão ERC‑20**

---

## 📄 Estrutura do Contrato

O arquivo principal do projeto é:

```bash
contracts/
 └── NANOToken.sol
```

### Principais Componentes

* **SafeMath** → Evita overflow e underflow
* **ERC20Interface** → Define o padrão ERC‑20
* **ApproveAndCallFallBack** → Aprovação com execução
* **NANOToken** → Implementação final do token

---

## 💰 Especificações do Token

| Atributo       | Valor          |
| -------------- | -------------- |
| Nome           | FIAPNANO Coin  |
| Símbolo        | NANOFaiol      |
| Decimais       | 2              |
| Supply Inicial | 100.000 tokens |
| Padrão         | ERC‑20         |

O supply inicial é atribuído a um endereço específico definido no construtor do contrato.

---

## 🧪 Como Testar o Contrato

### 1️⃣ Abrir no Remix

* Acesse: [https://remix.ethereum.org](https://remix.ethereum.org)
* Crie um novo arquivo `NANOToken.sol`
* Cole o código do contrato

### 2️⃣ Compilar

* Selecione o compilador **Solidity 0.4.24**
* Compile o contrato

### 3️⃣ Deploy

* Use o ambiente **Injected Provider**
* Conecte com a **MetaMask**
* Realize o deploy

### 4️⃣ Testes

* Verifique o balance inicial
* Execute `transfer`, `approve` e `transferFrom`
* Observe os eventos no console

---

## 🔐 Segurança

✔️ Uso de **SafeMath**
✔️ Fallback bloqueando envio de Ether
✔️ Implementação fiel ao padrão ERC‑20

> 🔎 Apesar disso, **não é recomendado para uso em produção**.

---

## 📚 Aprendizados

Com este projeto foi possível consolidar:

* Funcionamento de contratos inteligentes
* Estrutura de tokens ERC‑20
* Integração com wallets
* Deploy e testes em blockchain

---

## 👨‍🎓 Autor

Projeto desenvolvido para fins **acadêmicos e educacionais**, como parte do aprendizado em **Blockchain e Smart Contracts**.

---

## 📜 Licença

Este projeto é distribuído sob licença **MIT**, exclusivamente para estudo e aprendizado.

---

⭐ Se este repositório te ajudou nos estudos, deixe uma estrela!
