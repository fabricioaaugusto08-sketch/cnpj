# 📋 Consulta CNPJ

Aplicação desenvolvida em **Flutter** para realizar consultas de CNPJ por meio de uma API externa. O sistema permite que o usuário informe um CNPJ e consulte informações básicas da empresa, como razão social, nome fantasia, situação cadastral e estado.

## 📌 Sobre o projeto

O projeto tem como objetivo demonstrar a criação de uma aplicação Flutter capaz de:

* Receber um CNPJ informado pelo usuário;
* Enviar uma solicitação para uma API;
* Receber os dados da empresa;
* Interpretar as informações retornadas;
* Exibir os resultados diretamente na tela.

A aplicação utiliza a API **OpenCNPJ** para realizar as consultas.

## 🚀 Tecnologias utilizadas

* **Flutter** — desenvolvimento da aplicação;
* **Dart** — linguagem de programação;
* **HTTP** — comunicação com a API;
* **JSON** — formato utilizado para receber e interpretar os dados da API.

## 📁 Estrutura principal

```text
cnpj/
├── android/
├── ios/
├── lib/
│   └── main.dart
├── test/
├── web/
├── windows/
├── pubspec.yaml
├── analysis_options.yaml
└── README.md
```

### `lib/main.dart`

É o arquivo principal da aplicação. Nele estão:

* A criação da interface;
* O campo para informar o CNPJ;
* O botão de consulta;
* A comunicação com a API;
* O tratamento dos dados recebidos;
* A apresentação das informações na tela.

### `pubspec.yaml`

Arquivo responsável pelas configurações do projeto e pelo gerenciamento das bibliotecas utilizadas.

Entre as principais dependências estão:

* `flutter`
* `cupertino_icons`
* `http`
* `flutter_lints`

## 🔎 Funcionamento

O funcionamento da aplicação ocorre da seguinte maneira:

```text
Usuário informa o CNPJ
          ↓
Clica em "Consultar"
          ↓
Aplicação envia o CNPJ para a API
          ↓
API processa a solicitação
          ↓
Aplicação recebe os dados
          ↓
Dados são interpretados
          ↓
Informações da empresa aparecem na tela
```

## 📊 Informações apresentadas

Após uma consulta, a aplicação apresenta:

* **Razão social** — nome oficial da empresa;
* **Nome fantasia** — nome pelo qual a empresa é conhecida;
* **Situação cadastral** — situação atual do CNPJ;
* **UF** — estado em que a empresa está registrada.

## 🖥️ Interface

A aplicação possui uma interface simples, contendo:

1. Título **"Consulta CNPJ"**;
2. Ícone relacionado à localização;
3. Campo para informar o CNPJ;
4. Botão **"Consultar"**;
5. Área destinada à apresentação dos resultados.

## ⚙️ Pré-requisitos

Para executar o projeto, é necessário ter instalado:

* **Flutter SDK**;
* **Dart SDK**;
* **Android Studio** ou **Visual Studio Code**;
* Um dispositivo físico ou emulador, caso a aplicação seja executada em Android.

Também é necessário possuir acesso à internet, pois a aplicação consulta uma API externa.

## ▶️ Como executar

### 1. Clonar o projeto

```bash
git clone <URL_DO_REPOSITORIO>
```

### 2. Entrar na pasta do projeto

```bash
cd cnpj
```

### 3. Instalar as dependências

```bash
flutter pub get
```

### 4. Executar a aplicação

```bash
flutter run
```

O Flutter irá executar a aplicação no dispositivo ou emulador selecionado.

## 🌐 API utilizada

A aplicação utiliza a API **OpenCNPJ** para obter os dados relacionados ao CNPJ informado pelo usuário.

O CNPJ digitado é enviado para a API e os dados retornados são recebidos no formato **JSON**.

## ⚠️ Observações

* É necessário possuir conexão com a internet para realizar as consultas.
* A disponibilidade e o funcionamento da consulta dependem da API utilizada.
* O projeto atualmente possui uma interface simples, desenvolvida com finalidade de estudo e demonstração.
* O tratamento de possíveis erros de conexão ou de CNPJ inválido pode ser aprimorado em versões futuras.

## 🔮 Possíveis melhorias

Algumas melhorias que
