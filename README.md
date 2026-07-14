<div align="center">

<img src="assets/pr-header.svg" alt="Pull request aberto: feat — adicionar Francisco Montalvão ao seu time de backend" width="840">

<br><br>

`💬 Conversa` · `📝 Commits (3)` · `✅ Checks (4)` · `📁 Arquivos alterados (2)`

</div>

<br>

## 💬 Conversa

> **barbaro-br** comentou — *autor deste PR*

Este pull request adiciona um **desenvolvedor backend júnior** ao seu time — Java, Spring Boot e PostgreSQL, com uma particularidade: antes de escrever código, passei anos **vendendo**. Hoje construo os sistemas que sustentam vendas.

**Por que aceitar este merge:** não sou dev de tutorial. Meu principal projeto é um sistema completo pra uma hamburgueria de verdade — cliente real, pedidos reais, regra de negócio real, indo pra produção. E a experiência de vendas veio junto no pacote: quem já negociou cara a cara com cliente difícil não tem medo de requisito mal escrito.

<br>

## 📁 Arquivos alterados

**`seu-time/backend/composicao.diff`**

```diff
  time de backend
+ dev que já colocou sistema real em produção (não é clone de tutorial)
+ domínio rico: entities com validação e comportamento — sem setter anêmico
+ migrations escritas à mão, constraint por constraint (Flyway, 11 tabelas)
+ contract-first: API documentada antes da primeira linha de código
+ zero trust no front: backend recalcula todo total — o cliente nunca dita preço
- medo de requisito mal escrito
- "funciona na minha máquina" como resposta final
```

**`seu-time/soft-skills.diff`**

```diff
  comunicação com stakeholders
+ anos de vendas na vida real: escuta, negociação e paciência forjadas no balcão
+ tradução fluente entre "o que o cliente pediu" e "o que o cliente precisa"
- silêncio desconfortável na daily
```

<br>

## 📝 Commits

```
* f5a9c21  feat!: migração de vendas para engenharia de software
|          BREAKING CHANGE — não foi acidente, foi deploy planejado.
* 8d3e07b  feat: sistema de pedidos em produção para cliente real
|          Spring Boot · JPA · Flyway · Docker — hamburgueria de verdade.
* 1a00000  init: primeiro "Hello, World"
```

<br>

## ✅ Checks

| Check | Status | Detalhes |
|---|---|---|
| **build** | ✅ passou | Java 21→25 · Spring Boot 4 · PostgreSQL · Docker · Maven |
| **integração com produção** | ✅ passou | Sistema real pra cliente real — repo privado (projeto comercial); demo e walkthrough do código sob pedido |
| **formação** | ✅ passou | Engenharia de Software · base em Montalvânia — MG, Brasil |
| **review** | ⏳ aguardando | Um revisor precisa aprovar. **Esse revisor é você.** |

<div align="center">

![Java](https://img.shields.io/badge/Java_21→25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br>

## 📋 Checklist de review

- [x] Sabe modelar banco de dados? *— schema de 11 tabelas escrito à mão, versionado com Flyway*
- [x] Escreve API que outro dev entende? *— contract-first: o contrato nasce antes do código*
- [x] Aguenta pressão e cliente difícil? *— sobrevivi a anos de vendas; a daily é moleza*
- [x] Continua aprendendo? *— JPA a fundo, arquitetura de software e boas práticas REST, todo dia*
- [ ] Faz parte do seu time? *— esse checkbox é seu* 👇

<br>

## 🔗 Issues vinculadas

> **Closes `#404`** — *"vaga de backend júnior não encontrada"* · aberto por **barbaro-br** · label: `remoto ou presencial`

<br>

## ✅ Merge pull request

> **Sem conflitos com o branch base.** O merge leva menos de um minuto:

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Merge_via_LinkedIn-238636?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/francisco-montalvao-76a1a090/)
[![Email](https://img.shields.io/badge/Merge_via_Email-238636?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:f.montalvao@outlook.com)

<br>

`// squash and merge recomendado: anos de história, um commit objetivo.`

</div>
