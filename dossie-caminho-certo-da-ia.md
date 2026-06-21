# Dossiê — "O Caminho Certo da IA"

Base de evidência verificada para o conteúdo INEMA. Duas rodadas de pesquisa profunda
(fan-out + verificação adversarial 3 votos) + verificação manual dos números de manchete.
Data de compilação: 2026-06-20.

**Como ler:** ✅ = confirmado com voto/fonte. ⚠️ = caveat obrigatório ao citar.
🔶 = reportado/amplamente citado mas NÃO confirmado contra fonte primária (usar com ressalva).

---

## TESE CENTRAL

O "caminho certo" não é o que o hype vende. Há um abismo entre promessa e realidade — e a
causa raiz das falhas **não é o modelo nem a regulação, é a falta de qualificação** para
avaliar, integrar e medir IA. Ao mesmo tempo o empoderamento é real e medido, mas **desigual:
depende da pessoa e da tarefa**. Quem domina o próprio domínio entende os limites da IA melhor
que o entusiasta que prevê sua obsolescência.

Dois eixos da qualificação:
1. **Alavancar com IA** (usar a ferramenta de verdade: contexto, iteração, automação, harness).
2. **Ser insubstituível** (as habilidades humanas que a IA não substitui).
Ancorados numa **camada de evidência** — afirmação com fonte, o oposto do guru raso.

---

## PARTE 1 — A PAISAGEM DO RUÍDO (as falhas)

✅ **Gartner — +40% dos projetos de IA agêntica serão CANCELADOS até o fim de 2027.** Por custo
crescente, valor de negócio incerto e controle de risco inadequado.
⚠️ É *previsão/forecast*, não resultado observado.
Fonte: Gartner press release 25/06/2025 (analista Anushree Verma; pesquisa jan/2025, 3.412 resp.).
https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027

✅ **"Agent washing" — só ~130 de milhares de fornecedores de IA agêntica são genuínos** (Gartner).
Rebatizam chatbot/RPA velho de "agente"; maioria das propostas agênticas carece de ROI.
⚠️ Metodologia do "130" não é transparente. Mesma fonte Gartner.

✅ **MIT NANDA "The GenAI Divide" — 95% das organizações sem retorno mensurável** apesar de
US$30–40 bi investidos; só 5% dos pilotos integrados extraem milhões. Funil corporativo:
60% avaliam → 20% pilotam → 5% chegam à produção.
⚠️ **CAVEAT FORTE:** working paper NÃO revisado por pares; amostra modesta (52 entrevistas,
153 respostas); conflito de interesse (projeto vende infra agêntica). A mídia DISTORCEU:
o correto é "95% das *orgs* sem impacto em P&L", **não** "95% dos pilotos falham".
Fonte: mlq.ai / MIT NANDA, ~ago/2025.

✅ **A "lacuna de aprendizado" é a causa raiz** — a ferramenta esquece contexto, não aprende,
não evolui. Para trabalho crítico, **90% preferem humanos**. Reclamações: "não aprende com meu
feedback" (65%), "exijo contexto manual toda vez" (60%). Gargalo = memória/adaptação, não
talento/infra/regulação. Fonte: MIT NANDA.

✅ **Por que falha na avaliação** — confiar na métrica do material de venda do fornecedor em vez
de interrogar a "ground truth". Pergunta nº1 ao avaliar IA: *"o gabarito é mesmo verdadeiro?"*
⚠️ Voto 2-1 (generalização de um estudo de caso, mas mecanismo corroborado por NANDA/RAND).
Fonte: MIT Sloan Management Review.
https://sloanreview.mit.edu/article/the-no-1-question-to-ask-when-evaluating-ai-tools/

---

## PARTE 2 — SEPARAR SINAL DE RUÍDO (anti-grift)

✅ **"AI Snake Oil" (Narayanan & Kapoor, Princeton)** — IA que não funciona como anunciada e
provavelmente não pode funcionar. Ex. de grift: ferramenta que diz prever desempenho no emprego
por vídeo de 30s, sem evidência científica (caso HireVue).
✅ Framework-chave: **"IA" são duas tecnologias** — a *generativa* (ChatGPT) avançou muito; a
*preditiva* é "planilha Excel glorificada". Confundir as duas gera a confusão pública.
Fonte: Princeton Research, 18/12/2024.
https://research.princeton.edu/news/ai-snake-oil-conversation-princeton-ai-experts-arvind-narayanan-and-sayash-kapoor

