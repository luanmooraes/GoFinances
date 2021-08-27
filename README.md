## 01 - Conhecendo o Styled Components

* Criando pastas src / screens
* Testando componente Dashboard

## 02 - Criando componentes com o Styled Components

* Instalação usando: `yarn add styled-components`
* Instalação tipagem e também como dependêcia de desenvolvimento: `yarn add @types/styled-components-react-native -D`
* Criando pasta Dasboard com 2 arquivos
* Explicando o porquê de um arquivo `index` ser carregado automaticamente
* Criando componentes no arquivo `styles.ts`
* Estilizando componente de estilo Container e Title no `styles.ts/Dashboard`

## 03 - Criando estilos globais

* Criando pasta `global` para guardar variáveis globais como cores e fontes
* Criando arquivo `theme.ts/global` e configurando as cores
* Importando `ThemeProvider` que é um tipo de contexto que envolve toda a aplicação e que esse tema pode ser usado em qualquer lugar da aplicação que está envolvida com este contexto
* Usando o arquivo theme.ts de forma desestruturada em estilos. Essa forma desestruturada ajuda na hora de chamar as cores.
* Criando arquivo `styled.d.ts` na pasta global que serve para sobrescrever tipos e faz ganhar produtividade na hora de codar.

## 04 - Utilizando fontes personalizadas

* Instalação de fontes externas usando o expo com o comando: `expo install expo-font @expo-google-fonts/poppins`
* Importação das fontes no arquivo `App.tsx`
* Uso do `useFonts` para criar uma variavel de estado que carrega as fontes que serão usadas no App.
* Uso do comando `expo install expo-app-loading` para instalar um componente que lida com o carregamento do App enquanto as fontes estao sendo carregadas

## 05 - Densidade de Pixel

## 06 - 