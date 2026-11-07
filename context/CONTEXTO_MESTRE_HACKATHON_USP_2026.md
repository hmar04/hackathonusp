# CONTEXTO MESTRE — HACKATHON USP 2026
## Saúde para todos: soluções para reduzir barreiras no acesso à saúde

> **Uso deste arquivo:** alimentar uma IA (ChatGPT, Claude, Gemini, Codex ou similar) com o cenário **oficial**, as informações operacionais do Hackathon USP 2026 e o estudo de caso da Capim. O propósito é apoiar descoberta, ideação, priorização, implementação de protótipo, validação e pitch.
>
> **Data de referência:** 07/11/2026, durante o primeiro dia do hackathon. Horários no fuso local de São Paulo (BRT, UTC−3).
>
> **Princípio central:** o desafio **NÃO está limitado à odontologia**. A palestra da Capim é uma fonte rica de problemas reais, mas a organização informou expressamente que projetos podem abordar **saúde em geral**: medicina, psicologia, fisioterapia, odontologia e outras áreas pertinentes.
>
> **Status do projeto:** nenhum produto, público-alvo, stack, integração ou dataset foi escolhido nos materiais fornecidos. As opções apresentadas neste documento são **possibilidades de ideação**, não decisões da equipe nem regras do evento.

---

## 0. LEITURA OBRIGATÓRIA — CONTEXTO EM UM MINUTO

Somos uma equipe participante do **Hackathon USP 2026 / HACKA-USP**, com atividades nos dias **7 e 8 de novembro de 2026**, realizadas na **Capim**, com envolvimento de **Núcleo de Empreendedorismo da USP**, **CodeLab** e parceiros mencionados nos materiais, entre eles **Capim** e **Pilea Lab**.

O tema oficial, conforme a apresentação institucional, é:

> **“Saúde para todos: soluções para reduzir barreiras no acesso à saúde.”**

A premissa dos organizadores é que saúde é um direito, não um privilégio. Queremos desenvolver tecnologia que **reduza barreiras reais de acesso, inclusão e qualidade de cuidado**. O recorte pode ocorrer em diversas especialidades de saúde. O time deve identificar uma dor específica, uma população beneficiada e um produto que possa ser **demonstrado com clareza** em pouco tempo.

A **Capim** ofereceu uma palestra de aprofundamento em odontologia: apesar de ampla oferta de clínicas e profissionais, pacientes enfrentam barreiras financeiras, de informação, de orçamento, de confiança, de comparecimento e de continuidade do tratamento; as clínicas também enfrentam dificuldades operacionais. Esse exemplo **não restringe o tema oficial**, mas ilustra como analisar um ecossistema de saúde de ponta a ponta.

**Prazos decisivos:** no domingo **08/11/2026, às 15h45**, ocorre o encerramento dos projetos (e, segundo a orientação oral, é o horário de entrega dos protótipos); **às 16h começam os pitches**, **17h45 a avaliação** e **18h a premiação**.

**Prêmios anunciados:** 1º lugar **R$ 3.000**, 2º **R$ 2.000**, 3º **R$ 1.000**.

**O que a IA deve fazer:** atuar como parceira de produto, pesquisa, engenharia, UX, IA aplicada e pitch; não inventar regulamentos ou dados; propor ideias diferentes; ajudar a selecionar uma solução com alto potencial e protótipo funcional, implementá-la e explicar o impacto com honestidade.

---

## 1. FONTES, PRECEDÊNCIA E NÍVEIS DE CONFIANÇA

### 1.1. Arquivos recebidos

| ID | Arquivo | Natureza | Uso principal |
|---|---|---|---|
| F1 | `Apresentação Hackathon USP 2026.pdf` | Apresentação institucional, 8 páginas | **Tema oficial**, propósito, dimensão anunciada do evento, parceiros, premiação |
| F2 | `Cronograma - Hackathon USP 2026.pdf` | Programação oficial, 2 páginas | **Datas e horários**, janelas de mentoria, fim dos projetos, pitches, avaliação, premiação |
| F3 | `07-11-2026 11.59.txt` | Transcrição automática das orientações dos organizadores | **Esclarecimento do escopo** (qualquer área de saúde), observações sobre mentoria e entrega de protótipo |
| F4 | `07-11-2026 10.33.txt` | Transcrição automática de palestra da Capim | **Estudo de caso** sobre acesso à odontologia, problemas de pacientes e clínicas |
| F5 | `CONTEXTO_HACKATHON_CAPIM.md` | Síntese analítica anterior baseada em F4 | Detalhamento complementar do caso odontológico, agora reclassificado como anexo |

**Hierarquia para divergências:** F2 é principal para horários e entregas; F1 para tema e prêmios; F3 esclarece o escopo do tema; F4 é fonte para alegações da palestra da Capim; F5 é elaboração assistida e não constitui regulamento.

### 1.2. Como interpretar informações

- **[OFICIAL]** consta diretamente dos PDFs institucionais (F1/F2).
- **[ORIENTAÇÃO ORAL]** foi afirmada na fala transcrita dos organizadores (F3), sujeita à qualidade da transcrição.
- **[CAPIM — PALESTRA]** foi afirmada durante a palestra (F4); não equivale a dado nacional auditado.
- **[HIPÓTESE/PROPOSTA]** foi incluída para ajudar a equipe; não é regra, resultado comprovado ou exigência dos jurados.
- **[NÃO INFORMADO]** não pode ser deduzido dos materiais recebidos.

**Regra para a IA:** sempre que usar um número ou requisito importante, informe a qual categoria pertence. Prefira os PDFs quando houver uma discrepância com a transcrição automática.

---

## 2. DESAFIO E MENSAGEM OFICIAIS

### 2.1. Tema confirmado [OFICIAL]

**“Saúde para todos: Soluções para reduzir barreiras no acesso à saúde.”** (F1, página 3).

### 2.2. Enquadramento institucional [OFICIAL]

A apresentação enfatiza que **saúde é um direito, não um privilégio**, que a inovação deve ampliar acesso, fortalecer inclusão e promover bem-estar (F1, página 4). A equipe deve traduzir esse princípio em um obstáculo concreto à obtenção ou continuidade de cuidados.

### 2.3. Escopo permitido [ORIENTAÇÃO ORAL]

A fala dos organizadores esclarece expressamente que a equipe pode focar em **odontologia, fisioterapia, medicina, psicologia e outras áreas da saúde**. O caso da Capim ilustra o tema, mas **não é uma exigência de vertical** (F3).

Exemplos de barreiras que podem ser analisadas, **sem afirmar que todas foram listadas pelos organizadores**:

- financeira: preço, previsibilidade de custo, falta de renda, transporte, dias de trabalho perdidos;
- geográfica: distância de serviços, áreas rurais e periferias, deslocamento;
- temporal/operacional: marcação de consulta, filas, cancelamentos, faltas, horários;
- informacional: dificuldade de entender opções, orientações, encaminhamentos, direito aos serviços;
- digital: acessibilidade, conexão ruim, baixa familiaridade com aplicativos;
- cultural e de confiança: linguagem, medo, estigma, segurança, acolhimento;
- continuidade: retorno, adesão, coordenação de múltiplos atendimentos e pós-consulta.

A solução **não precisa ser financiadora, aplicativo de agendamento ou chatbot**. A tecnologia só faz sentido se remover um gargalo específico na jornada de acesso ou na capacidade de atendimento.

### 2.4. Escala anunciada [OFICIAL + ORIENTAÇÃO ORAL]

F1 informa **36 horas de imersão** e **mais de 50 participantes** (página 2). A transcrição F3 menciona **cerca de 58 participantes** presentes/esperados; esta é uma estimativa oral, não uma lista oficial fechada.

### 2.5. O que NÃO está estabelecido nos documentos

