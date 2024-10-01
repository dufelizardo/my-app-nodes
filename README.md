# MY APP - Expo/React Native
## ![visitors](https://visitor-badge.laobi.icu/badge?page_id=dufelizardo.visitor-my-app-nodes) ![GitHub followers](https://img.shields.io/github/followers/dufelizardo.visitor-my-app-nodes?style=social) <img src="https://img.shields.io/badge/Completed-0%25-red"/>  <img src="https://img.shields.io/badge/public-Yes-green"/> <img src="https://img.shields.io/badge/Software Quality and Automated Testing-Yes-green"/>
Este projeto faz parte da atividade prática da disciplina de **Teste Mobile** da pós-graduação em Engenharia de Qualidade de Software e Testes Automatizados. O aplicativo **MY APP** é uma aplicação desenvolvida com **React Native** e **Expo**, com o objetivo de explorar técnicas de desenvolvimento mobile multiplataforma e aplicar testes automatizados.

## Índice
- [Descrição do Projeto](#descrição-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Testes](#testes)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Descrição do Projeto

O **MY APP** é um aplicativo mobile desenvolvido usando **React Native** e o framework **Expo**. Ele foi criado com o objetivo de demonstrar boas práticas em desenvolvimento mobile e testar funcionalidades usando ferramentas automatizadas. A principal meta deste projeto é aplicar testes de interface e funcionalidade no ambiente mobile.

Este projeto permite:
- Criar uma aplicação para Android e iOS de forma rápida utilizando Expo.
- Aplicar testes automatizados com frameworks como **Jest** e **React Native Testing Library**.
- Explorar as funcionalidades do React Native e Expo no desenvolvimento de interfaces nativas.

## Funcionalidades

As principais funcionalidades do **MY APP** incluem:
- [Funcionalidade 1]: Descrever a primeira funcionalidade.
- [Funcionalidade 2]: Descrever a segunda funcionalidade.
- [Funcionalidade 3]: Descrever a terceira funcionalidade.

## Requisitos

Para rodar e testar o **MY APP**, você precisará dos seguintes requisitos instalados no seu ambiente de desenvolvimento:

- [Node.js](https://nodejs.org/) versão 14 ou superior
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/) (gerenciadores de pacotes)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Dispositivo móvel (físico ou emulador) com o aplicativo **Expo Go** (disponível para [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en&gl=US) e [iOS](https://apps.apple.com/us/app/expo-go/id982107779))

## Instalação

1. Instale o gerenciador de pacotes mais recente:
   ```bash
   npm install -g npm
   ```

2. Instale o Expo CLI globalmente no sistema:
   ```bash
   npm install -g expo-cli
   ```

3. Crie um novo projeto Expo:
   ```bash
   npx create-expo-app@latest my-app
   ```

4. Navegue até o diretório do projeto:
   ```bash
   cd my-app
   ```

5. Instale as dependências do projeto:
   ```bash
   npm install
   ```

6. Inicie o servidor Expo:
   ```bash
   npm start
   ```

7. Abra o aplicativo **Expo Go** no seu dispositivo físico ou emulador e escaneie o QR Code exibido no terminal ou navegador para rodar o aplicativo.

## Testes

O **MY APP** vem preparado para a execução de testes automatizados utilizando **Jest** e outras ferramentas de teste para React Native.

### Executar os Testes

Para rodar os testes automatizados, use o comando:
```bash
npm test
```

### Ferramentas e Bibliotecas de Teste

As seguintes ferramentas e bibliotecas são utilizadas no **MY APP** para testes:
- [Jest](https://jestjs.io/): Framework de testes para JavaScript.
- [React Native Testing Library](https://testing-library.com/docs/react-native-testing-library/intro/): Para testar componentes React Native.
- [Expo Testing Library](https://docs.expo.dev/testing/test-suite/): Para realizar testes nativos em aplicações Expo.

### Exemplo de Teste

Aqui está um exemplo básico de teste de um componente React Native usando **Jest**:

```javascript
import React from 'react';
import { render } from '@testing-library/react-native';
import MyComponent from '../MyComponent';

test('deve renderizar o componente corretamente', () => {
  const { getByText } = render(<MyComponent />);
  expect(getByText('Olá, Mundo!')).toBeTruthy();
});
```

## Contribuições

Contribuições são bem-vindas! Para contribuir com o **MY APP**, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch para sua feature:
   ```bash
   git checkout -b feature-nova-funcionalidade
   ```
3. Implemente sua funcionalidade e adicione testes para ela.
4. Envie um Pull Request para revisão.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para mais detalhes.

---
