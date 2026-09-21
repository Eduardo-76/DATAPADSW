# DataPad — Inventário Star Wars

Versão PWA do DataPad.

## O que é

O DataPad agora funciona como uma aplicação web instalável:
- abre no Safari/Chrome;
- pode ser adicionada à tela inicial do iPhone;
- funciona offline depois de carregada;
- salva a ficha localmente no dispositivo;
- mantém o inventário, múltiplas grades, itens, stacks, detalhes, exportação e importação.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos estes arquivos para a raiz:
   - index.html
   - manifest.webmanifest
   - sw.js
   - icon-192.png
   - icon-512.png
3. No GitHub, abra Settings → Pages.
4. Em Build and deployment, escolha Deploy from a branch.
5. Escolha a branch principal e a pasta `/ (root)`.
6. Abra o endereço HTTPS gerado pelo GitHub Pages.

## Instalar no iPhone

No Safari:
1. Abra o endereço do DataPad.
2. Toque em Compartilhar.
3. Escolha "Adicionar à Tela de Início".
4. Abra pelo novo ícone.

Depois disso ele abre em modo de aplicativo, sem depender do visualizador de arquivos do iPhone.

## Importante

Cada jogador terá a própria ficha salva no armazenamento local do dispositivo.
Use Exportar para gerar um JSON de backup da ficha.
Use Importar para restaurar uma ficha em outro dispositivo.

## Versão 4
- Células de inventário de 75×75 px no celular.
- Cabeçalhos de equipamentos e grades reorganizados para telas pequenas.
- Seção Mãos redesenhada: qualquer item pode ser equipado sem ocupar uma grade ou possuir limite de tamanho.
- Itens das mãos podem ser adicionados, editados e removidos.