- critérios técnicos e pesos da avaliação; duração exata de cada pitch; formato obrigatório do vídeo ou apresentação;
- tamanho mínimo/máximo de equipes, definição de propriedade intelectual, regras de uso de dados;
- obrigação de utilizar IA generativa, agentes, tecnologias da Capim ou stack específica;
- disponibilidade de APIs, bases de dados, sistemas internos, acesso clínico ou créditos de nuvem;
- obrigação de vincular o MVP à odontologia ou à Capim;
- se o envio final deve ocorrer por GitHub, formulário, pasta ou outra plataforma.

**Não criar regras fictícias.** Confirmar esses pontos com organização/mentores conforme forem relevantes.

---

## 3. CRONOGRAMA OFICIAL — 7 E 8 DE NOVEMBRO DE 2026

**Local informado:** Capim. Fonte dos horários abaixo: F2, páginas 1 e 2.

### 3.1. Sábado — 07/11/2026

| Horário | Atividade anunciada |
|---|---|
| 08h30 | Coffee break |
| 09h00 | Palestra da Capim: desafios e oportunidades na área da saúde |
| 10h15 | Palestra da Pilea Lab: “Engenharia Agêntica: Desenvolvendo Software profissionalmente com IA” |
| 11h15 | Orientações para o desenvolvimento dos projetos |
| 12h00 | Desenvolvimento dos projetos |
| 13h00 | Almoço |
| 14h00 | Mentoria + desenvolvimento dos projetos |
| 16h15 | Coffee break |
| 16h45 | Desenvolvimento dos projetos |
| 20h00 | Jantar |
| 21h00 | Encerramento da programação do **primeiro dia** |

### 3.2. Domingo — 08/11/2026

| Horário | Atividade anunciada |
|---|---|
| 08h30 | Coffee break |
| 09h00 | Desenvolvimento dos projetos |
| 10h00 | Mentoria |
| 12h00 | Almoço |
| 13h00 | Desenvolvimento dos projetos |
| 15h15 | Coffee |
| **15h45** | **Encerramento dos projetos** — entrega dos protótipos, segundo F3 |
| **16h00** | **Apresentação dos pitches** |
| 17h45 | Avaliação |
| 18h00 | Premiação |

**Nota de interpretação:** a referência a “36 horas” nos slides é a descrição do evento, não uma indicação de 36 horas líquidas de desenvolvimento. O marco operacional que importa é **15h45 de 08/11**.

### 3.3. Uso estratégico do cronograma [PROPOSTA DA EQUIPE]

1. **Sábado, após orientações:** definir uma persona, um problema verificável e um fluxo de demonstração; validar com mentores às 14h.
2. **Sábado, tarde/noite:** implementar o fluxo ponta a ponta e deixar a demonstração local funcionando.
3. **Domingo, manhã:** estabilizar o MVP, testar erros e consultar mentores às 10h.
4. **Domingo, antes de 15h45:** congelar escopo, garantir backup, README, pitch e demonstração reproduzível.
5. **Domingo, a partir de 16h:** apresentar a história do problema, a experiência do produto, o impacto e limitações.

Esse plano é uma **sugestão**, não um cronograma adicional imposto pela organização.

---

## 4. ENTREGÁVEL, DEMONSTRAÇÃO E PREMIAÇÃO

### 4.1. O que foi efetivamente comunicado

- [OFICIAL] O cronograma registra **encerramento dos projetos às 15h45** de domingo.
- [ORIENTAÇÃO ORAL] Os organizadores disseram que pedirão a entrega de **protótipos até 15h45**.
- [OFICIAL] Os **pitches começam às 16h**; há avaliação às 17h45 e premiação às 18h.
- [OFICIAL] Prêmios: **1º R$ 3.000; 2º R$ 2.000; 3º R$ 1.000** (F1, página 7; F3 confirma oralmente).

### 4.2. Pacote de entrega recomendado [PROPOSTA, NÃO REGRA]

Se a equipe estiver criando software, é prudente manter:

- repositório com instruções simples de execução;
- protótipo navegável, com um fluxo principal realmente operacional;
- dados de demonstração **sintéticos** e resetáveis;
- documentação breve: problema, público, solução, arquitetura e limitações;
- plano B para demonstração (capturas ou vídeo local) caso a infraestrutura falhe;
- pitch curto com problema, usuário, evidência, demonstração e impacto estimado **sem fabricar resultados**.

O formato oficial de envio e os critérios da banca permanecem **não informados** nos documentos.

---

## 5. COMO DEFINIR UM PROBLEMA DE ACESSO À SAÚDE

### 5.1. Pergunta norteadora

> **Qual pessoa, em qual situação concreta, deixa de receber um cuidado necessário ou tem sua jornada interrompida — e qual barreira podemos reduzir com tecnologia?**

Bons recortes são identificáveis, por exemplo: dificuldade de conseguir o primeiro atendimento, falta de orientação administrativa para encaminhamento, ausência de comparecimento por transporte, dificuldades de continuidade ou falhas de coordenação de agenda. Isso é uma **metodologia de ideação** e não uma enumeração oficial de desafios.

### 5.2. Um formato útil de problem statement

```text
PÚBLICO: [quem enfrenta a barreira]
CUIDADO NECESSÁRIO: [qual atendimento/etapa]
BARREIRA REAL: [o que o impede]
MOMENTO DA JORNADA: [onde a barreira ocorre]
CONSEQUÊNCIA: [o que acontece quando não recebe o cuidado]
CAUSA OU MECANISMO: [por que o sistema atual falha]
HIPÓTESE: [o que pode remover parte desse atrito]
MÉTRICA DE ACESSO: [como verificar melhoria]
```

### 5.3. Jornadas gerais a considerar

1. Perceber necessidade e buscar informações.
2. Entender direitos, possibilidades e opções de serviço.
3. Encontrar estabelecimento/profissional adequado.
4. Agendar e se organizar para comparecer.
5. Receber atendimento, sem que a ferramenta substitua o profissional.
6. Compreender orientações e próximos passos.
7. Retornar, continuar o cuidado e superar obstáculos posteriores.

**Não confundir aumento de uso do aplicativo com aumento real do acesso à saúde.** Priorizem métricas como agendamento viável, comparecimento, redução de remarcações, conclusão de encaminhamentos ou continuidade do cuidado, quando forem mensuráveis.

---

## 6. MAPA DE OPORTUNIDADES — IDEIAS PARA EXPLORAR, NÃO PARA IMPOR

As alternativas a seguir são **propostas analíticas** construídas a partir do tema geral, não ideias oficiais do hackathon nem decisões da equipe.

| Possível frente | Persona / gargalo | Exemplo de MVP | Risco/dependência a validar |
|---|---|---|---|
| Navegação de serviços | Paciente não sabe onde buscar o tipo correto de atendimento | Guia acessível que informa caminhos e requisitos administrativos | Fontes confiáveis e atualização; não fazer triagem diagnóstica |
| Coordenação de encaminhamentos | Paciente se perde entre consulta, exame e retorno | Linha do tempo de tarefas e documentos, com lembretes | Integração com fluxos reais de serviço |
| Acessibilidade de comunicação | Idosos e pessoas com baixa alfabetização digital | Assistente que simplifica instruções e usa voz/texto acessíveis | Qualidade, idioma, acessibilidade e validação humana |
| Redução de ausências | Consultas perdidas por esquecimento ou deslocamento | Confirmação e remarcação assistidas; alerta de barreiras práticas | Consentimento e disponibilidade real das vagas |
| Continuidade de cuidado | Paciente abandona etapas de tratamento | Acompanhamento de próximos passos definidos por profissional | Não converter IA em conduta clínica |
| Suporte à pequena clínica | Falta pessoal e processos para contato/agenda | Painel simples de filas, pendências e confirmações | Privacidade e trabalho operacional da clínica |
| Organização de custos | Paciente abandona por imprevisibilidade financeira | Visão educativa de custos declarados, etapas e opções administrativas | Não prometer crédito nem alterar plano clínico |
| Saúde mental | Obstáculos de informação e encaminhamento para cuidado | Orientação não diagnóstica para acessar canais e horários disponíveis | Situações de crise exigem protocolos e supervisão |
| Fisioterapia/reabilitação | Dificuldade de continuidade entre sessões | Lembretes e orientações administrativas sobre presença e retorno | Sem prescrição automática de exercícios |
| Saúde bucal (Capim) | Orçamentos complexos, no-show, retorno, falta de crédito | Planejamento compreensível e faseamento **validado pelo dentista** | Não duplicar IA já mencionada pela Capim |

