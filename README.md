# LP GMX Digital

Landing page de geração de leads da **GMX Digital** — agência de branding, design e presença digital, em atividade desde 2003.

Arquivo único e autocontido: fontes, logos, imagens e scripts estão embutidos no HTML. Não há dependências externas, build ou instalação — funciona offline.

## Publicar com GitHub Pages

1. Suba os arquivos na raiz do repositório.
2. Em **Settings → Pages**, selecione a branch (`main`) e a pasta `/ (root)`.
3. A página fica disponível em `https://<usuario>.github.io/<repositorio>/`.

Para usar domínio próprio, adicione um arquivo `CNAME` na raiz com o domínio (ex.: `lp.gmxagencia.com.br`) e configure o DNS conforme a documentação do GitHub Pages.

## Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | A landing page completa (servida pelo Pages) |
| `.nojekyll` | Desativa o Jekyll, evitando que arquivos sejam ignorados |
| `.gitignore` | Ignora arquivos de sistema e temporários |

## Estrutura da página

1. Hero — "Sua empresa cresceu. Sua marca acompanhou?" com painel animado
2. Dores do público
3. Manifesto e pilares: Estratégia · Design · Tecnologia
4. Framework GMX: Gestão · Método · Experiência
5. Autoridade e cases
6. Marcas que já passaram pela GMX (faixa animada)
7. Case em detalhe — Fertilizon (Alemanha)
8. Números: 2003 · 6 países · 9 setores
9. Para quem é / para quem não é
10. Como funciona o diagnóstico
11. Dúvidas frequentes
12. CTA e formulário de diagnóstico

## Formulário

O envio monta uma mensagem e abre o WhatsApp **(11) 95463-1077** com os dados preenchidos. Não há back-end.

Para integrar a um CRM ou serviço de e-mail, substitua o handler do `submit` em `#leadform` (ao final do `index.html`) por uma chamada à sua API, mantendo o WhatsApp como alternativa.

## Acessibilidade e responsividade

- Testada de 360px a desktop, sem rolagem horizontal
- Barra de CTA fixa no mobile e carrossel de cases com snap
- Campos de formulário a 16px no mobile (evita o zoom automático do iOS)
- Animações respeitam `prefers-reduced-motion` quando o JavaScript não está disponível

## Pendências de conteúdo

- Indicadores de resultado do case Fertilizon
- Depoimentos de clientes autorizados
- **Os números do painel do hero são ilustrativos** — substituir por dados reais antes de veicular

## Identidade

Grafite `#202624`, lime `#ceff00`, tipografia Sora (embutida no arquivo).
