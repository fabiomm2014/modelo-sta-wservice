# 🔗 STA Web Service — Automacao de Testes de API 🇧🇷

![Java](https://img.shields.io/badge/Java-8-009C3B?style=flat&logo=openjdk&logoColor=white)
![Rest Assured](https://img.shields.io/badge/Rest%20Assured-4.0-FFDF00?style=flat&logoColor=black)
![Karate](https://img.shields.io/badge/Karate-0.9.4-002776?style=flat&logoColor=white)

Framework modelo para automacao de testes de web services / APIs REST (Sistema de Testes Automatizados — STA).

## Visao geral

Projeto-modelo Maven (Java 8) para testes automatizados de APIs e web services. Combina **Rest Assured 4.0** para validacao de endpoints REST com assertions Hamcrest, **Karate 0.9.4** para testes declarativos de API (DSL BDD sem codigo Java), e **Groovy** para parsing JSON/XML. Inclui suporte a JUnit 4/5 e integracao HTTP via Apache HttpComponents.

Convencao de testes: classes prefixadas com `CT*.java`.

## Tecnologias

- **Java 8** / **Maven**
- **Rest Assured 4.0** (validacao REST)
- **Karate 0.9.4** (testes declarativos BDD de API)
- **Groovy 2.5.6** (JSON/XML parsing)
- **JUnit 4.12** + **JUnit 5** (Jupiter)
- **Hamcrest 2.1**
- **Apache HttpComponents 4.5** (httpclient/httpmime)
- **JAXB** (binding XML)

## Como usar

```bash
mvn test              # executa testes CT*.java
mvn test -Dkarate.options="--tags @smoke"  # testes Karate por tag
```

## Licenca

Uso interno/educacional.

---
*Feito com 💚💛💙 — cores da bandeira do Brasil 🇧🇷*
