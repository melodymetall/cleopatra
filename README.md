# Cleópatra — protótipo visual v2

Etapa de aprovação visual anterior à implementação definitiva. Protótipo estático navegável, sem checkout, coleta de dados ou serviços de produção.

## Executar

`node server.cjs` — abrir http://127.0.0.1:4188.

Também é possível abrir `prototype/index.html` diretamente. As fontes usam Google Fonts, com fallback local.

## Direção

Obsidiana, ouro envelhecido, tipografia Cinzel Decorative nos títulos e Forum nas passagens narrativas. Sete capítulos contínuos em lista, cada um com uma cena cinematográfica exclusiva de Cleópatra vivendo a experiência. Alternância de composições íntimas e panorâmicas, com textos abaixo de cada título. Textos de apoio abaixo dos títulos, sem labels de seção. Copy condensada para o protótipo. Depoimentos omitidos por ausência de material real autorizado.

## Validação

- Sintaxe JavaScript validada com `node --check`.
- V2: sete cenas carregadas no navegador, seis links de continuidade, CTA final e modal de inscrição validados. IDs únicos, referências locais existentes, âncoras válidas e nenhuma imagem repetida no HTML.
- Revisão visual desktop e mobile, incluindo largura útil de 312 px; sem overflow horizontal. Cinzel Decorative carregada e verificada no navegador.
- Suporte a movimento reduzido, foco visível, links semânticos e todas as etapas acessíveis sem abas.

## Pendências para implementação final

Definir preço, pagamento, garantia, plataforma, prazo de acesso, duração das ativações e URL de checkout. Receber vídeo da personagem e amostra autêntica de 20–40 segundos. Aprovar direção visual e ajuste editorial da copy.

## Ambientes

Prévia local disponível. Nenhum ambiente DEV remoto ou repositório remoto foi fornecido/configurado; deploy DEV remoto pendente. Produção não alterada.

## Imagens

Geradas com a ferramenta integrada ImageGen. Doze imagens finais em `prototype/assets/`: retrato de abertura, trono de encerramento, sete cenas das camadas, conexão simbólica, convite e portal com alfa. O retrato principal aparece apenas uma vez. A capa do produto usa composição tipográfica própria. Prompts registrados em `image-prompts.md` e `image-prompts-v2.md` e `image-prompt-portal.md`.

Portal: PNG com transparência real, máscara radial complementar em CSS, desktop/mobile e abertura do diálogo verificados.
