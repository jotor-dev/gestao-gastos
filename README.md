# Gestão de Gastos 💸

Uma aplicação web simples para controle financeiro pessoal. Com este projeto, o usuário pode registrar suas entradas e saídas, editar transações existentes e visualizar o saldo atualizado.

## 🚀 Funcionalidades

* **Controle de Saldo**: Cálculo automático do saldo atual com base nas transações inseridas.
* **Gerenciamento de Transações (CRUD)**:
* **Adicionar**: Registro de novas transações com ID único.
* **Listar**: Visualização organizada de todos os gastos e ganhos.
* **Editar**: Alteração de dados de transações já existentes.
* **Excluir**: Remoção de registros da lista.
* **Tipagem **: Uso de TypeScript para garantir a integridade.

## 🛠️ Tecnologias Utilizadas

* **Core**: [React 18](https://reactjs.org/)
* **Linguagem**: [TypeScript](https://www.typescriptlang.org/)
* **Build Tool**: [Vite](https://vitejs.dev/)
* **Linting**: [ESLint](https://eslint.org/)

## 📁 Estrutura de Componentes

O projeto segue uma estrutura modular para facilitar a manutenção:

* `SaldoAtual`: Responsável por exibir o balanço total.
* `FormularioTransacao`: Componente inteligente que lida tanto com a criação quanto com a edição de dados.
* `ListaTransacoes`: Exibe a tabela ou lista de registros com opções de ação (editar/deletar).
* `types.ts`: Definição das interfaces TypeScript para padronização dos dados.

## 🔧 Instalação e Execução

1. **Clone o repositório:**
```bash
git clone https://github.com/jotor-dev/gestao-gastos.git
cd gestao-gastos
```
2. **Instale as dependências:**
```bash
npm install
```
3. **Inicie o servidor de desenvolvimento:**
```bash
npm run dev
```
4. **Acesse no navegador:**
Abra o endereço indicado no terminal (geralmente `http://localhost:5173`).

## 📦 Scripts Disponíveis

* `npm run dev`: Inicia o Vite para desenvolvimento.
* `npm run build`: Compila o projeto com o compilador do TypeScript (`tsc`) e gera os arquivos otimizados para produção via Vite.
* `npm run lint`: Analisa o código em busca de erros e padrões de estilo.
* `npm run preview`: Testa localmente o build gerado para produção.
