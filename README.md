# Criador de Formulários Dinâmico

## Objetivo

Desenvolver um sistema para gerenciamento, coleta de respostas e avaliação de formulários dinâmicos. O sistema permitirá ao usuário final criar formulários personalizados com uma variedade de tipos de campos, coletar respostas e visualizar os resultados agregados em gráficos de pizza.

## Tarefas

### 1. CRUD de Formulário 

- **Criação do formulário**: O sistema deve permitir ao usuário criar perguntas para serem incluídas em formulários. Cada pergunta pode ser de diferentes tipos, que o usuário deve poder selecionar durante a criação. Cada formulário pode ter uma ordem específica de perguntas, definida pelo usuário.

  Os tipos de campos podem incluir:
  - **text**: Campo para texto livre curto.
  - **textarea**: Campo para texto livre longo.
  - **number**: Campo para entrada de números.
  - **date**: Seletores de data.
  - **option**: Radio buttons, checkboxes ou dropdowns para escolhas múltiplas ou únicas.
  

  Os campos devem permitir validações como obrigatório, máximo/mínimo de caracteres, entre outros.

- **Edição de Perguntas**: Os usuários devem poder editar as perguntas existentes, alterando o texto, o tipo de campo ou as validações.

- **Exclusão de Perguntas**: Permitir que perguntas sejam excluídas do sistema.

- **Listagem de Perguntas**: Exibir uma lista de todas as perguntas criadas, com opções para editar ou excluir cada uma delas.

### 2. Visualização do Formulário

Uma vez montado, o formulário deve ser gerado dinamicamente com todos os campos especificados, pronto para coleta de respostas.

### 3. Coleta e Análise de Respostas

- **Coleta de Respostas**: O formulário disponibilizado deve permitir aos usuários finais submeter respostas, que serão armazenadas no sistema.

- **Análise de Respostas**: Desenvolver uma funcionalidade para visualizar as respostas coletadas. As respostas devem ser agregadas e apresentadas em um gráfico de pizza, que pode ser gerado para qualquer uma das perguntas do tipo opção (radio, checkbox, dropdown).

## Considerações Adicionais

O sistema deve ser responsivo e você é livre para usar qualquer framework ou interface pronta de front-end. A interface deve ser limpa e intuitiva, para facilitar a criação e gerenciamento de formulários sem necessidade de treinamento. Deve-se considerar a segurança na manipulação de dados, especialmente na proteção contra injeções SQL e no armazenamento seguro de arquivos enviados.

## Formato de Entrega

Após finalizar o teste, compacte novamente o arquivo e envie para dev@imobibrasil.com.br, com o assunto "Entrega Teste Backend". Importante utilizar o mesmo e-mail que usou em sua primeira comunicação.

## Prazo

A partir da data de recebimento do email com este repositório, você terá 5 dias para realização do teste.
