# Olá, sou Maciano 👨🏻‍💻

**`Desenvolvedor Back-end Java`**

Formado em Ciência da Computação pela Faculdade Católica da Paraíba, com foco em **Java**, **Spring Boot**, **APIs REST** e **PostgreSQL**. Em busca da minha primeira oportunidade como desenvolvedor back-end júnior.

<p align="left">
    <a href="https://www.linkedin.com/in/macianodantas" target="_blank">
        <img
            alt="LinkedIn"
            title="Conecte-se no LinkedIn"
            src="https://custom-icon-badges.demolab.com/badge/-Conecte%20se%20no%20LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white"
        />
    </a>
</p>

---

### 🚀 Projeto em destaque

#### [SmartTeca](https://github.com/Macinao/biblioteca-digital) — biblioteca acadêmica com assistente de IA

[![CI](https://github.com/Macinao/biblioteca-digital/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Macinao/biblioteca-digital/actions/workflows/ci.yml)

Começou como meu Trabalho de Conclusão de Curso e virou uma **arquitetura de microsserviços orientada a eventos**: 6 serviços Spring Boot, front-end em Next.js e um assistente com IA que busca no acervo.

- **Mensageria:** Kafka para eventos de domínio e RabbitMQ para comandos com fila morta, com **Transactional Outbox** para não perder eventos entre o banco e o broker.
- **Dados:** PostgreSQL para escrita e Elasticsearch para leitura e busca, com consistência eventual.
- **Segurança:** JWT em cookies HttpOnly, validado uma única vez no gateway.
- **Qualidade:** 629 testes Java com **Testcontainers** (PostgreSQL, Kafka, RabbitMQ, Redis e Elasticsearch reais), 75 testes de front e **CI no GitHub Actions**.
- **Medi e corrigi:** estoque sem *overselling* (testes de concorrência), paginação que remove um teto de 10 mil documentos na listagem e um chatbot 4× mais rápido.

`Stack: Java 21 · Spring Boot · Spring AI · Kafka · RabbitMQ · PostgreSQL · Elasticsearch · Redis · Docker · Kubernetes · Next.js · TypeScript`

---

### 🤖 Linguagens e Tecnologias

<p align="left">
  <img alt="Java" title="Java" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" />
  <img alt="Spring" title="Spring" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" />
  <img alt="PostgreSQL" title="PostgreSQL" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" />
  <img alt="Apache Kafka" title="Apache Kafka" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apachekafka/apachekafka-original.svg" />
  <img alt="RabbitMQ" title="RabbitMQ" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rabbitmq/rabbitmq-original.svg" />
  <img alt="Elasticsearch" title="Elasticsearch" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/elasticsearch/elasticsearch-original.svg" />
  <img alt="Redis" title="Redis" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" />
  <img alt="Docker" title="Docker" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" />
  <img alt="Kubernetes" title="Kubernetes" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-original.svg" />
  <img alt="GitHub Actions" title="GitHub Actions" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" />
  <img alt="React" title="React" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" />
  <img alt="Next.js" title="Next.js" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" />
  <img alt="TypeScript" title="TypeScript" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
  <img alt="MySQL" title="MySQL" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" />
  <img alt="Git" title="Git" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" />
  <img alt="Python" title="Python" width="40px" style="padding-right: 12px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
</p>
