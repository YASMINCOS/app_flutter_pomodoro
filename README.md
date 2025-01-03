# Pomodoro App

Este é um aplicativo simples de Pomodoro desenvolvido em Flutter. O método Pomodoro ajuda a melhorar o foco e a produtividade, dividindo o tempo de trabalho em intervalos com pausas regulares.

## Funcionalidades

- Defina o tempo para ciclos de trabalho e pausas.
- Controle simples para iniciar, pausar e reiniciar o temporizador.
- Estado gerenciado utilizando MobX para uma experiência reativa e fluida.

## Tecnologias Utilizadas

- **Flutter**: Framework para desenvolvimento multiplataforma.
- **MobX**: Gerenciamento de estado reativo.
- **Build Runner**: Ferramenta para geração de código.

## O que é o MobX?

MobX é uma biblioteca para gerenciamento de estado reativo que facilita a criação de interfaces de usuário dinâmicas e responsivas. Inspirado em conceitos de programação funcional e reativa, o MobX permite que os estados do aplicativo sejam sincronizados automaticamente com a interface do usuário. Suas principais características incluem:

- **Observables**: Representam os estados que podem mudar no aplicativo.
- **Actions**: São responsáveis por modificar os estados observáveis.
- **Reactions**: Automatizam atualizações na interface do usuário ou em outras partes do sistema com base nas mudanças de estado.

Com o MobX, o fluxo de dados no aplicativo é previsível e fácil de entender, o que reduz bugs e facilita a manutenção do código.

## Dependências

As seguintes bibliotecas foram utilizadas no projeto:

```yaml
dependencies:
  flutter:
    sdk: flutter
  mobx: ^2.1.2

dev_dependencies:
  flutter_test:
    sdk: flutter
  build_runner: ^2.4.14
  mobx_codegen: ^2.7.0
```

## Configuração e Execução

Siga estas etapas para configurar e executar o aplicativo:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as dependências:**

   ```bash
   flutter pub get
   ```

3. **Gere os arquivos necessários para o MobX:**

   ```bash
   flutter pub run build_runner build --delete-conflicting-outputs
   ```

4. **Execute o aplicativo:**

   ```bash
   flutter run
   ```

## Estrutura do Projeto

Abaixo está uma visão geral dos diretórios principais no projeto:

```
lib/
├── main.dart           # Ponto de entrada do aplicativo
├── stores/             # Stores do MobX para gerenciar o estado
├── widgets/            # Componentes personalizados
└── utils/              # Funções e helpers reutilizáveis
```

## Como Contribuir

1. Faça um fork do projeto.
2. Crie um branch para sua feature ou correção de bug:

   ```bash
   git checkout -b minha-feature
   ```

3. Commit suas alterações:

   ```bash
   git commit -m "Adiciona minha nova feature"
   ```

4. Faça o push para o branch:

   ```bash
   git push origin minha-feature
   ```

5. Abra um Pull Request.


