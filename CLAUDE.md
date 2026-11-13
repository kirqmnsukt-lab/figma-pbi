# Telas de PBI no Figma

Fluxo:
1. Usuário manda texto da PBI (com nº). Sem link → criar no arquivo/coluna padrão abaixo.
2. Faltou algo (nº da PBI, web ou mobile, tela base)? Perguntar antes. Não chutar.
3. Usar os node IDs abaixo; não explorar o arquivo. Clonar e ajustar; não montar do zero.
4. Título "Product Backlog Item <nº>: [BO-e][AIA][...] <resumo>" (clonar o título anterior).
5. Frames: "1 - Tipo de Pesquisa", "2 - Filtros X", "3 - Modal X"… (viram PNG para o time de requisitos).
6. Poucas chamadas: 1 leitura, 1 escrita, 1 screenshot final (recortar só o trecho alterado ao conferir).
7. Resposta final: português, 2–4 linhas. Terminar com "PBI concluída — rode /compact."
8. PDF de apresentação (Claude-Telas-BO-e.pdf): só mexer se o usuário pedir.

Conteúdo:
- Campo vazio → "Não Informado" (textCase original).
- Ocorrência com 5 dígitos (00001); datas dd/MM/yyyy.
- Erro de obrigatoriedade: só "Campo obrigatório" (vermelho #F44336, 12px, abaixo do campo; borda do campo vermelha).
- Fluxo de validação: Pablo (design) → Requisitos → policiais. Não existe "PM" como papel (PM = policial militar).

## BO-e / AIA (RO-e)
Arquivo: https://www.figma.com/design/jkCgsXdY2Us6q1uiI4QeOf/AIA-ROe--Pablo- · página "📱Mobile Off-line" (2762:7256)
- Onde criar: coluna x=86697. Título 400px abaixo do item mais baixo da coluna; frames 350px abaixo do título; passo horizontal 1516.
- Web 1440px. Base Empenho: 4079:18450.
- Pesquisar Ocorrência (resultados): Providências 4191:19808 · Encerradas 4191:20567. Cards têm ação oculta no header ("Empenhar US" + ícone): tornar visível e trocar texto/ícone para novas ações.
- Modal padrão: overlay escuro; card branco (radius 8, sombra); título Roboto Bold 20 + divisor 1px #D9D9D9; texto 16; botões CANCELAR (#F44336) e CONFIRMAR (#28A745) dividindo a largura.
  - Modal com campo: 4226:20901 · com erro: 4226:21311 · lista com seleção: 4193:19934 (título antigo, aplicar padrão).
  - Atenção!: 4226:21729 (título, divisor, mensagem, CONFIRMAR largura total).
- Campo texto obrigatório com contador (Justificativa + 0/280): 4227:19844. Borda fica no frame interno de altura fixa; clipsContent=false nos wrappers.
- PDF da ocorrência: node 4167:19816.
- Fields das instâncias têm largura fixa: detachInstance antes de usar FILL.
