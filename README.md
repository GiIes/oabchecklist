# OAB 2027 — Painel de Estudos

Site estático em HTML, CSS e JavaScript, pronto para publicar no GitHub Pages.

## O que inclui
- 69 assuntos em 11 matérias, extraídos da planilha enviada, sem adicionar subtemas.
- Checklists de Conceito, Lei seca e Questões por assunto.
- Revisões automáticas D+7 e D+30 após marcar os três blocos como concluídos.
- Cronograma com as fases, datas e observações da planilha.
- Painel de progresso, busca, filtros e calendário semanal.
- Exportação e importação de backup em JSON.
- Armazenamento local no navegador, sem conta ou login.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie `index.html`, `data.js` e, opcionalmente, `README.md` (o `data.json` também pode ser mantido como fonte de dados).
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)` e salve.
6. Aguarde a publicação e abra a URL indicada na seção Pages.

## Persistência e backup
Os checklists ficam no `localStorage` do navegador/dispositivo atual. Não são sincronizados entre dispositivos e podem ser perdidos ao limpar os dados do navegador. Use **Exportar backup** periodicamente e **Importar backup** para restaurar.

## Observações
- A data de prova está configurada para 10/01/2027, conforme a planilha enviada; confirme a data oficial no edital da FGV.
- O cronograma é o que veio no Excel. As revisões D+7/D+30 são calculadas com base na data real em que os três blocos do assunto forem concluídos.
- O site não envia notificações push ou lembretes quando está fechado.
