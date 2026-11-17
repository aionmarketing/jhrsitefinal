# PROMPT MESTRE — ANTIGRAVITY IDE (MODO ORQUESTRADOR)
**Projeto:** Novo Site Institucional & SEO Local — J.H.R. Rebobinamentos de Motores Elétricos (`jhrmotores.com.br`)

---

## 🎯 CONTEXTO E OBJETIVO DA MISSÃO
Você está atuando no **Modo Orquestrador** de uma agência digital de alta performance. Sua missão é projetar, redigir, estilizar, otimizar para SEO e codificar do zero o novo site institucional da **JHR Rebobinamentos de Motores Elétricos**, localizada em Piracicaba/SP (atuante desde 2010).

O site antigo era visualmente datado, confuso e cheio de erros. Você deve construir uma aplicação web **moderna, rápida, limpa, mobile-first e focada em conversão B2B**, transmitindo autoridade técnica industrial, confiança e clareza.

**Regra de Ouro:** Reaproveitar **apenas a identidade/logo da JHR** (que será inserida na pasta `/public/images/logo-jhr.png` — crie um componente/placeholder SVG vetorial fiel e elegante caso o arquivo ainda não exista na pasta) e o destaque oficial de **Assistente Autorizado Hercules Motores Elétricos**. Nenhuma imagem ou texto quebrado do site antigo deve ser copiado literalmente.

---

## 🤖 ORQUESTRAÇÃO DE AGENTES (EXECUTE EM FLUXO COORDENADO)

Divida a execução nas seguintes frentes especializadas antes de finalizar o código:

### 1. AGENTE DE ARQUITETURA & ENGENHARIA FRONT-END
* **Stack:** Utilize **Astro (Static Output) + Tailwind CSS** (100% *AI-friendly*, modular, fácil de manter e com nota máxima de performance no Lighthouse).
* **Estrutura de Páginas & Navegação:**
  * `/` (**Home**): Hero Section de alto impacto, Selo Assistência Autorizada Hercules, Resumo dos 4 Pilares de Serviços, Diferenciais Técnicos (Estufa até 500 cv, Insumos WEG/SKF, Relatório de Rastreabilidade), Setores Atendidos, Prova Social (Nota 4,9 no Google), e CTA final.
  * `/sobre` (**A Empresa**): História desde 2010 em Piracicaba, compromisso de diagnóstico técnico honesto, estrutura da oficina e credenciamento Hercules.
  * `/servicos` (**Serviços** — *Arquitetura Modular V1*): Página estruturada com cards limpos e expansíveis/editáveis contendo os serviços base (Rebobinamento AC/DC, Rejuvenescimento Eletromecânico, Manutenção Preditiva/Preventiva/Corretiva e Assistência Autorizada Hercules), preparada para receber novos itens facilmente no futuro.
  * `/contato` (**Contato & Orçamento**): Botão direto para WhatsApp comercial, formulário objetivo de solicitação de orçamento (Nome, Empresa, Telefone/WhatsApp, Potência/Tipo do Motor, Descrição do Problema), endereço completo, horário de atendimento e mapa interativo do Google Maps.
* **Componentes Globais:**
  * `Navbar.astro`: Fixa, responsiva, com logo JHR, links limpos e botão de destaque *"Solicitar Orçamento"* / WhatsApp.
  * `WhatsAppFloat.astro`: Botão flutuante discreto e acessível com mensagem pré-preenchida para orçamento técnico.
  * `Footer.astro`: Dados completos da empresa, CNPJ, endereço corrigido, links rápidos, horário comercial e créditos.

### 2. AGENTE DE UI/UX DESIGN & DIREÇÃO DE ARTE INDUSTRIAL
* **Identidade Visual:** Estética **Engenharia Industrial Moderna** (limpa, precisa, sem poluição visual).
  * **Paleta de Cores:**
    * Primária: Azul Industrial Profundo (`#0F294A` / `#1E3A8A`) — remetendo à tradição técnica e à identidade da JHR/Hercules.
    * Acento / Destaque: Vermelho Técnico / Cobre Energético (`#C81E1E` ou `#D97706`) — usado estrategicamente em CTAs, badges de autorização e detalhes de bobinagem.
    * Neutros: Branco Puro (`#FFFFFF`), Cinza Gelo (`#F8FAFC`) para alternância de seções e Ardósia Escura (`#0F172A`) para tipografia de alta legibilidade.
  * **Tipografia:** Google Fonts (`Plus Jakarta Sans` ou `Barlow` para títulos técnicos fortes + `Inter` para leitura fluida e escaneável).
