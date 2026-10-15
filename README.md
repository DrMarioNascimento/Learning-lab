# Learning Lab — Laboratório do Pesquisador

## Ética e Pesquisa — aberta ao público

Esta linha reúne materiais e atividades interativas para apoiar o ensino de Ética e Metodologia da Pesquisa. Por meio de situações-problema, reflexão crítica e discussão, os recursos estimulam a construção do conhecimento.

Portal do autor: https://www.drmarionascimento.com.br/

O acesso público aos recursos não altera as condições de reutilização em [LICENSE.md](LICENSE.md).


## Estado e manutenção — 10 de outubro de 2026

Os dois laboratórios implementados são [Delineamentos](delineamentos/) e [Instrumentos de Coleta](instrumentos-de-coleta/). As escolhas, devolutivas e relatórios têm finalidade formativa; o índice de rigor não equivale à validação científica de um projeto real.

As páginas são HTML/CSS/JavaScript, sem processo de compilação. O modo de turma usa Firestore; o uso individual e a exportação de relatório têm fluxos próprios, descritos abaixo. Uma senha de interface não substitui autorização no serviço de dados. Não há workflow de CI nem suíte automatizada de testes no repositório nesta revisão.


**English** · [Português](#português)

> **Personal intellectual project of Mário César Nascimento, PhD. All rights reserved.**

Learning Lab: mobile-first research methods labs for Physical Education. Students act as junior researchers, choosing study designs and data collection instruments, and get formative feedback. Includes a classroom mode with QR code join and live tracking.

**Open online:** [laboratorio-de-pesquisa.drmarionascimento.com.br](https://laboratorio-de-pesquisa.drmarionascimento.com.br/)

The interface and all content are in Brazilian Portuguese.

## Who it is for

Undergraduate students in Physical Education research methods courses, and the instructors who use the labs in class. It is a formative learning environment, not an automated exam, and it does not replace the instructor.

## Labs

- **[Study Designs (Delineamentos)](https://laboratorio-de-pesquisa.drmarionascimento.com.br/delineamentos/)** — the student picks one of eight Physical Education subareas, receives a randomly drawn research scenario and builds a study design step by step: nature and purpose, approach and method, procedure and time frame, variables, sample and control, validity, and a set of methodological pitfalls. The lab ends with a written reflection and a methodological report with a rigor score, a checklist and a draft method description. A reference library of the concepts is available at any time.
- **[Data Collection Instruments (Instrumentos de Coleta)](https://laboratorio-de-pesquisa.drmarionascimento.com.br/instrumentos-de-coleta/)** — within one chosen subarea, the student goes through a short warm-up, three labs (Interview, Observation, Questionnaire), a comparison and triangulation stage, and an integrative mission of eight linked decisions. A wrong first answer triggers a hint and a second attempt (partial credit). The final report weights each stage.

The labs are independent and can be used separately.

## Classroom mode

Each lab has a password-protected instructor module. The instructor creates a room and shares its code, QR code or link; students join with a name and an emoji. The instructor sees, in real time, each student's stage and progress and, once they finish, their result and report, which can be exported as an image or PDF. The Instruments lab also exports the class list as CSV.

Room data (name, emoji, progress, choices and results) is stored in Firebase Cloud Firestore only when a student joins a room. Individual use saves nothing: there is no stored progress, and students keep their own record by exporting the final report as an image or PDF.

## Technology

Plain HTML, CSS and JavaScript (no framework), mobile-first; content embedded in each page as JSON; Firebase Cloud Firestore for live rooms; html2canvas for image export; Google Fonts; published with GitHub Pages.

## Author, license and contact

**Author and declared rights holder:** Mário César Nascimento, PhD — [DrMarioNascimento](https://github.com/DrMarioNascimento)

The author's affiliation with CEFID/UDESC is academic information only; the University is not the author, owner or licensor of this repository.

**License:** see [LICENSE.md](LICENSE.md) (all rights reserved; functional educational use permitted).

---

## Português

> **Projeto intelectual pessoal de Mário César Nascimento, PhD. Todos os direitos reservados.**

## Visão geral

O **Learning Lab — Laboratório do Pesquisador** é um ambiente digital de aprendizagem para o ensino de metodologia da pesquisa em Educação Física, usado na disciplina **Pesquisa em Educação Física I**. A página central reúne laboratórios interativos mobile-first nos quais o estudante assume o papel de **pesquisador júnior**, toma decisões metodológicas e recebe orientação formativa imediata do personagem **Orientador**.

## Acesso

- **Página central:** [laboratorio-de-pesquisa.drmarionascimento.com.br](https://laboratorio-de-pesquisa.drmarionascimento.com.br/)
- **Laboratório de Delineamentos:** [laboratorio-de-pesquisa.drmarionascimento.com.br/delineamentos/](https://laboratorio-de-pesquisa.drmarionascimento.com.br/delineamentos/)
- **Laboratório de Instrumentos de Coleta:** [laboratorio-de-pesquisa.drmarionascimento.com.br/instrumentos-de-coleta/](https://laboratorio-de-pesquisa.drmarionascimento.com.br/instrumentos-de-coleta/)

Os laboratórios funcionam no navegador, em celular ou computador, sem instalação.

## Para quem

- **Estudantes** de graduação em disciplinas de pesquisa em Educação Física, em aula ou em estudo individual.
- **Docentes** que desejam conduzir a atividade com a turma e acompanhar o percurso dos estudantes em tempo real.

O ambiente tem caráter **educativo e formativo**. Não é uma prova automatizada e não substitui a mediação docente nem o estudo das referências da disciplina.

## O que o ambiente oferece

Em ambos os laboratórios, o estudante:

- escolhe uma das **oito subáreas** da Educação Física, que se mantém ao longo do percurso (Lutas e Esportes de Combate; Danças e Expressão Corporal; Jogos, Brincadeiras e Cultura Lúdica; Fisiologia do Exercício e Treinamento; Saúde Pública e Fatores de Risco; Inclusão e Diversidade; Metodologias e Pedagogia do Esporte; Esportes Aquáticos e Menos Convencionais);
- trabalha com situações de pesquisa aplicadas à subárea escolhida;
- toma decisões em sequência e recebe devolutivas do Orientador;
- recebe, ao final, um parecer que integra as decisões tomadas.

Os laboratórios são complementares e podem ser realizados separadamente, conforme a orientação da disciplina.

### Laboratório de Delineamentos

O estudante constrói a arquitetura metodológica de um projeto de pesquisa a partir de um **cenário sorteado** dentro da subárea escolhida (o banco contém 80 cenários, 10 por subárea), com situação-problema e pergunta de pesquisa. O percurso passa por:

1. **Natureza e finalidade** do estudo;
2. **Abordagem e método**;
3. **Procedimentos e temporalidade**, além da descrição de variáveis independente e dependente, amostra e controle de variáveis estranhas;
4. **Validade** e **Armadilhas Metodológicas** (afirmações sorteadas a serem julgadas, com explicação).

Cada decisão recebe retorno imediato do Orientador sobre a coerência do projeto. Ao final, o estudante registra uma **reflexão** ("O que você mudaria no seu delineamento se fosse recomeçar? Por quê?") e recebe o **Relatório de Delineamento Metodológico**, com:

- índice de **Rigor Metodológico** calculado a partir de três pilares: Coerência Epistemológica (30%), Controle de Viés (40%) e Generalização e Escopo (30%);
- parecer final e lista de verificação dos elementos essenciais do projeto;
- descrição metodológica montada a partir das escolhas feitas.

O relatório pode ser exportado pelo próprio estudante em **imagem (PNG)** ou **PDF** (pela impressão do navegador). O botão **Consultar Acervo Teórico** reúne os conceitos de cada fase e referências clássicas de metodologia.

### Laboratório de Instrumentos de Coleta

Na mesma sessão e na subárea escolhida, o estudante percorre:

1. **Aquecimento orientado** — duas demonstrações sobre o tipo de dado que antecede a escolha do instrumento (não alteram a pontuação);
2. **Laboratório da Entrevista**, **Laboratório da Observação** e **Laboratório do Questionário** — cada ambiente começa com objetivos e uma revisão teórica breve, seguidos de decisões avaliativas;
3. **Comparação e Triangulação** — o que cada fonte produz e quando a combinação acrescenta evidência;
4. **Missão Integrativa** — oito decisões encadeadas para montar o plano de coleta de um novo projeto.

Quando a primeira resposta é incoerente, o Orientador oferece uma **pista** e uma nova tentativa; o acerto após a orientação recebe crédito parcial. Ao fim de cada ambiente há uma síntese do desempenho. O **Parecer Final** pondera as etapas (Entrevista 20%, Observação 20%, Questionário 20%, Comparação e triangulação 15%, Missão Integrativa 25%), apresenta as competências mobilizadas e pode ser exportado em **imagem (PNG)** ou **PDF** (pela impressão do navegador).

## Sala de aula e módulo do orientador

Cada laboratório tem um **Módulo do Orientador**, de acesso restrito por senha, para uso simultâneo em sala de aula:

- o orientador cria uma sala e obtém um **código**, um **QR code** e um **link** de acesso;
- os estudantes entram pelo código, pelo QR code ou pelo link, informando nome (ou identificação) e escolhendo um emoji;
- o painel mostra, **em tempo real**, os participantes, a etapa em que cada um está e o progresso; ao concluir, aparecem o resultado e o relatório do estudante;
- o orientador pode abrir o relatório de cada estudante que concluiu e exportá-lo em imagem ou PDF;
- no Laboratório de Instrumentos de Coleta, a lista da turma também pode ser exportada em **CSV**;
- o orientador pode encerrar a sessão (no Laboratório de Delineamentos, também gerar um novo código).

### Registro de dados

- **Uso individual (sem sala):** nada é salvo. Não há armazenamento de progresso; ao recarregar a página, o percurso recomeça. O registro da atividade é o relatório final, que o próprio estudante exporta em imagem ou PDF.
- **Uso em sala:** ao entrar em uma sala, o nome, o emoji, a etapa, o progresso, as escolhas e os resultados do estudante são enviados ao **Firebase (Cloud Firestore)** para exibição no painel do orientador. Ao encerrar a sessão, a sala é marcada como inativa; os registros não são apagados automaticamente.

O módulo do orientador é uma área de apoio pedagógico. Dados identificáveis devem ser utilizados somente para a atividade acadêmica, com os cuidados institucionais aplicáveis.

## Tecnologia

- HTML5, CSS3 e JavaScript sem framework;
- interface mobile-first, otimizada para smartphones;
- conteúdo pedagógico (cenários, casos, alternativas, devolutivas) embutido em cada página como JSON, com cópia em `lab_data.json` e planilhas-base `.xlsx` na pasta de cada laboratório;
- Firebase JavaScript SDK (Cloud Firestore), carregado por CDN, para salas, participantes e registros de atividade em sala;
- html2canvas, carregado por CDN, para exportação de relatórios em imagem; exportação em PDF pela impressão do navegador;
- QR code das salas gerado pelo serviço externo api.qrserver.com (com o código da sala como alternativa);
- fontes Oswald, Lora e IBM Plex Mono, via Google Fonts;
- publicação pelo GitHub Pages.

## Estrutura do repositório (manutenção)

```text
Learning-lab/
├── index.html                                   # página central (Pesquisa em Educação Física I)
├── brand/
│   └── orientador.webp                          # imagem do Orientador e ícone das páginas
├── delineamentos/
│   ├── index.html                               # Laboratório de Delineamentos (dados embutidos)
│   ├── lab_data.json                            # dados do laboratório (usado como alternativa se os dados embutidos forem removidos)
│   └── Laboratorio_Pesquisador_Base_Dados.xlsx  # planilha-base dos dados
├── instrumentos-de-coleta/
│   ├── index.html                               # Laboratório de Instrumentos de Coleta (dados embutidos)
│   ├── lab_data.json                            # cópia dos dados embutidos
│   ├── Laboratorio_Pesquisador_Instrumentos_Coleta_Base_Dados.xlsx
│   ├── avatar-orientador-corpo.png              # imagens do Orientador
│   └── avatar-orientador-rosto.png
├── README.md
└── LICENSE.md
```

Notas para manutenção:

- Os dados de cada laboratório têm origem na planilha `.xlsx` da respectiva pasta, são exportados para `lab_data.json` e embutidos no `index.html`. Ao alterar o conteúdo, mantenha os três sincronizados.
- As páginas são estáticas: basta servi-las por HTTP. A sala ao vivo e o QR code só funcionam quando a página está publicada em endereço público (por exemplo, GitHub Pages); aberta como arquivo local, o link gerado não é acessível a outros aparelhos, e a própria página avisa isso.
- As salas ficam na coleção `sessoes` do Cloud Firestore, com os participantes em `sessoes/{código}/alunos`.

## Autoria, licença e contato

**Autor e titular declarado:** Mário César Nascimento, PhD  
**Projeto pessoal:** Learning Lab — Laboratório do Pesquisador  
**Perfil responsável:** [DrMarioNascimento](https://github.com/DrMarioNascimento)

A vinculação profissional do autor ao CEFID/UDESC é informação acadêmica e não identifica a Universidade como autora, titular ou licenciadora deste repositório.

Copyright © 2026 Mário César Nascimento. Todos os direitos reservados.

**Licença:** ver [LICENSE.md](LICENSE.md) (todos os direitos reservados; uso educacional funcional permitido). A disponibilização pública do código não autoriza sua cópia, adaptação, republicação ou exploração comercial.

Pedidos de autorização e contato: pelo perfil [DrMarioNascimento](https://github.com/DrMarioNascimento) no GitHub.

**Identificação profissional do autor**

**Prof. Dr. Mário César Nascimento**  
CREFSC 000004/G  
Doutor em Ciências da Reabilitação  
Avaliação e intervenção terapêutica/Fisiologia Translacional  
Universidade do Estado de Santa Catarina — UDESC  
Centro de Ciências da Saúde e do Esporte — CEFID

---

Material didático destinado ao ensino e à aprendizagem de metodologia da pesquisa em Educação Física.
