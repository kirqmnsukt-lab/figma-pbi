# Telas de PBI no Figma

Fluxo:
1. Usuário manda texto da PBI (com nº) + link de onde criar as telas.
2. Faltou algo (nº da PBI, web ou mobile, tela base, padrão visual)? Perguntar antes. Não chutar.
3. Ler só a tela base (1 metadata + 1 screenshot). Clonar e ajustar; não montar do zero.
4. Criar abaixo/à direita das existentes, com título "Product Backlog Item <nº>: [BO-e][AIA][...] <resumo>" (clonar o título anterior).
5. Frames: "1 - Tipo de Pesquisa", "2 - Filtros X", "3 - Modal X"… (viram PNG para o time de requisitos).
6. Poucas chamadas: 1 leitura, 1 escrita, 1 screenshot final. Responder em português, curto.

Conteúdo:
- Campo vazio → "Não Informado" (textCase original).
- Ocorrência com 5 dígitos (00001); datas dd/MM/yyyy.

## BO-e / AIA (RO-e)
Arquivo: https://www.figma.com/design/jkCgsXdY2Us6q1uiI4QeOf/AIA-ROe--Pablo- · página "📱Mobile Off-line"
- Web 1440px. Base de tela: node 4079:18450 (Empenho: header, filtros em linha + Pesquisar, divisor, Resultados, cards).
- Pesquisar Ocorrência: título "Ambiental - AIA Eletrônico"; card com Tipo de Pesquisa (largo) + CONFIRMAR; abaixo, filtros + Pesquisar + resultados. Exemplo: frames "1 - Tipo de Pesquisa" a "6 - …" da PBI de filtros Providências/Encerradas.
- Modal: overlay escuro; card branco 700px; título Roboto Regular 22; campo "Pesquisar" com lupa; itens em cards com sombra e ícone check (selecionado verde #28A745); botões CANCELAR (#F44336) e CONFIRMAR (#28A745) dividindo a largura.
- PDF da ocorrência: node 4167:19816.
- Fields das instâncias têm largura fixa: detachInstance antes de usar FILL.