✅ **Julgamento de domínio > hype de obsolescência** — previsões de "a IA vai substituir o
emprego X" vêm de entendimento raso do trabalho. Ex. real: Hinton previu em 2016 radiologistas
obsoletos; uma década depois há escassez e salários altos. Ceticismo com previsões de
Gates/Altman (subestimam conhecimento tácito/contextual). Fonte: CITP/Princeton (Narayanan &
Melanie Mitchell), 02/04/2025.
https://blog.citp.princeton.edu/2025/04/02/a-guide-to-cutting-through-ai-hype-arvind-narayanan-and-melanie-mitchell-discuss-artificial-and-human-intelligence/

---

## PARTE 3 — O EMPODERAMENTO REAL (medido, peer-reviewed)

✅ **Suporte ao cliente: +14% na média, +34% para novatos**, ~zero para experientes. Mecanismo:
a IA dissemina a melhor prática dos top performers e acelera o iniciante na curva.
Fonte forte: Brynjolfsson, Li & Raymond — NBER w31161, publicado no *Quarterly Journal of
Economics 2025*, 3M+ chats reais. **Sem refutação.**
https://www.nber.org/papers/w31161

✅ **Devs com Copilot: 55,8% mais rápidos** numa tarefa única de servidor HTTP; **+12,9% a
+21,8% mais pull requests/semana** (Microsoft), +7,5–8,7% (Accenture).
⚠️ O "55,8%" é tarefa artificial com conflito de interesse (Microsoft/GitHub); estudo
*independente* (BlueOptima, ~218 mil devs) achou só **~4%** real. Números de campo são
"preliminares/sugestivos". Fontes: arXiv:2302.06590; MIT GenAI/Cui et al.

✅ **A ilusão de produtividade (achado mais importante)** — RCT METR: 16 devs *experientes*
usando IA nos próprios repos ficaram **19% MAIS LENTOS**. Esperavam +24%; mesmo depois de medido,
ainda achavam que aceleraram +20%.
⚠️ Específico de expert em código maduro/familiar; reafirmado em 24/02/2026.
Fonte: METR, 10/07/2025.
https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/

> **A reconciliação (o coração da tese):** a IA ajuda novato + tarefa simples e pode atrapalhar
> expert + código complexo. O ganho não vem da ferramenta — vem da **qualificação** de quem usa.

---

## PARTE 4 — REFORMA EDUCACIONAL (o mundo se ajustando)

✅ **China — "AI + Education Action Plan" (abril/2026)** emitido por 5 órgãos centrais liderados
pelo Ministério da Educação (MOE). Meta até 2030: sistema nacional de alfabetização em IA
cobrindo **todos os níveis de ensino e a sociedade inteira**.
Fonte primária: gov.cn, 15/04/2026.
https://english.www.gov.cn/news/202604/15/content_WS69df29e6c6d00ca5f9a0a6b1.html

✅ **China — ensino superior:** IA vira disciplina pública básica, livros-texto por área,
programas interdisciplinares, novos cursos alinhados ao upgrade industrial. **+38 cursos de
graduação em IA/energia** adicionados em abril/2026. Mesma fonte gov.cn + Global Times.

🔶 **China — 12.200 cursos de graduação revogados/suspensos entre 2021–2025 (~30% dos programas
afetados), em favor de áreas tech; ~10.200 programas de IA/robótica adicionados.**
⚠️ Fontes secundárias (mas múltiplas e convergentes): SCMP (Carol Yang, 14/06/2026) e Tech
Startups (15/06/2026). O número exato "12 mil" não foi confirmado contra documento primário do MOE.
https://www.scmp.com/economy/china-economy/article/3356913/chinas-universities-cut-12000-obsolete-degrees-amid-race-embrace-ai-era

✅ **China — sistema escalonado de educação em IA (maio/2025)** do fundamental ao médio, com
objetivos por faixa etária + "Guia de Uso de IA Generativa em Escolas (Edição 2025)".
Fontes: SCIO/Xinhua 13/05/2025; CSET/Georgetown.

✅ **UE — AI Act, Artigo 4:** alfabetização em IA é **obrigação legal vinculante** para
provedores E implantadores, em aplicação desde **02/02/2025**, fiscalização a partir de ago/2026.
⚠️ **CAVEAT TEMPORAL:** o "Digital Omnibus" (acordo político provisório mai/2026) propõe
SUAVIZAR o Art. 4 — mas só vale após adoção formal + publicação no Jornal Oficial, o que NÃO
ocorreu até jun/2026. Permanece vinculante hoje, pode mudar em semanas.
https://artificialintelligenceact.eu/article/4/

