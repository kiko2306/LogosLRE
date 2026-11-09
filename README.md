# Livro de Reclamações logos

Official Livro de Reclamações Eletrónico (LRE) logos for client websites.
Under Decreto-Lei n.º 156/2005 (as amended by Decreto-Lei n.º 74/2017), businesses with a website must show the electronic complaints book in a visible, prominent place, so every site gets one of these in the footer.

## Files

All logos are 140×58 PNG with transparency.

| File | Use on |
|---|---|
| `logo_LRE_azul negativo.png` | Dark backgrounds (default choice) |
| `logo_LRE_azul positivo.png` | Light backgrounds |
| `logo_LRE_preto negativo.png` | Dark backgrounds, monochrome designs |
| `logo_LRE_preto positivo.png` | Light backgrounds, monochrome designs |
| `logo_LRE_vermelho negativo.png` | Dark backgrounds, red palettes |
| `logo_LRE_vermelho positivo.png` | Light backgrounds, red palettes |

**Negativo** = for dark backgrounds. **Positivo** = for light backgrounds.

## How to use

1. Copy the logo into the site's own assets (rename without spaces, e.g. `img/logo-lre.png`). Don't hotlink this repo.
2. Put it in the footer of every page, linked to the official portal:

```html
<a href="https://www.livroreclamacoes.pt/inicio" target="_blank" rel="noopener noreferrer">
  <img src="/img/logo-lre.png" alt="Livro de Reclamações" width="140" height="58" loading="lazy">
</a>
```

3. Keep it legible: don't stretch, recolour or put it inside a semi-transparent container.
4. On English pages keep the logo as is; alt text can be `Complaints Book (Livro de Reclamações)`.
5. Next to it, link the competent dispute-resolution entity (RAL), e.g. [CICAP](https://cicap.pt) for Porto.
