<h1 align="center">🔗 STA Web Service — Automação de Testes de API 🇧🇷</h1>

<p align="center">
  <b>Framework modelo para automação de testes de web services e APIs REST.</b><br>
  Sistema de Testes Automatizados (STA) com Rest Assured, Karate DSL
  e validação HTTP avançada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-8-009C3B?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 8">
  <img src="https://img.shields.io/badge/Rest%20Assured-4.0-FFDF00?style=for-the-badge&logoColor=black" alt="Rest Assured">
  <img src="https://img.shields.io/badge/Karate-0.9.4-002776?style=for-the-badge&logoColor=white" alt="Karate">
  <img src="https://img.shields.io/badge/Groovy-2.5-009C3B?style=for-the-badge&logo=apachegroovy&logoColor=white" alt="Groovy">
  <img src="https://img.shields.io/badge/JUnit-4%20%2B%205-FFDF00?style=for-the-badge&logo=junit5&logoColor=black" alt="JUnit">
  <img src="https://img.shields.io/badge/Maven-002776?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-009C3B?style=flat-square&color=009C3B" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-FFDF00?style=flat-square&color=FFDF00" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-002776?style=flat-square&color=002776" height="6" width="120" alt="">
</p>

---

## 📑 Sumário

- [🔎 Visão geral](#-visão-geral)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias](#️-tecnologias)
- [🚀 Como usar](#-como-usar)
- [📄 Licença](#-licença)

---

## 🔎 Visão geral

Projeto-modelo **Maven** (Java 8) para testes automatizados de APIs e web services. Combina **Rest Assured 4.0** para validação de endpoints REST com assertions Hamcrest, **Karate 0.9.4** para testes declarativos de API (DSL BDD sem código Java) e **Groovy** para parsing JSON/XML. Inclui suporte a JUnit 4/5 e integração HTTP via Apache HttpComponents.

Convenção de testes: classes prefixadas com `CT*.java`.

---

## ✨ Funcionalidades

| Módulo | Descrição |
| :----- | :-------- |
| 🔌 **Testes REST** | Rest Assured 4.0 com assertions Hamcrest |
| 📝 **BDD declarativo** | Karate DSL (cenários sem código Java) |
| 🔄 **Parsing** | Groovy para JSON e XML |
| 🧪 **Frameworks** | JUnit 4 + JUnit 5 (Jupiter) |
| 🌐 **HTTP** | Apache HttpComponents (httpclient/httpmime) |
| 📄 **XML Binding** | JAXB |

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
| :----- | :--------- |
| 💻 **Linguagem** | Java 8 |
| 🔌 **REST** | Rest Assured 4.0 |
| 📝 **BDD** | Karate 0.9.4 |
| 🔄 **Scripting** | Groovy 2.5.6 (JSON/XML) |
| 🧪 **Testes** | JUnit 4.12 + JUnit 5 (Jupiter) |
| ✅ **Assertions** | Hamcrest 2.1 |
| 🌐 **HTTP** | Apache HttpComponents 4.5 |
| 📄 **XML** | JAXB |
| 🔧 **Build** | Maven |

---

## 🚀 Como usar

<details open>
<summary><b>▶️ Executar testes</b></summary>

```bash
mvn test                                       # executa testes CT*.java
mvn test -Dkarate.options="--tags @smoke"       # testes Karate por tag
```

</details>

---

## 📄 Licença

Projeto de uso interno/educacional.

<p align="center">
  <img src="https://img.shields.io/badge/-009C3B?style=flat-square&color=009C3B" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-FFDF00?style=flat-square&color=FFDF00" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-002776?style=flat-square&color=002776" height="6" width="120" alt="">
</p>

<p align="center"><sub>Feito com 💚💛💙 — cores da bandeira do Brasil 🇧🇷</sub></p>
