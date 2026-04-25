# Vault.9 Studios — GitHub Pages

Site de apresentação do estúdio para divulgação no Instagram.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub chamado `vault9studios` (ou o nome que preferir)
2. Faça upload do arquivo `index.html` para a raiz do repositório
3. Vá em **Settings → Pages**
4. Em "Source", selecione **Deploy from a branch**
5. Escolha a branch `main` e a pasta `/ (root)`
6. Clique em Save
7. Aguarde ~1 minuto — seu site ficará em: `https://SEU-USUARIO.github.io/vault9studios/`

---

## Como personalizar as fotos

### Cards do Catálogo
Cada card tem um comentário `<!-- Card N -->` no HTML. Para adicionar sua foto:

```html
<!-- Substitua o bloco <div class="card-img card-gradient-X"> por: -->
<div class="card-img">
  <div class="card-img-inner">
    <img src="sua-foto.jpg" alt="Nome da peça" style="width:100%;height:100%;object-fit:cover;" />
  </div>
</div>
```

### Grid do Instagram
Os 5 quadrados cinzas são placeholders. Substitua por `<img>` das suas fotos ou use um widget de feed real.

### Informações de contato
Edite os links de e-mail, WhatsApp etc. diretamente no HTML (seção `#contato`).

---

## Estrutura de arquivos sugerida

```
/
├── index.html          ← página principal
├── fotos/
│   ├── peca-01.jpg
│   ├── peca-02.jpg
│   └── ...
└── README.md
```

---

Feito com ❤️ para o Vault.9 Studios
