# 📚 Miniguia de Estudos sobre APIs REST com NotebookLM

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DIO-Desafio%20de%20Projeto-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NotebookLM-Aprendizagem%20Ativa-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/API-REST-green?style=for-the-badge" />
</p>

---

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio da **DIO (Digital Innovation One)** com o objetivo de explorar o uso da **Inteligência Artificial como ferramenta de aprendizagem ativa** utilizando o **NotebookLM**.

O tema escolhido foi **APIs REST**, devido à sua ampla utilização no desenvolvimento de sistemas modernos e sua relevância no mercado de tecnologia.

Ao longo do estudo, foram utilizadas documentações oficiais, artigos acadêmicos e guias de boas práticas para construir um caderno temático capaz de consolidar conhecimentos sobre arquitetura REST, segurança, documentação, maturidade e governança de APIs.

---

## 🎯 Objetivos de Estudo

- Compreender os fundamentos das APIs REST;
- Estudar os princípios arquiteturais definidos por Roy Fielding;
- Entender os métodos HTTP e seus códigos de status;
- Conhecer boas práticas de design de APIs;
- Estudar segurança em APIs segundo o OWASP;
- Compreender o Richardson Maturity Model;
- Conhecer os padrões RFC 7807 e RFC 9457 para tratamento de erros;
- Explorar a OpenAPI Specification e sua aplicação no ciclo de vida das APIs;
- Utilizar IA como ferramenta de apoio ao aprendizado.

---

## 🧠 Competências Desenvolvidas

- Arquitetura REST;
- Design de APIs;
- Segurança de APIs;
- OpenAPI Specification;
- Engenharia de Prompts;
- Curadoria Técnica de Conteúdo;
- Aprendizagem Ativa com IA;
- Pesquisa Técnica e Acadêmica;
- Documentação Técnica.

---

## 🗂️ Estrutura do Repositório

```bash
📦 estudos-api-rest-notebooklm
│
├── README.md
├── assets/
│   ├── imagens/
│   └── prints/
```

---

# 🔎 Curadoria de Fontes

## Fontes Principais

| Fonte | Tipo |
|--------|------|
| Principled Design of the Modern Web Architecture (Fielding & Taylor) | Artigo Científico |
| API Design Guide - Google Cloud | Guia Oficial |
| OpenAPI Specification | Especificação Técnica |
| REST Security Cheat Sheet - OWASP | Guia de Segurança |
| Uma visão geral do HTTP - MDN | Documentação Oficial |

## Referências Complementares

- RFC 7807 - Problem Details for HTTP APIs;
- RFC 9457 - Problem Details for HTTP APIs;
- OWASP API Security Top 10 (2023);
- Richardson Maturity Model - Martin Fowler;
- Azure Architecture Center - Microsoft Learn;
- Swagger Documentation;
- Artigos acadêmicos sobre design e segurança de APIs REST.

---

# 🤖 Engenharia de Prompts

Para conduzir as interações no NotebookLM, foi utilizada a seguinte instrução base:

> **"Assuma a personalidade de um Especialista de ensino."**

---

## Prompt 1 - Fundamentos de APIs REST

```text
Explique o conceito de API REST de forma didática, apresentando seus princípios fundamentais e exemplos práticos.
```

### Principais Aprendizados

- REST é um estilo arquitetural;
- APIs REST são orientadas a recursos;
- Recursos são identificados por URIs;
- Os métodos HTTP representam ações sobre recursos.

---

## Prompt 2 - Princípios Arquiteturais

```text
Explique os princípios arquiteturais definidos por Roy Fielding para uma API REST e apresente exemplos de implementação.
```

### Principais Aprendizados

- Cliente-Servidor;
- Stateless;
- Cache;
- Interface Uniforme;
- Sistema em Camadas;
- Código sob Demanda.

---

## Prompt 3 - REST vs SOAP vs GraphQL

```text
Compare APIs REST, SOAP e GraphQL destacando vantagens, limitações e cenários ideais de uso.
```

### Principais Aprendizados

| Tecnologia | Característica Principal |
|------------|-------------------------|
| REST | Simplicidade e escalabilidade |
| SOAP | Segurança e transações |
| GraphQL | Flexibilidade e otimização de dados |

---

## Prompt 4 - Segurança em APIs

```text
Quais são as principais vulnerabilidades de segurança em APIs REST segundo a OWASP e quais estratégias podem ser adotadas para mitigá-las?
```

### Principais Aprendizados

- BOLA;
- Broken Authentication;
- SSRF;
- Rate Limiting;
- OAuth 2.1;
- JWT;
- HTTPS/TLS.

---

## Prompt 5 - Richardson Maturity Model

```text
Explique os quatro níveis do Richardson Maturity Model e forneça exemplos práticos para cada nível.
```

### Principais Aprendizados

