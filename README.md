# JSExpertHub Pre-processing videos on browsers - Semana JS Expert 8.0

## Pre-reqs

- Este projeto foi criado usando Node.js v18.17.0

## Running
- Execute `npm ci` na pasta que contém o arquivo `package.json` para restaurar os pacotes
- Execute `npm start` e em seguida vá para o seu navegador em [http://localhost:3000](http://localhost:3000) para visualizar a página acima

## Checklist Features

- Video Uploader
  - [x] - Deve entender videos em formato MP4 mesmo se não estiverem fragmentados
  - [x] - Deve processar itens em threads isoladas com Web Workers
  - [x] - Deve converter fragmentos de videos em formato `144p`
  - [x] - Deve renderizar frames em tempo real em elemento canvas
  - [x] - Deve gerar arquivos WebM a partir de fragmentos

### Desafios
- [ ] - Encodar em 360p e 720p
- [ ] - Fazer encoding/decoding track de áudio
- [ ] - Fazer também upload de track de áudio
- [ ] - Concatenar o arquivo final no servidor em um arquivo só
- [ ] - Corrigir problema do Webm de não mostrar a duração do video
- [ ] - Corrigir a responsividade do site
- [ ] - Tentar usar outros muxers
  - https://github.com/Vanilagy/webm-muxer
  - https://github.com/Vanilagy/mp4-muxer
