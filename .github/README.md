# Site do Bruno Daner Sax

Site do Bruno Daner, DJ e saxofonista ao vivo no mesmo artista, do Rio de Janeiro, para casamentos e eventos no Brasil e no exterior.
**No ar:** https://brunodanersax.com

| Computador | Celular |
|---|---|
| ![Abertura do site no computador](prints/computador.jpg) | ![Abertura do site no celular](prints/celular.jpg) |

## O que o site faz

- **Três idiomas** (português, inglês e espanhol), com troca na própria página e sem recarregar.
- **Vídeos de eventos reais**, formatos de apresentação, história do artista, parcerias, depoimentos e repertório.
- **Consultar data** direto no WhatsApp, com a mensagem já escrita.
- **Propostas por cliente:** cada cliente recebe um link próprio com as opções, os extras e o total.
- **Painel com senha** para o Bruno montar e acompanhar as propostas.
- **Pensado para o Google:** título e descrição, dados estruturados (schema.org), sitemap e domínio próprio.

## Como foi feito

- O site antigo era na Wix. Foi refeito do zero e migrado para o GitHub Pages **sem trocar o domínio**: o DNS foi apontado no próprio painel da Wix, onde o domínio continua registrado.
- HTML, CSS e JavaScript puro, sem framework. A tradução é feita na página: cada texto tem uma chave e o idioma escolhido fica salvo no navegador.
- As propostas e o painel conversam com uma API em Cloudflare Worker + banco D1 (código fora deste repositório). A versão genérica do mesmo sistema é pública em [JoaoVitorRk/painel-propostas](https://github.com/JoaoVitorRk/painel-propostas).
- Construído com apoio do Claude Code: eu defino o que o site precisa fazer, testo no computador e no celular e reviso o resultado.

Feito pela [RK Performance](https://rkperformance.com.br) · [João Vitor Raifur Kos](https://www.linkedin.com/in/joao-vitor-raifur-kos).
Fotos, vídeos, textos e marca pertencem ao Bruno Daner.
