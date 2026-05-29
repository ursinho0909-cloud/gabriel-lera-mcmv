# Briefing — Cliente Novo

> Preencha as seções abaixo. Quando terminar, me avise e eu monto o site usando o `template.html`.

---

## 1. Dados do profissional

- **Nome completo:**
- **Profissão / título (aparece nos textos):** _ex: Corretor MCMV, Personal Trainer, Advogada Tributarista, Esteticista…_
- **Especialidade / nicho específico:** _ex: Minha Casa Minha Vida, harmonização facial, divórcio amigável…_
- **Registro profissional (se tiver):** _ex: CRECI 310955-F, OAB/SP 999999, CRM 12345_
- **Cidade / região de atuação:**
- **WhatsApp pra receber os leads (com DDI 55 + DDD, só números):** _ex: 5515998460906_

---

## 2. Pasta dos arquivos do cliente

> Aqui você me diz onde estão o vídeo e as fotos do cliente.

- **Pasta com os arquivos:** _padrão: `cliente-novo/assets/` — você pode jogar os arquivos lá dentro. Se preferir outro caminho, me diga aqui_
- **Nome do arquivo do vídeo:** _padrão: `vsl.mp4` (vertical, 9:16, com áudio)_
- **Quantas imagens da galeria:** _entre 4 e 8 funciona melhor_
- **Nomes das imagens:** _padrão: `img1.jpg`, `img2.jpg`, `img3.jpg`… Se vier com outros nomes, me diga aqui_

---

## 3. Paleta de cores

> Cole o código HEX de cada cor. Se não souber, descreva o clima (ex: "tons terrosos com dourado", "azul marinho com prata", "verde-floresta com bege").

- **Cor primária (média) — fundo principal do topo:** `#`
- **Cor primária escura — variação mais fechada:** `#`
- **Cor primária clara — variação mais aberta:** `#`
- **Cor de destaque (accent) — botões, detalhes, brilhos:** `#`
- **Accent claro:** `#`
- **Accent escuro:** `#`
- **Fundo geral (off-white claro):** `#`
- **Fundo alternativo (off-white levemente mais escuro pra seções):** `#`

> **Não sabe gerar tons claro/escuro?** Me passe só a cor principal e a de destaque que eu derivo as variações.

---

## 4. Topo do site (hero)

- **Tag pequena acima do título** _(cidade · especialidade):_ ex: `Itapetininga · Especialista MCMV`
- **Frase principal grande:** _ex: "Pare de pagar aluguel."_
- **Continuação em itálico (cor de destaque):** _ex: "Comece a pagar o que é seu."_
- **Sub-headline (linha menor abaixo):** _ex: "Especialista em MCMV em Itapetininga. Aprovação em até 48h."_

---

## 5. Três cards de diferenciais (stats)

> 3 destaques curtos. Cada um tem um número/palavra grande + uma descrição de 2 a 4 palavras.

- **Card 1 — destaque:** _ex: `MCMV`_ → **descrição:** _ex: `foco exclusivo`_
- **Card 2 — destaque:** _ex: `48h`_ → **descrição:** _ex: `aprovação na Caixa`_
- **Card 3 — destaque:** _ex: `1h`_ → **descrição:** _ex: `resposta no WhatsApp`_

---

## 6. Quiz

- **Selo acima do quiz:** _ex: `SEU IMÓVEL EM 60 SEGUNDOS`_
- **Texto do botão final:** _ex: `Ver imóveis no WhatsApp`_
- **Frase de tranquilização abaixo do botão:** _ex: `Resposta em até 1 hora útil`_

### 6.1 Perguntas

> Liste cada pergunta com as opções de resposta.
> **Não precisa incluir nome + WhatsApp no final — eu já cuido disso.**
> **Use uma chave curta em inglês/sem acento pra cada pergunta** (ex: `objetivo`, `fgts`, `renda`). Essa chave aparece na mensagem do WhatsApp.

#### Pergunta 1
- **Chave:** `objetivo`
- **Texto da pergunta:** O que você está buscando?
- **Opções:**
  1. Comprar minha primeira casa
  2. Trocar de imóvel
  3. Investir em imóvel
  4. Ainda estou pesquisando

#### Pergunta 2
- **Chave:** `fgts`
- **Texto da pergunta:** Você tem FGTS pra usar?
- **Opções:**
  1. Sim, tenho FGTS pra usar
  2. Não tenho ou não sei dizer

#### Pergunta 3
- **Chave:**
- **Texto da pergunta:**
- **Opções:**
  1.
  2.
  3.

> _Continue adicionando até o número de perguntas que quiser. Recomendo entre 4 e 7 perguntas._

### 6.2 Mensagem que vai no WhatsApp

> Como você quer que a mensagem chegue no seu WhatsApp depois que o lead enviar?
> Use `{{nome}}`, `{{whats}}` e o nome de cada chave de pergunta entre `{{ }}` para incluir as respostas.

```
Oi [seu nome]! Acabei de responder o quiz no seu site.

Sou *{{nome}}*
WhatsApp: {{whats}}

Objetivo: {{objetivo}}
FGTS: {{fgts}}
...

Pode me passar mais informações?
```

---

## 7. Galeria de fotos

- **Tag pequena acima do título:** _ex: `REALIZAÇÕES`, `PORTFÓLIO`, `ANTES E DEPOIS`_
- **Título da seção:** _ex: `Imóveis em Itapetininga e região`_

---

## 8. Sobre

- **Tag pequena:** _ex: `SOBRE`, `QUEM ATENDE VOCÊ`_
- **Título da seção:** _ex: `Da primeira conversa à chave na mão.`_
- **Texto (1 parágrafo de 2 a 4 linhas):**
- **Assinatura (registro + cidade):** _ex: `CRECI 310955-F · Itapetininga / SP`_

---

## 9. Rodapé

- **Texto do copyright:** _ex: `© 2026 Todos os direitos reservados.`_

---

## 10. SEO

- **Título da aba do navegador:** _ex: `Pare de pagar aluguel — Gabriel Lera, MCMV Itapetininga`_
- **Descrição (até ~155 caracteres):** _ex: `Especialista em Minha Casa Minha Vida em Itapetininga. Aprovação em até 48h.`_

---

## 11. Deploy

- **Quer criar repositório novo no GitHub?** (sim/não)
- **Nome do repositório:** _ex: `cliente-fulano-site`_
- **Quer criar projeto novo na Vercel?** (sim/não)
- **Domínio personalizado?** _se sim, qual?_

---

✅ **Pronto?** Me dê o "manda ver" que eu:
1. Copio os assets da pasta indicada
2. Preencho o `template.html` com tudo daqui
3. Crio o repositório + projeto Vercel
4. Faço o deploy em produção
