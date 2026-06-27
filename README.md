# RevisIA

Landing page do projeto **RevisIA** — aplicativo de flashcards com IA integrada, desenvolvido para a disciplina de Interação Humano-Computador (UTFPR, Campo Mourão, 2026).

🔗 **Página publicada:** `https://SEU-USUARIO.github.io/NOME-DO-REPO/`
*(atualize este link depois de ativar o GitHub Pages — veja instruções abaixo)*

## Equipe

- Arthur Menegon
- Arthur de Lima Souza
- Gabriel Rolim de Almeida Kihara
- Juan Henrique do Carmo

## Estrutura do repositório

```
.
├── index.html              → página única (HTML + CSS + JS embutidos)
├── assets/
│   └── img/
│       ├── sprint/         → mapa de usuário, esboços e storyboard
│       ├── prototype/      → capturas de tela do protótipo (se precisar)
│       └── team/           → fotos dos integrantes
├── CHECKLIST.md            → o que falta preencher antes da entrega
└── README.md
```

## Como publicar no GitHub Pages

1. Suba este repositório no GitHub (veja seção abaixo se ainda não fez isso).
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
4. Clique em **Save**. Em 1–2 minutos o link aparece no topo da mesma página.
5. Atualize o link no início deste README.

## Como subir este projeto pela primeira vez

Se você baixou estes arquivos e ainda não tem o repositório no GitHub:

```bash
cd revisia-landing
git init
git add .
git commit -m "Landing page inicial do RevisIA"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPO.git
git push -u origin main
```

## Como atualizar depois de editar

```bash
git add .
git commit -m "descreva o que mudou"
git push
```

O GitHub Pages atualiza automaticamente em 1–2 minutos após o push.

## Editando o conteúdo

Tudo está em `index.html`. Os pontos que ainda precisam ser preenchidos estão marcados com comentários `<!-- ... -->` no código e listados em [`CHECKLIST.md`](./CHECKLIST.md).
