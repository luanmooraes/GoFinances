## 01 - Conhecendo o Styled Components

* Criando pastas src / screens
* Testando componente `Dashboard`

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

## 06 - Utilizando proporções em medidas

* Montar o `Dashboard`
* Criando componente estilizado `Header` e explicar como é montado esse componente
* Instalação de uma biblioteca para trabalhar com proporções, pois há diferenças de densidades de pixels em celulares diferentes. Uso do seguinte comando: `yarn add react-native-responsive-fontsize`
* Explicando noções de flexbox e de como o layout se comporta
* Criando os componentes de estilização `UserInfo`,`Photo`,`User``UserGreeting` e `UserName` na pasta `Dashboard`   
* Estilizando uma foto com a imagem pessoal tirado do perfil do github, usando o `RFValue` para delimitar as proporções da foto 
* Estilizando componentes restantes e criação e estilização do componente `UserWrapper` para envolver todo o `ÙserInfo`.    

## 07 - Utilizando ícones

* Importação da lib de ícones `@expo/vector-icons` diretamente no `styles.ts`
* Criação e estilização de um componente de estilo chamado `Icon` que foi feito no arquivo `styles.ts` usando dos artificios do styled components. *Ex:*`export const Icon = styled(Feather)`

## 08 - Criação dos cartões de Destaque

* Criação da pasta `Components`
* Criação do componente `HighlightCard` e posteriormente feita sua estilização
* Importante destacar a criação dos componentes de estilo `Header` e `Footer` que trazem uma lógica de organização do layout
