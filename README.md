# Landing page Ecosolary Renewable Energy

Esta é a landing page da **Ecosolary Renewable Energy**. Ela foi gerada automaticamente por `_automacao/gerar-site.js` a partir de `_automacao/clientes/ecosolary.json`. O site é estático (HTML + Bootstrap 4 + jQuery): basta abrir `index.html` ou publicar a pasta na Vercel, Netlify ou GitHub Pages.

> Para mudar textos, edite o JSON e rode `node gerar-site.js clientes/ecosolary.json` de novo. Isso sobrescreve o `index.html`.

## Estrutura
- `index.html` contém a página inteira.
- `css/` guarda o Bootstrap e os estilos com a paleta do cliente (primária `#7b1e3c`, destaque `#f5a623`, escura `#2b0d1c`).
- `js/` controla carrosséis, navegação, o vídeo do banner e o formulário que abre o WhatsApp `(98) 3197-7037`.
- `video/` guarda o vídeo do banner (1080p e versão leve para celular) e a imagem de capa.
- `img/` guarda as imagens: as `cliente-*.jpg` são fotos reais da empresa; as demais são genéricas.

## Dados usados (levantados em 03/11/2026)
| Informação | Valor | Fonte |
|---|---|---|
| Nome, categoria, nota, endereço, telefone | Eco Solary Renewable Energy · Empresa de energia solar · 4,8 · Av. Prof. Carlos Cunha, 3000 - Cohafuma, São Luís - MA, 65076-820 · (98) 3197-7037 | Google Maps |
| Nº de avaliações e serviço | 26 avaliações · comercial | Diretório energiasolarexplicada.com.br |
| Foto da loja e logo | img/cliente-1.jpg (fachada) e img/cliente-logo.png (logo recortado da fachada) | Foto do perfil no Google Maps |
| Frase e produto | "Saber aproveitar o melhor da natureza é investir em produção de energia solar" · banner "Kit de energia solar" | Fachada da loja (foto do Maps) |
| Link de WhatsApp antigo | mywhats.net/ecosolary, hoje um domínio estacionado (não leva ao WhatsApp) | Verificado no Chrome em 03/11/2026 |

## Confirmar com o cliente
- Se o (98) 3197-7037 tem WhatsApp. O formulário e os botões de WhatsApp usam esse número; se não for, troque pelo número correto no JSON.
- Instagram da empresa (não encontrado).
- Se a empresa faz instalação residencial (o diretório cita só "comercial").
- Pedir o logo original em boa qualidade (o atual foi recortado da foto da fachada).

## Não usado de propósito
- O slogan da fachada que aparece cortado na foto ("Deixe o so..."); o título do site usa uma frase parecida, mas própria.
- Nenhum percentual de economia, número de instalações ou depoimento, porque não havia fonte.

## Imagens para substituir
Substitua mantendo o mesmo nome do arquivo:
- `video/hero.mp4`, `hero-mobile.mp4` e `hero-poster.jpg`: vídeo do banner.
- `img/about.jpg` e `img/gallery-*.jpg`: fotos de obras.
- `img/favicon.svg`: logo.
