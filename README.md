# Macapá Eleições

Essa aplicação segue modelos do Framework Ionic e Angular.

Aplicativo voltado para a matéria de Programação para Dispositivos Móveis.

Professor: Paulo Mergulhão.

Envolvidos: Jaime Juan, 20952210; Rafael Alves, 20765711; Wesley Silvestre, 21027242.

## Ambientalizando

* [Baixe o instalador](https://nodejs.org/) para Node LTS.
* Clone o repositório: `https://github.com/JaimeJuan11/dispositivos-moveis.git`.
* Mova-se até a pasta criada: `cd dispositivos-moveis`.
* Rode `ionic serve`.
* Caso não tenha o ionic instalado, o próprio instalador irá acusar e questionar se queres instalar, aceite.

## Funcionalidades

* Acesso a Banco de Dados.
* Mapa.

## Rodando no Celular - Android

### Habilitar modo desenvolvedor:
* Ir em configurações -> Sobre o telefone
* Clicar em Informações do Software
* Clicar 8 vezes em Número de compilação

### Configurar opções de desenvolvedor:
* Ativar modo de desenvolvedor
* Ativar opção `Permanecer ativo`
* Ativar opção `Depuração de USB`
* Ativar opção `Verificar aplicativos via USB` (ADB/ADT)
* Clicar em `Configuração USD`
* Selecionar a opção `USB Ethernet`

### [Instalar](https://developer.android.com/studio?hl=pt-br) o Android Studio
### Entrar no Android Studio e escolher a opção `Options => SDK manager`
### Instalar as versões do emulador Android 7.0 e superiores
### No terminal, ir para a pasta da aplicação
### Rodar a aplicação com `ionic cordova run android`
### No chrome, acessar a [url](chrome://inspect/#devices) `chrome://inspect/#devices` e verificar se o celular aparece
### Quando aparecer o dispositivo, clicar no item `inspect` para o aplicativo também rodar no browser.
### Para colocar um breakpoint, inserir no código uma linha com `debugger;`
