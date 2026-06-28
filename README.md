# SUTIL NFE Frontend

Frontend em React + Vite para o projeto SUTIL NFE, voltado para gestão e análise de notas fiscais com foco em visualização de dados, edição de informações e acompanhamento de metas.

## O que este projeto faz

Esta aplicação permite:

- selecionar anos e carregar dados de notas fiscais;
- visualizar informações em abas de navegação;
- editar detalhes das notas fiscais;
- acompanhar indicadores e metas anuais;
- analisar divisão de valores e gráficos relacionados à receita.

## Tecnologias utilizadas

- React
- Vite
- Tailwind CSS
- Recharts
- ESLint

## Requisitos

- Node.js 18 ou superior
- npm 9 ou superior
- backend do projeto SUTIL NFE rodando localmente na porta 8080

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/afarms/sutil-nfe-frontend.git
   cd sutil-nfe-frontend
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

A aplicação ficará disponível no navegador em http://localhost:5173.

## Scripts disponíveis

```bash
npm run dev
npm run build
npm run preview
npm run lint
```

## Estrutura principal

- src/components: componentes da interface
- src/hooks: lógica de estado e integração com dados
- src/services: comunicação com a API
- src/utils: funções utilitárias e formatação
- src/constants: dados e configurações compartilhadas

## Integração com a API

A aplicação consome a API do backend em:

```text
http://localhost:8080/api
```

Certifique-se de que o backend esteja em execução antes de usar os fluxos que dependem de dados.

## Contribuição

Contribuições são bem-vindas. Para alterações maiores, abra uma issue antes de enviar um pull request.

## Licença

Este projeto é de uso pessoal e acadêmico, conforme a necessidade do desenvolvimento local.
