<div align="center">

# Samuel Madeiro

**Java Backend · Visão Computacional aplicada a Acessibilidade**

**[Sobre](#sobre) · [Stack](#stack) · [Projetos](#projetos) · [Contato](#contato)**

</div>

---

## Sobre

Sou Samuel, estudante de Ciência da Computação. Construo backend em Java e sistemas
de visão computacional aplicados a acessibilidade.

Meus projetos tendem a nascer de um problema concreto: alguém precisa decidir se
compra um negócio, alguém não consegue usar o computador com as mãos, alguém
precisa treinar para a entrevista técnica que vem semana que vem.
**O código vem depois do problema.**

---

## Stack

**Desenvolvimento**

<p>
  <img height="64" src="https://skillicons.dev/icons?i=java&theme=dark" title="Java" alt="Java" />
  <img height="64" src="https://skillicons.dev/icons?i=spring&theme=dark" title="Spring Boot" alt="Spring Boot" />
  <img height="64" src="https://skillicons.dev/icons?i=python&theme=dark" title="Python" alt="Python" />
  <img height="64" src="https://skillicons.dev/icons?i=fastapi&theme=dark" title="FastAPI" alt="FastAPI" />
  <img height="64" src="https://skillicons.dev/icons?i=androidstudio&theme=dark" title="Android Studio" alt="Android Studio" />
  <img height="64" src="https://skillicons.dev/icons?i=opencv&theme=dark" title="OpenCV" alt="OpenCV" />
  <img height="64" src="https://skillicons.dev/icons?i=scikitlearn&theme=dark" title="scikit-learn" alt="scikit-learn" />
</p>

<sub>Também: MediaPipe · NumPy · Android nativo com CameraX e Room</sub>

**Infraestrutura e DevOps**

<p>
  <img height="64" src="https://skillicons.dev/icons?i=postgresql&theme=dark" title="PostgreSQL" alt="PostgreSQL" />
  <img height="64" src="https://skillicons.dev/icons?i=sqlite&theme=dark" title="SQLite" alt="SQLite" />
  <img height="64" src="https://skillicons.dev/icons?i=kafka&theme=dark" title="Apache Kafka" alt="Apache Kafka" />
  <img height="64" src="https://skillicons.dev/icons?i=redis&theme=dark" title="Redis" alt="Redis" />
  <img height="64" src="https://skillicons.dev/icons?i=docker&theme=dark" title="Docker" alt="Docker" />
  <img height="64" src="https://skillicons.dev/icons?i=githubactions&theme=dark" title="GitHub Actions" alt="GitHub Actions" />
</p>

<sub>Também: Flyway para migration versionada</sub>

**Ferramentas**

<p>
  <img height="64" src="https://skillicons.dev/icons?i=idea&theme=dark" title="IntelliJ IDEA" alt="IntelliJ IDEA" />
  <img height="64" src="https://skillicons.dev/icons?i=maven&theme=dark" title="Maven" alt="Maven" />
  <img height="64" src="https://skillicons.dev/icons?i=git&theme=dark" title="Git" alt="Git" />
  <img height="64" src="https://skillicons.dev/icons?i=github&theme=dark" title="GitHub" alt="GitHub" />
</p>

<sub>Também: JUnit 5 · Testcontainers · pytest</sub>

<div align="center">

<img src="https://helio-github-stats.vercel.app/api/top-langs?username=samuelmadeiro&layout=compact&stats_format=percentages&theme=dark&hide_border=true&border_radius=4.5&card_width=466&locale=pt-br&custom_title=Linguagens+mais+usadas" alt="Linguagens mais usadas nos repositórios: Java 50%, Python 31%, JavaScript 12%, HTML 3%, CSS 2%" />

</div>

---

## Projetos

### Backend

**[LiveCoding Simulator](https://github.com/samuelmadeiro/livecoding-simulator)** — simula a entrevista técnica antes dela acontecer: o candidato filtra desafios por nível de vaga, tecnologia e tipo, recebe o template e envia a solução para correção automática. API stateless com JWT, os três filtros opcionais resolvidos em uma única JPQL com `JOIN FETCH`, e a correção isolada atrás de um serviço próprio — o ponto de troca para um runner em sandbox.

<p>
  <img src="https://img.shields.io/badge/Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring%20Boot%203.3-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot 3.3" />
  <img src="https://img.shields.io/badge/Spring%20Security%20%2B%20JWT-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security e JWT" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit 5" />
</p>

**[Valor Justo](https://github.com/samuelmadeiro/valorjusto)** — avalia se vale a pena comprar uma empresa à venda no Brasil: índice de 0 a 100 com VPL, TIR e payback por trás. SQL explícito sem JPA, allowlist contra SSRF e pagamento reconferido na API do gateway.

<p>
  <img src="https://img.shields.io/badge/Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

### Acessibilidade

**[AccessAI](https://github.com/samuelmadeiro/accessai)** — audita a acessibilidade de documentos `.docx` e devolve um score explicável: cada ponto perdido rastreia até um problema com evidência e critério WCAG2ICT. Rule Engine determinístico, Kafka com outbox e DLT, e guardrail de IA nas duas pontas.

<p>
  <img src="https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 25" />
  <img src="https://img.shields.io/badge/Spring%20Boot%204.1-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot 4.1" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

**[Comunicador Ocular](https://github.com/samuelmadeiro/comunicador-ocular)** — controle do computador pelo olhar com webcam comum, boca como clique, para pessoas sem fala e sem movimento dos membros. Filtro One Euro escrito à mão e regressão ridge sobre a pose da cabeça.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/MediaPipe%20FaceMesh-0097A7?style=flat-square&logo=google&logoColor=white" alt="MediaPipe FaceMesh" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

### Outros

**[Reconhecimento de Libras](https://github.com/samuelmadeiro/libras-reconhecimento)** — reconhece sinais de Libras pela câmera, incluindo as letras que só existem enquanto movimento. Pipeline Python com MediaPipe e app Android nativo rodando o mesmo algoritmo on-device. <sub>`Python` · `MediaPipe` · `Android` · `SQLite`</sub>

> As decisões técnicas de cada projeto — o porquê de cada escolha e o que foi
> descartado — estão no README do repositório.

---

## Contato

<div align="center">

<a href="mailto:samuelborbamadeiro@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Enviar e-mail" /></a>
<a href="https://github.com/samuelmadeiro"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="Perfil no GitHub" /></a>

</div>
