```markdown
# App em React Native com Expo

Aplicativo mobile desenvolvido com React Native e Expo, que realiza operações de CRUD de usuários consumindo uma API backend local feita com Node.js e SQLite.

## Funcionalidades

- Listar usuários cadastrados com nome e email
- Adicionar novo usuário com dados: nome, email, login, senha e cidade
- Editar dados de usuários existentes
- Excluir usuários
- Navegação entre telas utilizando Stack Navigation
- Componentes reutilizáveis para cabeçalho (Header) e rodapé (Footer)

## Tecnologias Utilizadas

- **Frontend:** React Native, Expo, TypeScript, React Navigation (Stack Navigator)
- **Backend:** Node.js, Express, SQLite
- **Outros:** Axios para comunicação entre app e API


## Como Executar

### Backend (API)

1. Acesse a pasta da API:
```bash
cd api
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor:
```bash
npm start
```

A API estará disponível em: `http://localhost:3000`

### Aplicativo Mobile

1. Volte para a raiz do projeto:
```bash
cd ..
```

2. Instale as dependências do app:
```bash
npm install
```

3. Inicie o servidor do Expo:
```bash
npx expo start
```

4. Utilize o app **Expo Go** no seu celular para escanear o QR code exibido no terminal.

> **Observação:** Certifique-se de que:
> - Seu dispositivo móvel e computador estejam na mesma rede Wi-Fi
> - O servidor da API esteja rodando antes de iniciar o app mobile
```