| Nível | Descrição |
|--------|------------|
| Nível 0 | RPC sobre HTTP |
| Nível 1 | Recursos |
| Nível 2 | Verbos HTTP |
| Nível 3 | HATEOAS |

---

## Prompt 6 - RFC 7807 vs RFC 9457

```text
Quais são as diferenças entre o RFC 7807 e o RFC 9457 no tratamento de erros em APIs HTTP?
```

### Principais Aprendizados

- Padronização de erros;
- Registro IANA;
- Maior interoperabilidade;
- Melhor suporte à extensibilidade.

---

## Prompt 7 - OpenAPI Specification

```text
Explique a finalidade da especificação OpenAPI e como ela contribui para o desenvolvimento, documentação e manutenção de APIs REST.
```

### Principais Aprendizados

- API First;
- Geração automática de documentação;
- Governança;
- Testes de contrato;
- Automação.

---

# 🩹 Dificuldades Encontradas e Soluções

| Dificuldade | Estratégia Utilizada |
|------------|---------------------|
| Respostas muito amplas | Refinamento dos prompts |
| Pouca profundidade técnica | Inclusão de fontes acadêmicas |
| Excesso de informação | Organização temática |
| Respostas genéricas | Uso de persona especializada |
| Necessidade de exemplos práticos | Solicitação explícita de casos reais |

---

# 📘 Miniguia de Estudos

## O que é uma API REST?

Uma API REST é uma interface de comunicação entre sistemas baseada no estilo arquitetural REST, utilizando recursos identificados por URIs e manipulados através dos métodos HTTP.

---

## 🏛️ Restrições Arquiteturais REST

- Cliente-Servidor;
- Stateless;
- Cache;
- Interface Uniforme;
- Sistema em Camadas;
- Código sob Demanda (opcional).

---

## 🌐 Principais Métodos HTTP

| Método | Finalidade |
|---------|------------|
| GET | Recuperar recursos |
| POST | Criar recursos |
| PUT | Atualizar integralmente |
| PATCH | Atualizar parcialmente |
| DELETE | Remover recursos |

---

## 🔐 Boas Práticas de Segurança

- Utilizar HTTPS;
- Implementar autenticação robusta;
- Aplicar autorização adequada;
- Utilizar Rate Limiting;
- Validar entradas;
- Seguir recomendações do OWASP API Security Top 10.

---

## 📈 Richardson Maturity Model

```text
Nível 0 → RPC sobre HTTP
Nível 1 → Recursos
Nível 2 → Verbos HTTP
Nível 3 → HATEOAS
```

---

## 📚 Glossário

| Termo | Definição |
|--------|-----------|
| API | Interface de Programação de Aplicações |
| REST | Estilo arquitetural para sistemas distribuídos |
| URI | Identificador único de recurso |
| JSON | Formato leve de troca de dados |
| HATEOAS | Hipermídia como motor do estado da aplicação |
| JWT | JSON Web Token |
| OAuth | Protocolo de autorização |
| OpenAPI | Especificação para descrição de APIs |
| BOLA | Vulnerabilidade de autorização em nível de objeto |
| Rate Limiting | Limitação da quantidade de requisições |

---

# 🚀 Prompts Reutilizáveis

```text
Explique [conceito] de forma didática com exemplos práticos.
```

```text
Compare [tecnologia A] e [tecnologia B] destacando vantagens, desvantagens e cenários de uso.
```

```text
Quais são as melhores práticas para implementar [conceito] em APIs REST?
```

```text
Resuma os principais pontos sobre [tema] em tópicos objetivos.
```

```text
Quais perguntas técnicas sobre [tema] podem ser feitas em entrevistas?
```

---

# 📸 Evidências do Processo

> **Observação:** As imagens abaixo representam o processo de construção do caderno temático no NotebookLM.

## Fontes utilizadas no NotebookLM

```md
![Fontes NotebookLM](assets/prints/fontes-notebooklm.png)
```

## Exemplo de Prompt

```md
![Prompt NotebookLM](assets/prints/prompt-api-rest.png)
```

## Exemplo de Resposta

```md
![Resposta NotebookLM](assets/prints/resposta-api-rest.png)
```

---

# 💡 Principais Aprendizados

O desenvolvimento deste projeto permitiu consolidar conhecimentos sobre arquitetura REST, segurança, documentação, governança e boas práticas de desenvolvimento de APIs.

Além do aprofundamento técnico, a experiência demonstrou como ferramentas de Inteligência Artificial podem potencializar o aprendizado quando utilizadas de forma crítica, estruturada e apoiadas por fontes confiáveis.

---

## 👨‍💻 Autor

**Renan Dorio**

- GitHub: https://github.com/D0r1o
- LinkedIn: https://www.linkedin.com/in/renan-dorio-0b9b55a5

---

⭐ Projeto desenvolvido para fins educacionais durante o desafio de projeto da DIO.
