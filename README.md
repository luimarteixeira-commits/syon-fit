# SYON FIT 3.0

Aplicativo web instalável de treino funcional. Inclui cronômetro, voz técnica em português, biblioteca de referências no YouTube, cadastro de exercícios, criação de circuitos e reprodutor incorporado do Spotify por link compartilhável.

## Publicação

Envie `index.html`, `manifest.webmanifest`, `sw.js` e `README.md` para a raiz da branch `main` no GitHub Pages. Não envie o ZIP sem extrair.

## Spotify

Em Ajustes, cole um link `https://open.spotify.com/playlist/...` (ou álbum/faixa) e toque em **Salvar player**. O app incorpora o player oficial do Spotify, sujeito a login, disponibilidade e limitações do Spotify e do Safari. Não implementa autenticação OAuth, Spotify Web Playback SDK nem controle remoto da conta. A música pode pausar ao bloquear a tela ou ao trocar de app.

## Dados

Histórico e medidas continuam usando as chaves locais `syon_history` e `syon_measures`. Novos treinos usam `syon_plans` e `syon_customExercises`. Faça backup em Ajustes antes de atualizar ou limpar os dados do Safari.
