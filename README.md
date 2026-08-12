# 💸 Controle de Gastos — App React Native

Aplicativo mobile para controle de gastos pessoais, desenvolvido em **React Native**. Permite registrar receitas e despesas, categorizá-las e acompanhar o saldo e os gastos ao longo do tempo direto do celular.

> Desenvolvido por [Heloísa Bolognesi](https://github.com/heloisabolognesi).

---

## 📋 Sumário

- [Sobre o projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades-planejadas)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Estrutura de pastas sugerida](#-estrutura-de-pastas-sugerida)
- [Pré-requisitos](#-pré-requisitos)
- [Como rodar o projeto localmente](#-como-rodar-o-projeto-localmente)
- [Variáveis de ambiente](#-variáveis-de-ambiente)
- [Scripts disponíveis](#-scripts-disponíveis)
- [Roadmap](#-roadmap)
- [Contribuindo](#-contribuindo)
- [Licença](#-licença)
- [Contato](#-contato)

---

## 📖 Sobre o projeto

O **Controle de Gastos** é um aplicativo mobile pensado para ajudar o usuário a organizar sua vida financeira de forma simples: cadastrar entradas e saídas, classificar por categoria e visualizar para onde o dinheiro está indo, tudo em um app nativo construído com React Native.

---

## ✨ Funcionalidades (planejadas)

- **➕ Cadastro de transações** — registro de receitas e despesas, com valor, data, descrição e categoria.
- **🏷️ Categorização** — organização dos gastos por categorias (alimentação, transporte, lazer, moradia, etc.).
- **📊 Resumo financeiro** — visão geral do saldo, total de entradas e total de saídas.
- **📈 Histórico** — listagem cronológica de todas as transações, com filtros por período e/ou categoria.
- **✏️ Edição e exclusão** — atualização ou remoção de lançamentos já cadastrados.
- **💾 Persistência local e/ou remota** — armazenamento dos dados no dispositivo e/ou sincronização com um backend (a definir conforme a implementação).

> Ajuste esta lista assim que as telas e funcionalidades reais forem implementadas.

---

## 🛠 Tecnologias utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/) *(caso o projeto use o fluxo gerenciado do Expo — confirmar)*
- JavaScript/TypeScript
- Biblioteca de navegação, ex. [React Navigation](https://reactnavigation.org/)
- Armazenamento local, ex. [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) ou banco local (SQLite/Realm)

> Atualize esta seção com as dependências reais listadas no `package.json` do projeto assim que o código for versionado.

---

## 📁 Estrutura de pastas sugerida

```
controle-gastos/
├── src/
│   ├── screens/          # Telas do app (Home, Nova Transação, Histórico, etc.)
│   ├── components/       # Componentes reutilizáveis de UI
│   ├── navigation/        # Configuração de rotas/navegação
│   ├── services/          # Integrações com API/armazenamento
│   ├── context/           # Contextos globais (ex. estado financeiro)
│   ├── hooks/              # Hooks customizados
│   └── utils/               # Funções utilitárias (formatação de moeda, datas, etc.)
├── assets/                # Ícones, imagens e fontes
├── App.js / App.tsx
└── package.json
```

> Esta é apenas uma sugestão de organização comum em projetos React Native — substitua pela estrutura real do repositório assim que ela existir.

---

## ✅ Pré-requisitos

- [Node.js](https://nodejs.org/) 18 ou superior
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/) *(se o projeto usar Expo)* ou ambiente nativo configurado (Android Studio / Xcode) para build via React Native CLI
- Um emulador Android/iOS ou um dispositivo físico com o app **Expo Go** instalado (se aplicável)

---

## 🚀 Como rodar o projeto localmente

1. **Clone o repositório**

   ```bash
   git clone https://github.com/heloisabolognesi/Projeto-React.Native.git
   cd Projeto-React.Native/controle-gastos
   ```

2. **Instale as dependências**

   ```bash
   npm install
   # ou
   yarn install
   ```

3. **Inicie o projeto**

   Se o projeto usar Expo:

   ```bash
   npx expo start
   ```

   Se o projeto usar React Native CLI puro:

   ```bash
   npx react-native run-android
   # ou
   npx react-native run-ios
   ```

4. Abra o app no emulador ou escaneie o QR code com o app **Expo Go** no seu celular (caso esteja usando Expo).

> Substitua os comandos acima pelos scripts reais definidos no `package.json` assim que o código estiver disponível.

---

## 🔑 Variáveis de ambiente

Caso o app venha a se integrar com uma API externa ou serviço de backend, documente aqui as variáveis necessárias, por exemplo:

```env
API_URL=https://sua-api.com
```

---

## 📜 Scripts disponíveis

| Script            | Descrição                                    |
|-------------------|-------------------------------------------------|
| `npm start`       | Inicia o servidor de desenvolvimento (Metro/Expo) |
| `npm run android` | Roda o app em um emulador/dispositivo Android    |
| `npm run ios`     | Roda o app em um emulador/dispositivo iOS        |
| `npm run lint`    | Executa o linter no projeto (se configurado)     |

> Ajuste conforme os scripts reais definidos no `package.json`.

---

## 🗺 Roadmap

- [ ] Definir e implementar a estrutura inicial das telas
- [ ] Implementar cadastro de receitas e despesas
- [ ] Implementar categorização e filtros
- [ ] Adicionar gráficos de gastos por categoria/período
- [ ] Persistência local (AsyncStorage/SQLite) e/ou integração com backend
- [ ] Autenticação de usuário (se necessário)
- [ ] Testes automatizados

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Faça commit das suas alterações (`git commit -m 'feat: adiciona minha feature'`)
4. Faça push para a branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto ainda não possui uma licença definida. Caso deseje torná-lo open source formalmente, considere adicionar um arquivo `LICENSE` (por exemplo, [MIT](https://choosealicense.com/licenses/mit/)).

---

## 📬 Contato

Desenvolvido por **Heloísa Bolognesi**
GitHub: [@heloisabolognesi](https://github.com/heloisabolognesi)

---

<p align="center">💰 Organize suas finanças, um lançamento por vez.</p>
