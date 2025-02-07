# Gerenciador de Transações Financeiras

Bem-vindo ao **Gerenciador de Transações Financeiras**, uma aplicação desenvolvida em TypeScript que permite gerenciar suas finanças pessoais de forma eficiente e organizada. Este projeto foi elaborado durante o curso "TypeScript na prática: implemente um projeto completo com TypeScript e módulos" da Alura, concluído em 07 de fevereiro de 2025. 

## Funcionalidades

- **Registro de Transações**: Adicione novas transações financeiras, especificando o tipo (Depósito, Transferência ou Pagamento de Boleto), valor e data.
- **Exibição de Saldo**: Visualize o saldo atual da conta, atualizado automaticamente após cada transação.
- **Extrato de Transações**: Consulte o histórico de transações agrupadas por mês, com detalhes sobre cada movimentação.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **src/main.ts**: Ponto de entrada da aplicação, responsável por importar os componentes principais.
- **src/utils/formatters.ts**: Contém funções utilitárias para formatação de moeda e data.
- **src/types/**: Define os tipos e enums utilizados na aplicação, como `Transacao`, `TipoTransacao` e `FormatoData`.
- **src/components/**: Inclui os componentes da interface, como `nova-transacao-component.ts`, `saldo-component.ts` e `extrato-component.ts`.

## Destaques do TypeScript

Este projeto faz uso extensivo dos recursos do TypeScript para garantir um desenvolvimento mais seguro e eficiente:

- **Tipagem Estática**: Utilização de tipos e interfaces para definir a estrutura dos dados, como a interface `Transacao` e o enum `TipoTransacao`.
- **Modularização**: Organização do código em módulos, facilitando a manutenção e reutilização de componentes.
- **Funções Utilitárias**: Implementação de funções auxiliares com tipagem definida, como `formatarMoeda` e `formatarData`, garantindo consistência na formatação de valores e datas.

## Como Executar

1. **Instalação de Dependências**: Certifique-se de ter o Node.js instalado. Em seguida, instale o TypeScript globalmente:

   ```bash
   npm install -g typescript
   ```

2. **Compilação**: Navegue até o diretório do projeto e execute o comando para compilar os arquivos TypeScript:

   ```bash
   tsc
   ```

3. **Execução**: Abra o arquivo `index.html` em seu navegador preferido para interagir com a aplicação.

## Considerações Finais

Este projeto exemplifica a aplicação prática do TypeScript no desenvolvimento de uma aplicação web modularizada e tipada, seguindo as melhores práticas aprendidas durante o curso. A utilização do TypeScript proporciona maior segurança e robustez ao código, facilitando a manutenção e escalabilidade da aplicação.
