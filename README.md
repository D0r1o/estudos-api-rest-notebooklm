# 📚 Miniguia de Estudos sobre APIs REST com NotebookLM

<p align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/D0r1o/miniguia-api-rest-notebooklm?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/D0r1o/miniguia-api-rest-notebooklm?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/D0r1o/miniguia-api-rest-notebooklm?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Markdown-Documentation-blue?style=for-the-badge\&logo=markdown)

</p>

---

## 🎯 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)** com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa através do **NotebookLM**.

O tema escolhido foi **APIs REST**, devido à sua importância no desenvolvimento de sistemas modernos e ampla utilização no mercado de tecnologia.

Durante o projeto foram utilizadas fontes acadêmicas, documentações oficiais, padrões de mercado e boas práticas reconhecidas pela indústria para construir um caderno temático completo sobre o assunto.

---

## 🧠 Objetivos de Aprendizagem

* Compreender os princípios fundamentais das APIs REST;
* Estudar as restrições arquiteturais definidas por Roy Fielding;
* Conhecer os principais métodos HTTP e códigos de status;
* Analisar boas práticas de design de APIs;
* Investigar padrões modernos de documentação utilizando OpenAPI;
* Estudar vulnerabilidades e estratégias de mitigação segundo o OWASP;
* Compreender o Modelo de Maturidade de Richardson;
* Explorar padrões de tratamento de erros através das RFCs 7807 e 9457.

---

# 🗂️ Estrutura do Repositório

```bash
📦 miniguia-api-rest-notebooklm
│
├── README.md
├── assets/
│   ├── imagens/
│   └── prints/
└── fontes/
```

---

# 🔎 Curadoria de Fontes

## Fontes Principais

| Fonte                                                                | Tipo                  |
| -------------------------------------------------------------------- | --------------------- |
| Principled Design of the Modern Web Architecture (Fielding & Taylor) | Artigo Científico     |
| Uma visão geral do HTTP - MDN                                        | Documentação Oficial  |
| OpenAPI Specification                                                | Especificação Técnica |
| REST Security Cheat Sheet - OWASP                                    | Guia de Segurança     |
| API Design Guide - Google Cloud                                      | Guia de Boas Práticas |

## Referências Complementares

* RFC 7807 - Problem Details for HTTP APIs;
* RFC 9457 - Problem Details for HTTP APIs;
* OWASP API Security Top 10 (2023);
* Richardson Maturity Model - Martin Fowler;
* Microsoft API Guidelines;
* Azure Architecture Center;
* Swagger Documentation;
* Artigos acadêmicos sobre APIs REST.

---

# 🤖 Engenharia de Prompts

Para orientar as respostas do NotebookLM foi utilizada a seguinte persona:

> **"Assuma a personalidade de um Especialista de ensino."**

## Prompt 1

```text
Explique o conceito de API REST de forma didática, apresentando seus princípios fundamentais e exemplos práticos.
```

### Principais Aprendizados

* REST é um estilo arquitetural;
* APIs REST são orientadas a recursos;
* URIs identificam recursos únicos;
* HTTP fornece os verbos de manipulação.

---

## Prompt 2

```text
Explique os princípios arquiteturais definidos por Roy Fielding para uma API REST e apresente exemplos de implementação.
```

### Principais Aprendizados

* Cliente-Servidor;
* Stateless;
* Cache;
* Interface Uniforme;
* Sistema em Camadas;
* Código sob Demanda.

---

## Prompt 3

```text
Compare APIs REST, SOAP e GraphQL destacando vantagens, limitações e cenários ideais de uso.
```

### Principais Aprendizados

| Tecnologia | Principal Característica            |
| ---------- | ----------------------------------- |
| REST       | Simplicidade e escalabilidade       |
| SOAP       | Segurança e transações              |
| GraphQL    | Flexibilidade e eficiência de dados |

---

## Prompt 4

```text
Quais são as principais vulnerabilidades de segurança em APIs REST segundo a OWASP e quais estratégias podem ser adotadas para mitigá-las?
```

### Principais Aprendizados

* BOLA;
* Broken Authentication;
* SSRF;
* Rate Limiting;
* HTTPS/TLS;
* OAuth 2.1 e JWT.

---

## Prompt 5

```text
Explique os quatro níveis do Richardson Maturity Model e forneça exemplos práticos para cada nível.
```

### Principais Aprendizados

