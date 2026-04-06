# 🎫 Compra de Ingresso

O **Compra de Ingresso** é uma aplicação interativa que simula um sistema de bilheteria online. O foco principal do projeto é o gerenciamento de quantidades disponíveis para diferentes setores (Pista, Cadeira Superior e Cadeira Inferior), garantindo que o usuário não compre mais ingressos do que o estoque permite.

## 🛠️ Tecnologias

- **HTML5**: Estrutura do formulário de compra e exibição do inventário.
- **CSS3**: Estilização visual e layout responsivo.
- **JavaScript (ES6+)**: 
    - Lógica de subtração de estoque.
    - Captura e validação de valores de entrada (inputs).
    - Atualização dinâmica de texto no DOM.

## ✨ Funcionalidades

- **Seleção de Setor**: Menu suspenso para escolher entre Pista, Cadeira Superior ou Inferior.
- **Validação de Quantidade**: O sistema verifica se a quantidade desejada é positiva e se há ingressos suficientes antes de confirmar a compra.
- **Atualização em Tempo Real**: Assim que a compra é confirmada, a quantidade disponível no painel de "Ingressos Disponíveis" é atualizada automaticamente.
- **Alertas de Erro**: Notificações caso o usuário tente comprar uma quantidade excedente ao estoque atual.

## 🧠 O que eu aprendi

Este projeto foi essencial para praticar a integração entre lógica de negócio e interface:
1. **Recuperação de IDs**: Como utilizar `document.getElementById` para ler valores de `select` e `input`.
2. **Conversão de Tipos**: Uso de `parseInt` para garantir que cálculos matemáticos sejam feitos corretamente com as quantidades.
3. **Persistência de Estado Simples**: Manter o controle da variável de estoque durante a sessão de uso da página.
4. **UX (Experiência do Usuário)**: Implementação de mensagens de feedback (Alerts) para guiar o usuário em casos de erro ou sucesso.

## 💻 Como executar o projeto

1. Clone o repositório:
   ```bash
   git clone [https://github.com/maryolivr/compra-de-ingresso.git](https://github.com/maryolivr/compra-de-ingresso.git)
