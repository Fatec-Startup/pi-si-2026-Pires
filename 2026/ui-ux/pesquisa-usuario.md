# Research UX/UI: Definição do Problema, Persona e Jornada do Usuário

## 1. Definição do Problema

### Contexto
Atualmente, a Prefeitura realiza o processo de matrícula de alunos em projetos sociais municipais (esportes, artes, capacitação, reforço escolar, etc.) de forma totalmente manual/física (à mão).

### Problemas Identificados
* **Para a população:** Necessidade de deslocamento físico, longas filas em horários comerciais, perda de tempo, risco de falta de documentos na hora do atendimento e falta de visibilidade sobre vagas disponíveis.
* **Para a gestão pública:** Alto consumo de papel e espaço físico para armazenamento, risco de perda ou rasura de fichas físicas, lentidão na validação de documentos e dificuldade para gerar relatórios e estatísticas das atividades.

### Objetivo da Solução
Desenvolver uma plataforma digital (web/mobile) que automatize o fluxo de inscrição e matrícula nos projetos sociais, permitindo que os responsáveis efetuem o cadastro online e a prefeitura gerencie as vagas e os alunos de forma centralizada e eficiente.

---

## 2. Matriz CSD (Certezas, Suposições e Dúvidas)

| Certezas (C) | Suposições (S) | Dúvidas (D) |
| :--- | :--- | :--- |
| O processo de matrícula atual é feito manualmente no papel. | A maioria dos usuários prefere se matricular pelo celular do que ir presencialmente. | Qual a porcentagem de munícipes que não possui acesso contínuo à internet? |
| Famílias e alunos perdem tempo em filas presenciais para garantir vagas. | Os funcionários da prefeitura têm dificuldade para organizar e buscar cadastros antigos. | A prefeitura exige apresentação física dos documentos para validação legal? |
| A falta de digitalização dificulta o controle de vagas em tempo real. | Avisos e lembretes sobre aulas poderiam ser enviados via WhatsApp ou notificações. | Haverá necessidade de um ponto de atendimento presencial para auxílio no cadastro? |

---

## 3. Personas

### Persona Principal: O Responsável/Mãe do Aluno
* **Nome:** Maria da Silva
* **Idade:** 34 anos
* **Ocupação:** Atendente de comércio
* **Escolaridade:** Ensino Médio completo
* **Acesso à Tecnologia:** Smartphone com conexão de dados móveis (3G/4G).
* **Objetivos:** Matricular seu filho de 10 anos nas aulas gratuitas de futsal do projeto social municipal sem precisar faltar ao trabalho.
* **Dores:** Não consegue ir à prefeitura/centro comunitário no horário comercial; tem medo de perder a vaga porque as filas começam de madrugada; acha burocrático ter que levar cópias de documentos impressos.

### Persona Secundária: A Gestora da Prefeitura
* **Nome:** Ana Paula Souza
* **Idade:** 42 anos
* **Ocupação:** Servidora pública / Coordenadora dos Projetos Sociais
* **Objetivos:** Ter controle claro da quantidade de alunos matriculados, turmas lotadas e fila de espera sem acumular pilhas de papel.
* **Dores:** Perde muito tempo organizando fichas de papel; às vezes não entende a caligrafia nas fichas; dificuldade em gerar dados para os relatórios da secretaria.

---

## 4. Mapa de Empatia (Persona: Maria da Silva)

* **O que ela Ouve?** 
  * Vizinhos dizendo que as vagas do projeto acabam rápido.
  * Colegas de trabalho reclamando da burocracia do atendimento presencial.
* **O que ela Pensa e Sente?**
  * *"Quero que meu filho tenha atividades saudáveis no contra-turno escolar."*
  * Sentimento de frustração por ter que pedir folga no trabalho só para fazer uma inscrição.
* **O que ela Vê?**
  * Filas dobrando o quarteirão nos dias de abertura de inscrição.
  * Divulgações das oficinas e projetos nas redes sociais da prefeitura.
* **O que ela Fala e Faz?**
  * Usa o smartphone no transporte público para acessar redes sociais e mensagens.
  * Comenta com a família que quer matricular o filho, mas não tem tempo de ir até o local.
* **Dores:**
  * Falta de tempo.
  * Burocracia presencial.
  * Incerteza se vai conseguir a vaga.
* **Ganhos:**
  * Resolver a matrícula pelo celular em poucos minutos.
  * Receber confirmação instantânea da vaga.
  * Ter acesso rápido aos horários e locais das aulas.

---

## 5. Jornada do Usuário (Fluxo Principal: Matrícula Online)

**Cenário:** Maria deseja matricular seu filho em uma oficina esportiva do município usando seu celular.

| Estágio | 1. Descoberta | 2. Acesso e Escolha | 3. Cadastro e Envio | 4. Confirmação |
| :--- | :--- | :--- | :--- | :--- |
| **Ação do Usuário** | Vê o anúncio das vagas no celular ou folheto. | Acessa o sistema, visualiza as oficinas e escolhe o Futsal Infantil. | Preenche os dados do filho e envia fotos dos documentos solicitados. | Recebe o comprovante com o status da matrícula e dados das aulas. |
| **Pensamentos** | *"Preciso garantir a vaga do meu filho antes que acabe."* | *"Espero que seja fácil encontrar o horário certo."* | *"Que bom que posso tirar foto do documento direto do celular."* | *"Ufa! Deu tudo certo e não precisei sair de casa."* |
| **Emoção** | Ansiedade / Expectativa | Curiosidade | Atenção | Alívio / Satisfação |
| **Oportunidade UX/UI** | Divulgação com link direto / QR Code para a página do projeto. | Filtros simples por bairro, idade e modalidade esportiva/cultural. | Formato responsivo para celular, com opção de upload simples de arquivos/fotos. | Tela de confirmação clara com opção de baixar comprovante em PDF ou receber via e-mail/WhatsApp. |