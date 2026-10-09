# Stack — Design System

Design system da Stack by PM3 & Alura: logo, cores, tipografia, grid e grafismo de pixels, e tokens. As regras de comunicação (voz, hierarquia da promessa, vocabulário, fórmulas por formato, checklist) ficam resumidas no contexto para IA da última seção. Mesma estrutura do design system da PM3.

## Arquivos

| Arquivo | O que é |
|---|---|
| `Design-System-Stack.html` | Guia web completo, **autossuficiente** (imagens embutidas) e com tela de login. Abra direto no navegador. |
| `Design-System-Stack.pdf` | Versão em PDF do guia web (impressão em página longa, 1280 px de largura). |
| `Design-System-Stack-16x9.pdf` | Apresentação resumida em 10 slides 16:9 (1920 × 1080). |
| `Design-System-Stack-16x9.html` | Fonte dos slides (autossuficiente; exportada a PDF via Chrome headless). |
| `Design-System-Stack.fonte.html` | Fonte editável do guia web (usa a pasta `assets/`). |
| `assets/` | Logos (SVG, nas três cores e nos três arranjos), padrões de pixels (PNG) e key visual de cubos. |

## Fontes do conteúdo

- `../Stack Keyvisual/brandbook-stack.html` (Brandbook v1.1) e os frames do key visual
- stack.com.br e builderscamp.com.br (textos, CTAs, tokens de interface)
- `../Pesquisa Quali/pesquisa-stack-relatorio-completo.md` (91 respostas, jun–set 2026)
- `../Pesquisa Quali/regua-stack-metodologia.html` (Régua Stack v2.0, 7 critérios)

## Observações

- O login pede a senha `pm3-admin-2026` (a mesma do guia PM3). A verificação é por hash SHA-256 no navegador e vale só como barreira leve; a sessão fica salva no navegador (chave `stack_ds_ok`), separada da do guia PM3.
- Para alterar o guia: edite a fonte, regere o HTML autossuficiente (substituir cada `assets/...` por data URI base64) e o PDF (Chrome headless, `--print-to-pdf`).
- O padrão de pixels é gerado por JavaScript (função `genDissolve`) com as regras da seção Grid; o botão "Baixar SVG" exporta a variação exibida.
- Itens marcados com o selo **proposta** (respiro do logo, fotografia, movimento) não estão no brandbook e podem ser revisados.
- Fontes carregadas do Google Fonts: Roboto e Roboto Mono.
