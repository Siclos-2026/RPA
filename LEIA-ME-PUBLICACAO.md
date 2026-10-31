# Publicação do Emissor RPA como PWA

## Teste local
Não abra o `index.html` diretamente. Na pasta do projeto, use um servidor HTTP, por exemplo:

```bash
python3 -m http.server 8080
```

Abra `http://localhost:8080`.

## GitHub Pages
1. Crie um repositório no GitHub.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. Em **Settings > Pages**, escolha **Deploy from a branch**.
4. Selecione a branch `main`, pasta `/ (root)`, e salve.
5. Abra o endereço exibido em Pages pelo Android/Chrome e toque em **Instalar app** ou **Adicionar à tela inicial**.

## Atualizações
Troque `rpa-valmera-v1` no arquivo `sw.js` para `v2`, `v3` etc. sempre que publicar uma nova versão. Isso força a renovação do cache.

## Privacidade e dados
O aplicativo grava os cadastros no armazenamento local do navegador/aplicativo. Faça backups pelo painel. Limpar os dados do navegador ou desinstalar o APK pode apagar dados locais.
