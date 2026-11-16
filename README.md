# SYON FIT 2.0

PWA de treino funcional de 30 minutos (05h20–05h50), com cronômetro, repetições, orientação por voz em português brasileiro, preferência por voz masculina quando disponível e biblioteca de links de busca de vídeos para todos os movimentos.

## Publicação
Envie os arquivos **extraídos** para a raiz da branch `main` do repositório GitHub Pages. O arquivo `index.html` deve estar na raiz. O service worker `sw.js` usa novo cache v2.

## Dados
Os registros existentes em `localStorage` (`syon_history`, `syon_measures`) são preservados quando o aplicativo é atualizado no mesmo domínio e navegador. Faça exportação preventiva em Ajustes. O aplicativo não sincroniza dados entre aparelhos.

## Voz
A Web Speech API não expõe gênero; o aplicativo tenta priorizar nomes de vozes masculinas `pt-BR` e permite escolha manual. Não há garantia de voz masculina ou neural no iPhone.

## Vídeos
Os links abrem pesquisas do YouTube, não vídeos incorporados e individualmente verificados. A biblioteca precisa de conexão à internet.
