# Checklist — o que falta para a entrega

Marque conforme for completando. Cada item indica onde editar no `index.html`.

## 🎥 Vídeo de demonstração (50 pts)
- [ ] Gravar/produzir o vídeo (até 2 minutos)
- [ ] Subir no YouTube como **não listado**
- [ ] No `index.html`, procurar o comentário `QUANDO O VÍDEO ESTIVER PRONTO` (seção `#video`) e substituir o placeholder pelo iframe:
  ```html
  <iframe src="https://www.youtube.com/embed/SEU_ID_AQUI" title="Vídeo RevisIA" allow="autoplay; fullscreen" allowfullscreen></iframe>
  ```

## 🧩 Protótipo Figma (5 pts)
- [ ] Gerar o link de **compartilhamento público** do protótipo no Figma (Share → Anyone with the link → Can view)
- [ ] No `index.html`, procurar `QUANDO TIVER O LINK DE COMPARTILHAMENTO` (seção `#prototipo`) e substituir pelo iframe:
  ```html
  <iframe src="https://www.figma.com/embed?embed_host=share&url=SEU_LINK_AQUI" allowfullscreen></iframe>
  ```
- [ ] Atualizar o botão "Abrir repositório no GitHub →" com o link real do repositório

## 🗺️ Artefatos do Design Sprint (30 pts)
Salvar as imagens em `assets/img/sprint/` e trocar os placeholders (blocos com padrão diagonal) por `<img>`:

- [ ] **Mapa de Usuário → Objetivo** (com objetivo de longo prazo, cenários pessimistas, HMWs e foco do sprint circulado)
  → salvar como `assets/img/sprint/mapa-usuario-objetivo.png`
- [ ] **Esboços das soluções votadas**
  → salvar como `assets/img/sprint/esbocos-votados.png`
- [ ] **Storyboard** (4 quadros) — pode ser 1 imagem só ou 4 separadas
  → salvar como `assets/img/sprint/storyboard-01.png` a `storyboard-04.png`

Exemplo de troca no código (dentro de `.artifact-figure` ou `.story-frame`):
```html
<!-- antes -->
<div class="ph">...</div>

<!-- depois -->
<img src="assets/img/sprint/mapa-usuario-objetivo.png" alt="Mapa de usuário e objetivo do RevisIA">
```

## 👤 Fotos da equipe (5 pts)
Salvar fotos em `assets/img/team/` (recomendado: quadradas, mínimo 300x300px):

- [ ] `assets/img/team/arthur-menegon.jpg`
- [ ] `assets/img/team/arthur-lima-souza.jpg`
- [ ] `assets/img/team/gabriel-kihara.jpg`
- [ ] `assets/img/team/juan-henrique.jpg`

No `index.html`, seção `#equipe`, troque cada `<div class="avatar">...</div>` por:
```html
<div class="avatar">
  <img src="assets/img/team/arthur-menegon.jpg" alt="Foto de Arthur Menegon" style="width:100%;height:100%;border-radius:50%;object-fit:cover;">
</div>
```

## ✅ Antes de entregar
- [ ] Testar todos os links (vídeo, Figma, GitHub) abrindo a página publicada, não só localmente
- [ ] Conferir em um celular real (não só no navegador do PC)
- [ ] Conferir se o GitHub Pages está mesmo no ar (link funcionando para qualquer pessoa, fora da rede da faculdade)
