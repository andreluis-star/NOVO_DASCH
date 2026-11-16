# NOVO DASCH — Painel da Expedição PortoEx (TV)

- `tv-v2.html` — exibição na TV (abre direto pelo `index.html`)
- `config-v2.html` — cadastro rápido das operações do dia e configurações (letreiro, telas, segurança)
- Prévia com dados fictícios: `tv-v2.html?demo=1` (uma tela só: `?demo=1&tela=ops|resumo|equipe|conf|pal`)

Fontes: Programação (planilha diária), Conferência Geral (Firestore `operacoes`), ABSENTEISMO e CONTROLE-MAO-DE-OBRA (Realtime Database).
Configuração gravada em `dasch_config/painel` (campos `v2` e `opsV2`).
