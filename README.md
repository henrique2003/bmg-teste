# Teste - Bmg Seguridade

## Link do projeto em produção
- [https://bmg-web-woad.vercel.app](https://bmg-web-woad.vercel.app)

## Link dos repositórios Frontend e Backend:
- Frontend: [https://github.com/henrique2003/bmg-web](https://github.com/henrique2003/bmg-web)
- Backend: [https://github.com/henrique2003/bmg-backend](https://github.com/henrique2003/bmg-backend)

## Tecnologias

- **Backend**: .NET 8
- **Banco de Dados**: MySQL
- **Frontend**: React/Next.js, TypeScript

## Requisitos

- **Node.js**: 20
- **.NET**: 8
- **MySQL** ou **Docker**

## Scripts de Banco de Dados

Os scripts de banco de dados estão localizados em Adapter/Bmg.Repository/Dumps. Você pode executá-los manualmente se desejar.

## Instruções para Rodar o Backend

1. **Usando MySQL Local**:

   - Crie a base de dados bmg.
   - Para iniciar a API, defina o IIS Express e depois inicie.

2. **Usando Docker**:
   - Execute o seguinte comando para iniciar o ambiente:
     ```bash
     docker compose up
     ```

- Para iniciar a API, defina o IIS Express e depois inicie.

## Instruções para Rodar o Frontend

1. Instale as dependências do projeto:
   ```bash
   npm install
   ```
2. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

## Padrões Utilizados

### Repository

O padrão Repository é utilizado para abstrair a lógica de acesso a dados. Ele permite que a aplicação interaja com a fonte de dados (como um banco de dados) de maneira desacoplada, facilitando testes e manutenções.

### Envelope

O padrão Envelope é usado para padronizar as respostas da API. Ele encapsula a resposta, permitindo incluir informações adicionais, como metadados ou status, tornando as respostas mais consistentes e informativas.

### Result

O padrão Result é utilizado para encapsular os resultados das operações, especialmente em cenários de sucesso e erro. Ele permite que a API retorne resultados de forma mais estruturada, facilitando o tratamento de erros e a manipulação de dados na aplicação.