🔶 **EUA — Executive Order 14277 "Advancing AI Education for American Youth"** (Trump, 23/04/2025),
cria White House Task Force on AI Education. ⚠️ NÃO confirmada nesta rodada (votos abstidos por
rate-limit); existe no Federal Register mas não verificada pelo nosso processo.

---

## PARTE 5 — HABILIDADES QUE IMPORTAM (WEF Future of Jobs 2025)

✅ **Mercado de trabalho até 2030:** 170M novos empregos criados, 92M deslocados, **saldo
líquido +78M**; **22% dos empregos atuais** sofrem disrupção; **~39% (dois quintos) das
habilidades mudam** até 2030; **63% dos empregadores** citam a lacuna de skills como maior
barreira; 85% planejam priorizar upskilling.
Fonte: WEF Future of Jobs Report 2025 (jan/2025), via People Matters e Coursera citando o
relatório (acesso direto deu 403; números convergentes em 2 fontes).
https://www.weforum.org/publications/the-future-of-jobs-report-2025/

✅ **Top 10 habilidades centrais 2025 (WEF) — % de empresas que consideram essencial:**
1. Pensamento analítico — 69% (7 de 10 empresas)
2. Resiliência, flexibilidade e agilidade — 67%
3. Liderança e influência social — 61%
4. Pensamento criativo — 57%
5. Motivação e autoconsciência — 52%
6. Alfabetização tecnológica — 51%
7. Empatia e escuta ativa — 50%
8. Curiosidade e aprendizado ao longo da vida — 50%
9. Gestão de talentos — 47%
10. Orientação a serviço / atendimento — 47%
Fonte: WEF "Skills outlook", cap. 3 do Future of Jobs 2025.

> Habilidades de MAIOR CRESCIMENTO 2025–2030 (IA & big data #1, redes/cibersegurança, etc.):
> mencionadas pelas fontes mas não travadas voto-a-voto — usar como "reportado".

---

## CRUZAMENTO — As 12 habilidades do PDF ↔ evidência WEF/Princeton/MIT

| PDF "12 habilidades humanas" | Ancoragem verificada |
|---|---|
| 2. Pensamento crítico / 6. Data literacy / 12. Coragem ética | AI Snake Oil (Princeton); "ground truth" (MIT Sloan); o anti-grift |
| 11. Aprender a aprender | Lacuna de aprendizado (MIT NANDA); +34% novatos (Brynjolfsson); WEF #8 curiosidade/lifelong learning |
| 8. Definir o que fazer (priorização) | Ilusão METR (executar ficou barato; decidir e medir vale mais) |
| 9. Lidar com incerteza | WEF #2 resiliência/flexibilidade/agilidade (67%) |
| 1. Empatia / 10. Conexão humana | WEF #7 empatia e escuta ativa (50%); #3 liderança e influência social (61%) |
| 2. Pensamento crítico | WEF #1 pensamento analítico (69%) |
| 3. Criatividade | WEF #4 pensamento criativo (57%) |
| 7. Vontade e propósito | WEF #5 motivação e autoconsciência (52%) |
| 4. Nexialismo / 5. Repertório | Conhecimento tácito/contextual e julgamento de domínio (Princeton/Mitchell) |

**Conclusão:** as 12 habilidades do PDF batem quase 1-para-1 com o ranking verificado do WEF —
o material deixa de ser opinião e passa a ter lastro institucional.

---

## OS 2 EIXOS DO MODELO INEMA

**Eixo 1 · Alavancar com IA** (do material de 7 pontos do usuário):
1. IA não é só pra técnico — toda área usa.
2. Virar a "pessoa de IA" do time.
3. Usar IA com julgamento humano (revisar, adaptar, assumir o resultado).
4. Engenharia de contexto (ensinar a IA com dados reais do seu trabalho).
5. Trabalhar por iteração (prototipar, testar, corrigir).
6. Automatizar tarefas previsíveis (e saber quando automação simples basta).
7. Criar segurança profissional/financeira (nova renda em torno de um interesse).

**Eixo 2 · Ser insubstituível** (as 12 habilidades humanas do PDF):
empatia · pensamento crítico · criatividade · nexialismo · repertório · data literacy ·
vontade e propósito · definir o que fazer · lidar com incerteza · conexão humana ·
aprender a aprender · coragem ética.

**Plano de 4 semanas** (do PDF): autoconhecimento → pensamento+repertório →
dados+decisão+incerteza → relações+propósito+ética.