**Atenção ao diferencial:** soluções genéricas de chatbot, agendamento e lembrete já existem. O valor do projeto deve estar em **público desassistido, contexto específico, integração plausível, experiência acessível ou barreira removida**, não somente em “usar IA”.

### 6.1. Critérios para comparar opções [MATRIZ INTERNA]

Pontue cada dimensão de 1 a 5 para cada ideia; **isso NÃO reproduz a rubrica de avaliação dos jurados**.

- impacto potencial no acesso ao cuidado;
- clareza da persona e evidência do problema;
- facilidade de comprovar valor em uma demo de poucos minutos;
- viabilidade de construir MVP até domingo 15h45;
- possibilidade de operar com dados sintéticos sem integração externa;
- diferencial em comparação com alternativas existentes;
- segurança, privacidade e baixo risco de decisão clínica indevida;
- escalabilidade e utilidade após o hackathon.

### 6.2. Três decisões que destravam a construção

**Escolher:** (a) uma pessoa específica; (b) **uma** fricção central; (c) uma ação que o sistema torna visivelmente mais fácil. Evitar começar por uma arquitetura gigantesca sem definir a mudança na vida do usuário.

---

## 7. APLICAÇÃO RESPONSÁVEL DE IA E TECNOLOGIA

### 7.1. A palestra de Engenharia Agêntica

F2 registra uma palestra da **Pilea Lab** em 07/11 às 10h15 intitulada **“Engenharia Agêntica: Desenvolvendo Software profissionalmente com IA”**. Isso é uma atividade do evento; os arquivos **não estabelecem que o produto entregue precise usar agentes ou um modelo específico**.

### 7.2. Quando IA pode ajudar [PROPOSTA]

- tornar formulários e orientações administrativas mais compreensíveis;
- extrair e estruturar informações de documentos **fictícios ou autorizados**;
- apoiar equipes na organização de tarefas, mensagens e pendências;
- ajudar navegação em serviços a partir de bases verificadas;
- gerar interfaces mais inclusivas com revisão e testes;
- apoiar análise de requisitos, programação, documentação e testes.

### 7.3. Limites necessários

- **Não diagnosticar, prescrever, estabelecer urgência clínica ou substituir profissional habilitado**.
- **Não afirmar existência de vagas, preços ou direitos sem dados verificáveis**.
- **Não aprovar crédito, seguro ou elegibilidade clínica de maneira fictícia**.
- Tratar dados de saúde como **dados pessoais sensíveis** sob a LGPD; minimizar coleta, usar consentimento/base legal adequada quando cabível e não enviar registros reais a serviços de IA sem autorização e controles.
- Prever revisão humana, aviso de limitações e caminhos para exceções.
- Para demonstração, preferir **dados sintéticos**, cenários controlados e estrutura que mostre o processo completo.

---

## 8. MVP DEMONSTRÁVEL: ESTRATÉGIA DE ENGENHARIA [PROPOSTA]

### 8.1. Princípios

- Uma única jornada **fim a fim** funcionando é melhor que dez telas simuladas sem conexão.
- A demonstração deve mostrar **antes → interação → depois** para uma pessoa concreta.
- A stack é livre na documentação recebida; escolher a mais familiar ao time e de fácil execução.
- É permitido trabalhar com mocks **desde que rotulados como mocks** e que a equipe saiba distinguir simulação de integração real.
- A solução não precisa coletar dado clínico real para provar a interface e o processo.
- Evitar integrações dependentes de conta, aprovação ou API que ainda não existem.
- Documentar como rodar, incluindo variáveis de ambiente de exemplo, nunca segredos reais.

### 8.2. Backlog de primeira prioridade

1. Definir persona e objetivo de sucesso.
2. Criar exemplo sintético representativo.
3. Implementar fluxo principal de ponta a ponta.
4. Criar uma tela de resultado explicável.
5. Lidar com dados vazios e um caso de erro.
6. Adicionar indicadores demonstráveis do fluxo (não inventar estatísticas de impacto).
7. Preparar README e roteiro de apresentação.

### 8.3. Checklist de teste rápido

- O usuário entende o objetivo da aplicação sem explicação externa?
- O fluxo principal funciona após atualizar a página/reiniciar aplicação?
- É possível testar sem contas reais e sem dados sensíveis?
- Existe tratamento para ausência de dados e falha da API/modelo?
- Se usa IA, há limites contra respostas clínicas indevidas?
- O produto indica o que é simulado e o que é funcional?
- Há um plano B se internet ou deploy falhar?

---

## 9. MENTORIA — PERGUNTAS QUE VALEM TEMPO

F2 agenda **mentoria a partir das 14h de sábado** e **às 10h de domingo**. Na orientação oral, os mentores são descritos como pessoas que percorrem os grupos e questionam sobretudo o que está sendo construído e sua viabilidade técnica (F3).

Perguntas sugeridas aos mentores/organização (não são critérios publicados):

1. Nosso público e problema estão dentro do escopo amplo do evento?
2. Esta dor foi realmente observada em pacientes, profissionais ou clínicas?
3. Qual etapa da jornada tem maior desperdício ou abandono?
4. Em que a proposta se diferencia de ferramentas já disponíveis?
5. A solução depende de uma integração que não está autorizada/disponível?
6. Quais exigências éticas e de privacidade são relevantes ao nosso recorte?
7. Qual seria um teste simples e legítimo para medir impacto no acesso?
8. Qual é o formato obrigatório da entrega e onde enviar o protótipo?
9. Há tempo máximo de pitch e requisitos de slides/demo?
10. Quais são os critérios e pesos de avaliação da banca? (**não informados nos arquivos**)

---

## 10. COMO PREPARAR O PITCH [PROPOSTA]

### 10.1. Estrutura curta adaptável

1. **Problema humano:** quem perde acesso, em que momento, e com qual consequência?
2. **Evidência:** qual dado da fonte ou observação sustenta a necessidade? Identificar se é fala, estimativa ou dado verificado.
3. **Solução:** uma frase simples, com beneficiário principal.
4. **Demo:** uma tarefa concreta executada com a ferramenta.
5. **Impacto esperado:** qual indicador melhoraria? Informar claramente se é meta, hipótese ou medição real.
6. **Viabilidade e limites:** o que funciona, o que é simulado e como evoluir.

**Duração exata do pitch: não informada nos arquivos.** Ensaie uma versão compacta e confirme a regra com a organização.

### 10.2. O que evitar

- prometer redução de custos, aumento de acesso ou eficácia clínica sem medição;
- confundir o tema geral com a odontologia específica;
- tratar dados da palestra da Capim como estatísticas nacionais atualizadas;
- mostrar apenas telas estáticas sem uma mudança clara na jornada;
- demonstrar diagnósticos automatizados ou decisões financeiras potencialmente danosas;
- apresentar funcionalidades e APIs inexistentes como se estivessem integradas.

---

