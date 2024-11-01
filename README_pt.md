
# Aplicativo de Notas

Este é um aplicativo de anotações construído com Vite e Tailwind CSS, projetado para que os usuários possam criar, gerenciar e organizar suas notas.
O app oferece funcionalidades adicionais como filtro de busca e criação de notas via comando de voz.

**[Read this documentation in English](README.md)**

## Funcionalidades

- **Criação de Notas**: Adicione novas notas com texto ou via comando de voz.
- **Persistência em Local Storage**: As notas são salvas no local storage, mantendo-as disponíveis mesmo após atualizar a página.
- **Funcionalidade de Busca**: Filtre notas pelo conteúdo.
- **UI Responsiva**: Projetado com Tailwind CSS para uma experiência responsiva e mobile-first.
- **Modais para Visualização de Notas**: As notas podem ser visualizadas em modais/diálogos usando Radix UI.
- **Notificações**: Notificações toast para ações bem-sucedidas, como adicionar ou deletar notas.

## Início Rápido

### Pré-requisitos
- [Node.js](https://nodejs.org/) (v14 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

### Instalação

1. Clone o repositório:
    ```bash
    git clone <repository-url>
    cd notes-app
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute a aplicação:
    ```bash
    npm run dev
    ```

4. Abra [localhost:5173/](http://localhost:5173/) no seu navegador para visualizar o app.

## Melhorias Planejadas

As seguintes melhorias estão planejadas para atualizações futuras:

1. **Validação e Limpeza de Notas**: Limitar o comprimento das notas, remover espaços em branco e evitar duplicatas ou notas vazias.
2. **Confirmação de Exclusão**: Adicionar uma etapa de confirmação antes de excluir permanentemente as notas.
3. **Categorias e Etiquetas**: Organizar notas com categorias ou etiquetas para aprimorar a busca e o filtro.
4. **Editor de Texto Rico**: Integrar um editor de texto como `react-quill` para formatação básica de texto.
5. **Backup e Sincronização**: Exportar e importar notas em formato JSON ou sincronizar notas usando Firebase.
6. **Animações e Feedback Visual**: Adicionar animações sutis para adição e exclusão de notas, usando Tailwind CSS ou Framer Motion.
7. **Testes Unitários**: Assegurar a integridade da funcionalidade implementando testes unitários e de integração, especialmente para lógica central como criação e exclusão de notas.

---

