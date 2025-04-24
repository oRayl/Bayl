# Bayl - Plataforma de E-commerce

**Bayl** é uma solução moderna de e-commerce com suporte para múltiplos idiomas e moedas, incluindo criptomoedas. É projetada para ser responsiva, fácil de usar e escalável.

## 🌟 Funcionalidades
- 🌍 **Suporte a múltiplos idiomas**: Português, Inglês e Espanhol.
- 💳 **Pagamentos com múltiplas moedas**: Inclui suporte para criptomoedas.
- 📱 **Design responsivo**: Compatível com dispositivos móveis e desktops.
- 🔍 **Fácil de personalizar**: Código modular e bem estruturado.

## 🚀 Como Configurar Localmente
Siga estas etapas para executar o projeto na sua máquina local:

### 1. Pré-requisitos
Certifique-se de que você possui:
- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [npm](https://www.npmjs.com/) (gerenciador de pacotes do Node.js)

### 2. Clone o Repositório
```bash
git clone https://github.com/oRayl/bayl.git
cd bayl
```

### 3. Instale as Dependências
```bash
npm install
```

### 4. Configure as Variáveis de Ambiente
Crie um arquivo `.env.local` na raiz do projeto com o seguinte conteúdo:
```env
REACT_APP_API_BASE_URL=https://api.bayl.com
REACT_APP_PAYMENT_API_KEY=sua-chave-de-pagamento
REACT_APP_CRYPTO_API_KEY=sua-chave-de-criptomoeda
```

### 5. Inicie o Servidor
```bash
npm start
```

Acesse o projeto no navegador em `http://localhost:3000`.

---

## 🌐 Hospedagem no GitHub Pages
Este projeto pode ser facilmente hospedado no GitHub Pages. Siga estas etapas:

1. Adicione o campo `homepage` no `package.json`:
   ```json
   "homepage": "https://oRayl.github.io/bayl"
   ```

2. Instale o pacote `gh-pages`:
   ```bash
   npm install gh-pages --save-dev
   ```

3. Adicione os seguintes scripts ao `package.json`:
   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```

4. Faça o deploy:
   ```bash
   npm run deploy
   ```

O site estará disponível em `https://oRayl.github.io/bayl`.

---

## 📂 Estrutura de Pastas
```
bayl/
├── public/               # Recursos públicos do projeto (ex.: assets)
├── src/                  # Código-fonte do projeto
│   ├── components/       # Componentes reutilizáveis
│   ├── pages/            # Páginas principais
│   ├── translations/     # Arquivos de tradução
│   ├── App.jsx           # Configuração principal do React
│   └── index.js          # Ponto de entrada da aplicação
├── .env.local            # Variáveis de ambiente (não incluídas no repositório)
├── package.json          # Configurações e dependências
├── README.md             # Documentação do projeto
└── .gitignore            # Arquivos ignorados pelo Git
```

---

## 📜 Licença
Este projeto está licenciado sob a [Licença Apache 2.0](LICENSE).

---

## 🛠️ Tecnologias Utilizadas
- **React**: Biblioteca JavaScript para construir interfaces de usuário.
- **React Router**: Gerenciamento de rotas.
- **i18next**: Internacionalização para múltiplos idiomas.
- **dotenv**: Gerenciamento de variáveis de ambiente.
- **gh-pages**: Deploy no GitHub Pages.

---

## 📞 Suporte
Se você tiver dúvidas ou problemas, sinta-se à vontade para abrir uma [issue](https://github.com/oRayl/bayl/issues) ou entrar em contato.

---

## 📝 Contribuições
Contribuições são bem-vindas! Siga estas etapas para contribuir:
1. Faça um fork do repositório.
2. Crie uma nova branch:
   ```bash
   git checkout -b minha-nova-feature
   ```
3. Faça suas alterações e commit:
   ```bash
   git commit -m "Adiciona nova funcionalidade"
   ```
4. Envie suas alterações:
   ```bash
   git push origin minha-nova-feature
   ```
5. Abra um Pull Request.

---