## 11. INSTRUÇÕES MESTRAS PARA A IA QUE RECEBER ESTE ARQUIVO

**Papel:** seja uma equipe virtual multidisciplinar de *product manager*, pesquisador UX, engenheiro de software, desenvolvedor full-stack, especialista em IA aplicada, profissional de acessibilidade e mentor de pitch. Não finja ser profissional de saúde responsável pelo atendimento.

### 11.1. Prioridades de comportamento

1. **Leia este documento antes de sugerir ideias.** O desafio oficial é **saúde em geral**, não necessariamente odontologia.
2. Distinga F1/F2 (materiais institucionais), F3 (fala de orientações), F4 (palestra da Capim) e propostas desta síntese.
3. Respeite o marco de **domingo 08/11 às 15h45** para encerrar o protótipo, salvo atualização oficial posterior.
4. Não invente entregáveis obrigatórios, regulamento, pesos de nota, infraestrutura disponibilizada, duração de pitch ou disponibilidade de dados.
5. Se a equipe ainda não definiu a ideia, apresente alternativas **genuinamente distintas** e compare-as por acesso, viabilidade, diferenciação, riscos e potencial de demonstração.
6. Recomende uma ideia quando solicitado, justificando trade-offs e premissas; não a declare escolhida sem decisão da equipe.
7. Após uma ideia ser escolhida, ajude com backlog enxuto, arquitetura simples, código, testes, UX e pitch.
8. Não troque problema por tecnologia: agentes/LLMs só entram quando ajudam a reduzir uma barreira concreta.
9. Prefira código executável e demos funcionais com dados sintéticos, sem depender de segredos ou APIs não confirmadas.
10. Não reproduza estatísticas frágeis como fatos científicos, nem confunda hipótese de impacto com resultado medido.
11. Considere o risco de dados sensíveis, vieses e acesso desigual; inclua alternativa quando a pessoa não tem smartphone, internet ou alta alfabetização digital.
12. Não pratique triagem/diagnóstico automatizado de pacientes nem encaminhamento clínico sem profissional responsável.
13. Pergunte apenas o que impede uma decisão importante; caso contrário, faça uma premissa explícita e avance.
14. Ao programar, forneça artefatos concretos: estrutura, comandos de instalação, exemplos de variáveis de ambiente, validações e testes.
15. Ao redigir pitch, seja claro, humano e rigoroso com as evidências.

### 11.2. Formato de análise de ideia

```text
NOME PROVISÓRIO:
ÁREA(S) DA SAÚDE:
PERSONA:
JORNADA EM QUE HÁ A BARREIRA:
PROBLEMA ESPECÍFICO:
EVIDÊNCIA / FONTE / GRAU DE CONFIANÇA:
SOLUÇÃO EM UMA FRASE:
ANTES -> DEPOIS (3 PASSOS):
O QUE É IA E O QUE É CÓDIGO TRADICIONAL:
DIFERENCIAL EM RELAÇÃO A ALTERNATIVAS:
MVP PRONTO PARA DEMO ATÉ 15H45:
DEPENDÊNCIAS / MOCKS:
MÉTRICA DE ACESSO:
RISCOS CLÍNICOS, DE SEGURANÇA E PRIVACIDADE:
TESTES MÍNIMOS:
ESTRUTURA DO PITCH:
```

### 11.3. Formato do status do projeto

Manter em texto ou seção atualizada as seguintes informações para preservar a continuidade entre IAs:

```text
IDEIA ESCOLHIDA: ainda não definida nos materiais recebidos
PROBLEMA / PERSONA: a definir
PROPOSTA DE VALOR: a definir
TECNOLOGIAS / REPOSITÓRIO: não informados
DADOS REAIS OU SINTÉTICOS: não definidos; recomendação de sintéticos
MVP IMPLEMENTADO: não informado
TESTES EXECUTADOS: não informados
MENTORIA / FEEDBACK RECEBIDO: não informado
RESPONSÁVEIS: não informados
PRÓXIMO MARCO: finalizar projetos em 08/11/2026, 15h45
PITCH: a partir de 08/11/2026, 16h
```

---

## 12. PROMPT PRONTO PARA ABRIR OUTRA CONVERSA COM IA

> Estamos no **Hackathon USP 2026 (7–8 de novembro de 2026)**. Leia o documento `CONTEXTO_MESTRE_HACKATHON_USP_2026.md` inteiro. **O tema oficial é “Saúde para todos: soluções para reduzir barreiras no acesso à saúde”, e NÃO estamos limitados à odontologia.** A Capim apresentou um caso detalhado de odontologia, que deve servir como exemplo e fonte de oportunidades, mas podemos construir soluções para medicina, psicologia, fisioterapia e outras frentes. O protótipo deve estar encerrado **domingo 08/11 às 15h45**; pitches a partir das **16h**. Primeiro, resuma o desafio e os principais riscos/limites. Depois, proponha 5 ideias diferentes (pelo menos 3 fora de odontologia), cada uma com persona, barreira, inovação real, fluxo, diferencial, dados necessários, viabilidade e demo até o prazo. Compare as ideias com uma matriz transparente, sem fingir que é a avaliação oficial, e recomende as duas mais promissoras. **Separe fatos dos documentos, dados da palestra, hipóteses e propostas. Não invente integrações.** Depois de escolhermos, ajude a construir o MVP completo, testar e preparar o pitch.

---

## 13. OBSERVAÇÕES DE TRANSCRIÇÃO E LACUNAS

- No F3, várias palavras estão incorretas (por exemplo, transcrições aproximadas de “hackathon”, “Capim” e “Pilea”). Quando houver divergência de nomes, **preferir os PDFs**.
- A menção oral a “cerca de 58 participantes” complementa, mas não substitui, a informação oficial de “50+ participantes”.
- A menção oral de “às 8h” para divulgação de vencedores é ambígua/possível erro: **F2 estabelece premiação domingo às 18h**.
- F2 indica “encerramento dos projetos” às **15h45**; F3 explicitamente fala em **entrega de protótipos** neste horário. O canal e formato de entrega permanecem desconhecidos.
- Os números do setor odontológico na palestra da Capim refletem falas e/ou dados internos sem fonte metodológica reproduzida; não declarar que estão validados nacionalmente.
- O cronograma confirma apenas a palestra de Engenharia Agêntica; não comprova que IA seja requisito técnico do MVP.

---

## ANEXO A — CASO CAPIM: APROFUNDAMENTO EM ODONTOLOGIA

**Esta seção contém o contexto temático anteriormente consolidado a partir da palestra da Capim e foi incluída para preservar os detalhes, exemplos, dados apresentados, oportunidades e riscos. É um estudo de caso, não a formulação do desafio oficial nem uma exigência de recorte.** As referências a “objetivo do hackathon” dentro desse anexo devem ser interpretadas como **objetivo hipotético de um projeto que escolha odontologia**, nunca como restrição das regras do evento.

**Origem:** F4, transcrição automática `07-11-2026 10.33.txt`; elaboração anterior F5. Termos foram normalizados somente quando o contexto permite inferência razoável. Valores e falas não foram auditados.

### 1. SOBRE A CAPIM E O CONTEXTO DA APRESENTAÇÃO

#### 1.1. O que a Capim faz

A Capim foi apresentada como uma empresa que começou facilitando o **crédito para tratamentos odontológicos**. Exemplo ilustrativo da fala: o paciente precisa fazer um tratamento de aproximadamente **R$ 4.000**, mas só dispõe de **R$ 1.500 de limite de cartão**; talvez já tenha outras parcelas ou restrições de crédito. Mesmo precisando do tratamento, não consegue pagar na forma convencional.

