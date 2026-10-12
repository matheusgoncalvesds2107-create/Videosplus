# Vídeos Plus PWA

PWA de vídeos curtos, com feed vertical, pesquisa, upload, curtidas, comentários, compartilhamento, perfil, seguidores e notificações internas.

## Rodar

Hospede a pasta em HTTPS (GitHub Pages, Netlify ou Render Static Site). Para teste local, execute `python -m http.server 8080` e abra http://localhost:8080.

## Limitações

Esta versão salva dados e vídeos localmente no navegador usando IndexedDB. Não sincroniza entre aparelhos nem oferece contas públicas reais. Notificações são internas e locais. A gravação depende da permissão de câmera/microfone e de suporte do navegador. Para rede social pública, é necessário backend com autenticação, armazenamento de vídeos e moderação.
