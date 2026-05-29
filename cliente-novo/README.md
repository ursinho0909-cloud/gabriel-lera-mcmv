# Cliente novo — passo a passo

Quando você for fazer um site novo, é assim:

## 1. Cole os arquivos do cliente em `assets/`
Dentro desta pasta (`cliente-novo/assets/`), coloque:
- **`vsl.mp4`** — o vídeo vertical (9:16) com áudio
- **`img1.jpg`, `img2.jpg`, …** — as fotos da galeria

> Pode usar outros nomes — só me avise no briefing.

## 2. Preencha o `briefing.md`
Abra o arquivo `briefing.md` aqui na pasta e preencha cada seção.
Não precisa ser longo — frases curtas funcionam.

## 3. Me chama
Aqui no chat, é só dizer algo como:
> "Cria o site do cliente novo"

Eu vou:
1. Ler o `briefing.md`
2. Pegar os arquivos de `cliente-novo/assets/`
3. Usar `template.html` como base
4. Gerar o site final
5. (Se você quiser) criar repositório novo no GitHub e fazer deploy na Vercel

---

## Estrutura de arquivos esperada

```
gabriel lera/
├── template.html             ← esqueleto (não editar)
├── index.html                ← site do Gabriel (já no ar)
├── cliente-novo/
│   ├── briefing.md           ← você preenche
│   ├── README.md             ← este arquivo
│   └── assets/
│       ├── vsl.mp4
│       ├── img1.jpg
│       ├── img2.jpg
│       └── ...
└── ...
```