A distribuição inicial ocorre junto às clínicas: a empresa se relaciona com dentistas e clínicas, que passam a oferecer alternativas aos pacientes. É uma dinâmica **B2B com impacto no consumidor final (B2B2C)**. A fala usa os termos “B2B, B2C”, sem descrever formalmente uma taxonomia única de modelo de negócios.

A Capim relatou ter ampliado o ecossistema para ferramentas de **gestão das clínicas**, **meios de pagamento**, **alternativas de crédito** e **IA para relacionamento com pacientes**.

#### 1.2. Produtos e capacidades mencionados

| Componente | Papel segundo a apresentação |
|---|---|
| Crédito para tratamentos | Possibilitar o pagamento quando o paciente não tem limite ou recursos imediatos. |
| DASH / gestão da clínica | Apoiar acompanhamento e gestão operacional. O nome exato da solução deve ser confirmado. |
| Maquininha / pagamentos | Oferecer infraestrutura de pagamento; a empresa relatou ter construído uma operação própria de subadquirência. |
| Alternativas de crédito | Foram mencionadas outras modalidades, incluindo microcrédito e opções com diferentes condições. |
| IA de relacionamento (“Camila”) | Apoiar agendamento, conversão de orçamentos e reativação de pacientes inativos, inclusive com conteúdo educativo. |
| Apoio comercial / recorrência | Ajudar clínicas a acompanhar interessados e trazer pacientes de volta. |

A existência dessas soluções é relevante para a ideação: **propor “um chatbot que agenda consultas” isoladamente pode duplicar algo que a Capim já declarou fazer**. O diferencial precisaria estar em público, experiência, integração, capacidade adicional ou resultado mensurável.

#### 1.3. Indicadores de escala citados pela Capim

- **Mais de 12 mil clínicas**: número apresentado durante a fala.
- **R$ 10 milhões faturados por mês**: o apresentador explicitou a diferença entre **faturamento** e **originação de crédito**. Não confundir as duas grandezas.
- **Mais de 200 pessoas no time**: escala organizacional relatada.
- **Crédito de R$ 0 a R$ 30 mil**: faixa apresentada para o produto, com modelos em que o paciente pode ter ou não juros, conforme as condições da operação.

Esses números são **afirmações da apresentação**, não métricas verificadas independentemente. Não usá-los como dados de hoje sem validação adicional.


---

### 2. PROBLEMA PRINCIPAL: ALTA OFERTA, BAIXO ACESSO

#### 2.1. O paradoxo apresentado

A fala caracteriza o Brasil como um dos maiores mercados odontológicos do mundo, com alto número de dentistas, clínicas, formação profissional e capacidade técnica. Apesar da oferta, uma parcela muito grande da população não tem acesso regular, financeiramente viável e contínuo ao atendimento odontológico.

O problema não deve ser reduzido à frase “faltam dentistas”. A tese do apresentador é que existem **atritos sistêmicos entre necessidade, descoberta, escolha, orçamento, pagamento, comparecimento, tratamento e acompanhamento**.

#### 2.2. Indicadores citados — usar com cautela

| Indicador | Valor mencionado na fala | Observação importante |
|---|---:|---|
| Brasileiros com dificuldade de acesso à odontologia | **150 milhões** | Enunciado como magnitude do problema/ambição da empresa; definição e fonte original não informadas. |
| Pessoas que foram ao dentista nos últimos 12 meses | **~50% da população** | O outro grupo ficaria há mais de um ano sem consulta; não equivale necessariamente a “nunca foi”. |
| Pessoas que perderam todos os dentes | **14 milhões** | Número citado sem fonte ou ano. |
| População adulta que precisa de prótese | **Mais da metade** | Alegação da apresentação, sem metodologia especificada. |
| Pessoas com nome negativado | **84 milhões** | Contextualiza barreiras de crédito; período e definição não indicados. |
| Pessoas sem cartão de crédito | **60%** | Percentual falado sem população-base claramente definida. |
| Acesso a plano odontológico | **17% da população** | Dado da fala; não converter automaticamente em cobertura de outros seguros. |
| Planos odontológicos ligados a empregadores | **~3/4 entre os que têm plano** | Ressalta dificuldade para pessoas sem emprego formal. |
| Dentistas que aceitam convênio | **~35%** | Dado da apresentação, não necessariamente percentual nacional auditado. |
| Extrações entre pessoas sem plano | **~2,5 vezes mais** | A associação foi mencionada; não assumir causalidade sem pesquisa. |
| Consultas odontológicas agendadas com falta (*no-show*) | **~50%** | Estimativa citada na fala; não assumir validade para todas as clínicas. |
| Orçamentos de até R$ 500 que são fechados | **~75%** | Indicador descrito como proveniente de base da Capim. |
| Orçamentos acima de R$ 3.000 que são fechados | **~25%** | Indicador de base própria, sujeito a viés de seleção. |
| Empresas ligadas à odontologia | **Mais de 50 mil** | Definição exata de empresa não foi fornecida. |
| Profissionais dentistas | **Até ~600 mil, dependendo do critério** | Número apresentado com ressalva explícita do palestrante. |

**Nota metodológica importante:** os próprios palestrantes indicaram que alguns indicadores vêm da **base de pacientes atendidos/observados pela Capim**, que não representa necessariamente toda a população brasileira. Pessoas que jamais procuram atendimento podem ficar fora dessa amostra. Por isso:

1. Nunca declarar esses números como estatísticas públicas definitivas sem encontrar a fonte original.
2. Para o pitch, citar preferencialmente **“segundo os dados apresentados pela Capim”**.
3. Não misturar percentuais de populações diferentes nem somar métricas que podem se sobrepor.
4. Se algum valor parecer suspeito, manter como **“a validar”**, não corrigir silenciosamente.

---

### 3. POR QUE O ACESSO É TÃO DIFÍCIL?

#### 3.1. O custo de adiar tratamento

Um dos argumentos mais importantes da apresentação é resumido na frase:

> **“Pobreza cobra juros.”**

A pessoa sem dinheiro para tratar um problema no início adia a consulta e/ou o tratamento. A condição pode piorar, o orçamento necessário cresce e o problema fica ainda menos acessível. O palestrante ilustra a situação com uma pessoa que recebe cerca de **R$ 2.000** e, após sucessivos adiamentos, enfrenta um tratamento de **R$ 7.000**.

**Consequência para o hackathon:** prevenir o abandono e o adiamento pode ter tanto impacto quanto financiar tratamentos já muito caros. A solução pode atuar **antes da emergência**, no acompanhamento do plano de tratamento ou no pós-consulta.

#### 3.2. Principais barreiras do lado do paciente

1. **Gatilho tardio:** muitas pessoas procuram o dentista apenas quando sentem dor ou quando o problema se torna urgente.
2. **Desinformação:** não sabem quais alternativas de atendimento, pagamento ou cuidado realmente existem.
3. **Preço desconhecido:** não conseguem estimar quanto poderão gastar antes de passar por consulta e avaliação profissional.
4. **Surpresa no orçamento:** chegam à clínica, recebem proposta elevada e desistem.
5. **Baixa capacidade de pagamento:** renda insuficiente, falta de cartão, limite baixo, parcelas acumuladas e/ou restrição de crédito.
6. **Medo:** dor, constrangimento, tratamento, compromisso financeiro ou falta de confiança.
7. **Dificuldade de escolha:** reputação, proximidade, confiança e capacidade financeira influenciam a decisão.
8. **Ausência de continuidade:** o paciente não retorna, abandona o tratamento ou deixa de realizar a prevenção.
9. **Acesso geográfico e operacional:** distância, deslocamento e etapas presenciais desnecessárias também podem dificultar.
10. **Barreiras de compreensão:** um plano completo pode ser difícil de entender, comparar ou planejar.

#### 3.3. Principais barreiras do lado da clínica/dentista

