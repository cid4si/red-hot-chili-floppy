# Red Hot Fav Floppy — 8-bit

> Favicon assets gerados a partir de um desenho original: um [disquete vermelho no estilo 8 bits](./img/favicon.png), criado para meu site pessoal.

---

## Arquivos

### Favicon padrão
| Arquivo | Descrição |
|---|---|
| `favicon.ico` | Ícone principal para navegadores (multi-resolução) |
| `favicon-16x16.png` | Favicon pequeno (aba do navegador) |
| `favicon-32x32.png` | Favicon médio (atalhos, bookmarks) |
| `favicon-96x96.png` | Favicon grande (atalhos de desktop) |

### Apple / iOS
| Arquivo | Tamanho | Uso |
|---|---|---|
| `apple-icon.png` | padrão | Ícone geral Apple |
| `apple-icon-precomposed.png` | padrão | Versão sem efeito de brilho |
| `apple-icon-57x57.png` | 57×57 | iPhone (não-retina) |
| `apple-icon-60x60.png` | 60×60 | iPhone (iOS 7+) |
| `apple-icon-72x72.png` | 72×72 | iPad (não-retina) |
| `apple-icon-76x76.png` | 76×76 | iPad (iOS 7+) |
| `apple-icon-114x114.png` | 114×114 | iPhone Retina |
| `apple-icon-120x120.png` | 120×120 | iPhone Retina (iOS 7+) |
| `apple-icon-144x144.png` | 144×144 | iPad Retina |
| `apple-icon-152x152.png` | 152×152 | iPad Retina (iOS 7+) |
| `apple-icon-180x180.png` | 180×180 | iPhone 6 Plus |

### Android / PWA
| Arquivo | Tamanho | Densidade |
|---|---|---|
| `android-icon-36x36.png` | 36×36 | ldpi (0.75x) |
| `android-icon-48x48.png` | 48×48 | mdpi (1.0x) |
| `android-icon-72x72.png` | 72×72 | hdpi (1.5x) |
| `android-icon-96x96.png` | 96×96 | xhdpi (2.0x) |
| `android-icon-144x144.png` | 144×144 | xxhdpi (3.0x) |
| `android-icon-192x192.png` | 192×192 | xxxhdpi (4.0x) |

### Microsoft / Windows
| Arquivo | Tamanho | Uso |
|---|---|---|
| `ms-icon-70x70.png` | 70×70 | Live Tile pequeno |
| `ms-icon-144x144.png` | 144×144 | Live Tile IE10 |
| `ms-icon-150x150.png` | 150×150 | Live Tile médio |
| `ms-icon-310x310.png` | 310×310 | Live Tile grande |

### Configuração
| Arquivo | Descrição |
|---|---|
| `manifest.json` | Web App Manifest (PWA) — define nome, ícones e densidades para Android |
| `browserconfig.xml` | Configuração de tiles para Microsoft Edge / Windows |


## Tags

Tags para o `<head>` do HTML:

```html
<!-- Favicon padrão -->
<link rel="icon" type="image/x-icon" href="/favicon.ico">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="96x96" href="/favicon-96x96.png">

<!-- Apple -->
<link rel="apple-touch-icon" sizes="57x57" href="/apple-icon-57x57.png">
<link rel="apple-touch-icon" sizes="60x60" href="/apple-icon-60x60.png">
<link rel="apple-touch-icon" sizes="72x72" href="/apple-icon-72x72.png">
<link rel="apple-touch-icon" sizes="76x76" href="/apple-icon-76x76.png">
<link rel="apple-touch-icon" sizes="114x114" href="/apple-icon-114x114.png">
<link rel="apple-touch-icon" sizes="120x120" href="/apple-icon-120x120.png">
<link rel="apple-touch-icon" sizes="144x144" href="/apple-icon-144x144.png">
<link rel="apple-touch-icon" sizes="152x152" href="/apple-icon-152x152.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-icon-180x180.png">

<!-- Android / PWA -->
<link rel="manifest" href="/manifest.json">

<!-- Microsoft -->
<meta name="msapplication-TileColor" content="#ffffff">
<meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
<meta name="msapplication-config" content="/browserconfig.xml">

<!-- Theme color -->
<meta name="theme-color" content="#ffffff">
```

---

<!-- Desenho original criado em: 19 de Novembro de 2022 -->