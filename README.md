# Descrição
Esta aplicação implementa um frontend mobile extremamente simples, porém funcional, para a seguinte API desenvolvida: https://github.com/vitorbandeira/desafio-nodejs-nivel1

# Funcionalidades
- Listagem de repositórios 
- Adicionar "like" em um repositório

Tais ações são devidamente refletidas na base da dados da API utilizada.
# Conceitos exercitados
- Diferenças e similaridades entre o React Native e o React.js
- Integração com uma API Node.js utilizando a biblioteca Axios
- Criação de estilos para um componente mobile (StyleSheet)
- Componentes básicos do React Native como:
  - View
  - Text
  - SafeAreaView
  - FlatList
  - StatusBar
  - TouchableOpacity

# Setup
Após clonar o projeto em sua máquina e já ter um ambiente devidamente preparado para o React Native,
execute o seguinte comando na raiz do projeto para instalar as dependências necessárias:
```
yarn
```
# Conectando com a API
Clone também o projeto https://github.com/vitorbandeira/desafio-nodejs-nivel1 e instale suas dependências:
```
yarn
```
Inicialize a API:
```
yarn dev
```
> Crie alguns repositórios exemplo na API.
# Interagindo com o frontend mobile
> OBS.: A aplicação se encontra preparada para simulação em dispositivo físico Android.

Inicialize a aplicação mobile:
```
react native start
```
E em outra aba do terminal:
```
npx react-native run-android
```
# Testando
Rode os testes disponibilizados pelo template:
```
yarn test
```