1. **Receita e margem pressionadas:** o palestrante cita remuneração muito baixa em determinadas consultas por convênio (exemplos de **R$ 10 a R$ 15**).
2. **Dificuldade em vender/comunicar sem descaracterizar o cuidado:** muitos dentistas não gostam ou não sabem como discutir preço, prioridade e opções.
3. **Orçamentos não convertidos:** o paciente faz avaliação, recebe proposta, mas não inicia o tratamento.
4. **Faltas às consultas:** um horário reservado e não utilizado representa perda de capacidade operacional e de acesso.
5. **Pouca capacidade de gestão comercial:** clínicas menores podem não ter processos estruturados de lembretes, acompanhamento ou relacionamento.
6. **Baixa capacidade de oferecer parcelamento próprio:** sobretudo onde faltam capital, sistemas e confiança para isso.
7. **Desigualdade de estrutura:** grandes clínicas contam com profissionais, equipamentos, processos e soluções que muitas pequenas não conseguem reproduzir.
8. **Dependência de canais de distribuição:** convênios e outros intermediários podem definir como pacientes chegam à clínica.
9. **Dificuldade de planejar tratamentos em fases:** comunicar todos os problemas clínicos é importante, mas falta frequentemente um roteiro operacional claro e compreensível para execução gradual.

#### 3.4. Problemas do ecossistema

- **Convênio odontológico não cobre tudo:** há restrições de procedimentos, cobertura, rede e viabilidade econômica dos contratos.
- **Cobertura muito ligada ao vínculo empregatício:** pacientes em trabalho informal ou desempregados podem ficar à margem.
- **Tensão entre custo do plano e uso do benefício:** o apresentador associa o desafio à alta utilização/sinistralidade e à remuneração limitada ao prestador.
- **Desigualdade regional:** a fala sugere que **parcelamento por boleto é mais comum no interior**, atribuindo parte disso à confiança nas relações locais. Essa hipótese deve ser validada antes de generalizar.
- **Modelos atuais não resolvem todas as faixas de renda:** soluções voltadas a clientes bancarizados ou com renda estável podem excluir exatamente quem mais precisa.

#### 3.5. Impacto humano

A fala enfatiza que odontologia não é apenas uma questão de estética ou de dentes. A falta de acesso pode repercutir em:

- dor e qualidade de vida;
- autoconfiança e convivência social;
- capacidade de sorrir, comunicar-se e participar de entrevistas de emprego;
- saúde e bem-estar;
- produtividade, vida profissional e renda;
- custos futuros decorrentes da postergação de tratamentos.

**Orientação narrativa:** falar de **dignidade, saúde, autonomia, previsibilidade e continuidade do cuidado**, sem explorar de maneira sensacionalista pessoas com baixa renda ou problemas dentários.

---

### 4. A JORNADA COMPLETA DO PACIENTE

A Capim fez uma observação explícita: **uma ideia que não se encaixa na realidade operacional do paciente e da clínica dificilmente funciona**. Portanto, usar a jornada abaixo como estrutura de análise.

| Etapa | O que acontece | Obstáculo típico | Oportunidade potencial (hipótese) |
|---|---|---|---|
| 1. Percepção da necessidade | A pessoa percebe dor, desconforto, problema ou vontade de prevenção. | Só agir quando há dor. | Educação acessível, acompanhamento e incentivo à prevenção. |
| 2. Descoberta de alternativas | Busca saber onde pode ser atendida e quanto pode pagar. | Não conhecer serviços e modalidades de pagamento. | Navegação de opções elegíveis e informação de qualidade. |
| 3. Escolha da clínica | Compara confiança, local, preço, disponibilidade. | Incerteza, distância, falta de referência. | Melhor orientação e comparação de atributos verificáveis. |
| 4. Agendamento | Tenta encaixar a visita na rotina. | Atraso, fricção, desencontro de horários. | Agendamento simples e confirmação clara. |
| 5. Comparecimento | Precisa ir à consulta. | Falta, esquecimento, insegurança, deslocamento. | Lembretes adequados, comunicação prévia e remarcação. |
| 6. Diagnóstico e orçamento | Dentista avalia necessidades e explica alternativas. | Linguagem técnica, preço inesperado, valor integral alto. | Explicação clara, sem substituir o profissional. |
| 7. Planejamento | Paciente decide o que fazer e quando. | Orçamento total incompatível com o mês. | **Plano faseado validado pelo dentista**, com prioridades, etapas e custos. |
| 8. Pagamento | Precisa viabilizar o tratamento. | Limite baixo, negativação, crédito caro/inadequado. | Opções de pagamento transparentes e responsáveis. |
| 9. Tratamento | Realiza procedimentos. | Abandono, novas faltas, dificuldade de coordenação. | Acompanhamento de progresso e continuidade. |
| 10. Retorno e prevenção | Faz revisão e mantém saúde bucal. | Perda do contato e baixa recorrência. | Reativação, educação e lembretes clinicamente apropriados. |

#### 4.1. Perfis comportamentais citados

A fala menciona um espectro de pacientes:

- **Reativo:** costuma agir quando aparece um problema.
- **Funcional/pragmático:** procura atendimento quando entende que é necessário.
- **Preventivo/engajado:** mantém alguma rotina de acompanhamento, com intervalos mencionados de 6 a 12 meses, conforme o caso.

Esses perfis são simplificações operacionais, **não classificações clínicas ou diagnósticos**. Um mesmo paciente pode mudar de comportamento conforme renda, momento de vida e necessidade.

#### 4.2. A surpresa de preço como ponto crítico

O paciente gostaria de saber quanto pagará, mas a clínica frequentemente não comunica valores antecipadamente. A apresentação menciona **restrições éticas na publicidade de preços de serviços odontológicos** e o fato de que a avaliação clínica determina a conduta.

**Consequência de design:** evitar uma solução que publique “preço exato garantido” para procedimentos individuais sem avaliação, ou que transforme orientações gerais em diagnóstico. É mais responsável mostrar **informação de processo, faixas ou simulações devidamente qualificadas e revisadas**, caso sejam permitidas e sustentadas por dados.

#### 4.3. Tratamento faseado: uma oportunidade destacada

Um paciente pode receber um orçamento completo de muitos milhares de reais e simplesmente não conseguir começar. O apresentador sugeriu um caminho diferente: explicar ao paciente **tudo o que foi clinicamente identificado**, mas oferecer um **plano organizado em fases**, com a ordem definida pelo dentista, por exemplo:

1. cuidar de urgências identificadas;
2. estabilizar problemas prioritários;
3. executar procedimentos restauradores ou reabilitadores;
4. tratar objetivos eletivos ou estéticos, quando aplicáveis.

**A ordem concreta deve ser clínica e individualizada.** A IA pode ajudar a **comunicar, organizar, acompanhar e simular capacidade de pagamento**, mas não decidir sozinha que um procedimento necessário pode esperar.

> **Insight de alto valor:** parte do problema pode ser resolvida com **coordenação, comunicação e planejamento**, mesmo sem oferecer uma nova linha de crédito.

---

### 5. A JORNADA E A ECONOMIA DO DENTISTA

A clínica não é um canal passivo: ela tem incentivos e restrições próprios. Uma solução útil precisa melhorar a vida do paciente **sem exigir trabalho operacional ou risco financeiro desproporcional do dentista**.

#### 5.1. Pontos de atenção

