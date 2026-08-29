<div align="center">

# Samuel Madeiro

**Backend Java · Spring Boot · APIs REST**

Estudante de Ciência da Computação · aberto a estágio e vagas júnior em backend

<a href="mailto:samuelborbamadeiro@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
<a href="https://www.linkedin.com/in/samuelmadeiro/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

**[Sobre](#sobre) · [Stack](#stack) · [Projetos](#projetos) · [Contato](#contato)**

</div>

---

## Sobre

Construo backend em Java e sistemas de visão computacional aplicados a acessibilidade.

Meus projetos nascem de um problema concreto: alguém precisa decidir se compra um negócio,
alguém não consegue usar o computador com as mãos, alguém precisa treinar para a entrevista
técnica que vem semana que vem. **O código vem depois do problema.**

O que procuro em cada um: modelagem que aguenta mudar de requisito, teste que falha pelo motivo
certo, e decisão documentada — o README de cada repositório explica o que foi escolhido, o que
foi descartado e por quê.

---

## Stack

| | |
|---|---|
| **Linguagens** | Java 21/25 · Python · SQL |
| **Backend** | Spring Boot · Spring Security + JWT · Spring Data JPA / Hibernate · FastAPI |
| **Dados** | PostgreSQL · SQLite · H2 · Flyway · Redis |
| **Mensageria** | Apache Kafka (outbox, DLT) |
| **Testes** | JUnit 5 · Mockito · MockMvc · Testcontainers · pytest |
| **Infra** | Docker · GitHub Actions · Maven |
| **Visão computacional** | MediaPipe · OpenCV · scikit-learn · NumPy |

<p align="center">
  <img height="48" src="https://skillicons.dev/icons?i=java,spring,python,postgresql,kafka,docker,git&theme=dark" alt="Java, Spring, Python, PostgreSQL, Kafka, Docker, Git" />
</p>

<div align="center">

<img src="https://helio-github-stats.vercel.app/api/top-langs?username=samuelmadeiro&layout=compact&stats_format=percentages&theme=dark&hide_border=true&border_radius=4.5&card_width=466&locale=pt-br&custom_title=Linguagens+mais+usadas" alt="Linguagens mais usadas nos repositórios: Java 50%, Python 31%, JavaScript 12%, HTML 3%, CSS 2%" />

</div>

---

## Projetos

### Backend

**[LiveCoding Simulator](https://github.com/samuelmadeiro/livecoding-simulator)** — simula a entrevista técnica antes dela acontecer: o candidato filtra desafios por nível de vaga, tecnologia e tipo, recebe o template e envia a solução para correção automática.

<sub>**Decisões:** API stateless com JWT, sem sessão no servidor · três filtros opcionais resolvidos em uma única JPQL com `JOIN FETCH`, sem N+1 · correção isolada atrás de um serviço próprio, o ponto de troca para um runner em sandbox · 16 classes de teste, da unidade à cadeia de segurança</sub>

<p>
  <img src="https://img.shields.io/badge/Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Spring%20Data%20JPA-59666C?style=flat-square&logo=hibernate&logoColor=white" alt="Spring Data JPA e Hibernate" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/H2-1021FF?style=flat-square&logo=h2database&logoColor=white" alt="H2" />
  <img src="https://img.shields.io/badge/JUnit%205%20%2B%20Mockito-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit 5 e Mockito" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" alt="Maven" />
</p>

**[Valor Justo](https://github.com/samuelmadeiro/valorjusto)** — avalia se vale a pena comprar uma empresa à venda no Brasil: índice de 0 a 100 com VPL, TIR e payback por trás.

<sub>**Decisões:** SQL explícito, sem JPA, para enxergar cada query · schema versionado em Flyway · allowlist contra SSRF · pagamento reconferido na API do gateway, nunca confiando no callback · teste de integração em Postgres real via Testcontainers, rodando no CI</sub>

<p>
  <img src="https://img.shields.io/badge/Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring%20JDBC-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring JDBC" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" alt="Flyway" />
  <img src="https://img.shields.io/badge/Testcontainers-291A44?style=flat-square&logo=docker&logoColor=white" alt="Testcontainers" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

### Acessibilidade

**[AccessAI](https://github.com/samuelmadeiro/accessai)** — audita a acessibilidade de documentos `.docx` e devolve um score explicável: cada ponto perdido rastreia até um problema com evidência e critério WCAG2ICT.

<sub>**Decisões:** Rule Engine determinístico, com a IA fora do caminho da nota · critérios versionados, para o score de ontem continuar reproduzível · Kafka com padrão outbox e DLT protegida por índice único contra reprocessamento · serviço de ML em Python separado do backend · ArchUnit guardando as fronteiras entre camadas</sub>

<p>
  <img src="https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 25" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/OAuth2%20Resource%20Server-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="OAuth2 Resource Server" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" alt="Flyway" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Testcontainers-291A44?style=flat-square&logo=docker&logoColor=white" alt="Testcontainers" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

**[Comunicador Ocular](https://github.com/samuelmadeiro/comunicador-ocular)** — controle do computador pelo olhar com webcam comum, boca como clique, para pessoas sem fala e sem movimento dos membros.

<sub>**Decisões:** filtro One Euro escrito à mão, para o tremor sumir sem atrasar o cursor · regressão ridge sobre a pose da cabeça, treinada na calibração de cada usuário · perfis de calibração persistidos pelo backend Spring Boot · voz sintetizada offline, sem depender de internet</sub>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/MediaPipe%20FaceMesh-0097A7?style=flat-square&logo=google&logoColor=white" alt="MediaPipe FaceMesh" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

**[Reconhecimento de Libras](https://github.com/samuelmadeiro/libras-reconhecimento)** — reconhece sinais de Libras pela câmera, incluindo as letras que só existem enquanto movimento (H, J, K, X, Z).

<sub>**Decisões:** cada sinal tratado como sequência temporal normalizada, não como pose isolada · KNN sobre os landmarks da mão, leve o bastante para rodar em tempo real · o mesmo algoritmo reescrito em Java para rodar on-device no Android, sem servidor no meio</sub>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Android%20nativo-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android nativo" />
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

### Primeiros passos

**[ComputerToAnyone](https://github.com/samuelmadeiro/ComputerToAnyone)** — o protótipo que deu origem ao Comunicador Ocular: um script Python controlando o cursor pelo olhar, para pessoas pós-AVC. Fica aqui como registro de onde a ideia começou. <sub>`Python` · `OpenCV` · `MediaPipe`</sub>

> As decisões técnicas de cada projeto — o porquê de cada escolha e o que foi
> descartado — estão no README do repositório.

---

## Contato

<div align="center">

<a href="mailto:samuelborbamadeiro@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Enviar e-mail" /></a>
<a href="https://www.linkedin.com/in/samuelmadeiro/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="Perfil no LinkedIn" /></a>
<a href="https://github.com/samuelmadeiro"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="Perfil no GitHub" /></a>

</div>