| Nível | Descrição      |
| ----- | -------------- |
| 0     | RPC sobre HTTP |
| 1     | Recursos       |
| 2     | Verbos HTTP    |
| 3     | HATEOAS        |

---

## Prompt 6

```text
Quais são as diferenças entre o RFC 7807 e o RFC 9457 no tratamento de erros em APIs HTTP?
```

### Principais Aprendizados

* Padronização de erros;
* Registro IANA;
* Melhor suporte a múltiplos problemas;
* Maior extensibilidade.

---

## Prompt 7

```text
Explique a finalidade da especificação OpenAPI e como ela contribui para o desenvolvimento, documentação e manutenção de APIs REST.
```

### Principais Aprendizados

* API First;
* Geração automática de documentação;
* Governança;
* Testes de contrato;
* Automação.

---

# 🩹 Dificuldades Encontradas e Soluções

| Dificuldade                | Solução Aplicada                   |
| -------------------------- | ---------------------------------- |
| Respostas superficiais     | Refinamento dos prompts            |
| Excesso de conteúdo        | Organização temática               |
| Pouca profundidade técnica | Inclusão de artigos acadêmicos     |
| Falta de exemplos          | Solicitação de casos práticos      |
| Respostas genéricas        | Definição de persona especializada |

---

# 📘 Miniguia de Estudos

## O que é uma API REST?

Uma API REST é uma interface de comunicação entre sistemas baseada no estilo arquitetural REST, utilizando recursos identificados por URIs e manipulados através dos métodos HTTP.

---

## 🌐 Métodos HTTP

| Método | Função                  |
| ------ | ----------------------- |
| GET    | Recuperar dados         |
| POST   | Criar recursos          |
| PUT    | Atualizar integralmente |
| PATCH  | Atualizar parcialmente  |
| DELETE | Excluir recursos        |

---

## 🏛️ Restrições Arquiteturais REST

* Cliente-Servidor;
* Stateless;
* Cache;
* Interface Uniforme;
* Sistema em Camadas;
* Código sob Demanda.

---

## 🔐 Segurança em APIs

Boas práticas fundamentais:

* Utilizar HTTPS;
* Implementar autenticação robusta;
* Aplicar autorização adequada;
* Utilizar Rate Limiting;
* Validar entradas;
* Seguir o OWASP API Security Top 10.

---

## 📈 Richardson Maturity Model

```text
Nível 0 → RPC
Nível 1 → Recursos
Nível 2 → Verbos HTTP
Nível 3 → HATEOAS
```

---

# 📚 Glossário

| Termo         | Definição                                      |
| ------------- | ---------------------------------------------- |
| API           | Interface de Programação de Aplicações         |
| REST          | Estilo arquitetural para sistemas distribuídos |
| URI           | Identificador único de recurso                 |
| JSON          | Formato de troca de dados                      |
| HATEOAS       | Hipermídia como motor do estado da aplicação   |
| JWT           | JSON Web Token                                 |
| OAuth         | Protocolo de autorização                       |
| OpenAPI       | Especificação para descrição de APIs           |
| BOLA          | Vulnerabilidade de autorização em objetos      |
| Rate Limiting | Limitação de requisições                       |

---

# 🚀 Prompts Reutilizáveis

```text
Explique [conceito] de forma didática com exemplos práticos.
```

```text
Compare [tecnologia A] e [tecnologia B] destacando vantagens, desvantagens e casos de uso.
```

```text
Quais são as melhores práticas para implementar [conceito] em APIs REST?
```

```text
Resuma os principais pontos sobre [tema] em tópicos.
```

```text
Quais perguntas técnicas sobre [tema] podem ser feitas em entrevistas?
```

---

# 💡 Principais Aprendizados

O desenvolvimento deste projeto permitiu consolidar conhecimentos sobre arquitetura REST, segurança, documentação, governança e boas práticas de desenvolvimento de APIs.

Além disso, a experiência demonstrou como ferramentas de Inteligência Artificial podem potencializar o aprendizado quando utilizadas de maneira crítica, estruturada e apoiadas por fontes confiáveis.

---

## 👨‍💻 Autor

**Renan Dorio**

* LinkedIn: https://www.linkedin.com/in/renan-dorio-0b9b55a5
* GitHub: https://github.com/D0r1o

---

⭐ Projeto desenvolvido para fins educacionais na plataforma DIO.

