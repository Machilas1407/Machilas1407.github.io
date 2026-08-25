# Portfólio — Marcello Queiróz

Site pessoal feito em HTML/CSS/JS puro, sem framework e sem build. Um único arquivo (`portfolio.html`), pensado pra ser simples de manter e rápido de carregar.

## O que tem aqui

- Sobre / formação
- Experiência profissional
- Projetos (com links pra quem tá em produção)
- Skills técnicas
- Contato

A ideia visual é meio "trajeto de rota" — a linha lateral com os pontos (waypoints) que vão acendendo conforme rola a página. Fez sentido dado que boa parte da minha experiência é com sistemas de transporte e geolocalização.

## Como rodar

Não precisa de nada além de um navegador. Só abrir o `portfolio.html` direto, ou subir num servidor estático qualquer:

```bash
python3 -m http.server 8000
```

e acessar `localhost:8000/portfolio.html`.

## Stack

- HTML5 + CSS (variáveis CSS pra tema, sem preprocessador)
- JS vanilla (scroll spy da navegação, menu mobile, botão de voltar ao topo)
- Fontes: Space Grotesk, Inter e JetBrains Mono via Google Fonts

## Estrutura

Tudo num arquivo só de propósito — é um portfólio, não uma aplicação. Se crescer muito ou eu quiser reaproveitar em outro projeto, aí sim separo CSS/JS.

## Pendências / próximos passos

- [ ] Trocar `og-image.png` e URL do canonical quando o domínio for definido
- [ ] Botão de download do CV em PDF
- [ ] Versão em inglês
- [ ] Testar em leitor de tela de verdade (fiz os ajustes de acessibilidade "no olho", falta validar)

## Licença

Conteúdo e código são meus. Sinta-se livre pra olhar o código e se inspirar, mas não copie o conteúdo (textos, projetos, etc.) como se fosse seu.