- **Agenda e cadeira:** uma falta representa capacidade de atendimento desperdiçada, e tentar preencher horários de última hora pode ser difícil.
- **Conversa pós-orçamento:** a aprovação clínica não significa que o paciente consegue aceitar a proposta financeira.
- **Recebimento:** o dentista precisa receber com previsibilidade para pagar equipe, equipamentos, aluguel e insumos.
- **Parcelamento próprio:** permitir pagamento gradual pode aumentar acesso, mas transfere à clínica o risco de inadimplência se não houver estrutura adequada.
- **Gestão da carteira:** a clínica precisa acompanhar quem faltou, quem não fechou o orçamento, quem interrompeu tratamento e quem deve retornar.
- **Escalabilidade:** processos manuais que funcionam em clínica grande não são automaticamente replicáveis em consultório pequeno.

#### 5.2. Diferenças entre clínicas

A fala usa o contraste entre **clínicas profissionalizadas/grandes** e **clínicas menores**. As maiores tendem a dispor de mais equipamentos, equipe comercial, gestão, modalidades de pagamento e variedade de procedimentos.

Foram citados exemplos ilustrativos, como adoção de scanner intraoral, maior capacidade para determinados tratamentos e estrutura de acompanhamento. **Não transformar os percentuais citados nesse trecho em estatísticas precisas sem consultar os slides ou a pesquisa original**, porque a transcrição está fragmentada.

#### 5.3. Pergunta de produto

> **Como oferecer às clínicas menores capacidades operacionais, comerciais e de acompanhamento que hoje se concentram nas maiores — com baixo custo, uso simples e segurança?**

Essa é uma frente distinta, mas complementar, ao problema do financiamento.

---

### 6. MODELOS JÁ EXISTENTES E POR QUE NÃO BASTAM

| Modelo | Onde ajuda | Limitações ou cuidados destacados |
|---|---|---|
| Cartão de crédito parcelado | Simplicidade para clientes com limite. | Exclui quem não tem cartão ou limite suficiente. |
| Crédito especializado da Capim | Pode viabilizar tratamentos sem depender só do cartão tradicional. | Crédito não resolve sozinho confiança, faltas, baixa renda ou má comunicação. |
| Parcelamento em boleto pela clínica | Permite parcelamento fora do cartão. | Clínica assume gestão de cobrança e potencial risco de inadimplência. |
| Convênio odontológico | Pode ampliar uso de consultas e procedimentos cobertos. | Rede/cobertura limitadas, dependência de emprego e atratividade reduzida para prestadores. |
| Consórcio / pagamento prévio gradual | Pode servir a tratamentos planejáveis. | Não atende necessariamente urgência imediata; condições precisam ser compreendidas. |
| Redes populares e clubes de desconto | Podem reduzir custos para determinados públicos. | Disponibilidade e condições variam por rede e localidade. |
| SUS | É uma via relevante de acesso à odontologia. | Capacidade, serviços e oferta local variam; não foi detalhado na transcrição. |
| Atendimento remoto/tecnologias de suporte | Pode reduzir parte da fricção de distância e orientar a jornada. | Não substitui procedimentos que exigem exame e atuação presencial. |

**Princípio:** mapear e integrar as soluções já existentes pode ser mais valioso do que inventar outro produto financeiro.

---

### 7. OPORTUNIDADES DE INOVAÇÃO PARA EXPLORAR NO HACKATHON

As frentes abaixo são **interpretações/hipóteses de ideação**, não exigências oficiais e nem projetos escolhidos pela equipe.

#### Frente A — Começar o tratamento em vez de abandonar o orçamento

**Problema:** paciente recebe orçamento alto, se assusta e some.

**Possível abordagem:** transformar o orçamento definido pelo dentista em uma explicação acessível, com etapas, objetivos, prioridades clínicas **aprovadas pelo profissional**, cenários transparentes de pagamento e próximas ações.

**Indicadores possíveis:** taxa de aceitação de orçamento; tempo entre orçamento e início; percentual de pacientes que concluem uma etapa.

**Risco:** sugerir adiamentos clinicamente inadequados ou pressionar o paciente a assumir dívidas.

#### Frente B — Reduzir faltas e aproveitar melhor a agenda

**Problema:** no-show elevado diminui produtividade e acesso.

**Possível abordagem:** confirmação de presença, lembretes contextualizados, remarcação fácil e oferta de vagas liberadas a pacientes elegíveis/interessados.

**Indicadores possíveis:** taxa de comparecimento; horários recuperados; tempo médio até atendimento.

**Risco:** mensagens invasivas e pressão desnecessária em pessoas vulneráveis.

#### Frente C — Encontrar caminhos reais para atendimento

**Problema:** pacientes não sabem onde buscar atendimento compatível com sua necessidade, localidade, condições e orçamento.

**Possível abordagem:** orientador que explica opções disponíveis — SUS, redes populares, clínicas, cobertura de convênio e alternativas de pagamento, somente quando confirmadas.

**Indicadores possíveis:** taxa de encaminhamento útil; agendamento efetivado; custo ou tempo para encontrar opção viável.

**Risco:** recomendar estabelecimento inexistente, apresentar disponibilidade falsa ou confundir publicidade com orientação imparcial.

#### Frente D — Prevenção e retorno

**Problema:** pacientes reativos voltam apenas quando o quadro piora.

**Possível abordagem:** lembretes de acompanhamento, materiais educativos claros e jornadas de retorno personalizadas mediante consentimento.

**Indicadores possíveis:** retorno no intervalo indicado pelo profissional; adesão a revisão; abandono reduzido.

**Risco:** fazer triagem ou diagnóstico clínico automatizado como se fosse definitivo.

#### Frente E — “Gestão de clínica grande” para consultórios pequenos

**Problema:** pequenas clínicas não possuem equipe nem processos para gerir pacientes, orçamentos, retornos e pagamentos.

**Possível abordagem:** assistente operacional enxuto que organiza o funil administrativo, gera tarefas e mensagens para revisão humana e mede gargalos.

**Indicadores possíveis:** horas administrativas poupadas; orçamentos recuperados; faltas evitadas; uso ativo pela clínica.

**Risco:** criar um CRM genérico que já existe sem diferencial odontológico ou sem integração demonstrável.

#### Frente F — Comunicação, confiança e educação financeira

**Problema:** tratamentos complexos e opções de pagamento são pouco compreendidos.

**Possível abordagem:** explicador de orçamento e modalidades de pagamento em linguagem simples, com termos e custo total transparentes.

**Indicadores possíveis:** compreensão do paciente; decisão informada; redução de perguntas repetitivas; aceitação consciente.

**Risco:** ocultar taxas ou usar persuasão manipulativa para aumentar conversão.

#### Frente G — Acesso para pessoas sem cartão ou negativadas

**Problema:** justamente quem tem renda/limite restritos pode ficar excluído do cuidado.

**Possível abordagem:** navegação de alternativas existentes, elegibilidade informativa, ajuda na documentação ou planejamento de pagamento sem promessa de aprovação.

**Indicadores possíveis:** percentual que encontra caminho viável; início de tratamento; satisfação e compreensão do custo.

**Risco:** discriminação, uso inadequado de dados financeiros e endividamento excessivo.

#### Frente H — Integração e continuidade após a consulta

**Problema:** o paciente se perde entre avaliação, orçamento, agendamento, pagamento e múltiplas sessões.

**Possível abordagem:** linha do tempo do tratamento aprovada pela clínica, com status, próximas consultas, pendências administrativas e orientações não clínicas.

**Indicadores possíveis:** etapas concluídas; taxa de abandono; necessidade de contato manual da secretaria.

**Risco:** armazenamento excessivo de dados de saúde e mensagens com informações sensíveis expostas.

#### Como diferenciar uma boa ideia

Uma proposta convincente deveria responder a todas estas perguntas:

