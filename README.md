# IP_ Viewer

Aplicativo Android desenvolvido em Flutter para visualizar informações de rede do dispositivo de forma rápida e simples.  
Ideal para usuários técnicos, estudantes de TI e profissionais que precisam consultar IP público, IP local e detalhes da conexão.

---

## Visão geral:

O IP Viewer é um app leve para consulta de informações de rede do seu dispositivo Android:

- Exibe o IP público (via consulta externa)
- Exibe o IP local da rede Wi-Fi
- Mostra detalhes da interface de rede
- Mantém um **histórico** das consultas realizadas

Focado em simplicidade, rapidez e usabilidade, sendo adequado para testes, diagnósticos e uso em trabalhos acadêmicos.

## Observações

O aplicativo foi desenvolvido como parte de um trabalho acadêmico/TCC.

Nenhuma informação sensível do usuário é enviada a servidores próprios; somente a consulta do IP público é feita externamente.

O código-fonte pode ser ajustado para outros cenários de uso (ex.: ferramentas internas de suporte de TI).

---

## Funcionalidades

- IP público em tempo real  
  Consulta e exibe o IP externo do dispositivo.

- IP local (rede Wi-Fi)  
  Mostra o endereço IP interno atribuído pelo roteador.

- Detalhes da conexão  
  - Nome da rede (SSID)  
  - BSSID  
  - Intensidade do sinal (quando disponível)  
  - Gateway  
  - Máscara de sub-rede  

- Histórico de consultas  
  Registra automaticamente as consultas realizadas para consulta posterior.

- Detalhe do registro  
  Tela dedicada para visualizar com mais detalhes cada item do histórico.

- Compartilhamento  
  Permite compartilhar as informações (IP e detalhes) com outros aplicativos.

- Interface simples e responsiva  
  Layout limpo, focado em leitura rápida das informações de rede.

---

## Download

Para baixar a versão compilada (APK):

[Baixar APK – GitHub Releases](https://github.com/kadupoa/IP-Viewer/releases/latest)

Acesse o link acima e faça o download do arquivo `app-release.apk`.

---

## Instalação a partir do código-fonte

### Pré-requisitos

- [Flutter](https://flutter.dev) instalado
- SDK Android configurado
- Emulador ou dispositivo físico conectado

### Passos

# Clonar Conta
git clone https://github.com/kadupoa/IP-Viewer.git

cd IP-Viewer 

# Instalar dependências
flutter pub get

# Executar em modo debug
flutter run

--- 

## Utilizados:

Linguagem: Dart

Framework: Flutter

Plataforma alvo: Android

Gerenciamento de dependências: pubspec.yaml

Acesso a rede e informações de conexão: pacotes Flutter (ex.: HTTP / network_info, etc.)

Persistência local: SQLite / banco local para histórico de consultas