* **Gestão de Imagens (Geração / Banco de Imagens):**
  * Gere ou integre imagens fotográficas de alta resolução (ou placeholders HD via Unsplash/geração local em `/public/images/`) retratando:
    1. *Hero:* Motor elétrico industrial moderno em ambiente de engenharia limpo e iluminado.
    2. *Rebobinamento:* Close-up artístico e nítido de estator com enrolamento de fios de cobre esmaltado.
    3. *Tecnologia/Testes:* Engenheiro/técnico realizando inspeção com termografia ou instrumentação digital em motor industrial.
    4. *Oficina/Estrutura:* Bancada técnica organizada de manutenção eletromecânica.
  * Todas as imagens devem ter `alt` descritivos para SEO, `loading="lazy"` (exceto a imagem Hero com `fetchpriority="high"`) e proporções fixas (`aspect-ratio`) para zero *Layout Shift (CLS)*.

### 3. AGENTE DE COPYWRITING B2B & REVISÃO GRAMATICAL
* **Tom de Voz:** Técnico, direto, confiável e acessível. Fale diretamente com **Gerentes de Manutenção, Engenheiros, Compradores Industriais e Empresários** que precisam evitar paradas de produção.
* **Proibições Absolutas:**
  * **NUNCA** mencione que a JHR busca ou coleta motores (a empresa não oferece mais serviço de busca/leva-e-traz).
  * **NUNCA** mencione "Atendimento 24 horas" (o horário oficial é comercial: Seg a Sex, 08h às 18h).
  * Elimine 100% dos erros gramaticais antigos.
* **Argumentos de Autoridade Obrigatórios:**
  * **Assistência Técnica Autorizada Hercules Motores Elétricos** (destaque máximo como diferencial competitivo).
  * **Qualidade de Processo:** Uso de papel isolante Classe F, fio de cobre classe térmica 200°C, verniz WEG, secagem em estufa controlada (capacidade para motores de até **500 cv**), montagem com aquecedor indutivo e graxa **SKF**.
  * **Diagnóstico Honesto & Rastreabilidade:** Emissão de Relatório de Manutenção e Rastreabilidade após testes rigorosos (megômetro, vibração, termografia, alinhamento a laser). Filosofia da empresa: *"Analisamos o problema real e entregamos a solução correta, com transparência e o melhor custo-benefício."*

### 4. AGENTE DE SEO TÉCNICO & LOCAL (PIRACICABA E REGIÃO)
* **Palavras-chave Alvo:**
  * Primária: *Rebobinamento de motores elétricos em Piracicaba*
  * Secundárias: *Manutenção de motores elétricos Piracicaba*, *Assistência autorizada Hercules Motores*, *Rejuvenescimento de motores industriais*, *Conserto de motores elétricos AC DC Piracicaba e região*.
* **Implementação Técnica Obrigatória:**
  * Tags `<title>` e `<meta name="description">` únicas e otimizadas em todas as páginas.
  * URLs semânticas limpas (`/sobre`, `/servicos`, `/contato`), `canonical` tags, `robots.txt` e `sitemap.xml` automático (`@astrojs/sitemap`).
  * Injeção de **Dados Estruturados JSON-LD (`LocalBusiness` / `ElectricalContractor`)** no `<head>` contendo os dados oficiais exatos abaixo.

---

## 📋 DADOS OFICIAIS DA EMPRESA (FONTE ÚNICA DA VERDADE)
Use **exclusivamente** estes dados em todo o código, rodapé, contato e Schema JSON-LD:

* **Nome da Empresa:** J.H.R. Rebobinamentos de Motores Elétricos
* **Credenciamento:** Assistente Autorizado Hercules Motores Elétricos
* **CNPJ:** 18.772.157/0001-09
* **Fundação:** 2010
* **Endereço:** Rua Carmem Miranda, 56 – Vila Pacaembu, Piracicaba – SP
* **CEP:** 13424-487 *(Atenção: usar exatamente 13424-487)*
* **Telefone / WhatsApp:** (19) 2532-4135 | Link WhatsApp: `https://wa.me/551925324135?text=Olá!%20Gostaria%20de%20solicitar%20um%20orçamento%20para%20manutenção%20de%20motor%20elétrico.`
* **E-mails:** `jean@jhrmotores.com.br` | `henrique@jhrmotores.com.br`
* **Horário de Atendimento:** Segunda a sexta-feira, das 08h00 às 18h00
* **Avaliação Google:** 4,9 estrelas (baseada em 35+ avaliações de clientes)
* **Domínio:** `https://jhrmotores.com.br`

---

## ✅ CRITÉRIOS DE ACEITAÇÃO DA ENTREGA
Antes de concluir a tarefa, verifique e valide:
1. O projeto compila sem erros (`npm run build`).
2. Todas as páginas (`/`, `/sobre`, `/servicos`, `/contato`) estão completas, responsivas (mobile, tablet, desktop) e visualmente coesas.
3. A página `/servicos` está estruturada de forma limpa e modular para facilitar futuras adições de serviços.
4. O destaque de **Assistência Autorizada Hercules** está visível e valorizado.
5. Não há nenhuma menção a busca/retirada de motores nem a plantão 24h.
6. Todas as imagens carregam corretamente em alta definição (sem links quebrados) e os arquivos de SEO (`sitemap.xml`, `robots.txt`, JSON-LD) estão ativos.