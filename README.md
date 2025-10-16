Mukheru — Organização técnica e operacional

Visão geral

Mukheru é uma plataforma digital da Carmelo Microcrédito concebida para apoiar exclusivamente mulheres empreendedoras (18–45 anos) em contextos urbanos e rurais de Moçambique. A solução combina microcrédito, mentoria contínua e formação em literacia financeira, acessível por app Android e via USSD para telemóveis básicos. O objetivo é promover autonomia económica, inclusão digital e geração de rendimento através de crédito responsável + capacitação prática.

Funcionalidade

• Cadastro e perfil: inscrição simplificada (app / USSD), criação de perfil, validação básica de elegibilidade.
• Solicitação e gestão de microcrédito: pedido de empréstimo, avaliação automatizada simplificada, aprovação, plano de reembolso e histórico de pagamentos.
• Módulos de formação: trilhas de aprendizagem curtas (gestão financeira, marketing, vendas) acessíveis em app e em formatos resumidos via USSD/SMS.
• Mentoria e acompanhamento: atribuição de mentor, agenda de visitas/contatos mensais, registo de sessões e relatórios de progresso.
• Conteúdos e storytelling: acesso a conteúdos multimédia (vídeos curtos, áudios, infográficos) e destaque de histórias de sucesso.
• Notificações e comunicação: alertas por SMS/USSD/app para prazos de pagamento, convites para sessões e avisos administrativos.
• Coleta e análise de dados: métricas de adesão, conclusão de formação, uso de crédito e indicadores de impacto para personalização e avaliação.
• Segurança: autenticação de utilizadora, encriptação de dados sensíveis e backups periódicos.

Pré-requisitos

Técnicos

• Servidor/Cloud com base de dados (MySQL/Postgres) e API segura (HTTPS/SSL).
• Plataforma backend para gestão de crédito, workflows e dashboards administrativos.
• Aplicativo Android compatível com versões móveis amplamente usadas localmente.
• Gateway USSD integrado com operadora(s) móvel(is) local(is).
• Integração com provedores de pagamento / mobile money (ex.: integração com Moçambique M-Pesa / outros conforme parceiros).
• Serviço de SMS/Notificações push e serviço de armazenamento de média (vídeo/foto).
• Controlo de acesso, encriptação e políticas de privacidade/dados conforme legislação local.

Operacionais / Humanos

• Parcerias com operadoras móveis para USSD e códigos curtos.
• Equipa técnica (desenvolvedor backend, frontend/app, engenheiro devops).
• Equipa de conteúdos e formação (design pedagógico, produção de vídeo/áudio).
• Rede de mentores e formadores (locais e voluntários).
• Processos de KYC simplificados e critérios de elegibilidade.
• Orçamento para kits/equipamentos e fundos rotativos para microcrédito piloto.
• Plano de monitoria e avaliação (M&E) e ferramentas de recolha de dados.

Acessibilidade / Inclusão

• Conteúdos em linguagem simples; legendas / áudio; versões resumidas para USSD; possibilidade de leitura por voz.
• Procedimentos para apoiar utilizadoras com baixa literacia digital.

Instalação (passo a passo — técnico + piloto)

Fase 0 — Planeamento (2–4 semanas)
	1.	Confirmar parceiros (operadora USSD, gateway móvel, entidades financeiras).
	2.	Definir requisitos funcionais detalhados e KPIs do piloto.
	3.	Preparar equipa técnica e equipa de formação/mentoria.

Fase 1 — Infraestrutura & Desenvolvimento (6–10 semanas)
	1.	Provisionar servidores / cloud e configurar base de dados.
	2.	Desenvolver backend (APIs), painel administrativo e integração com gateways (USSD, SMS, mobile money).
	3.	Desenvolver app Android com UX simples; criar fluxos USSD (menus essenciais).
	4.	Implementar segurança (SSL, encriptação, autenticação).
	5.	Criar dashboards de monitoria e relatórios automáticos.

Fase 2 — Conteúdos & Preparação operacional (3–4 semanas, paralelo)
	1.	Produzir módulos formativos (vídeos curtos, guias, infográficos) e adaptar para USSD/SMS.
	2.	Treinar mentores e equipa de suporte.
	3.	Preparar kits/equipamentos para os beneficiários e políticas de distribuição.

Fase 3 — Testes & Validação interna (2 semanas)
	1.	Sessões de validação com equipa técnica e parceiros (UX, fluxos de crédito, USSD).
	2.	Ajustes baseados em feedback.
	3.	Garantir permissões/shortcodes com operadora.

Fase 4 — Piloto em Maputo (3 meses recomendado)
	1.	Recrutar 50–100 mulheres para piloto.
	2.	Onboarding (inscrição via USSD/app), entrega de kits piloto onde aplicável.
	3.	Monitoria contínua: recolha de dados quantitativos (adesão, uso, reembolsos) e qualitativos (entrevistas).
	4.	Ajustes iterativos na plataforma e conteúdos.

Fase 5 — Avaliação & Escala (4–6 semanas pós-piloto)
	1.	Análise dos resultados do piloto, relatório M&E e recomendações.
	2.	Corrigir problemas críticos e otimizar UX/USSD/fluxos de crédito.
	3.	Planejar expansão regional (Nampula, Manica, etc.) com base em lições aprendidas.