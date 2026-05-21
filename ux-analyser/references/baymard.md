# Baymard Institute — UX Best Practices

Referência baseada nas pesquisas do Baymard Institute sobre e-commerce e SaaS UX.

## Formulários e Checkout

### Campos e Labels
- Labels acima do campo (não dentro/placeholder) — usuário perde referência ao digitar
- Um campo por linha em formulários mobile — evita confusão
- Campos opcionais marcados como "(opcional)", não obrigatórios marcados com "*"
- Tamanho do campo deve sugerir o tamanho esperado da resposta (CEP != endereço)
- Teclado numérico para campos de número (CEP, telefone, cartão)

### Validação
- Validação inline após blur do campo (não ao submit)
- Mensagem de erro específica e próxima ao campo com problema
- Não apagar o que o usuário digitou ao mostrar erro
- Confirmar sucesso com feedback positivo, não apenas ausência de erro

### Processo de checkout
- Indicador de progresso claro com etapas nomeadas
- Sumário do pedido sempre visível (especialmente mobile: accordion)
- Edição direta na revisão sem voltar etapas
- Custo total visível antes do CTA de confirmação (sem surpresas)
- Guest checkout facilmente acessível (não enterrar atrás de login)

## CTAs e Conversão

### Hierarquia de ações
- Um CTA primário por tela/seção — clareza de ação esperada
- Diferenciação visual clara entre primary, secondary e ghost buttons
- CTA above the fold para landing pages de conversão
- Texto do CTA descreve a ação, não apenas "Enviar" ou "OK"
  - ✅ "Finalizar compra", "Criar minha conta", "Baixar grátis"
  - ❌ "Continuar", "Próximo", "Submit"

### Urgência e confiança
- Indicadores de estoque/disponibilidade (quando relevante) próximos ao CTA
- Selos de segurança e avaliações visíveis perto de CTAs de conversão
- Política de devolução/cancelamento visível antes do commit

## Navegação e Descoberta

### Menus e categorias
- Mega menus devem ter agrupamento claro com cabeçalhos de categoria
- Breadcrumbs em páginas de produto/categoria (ativa = link, página atual = texto)
- Sticky header com navegação principal em desktop
- Hamburguer menu em mobile deve ter texto "Menu" além do ícone

### Busca
- Busca proeminente — não escondida atrás de ícone em produtos com catálogo grande
- Placeholder da busca sugere o que pode ser buscado
- Resultados com 0 itens devem sugerir alternativas e não apenas "nenhum resultado"
- Auto-complete/sugestões quando possível

## Produto e Conteúdo

### Páginas de produto
- Imagens de alta qualidade com zoom — segunda maior causa de abandono
- Preço claramente visível e sem asteriscos ambíguos
- Variantes (cor, tamanho) com feedback visual do estado selecionado
- CTA principal fixo ou sempre visível enquanto o usuário rola

### Empty states
- Nunca deixar uma tela/seção vazia sem orientação
- Explicar por que está vazio e o que o usuário pode fazer
- Ação direta no empty state para resolver o estado vazio

## Mobile específico

- Itens de navegação mobile ≥ 44px de área de toque
- Espaçamento ≥ 8px entre itens clicáveis para evitar erros de toque
- Input zoom prevention: font-size ≥ 16px nos campos (evita zoom automático no iOS)
- Scroll horizontal deve ser evitado — o usuário não vai descobrir o conteúdo oculto
- Bottom navigation para ações frequentes (alcance do polegar)
