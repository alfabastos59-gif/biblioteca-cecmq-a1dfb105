# Biblioteca Maria Quitéria (CECMQ)
**Colégio Estadual do Campo Maria Quitéria - Tempo Integral**

Sistema completo de gestão bibliotecária escolar, catálogo interativo, escritores em destaque, empréstimos, ranking de leitores, audiolivros e painel administrativo.

---

## 🚀 Como Executar no seu Computador

### Pré-requisitos
- **Node.js** (versão 18 ou superior recomendada): [https://nodejs.org](https://nodejs.org)
- **NPM** (já vem incluído no Node.js) ou **Bun** / **Yarn** / **PNPM**

---

### Passo a Passo

1. **Extrair os arquivos**:
   Descompacte o arquivo `.zip` em uma pasta de sua preferência (ex: `C:\Projetos\biblioteca-cecmq` ou `~/Projetos/biblioteca-cecmq`).

2. **Abrir o terminal na pasta do projeto**:
   - No Windows: clique com o botão direito na pasta e selecione "Abrir no Terminal" ou digite `cmd` na barra de endereços da pasta.
   - No Mac/Linux: abra o terminal e navegue até a pasta (`cd caminho/para/biblioteca-cecmq`).

3. **Instalar todas as dependências**:
   Execute o comando:
   ```bash
   npm install
   ```

4. **Iniciar o servidor de desenvolvimento**:
   ```bash
   npm run dev
   ```

5. **Acessar a aplicação**:
   Abra o navegador no endereço indicado no terminal (normalmente [http://localhost:5173](http://localhost:5173) ou [http://localhost:3000](http://localhost:3000)).

---

## 🛠️ Comandos Disponíveis

| Comando | Descrição |
| :--- | :--- |
| `npm run dev` | Inicia o servidor local de desenvolvimento com Hot Reload |
| `npm run build` | Compila a versão de produção otimizada na pasta `/dist` |
| `npm run preview` | Testa a versão de produção compilada localmente |
| `npm run lint` | Executa a verificação de tipos e sintaxe TypeScript |

---

## 📁 Estrutura do Projeto

```
├── public/                 # Arquivos públicos, ícones e assets
├── src/
│   ├── assets/             # Imagens, posters e vídeos
│   ├── components/         # Todos os componentes React (Catálogo, Admin, Leitores, etc.)
│   ├── context/            # Contextos globais (Tema, Autenticação, etc.)
│   ├── data/               # Dados padrão (livros, autores, citações, etc.)
│   ├── services/           # Integração com Firebase e APIs
│   ├── types.ts            # Tipagens TypeScript completas
│   ├── App.tsx             # Componente raiz da aplicação
│   ├── main.tsx            # Ponto de entrada React
│   └── index.css           # Estilos globais e Tailwind CSS
├── firebase-applet-config.json  # Configuração do Firebase
├── firebase-blueprint.json      # Esquema e regras do banco
├── firestore.rules              # Regras de segurança do Firestore
├── package.json                 # Dependências e scripts do projeto
├── tsconfig.json                # Configuração do compilador TypeScript
└── vite.config.ts               # Configuração do Vite e plugins
```

---

## 💡 Dúvidas Frequentes

- **Erro de porta ocupada**: Caso a porta 3000 ou 5173 já esteja em uso, o Vite automaticamente selecionará a próxima disponível.
- **Node Modules**: A pasta `node_modules` não é incluída no arquivo zip por ser muito grande; ela é criada automaticamente ao rodar `npm install`.