- **Quem exatamente é o usuário inicial?** Ex.: paciente que recebeu orçamento e não conseguiu fechar; pequena clínica com alto no-show; paciente sem cartão.
- **Qual é a dor observável e frequente?** Onde a pessoa perde tempo, dinheiro ou acesso?
- **Qual etapa da jornada é atacada?** Evitar soluções que dizem resolver “tudo” de maneira superficial.
- **O que muda na prática?** Qual ação fica mais rápida, clara, acessível ou viável?
- **Por que não basta a ferramenta atual da Capim ou um sistema comum?** Demonstrar novidade/complementaridade.
- **Quem ganha valor e por quê?** Paciente, clínica, empresa parceira e sistema de saúde, quando aplicável.
- **O que pode ser demonstrado com dados fictícios?** Não depender de integrações não liberadas.
- **Como medir o benefício?** Definir uma métrica principal e um indicador de segurança/qualidade.

---

### 8. ORIENTAÇÕES PARA O PROJETO E PARA O MVP

#### 8.1. Princípios de desenho

1. **Foco em acesso real**, não apenas número de cliques, mensagens ou propostas de crédito.
2. **Paciente e dentista como dois lados do sistema**; evitar transferir todo o custo ao outro lado.
3. **Resolver uma etapa crítica primeiro**; hackathon favorece profundidade demonstrável.
4. **Baixa fricção**, especialmente para pessoas com poucos recursos digitais ou financeiros.
5. **Linguagem simples**, adequada a letramentos diferentes.
6. **IA onde agrega valor**, não como adorno: síntese de documentos, explicação, personalização supervisionada, automação assistida ou identificação de pendências.
7. **Humano responsável por decisões clínicas e financeiras reguladas**.
8. **Integração realista**, com dados sintéticos se não houver sistemas oficiais disponíveis.
9. **Transparência sobre limites e hipóteses** da demonstração.
10. **Impacto mensurável e responsável**.

#### 8.2. Exemplo de recorte viável para prototipação

Este é **apenas um exemplo ilustrativo**, não uma recomendação já decidida:

**Entrada simulada:** orçamento com itens descritos pelo dentista, custos e prioridades previamente validadas; disponibilidade de agenda; preferências do paciente; capacidade mensal de pagamento declarada pelo próprio usuário.

**Processamento:** gerar uma explicação em português simples e uma jornada faseada **sem alterar a prioridade clínica**, mostrar possibilidades de organização financeira que não equivalem a aprovação de crédito, e sugerir próximos passos administrativos.

**Saída:** painel do paciente e resumo para a clínica, com cronograma de acompanhamento e pontos em que um profissional precisa aprovar.

**Demo:** demonstrar o antes/depois de um orçamento difícil de entender, com dados inteiramente fictícios, mostrando uma pessoa conseguindo visualizar uma decisão informada sem prometer tratamento, diagnóstico, crédito ou resultados.

#### 8.3. Sugestão de estrutura de demo

1. Apresentar uma persona sintética e sua barreira realista.
2. Mostrar como a jornada falha hoje.
3. Executar o produto do ponto de vista do usuário.
4. Mostrar o que muda para a clínica.
5. Explicitar quando há revisão humana.
6. Exibir uma métrica que **seria medida em piloto**; diferenciar de resultado já obtido.
7. Explicar de forma objetiva o próximo experimento necessário para validar.

#### 8.4. Uma matriz útil para selecionar ideias

Usar notas de **1 a 5**, feitas pela equipe (não são critérios oficiais do hackathon):

| Critério interno | O que avaliar |
|---|---|
| Impacto potencial no acesso | A ideia aumenta a probabilidade real de atendimento e continuidade? |
| Dor e público bem definidos | Há um usuário, uma jornada e um problema verificáveis? |
| Factibilidade de MVP | Dá para desenvolver um fluxo funcional com o tempo e ferramentas disponíveis? |
| Diferenciação | Não é simplesmente um recurso já oferecido pela Capim? |
| Dependências e risco | Depende pouco de dados reais, aprovação regulatória e integrações fechadas? |
| Clareza de demonstração | O valor é compreensível em poucos minutos? |
| Potencial de escala | Poderia ser adaptado a muitas clínicas/pacientes sem operação manual inviável? |

**Não apresentar a matriz como rubrica de jurados.** É apenas uma ferramenta de priorização da equipe.

---

### 9. RISCOS, CUIDADOS E LIMITES

#### 9.1. Saúde e segurança clínica

- O software não deve fazer diagnóstico odontológico definitivo nem substituir avaliação de cirurgião-dentista.
- Classificação de urgência, sequenciamento e adiamento de procedimento dependem de **decisão clínica**.
- Se usar IA para gerar explicações de tratamento, o profissional deve revisar conteúdo clínico antes do uso com pacientes reais.
- Orientações gerais precisam avisar quando é necessário atendimento profissional; situações potencialmente urgentes não devem ser tratadas como mero problema de parcelamento.

#### 9.2. Crédito e transparência

- Não oferecer aprovação garantida, taxa inventada, limite fictício como se fosse real ou cálculo financeiro sem premissas visíveis.
- Expor **custo total**, parcelas e condições apenas quando forem reais ou claramente simulações.
- Não incentivar endividamento incompatível com renda nem discriminar pessoas negativadas.
- Integrações com crédito e pagamentos dependem de autorização e infraestrutura próprias.

#### 9.3. Privacidade e LGPD

- Dados odontológicos são **dados pessoais de saúde**, exigindo salvaguardas reforçadas sob a LGPD.
- Em demonstrações, usar **dados sintéticos/fictícios** como padrão, sem nomes, contatos ou exames reais.
- Coletar o mínimo necessário e definir finalidade, acesso, retenção, proteção e descarte.
- Não usar mensagens ou prontuários reais em prompts de modelos públicos sem base legal, autorização e medidas adequadas.
- Evitar enviar informações clínicas sensíveis em notificações que possam aparecer na tela bloqueada do paciente.

#### 9.4. Ética e experiência

- O material menciona restrições éticas para publicidade de preços odontológicos. **Verificar as regras vigentes com especialistas antes de implementar publicidade, promoções e comparadores comerciais**.
- Não usar escassez artificial, medo ou vergonha para converter tratamentos.
- Se sugerir clínicas, informar critérios objetivos e não inventar avaliações, serviços, preços ou disponibilidade.
- Considerar acessibilidade, baixa alfabetização digital e possibilidade de atendimento humano.

#### 9.5. Integrações, arquitetura e demos

- **Não presumir** que existe API pública/credencial do DASH, da “Camila”, dos sistemas das clínicas ou de crédito da Capim.
- Preferir separação clara entre **interface real**, **dados simulados** e **conectores futuros**.
- Se demonstrar mensagens, agenda ou pagamentos, rotular os eventos fictícios quando apropriado.
- Só afirmar “funciona em produção” quando houver evidência de funcionamento real.

---


---

## ANEXO B — GUIA DE RASTREABILIDADE DAS FONTES

| Informação | Referência exata dos materiais |
|---|---|
| Tema “Saúde para todos” | F1, página 3 |
| Propósito: saúde como direito, inclusão | F1, página 4 |
| 36 horas e 50+ participantes | F1, página 2 |
| Liberdade de abordar saúde além de odontologia | F3, transcrição de orientações, passagens iniciais e intermediárias |
| Palestras, mentoria e horários de sábado | F2, página 1 |
| Entrega/encerramento 15h45, pitches 16h, avaliação 17h45, premiação 18h | F2, página 2; F3 apoia entrega dos protótipos às 15h45 |
| Prêmios 3 mil / 2 mil / 1 mil | F1, página 7; F3 |
| Problemas de pacientes, dentistas, convênio, crédito e jornada | F4, palestra da Capim, passagens distribuídas no arquivo |
| Matriz, ideias, MVP, roadmap, riscos e estrutura do pitch | **Análise e sugestões deste documento**, não exigências oficiais |

**Última atualização deste contexto:** 07/11/2026. Reavaliar caso a organização comunique novos critérios ou instruções.
