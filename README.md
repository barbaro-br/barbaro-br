<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Backend+Developer+%C2%B7+Java+%26+Spring+Boot;De+vendas+para+tecnologia.+A+virada+foi+intencional.;Construindo+software+real+para+neg%C3%B3cios+reais.)

</div>

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   $ whoami                                                   ║
║   > Francisco Montalvão                                      ║
║                                                              ║
║   $ cat ./sobre.txt                                          ║
║   > Backend Developer · Java & Spring Boot                   ║
║   > Engenharia de Software · Montalvânia, MG                 ║
║   > Antes vendia. Agora constrói APIs.                       ║
║                                                              ║
║   $ git log --oneline --all                                  ║
║   > e94560a feat: entrar na área de tecnologia               ║
║   > 16213ef chore: abandonar zona de conforto                ║
║   > 0f3460b init: primeiro Hello World                       ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

<br>

## `$ cat ./destaque.md` — 🍔 Mestre do Sabor

> **Sistema completo para uma hamburgueria real** — cliente de verdade, pedidos de verdade,
> regras de negócio de verdade. Não é projeto de tutorial: é software indo pra produção.

```
┌─────────────────┐      ┌──────────────────┐
│  App do Cliente │      │   Painel Admin   │
│   React + Vite  │      │ React + Tailwind │
│ cardápio·pedido │      │ Kanban·PDV·CRM   │
└────────┬────────┘      └────────┬─────────┘
         │      REST / JSON       │
         ▼                        ▼
┌──────────────────────────────────────────┐
│           API · Spring Boot 4            │
│  Java 25 · JPA · Flyway · Bean Validation│
│  contrato definido ANTES do código       │
└────────────────────┬─────────────────────┘
                     ▼
          ┌─────────────────────┐
          │  PostgreSQL 18      │
          │  Docker Compose     │
          └─────────────────────┘
```

**Decisões de engenharia que eu defendo em entrevista:**

- 🔒 **Zero trust no cliente** — backend recalcula todos os totais; front nunca dita preço
- 📸 **Pedido é snapshot** — endereço e preços congelados no momento da compra (histórico imutável)
- 🗃️ **Migrations versionadas** com Flyway — schema com 11 tabelas escrito à mão, constraint por constraint
- 🧱 **Domínio rico** — entities com validação e comportamento, sem setters anêmicos, sem Lombok
- 📜 **Contract-first** — API documentada antes da primeira linha de código; front e back evoluem sem surpresa

**Roadmap:**

- [x] Modelagem do banco + migrations (Flyway)
- [x] Docker Compose gerenciado pela aplicação
- [x] Domínios Settings e Category (CRUD completo, validações, 409/404 semânticos)
- [ ] Customer · Product · Order (em andamento)
- [ ] Autenticação JWT com Spring Security
- [ ] Deploy em VPS: Caddy + Docker + backups automatizados com pg_dump

---

## `$ ls ./outros-projetos`

**[backend-challenges](https://github.com/Francisco-Montalvao/backend-challenges)**
```
Repositório de desafios práticos organizados por nível.
Júnior → Pleno → Sênior. Qualquer linguagem.
A ideia: aprender fazendo, não só lendo.
```

**[Gerenciador de Produtos](https://github.com/Francisco-Montalvao/backend-challenges-desafio-gerenciador-de-produtos)**
```
API REST completa. CRUD de produtos e categorias.
Validações, exceções customizadas, boas práticas REST.
Java 21 · Spring Boot · PostgreSQL · Docker
```

**[Customer Loans API](https://github.com/Francisco-Montalvao/loans)**
```
Elegibilidade para modalidades de empréstimo.
Regras de negócio por renda, idade e localização.
Java 21 · Spring Boot · Bean Validation
```

---

## `$ cat ./stack.json`

<div align="center">

![Java](https://img.shields.io/badge/Java_21→25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Swagger](https://img.shields.io/badge/SpringDoc_·_Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)

</div>

---

## `$ ./status --now`

```java
public String[] atualmente() {
    return new String[]{
        "Construindo: backend real em produção para cliente real (Mestre do Sabor)",
        "Estudando: arquitetura de software, JPA a fundo e boas práticas REST",
        "Buscando: primeira vaga como desenvolvedor backend — remoto ou presencial"
    };
}
```

<div align="center">

![Streak](https://streak-stats.demolab.com?user=Francisco-Montalvao&theme=tokyonight&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=8b949e)

</div>

---

## `$ cat ./fora_do_codigo.txt`

```
⚽ Futebol     → melhor que qualquer standup
🚴 Ciclismo    → debug em movimento
📚 Leitura     → refatorando o sistema operacional
🧘 Estoicismo  → tratamento de exceções da vida real
```

---

## `$ cat ./contatos.txt`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/francisco-montalvao-76a1a090/)
[![Email](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:f.montalvao@outlook.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5538997225058)

</div>

---

<div align="center">

```
// Ainda em desenvolvimento. Como todo bom software.
```

</div>
