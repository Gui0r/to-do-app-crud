# Lista de Tarefas - Flutter App

Um aplicativo simples de lista de tarefas (To-Do List) desenvolvido em Flutter para dispositivos móveis.

## 📱 Funcionalidades

- ✅ **Adicionar tarefas**: Crie novas tarefas com um título personalizado
- ✅ **Marcar como concluída**: Marque tarefas como concluídas ou não concluídas
- ✅ **Remover tarefas**: Delete tarefas que não são mais necessárias
- 💾 **Persistência de dados**: As tarefas são salvas localmente no dispositivo
- 🎨 **Interface moderna**: Design limpo e intuitivo com Material Design

## 🛠️ Tecnologias Utilizadas

- **Flutter 3.35.4**: Framework para desenvolvimento mobile
- **Dart 3.9.2**: Linguagem de programação
- **SharedPreferences**: Para persistência local de dados
- **Material Design**: Para interface do usuário

## 📁 Estrutura do Projeto

```
lib/
├── main.dart                 # Arquivo principal da aplicação
├── models/
│   └── task.dart            # Modelo de dados para as tarefas
├── screens/
│   └── home_screen.dart     # Tela principal do aplicativo
└── widgets/
    ├── task_item.dart       # Widget para exibir cada tarefa
    └── add_task_dialog.dart # Diálogo para adicionar novas tarefas
```

## 🚀 Como Executar

### Pré-requisitos

1. **Flutter SDK**: Instale o Flutter seguindo as instruções em [flutter.dev](https://flutter.dev/docs/get-started/install)
2. **Android Studio** ou **VS Code** com extensões do Flutter
3. **Dispositivo Android/iOS** ou **Emulador** configurado

### Passos para Execução

1. **Clone ou baixe o projeto**
   ```bash
   git clone <seu-repositorio>
   cd todo_app
   ```

2. **Instale as dependências**
   ```bash
   flutter pub get
   ```

3. **Execute o aplicativo**
   ```bash
   flutter run
   ```

### Comandos Úteis

- **Verificar problemas no código**: `flutter analyze`
- **Executar testes**: `flutter test`
- **Limpar cache**: `flutter clean`
- **Verificar dispositivos conectados**: `flutter devices`

## 📱 Como Usar o App

1. **Adicionar Tarefa**: Toque no botão "+" no canto inferior direito
2. **Marcar como Concluída**: Toque no círculo ao lado da tarefa
3. **Remover Tarefa**: Toque no ícone de lixeira e confirme a remoção
4. **Visualizar Tarefas**: Todas as tarefas são listadas na tela principal

## 🎯 Requisitos Atendidos

✅ O usuário pode adicionar uma nova tarefa  
✅ O usuário pode marcar uma tarefa como concluída  
✅ O usuário pode remover uma tarefa  
✅ As tarefas são persistidas localmente no dispositivo  

## 🔧 Dependências

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  shared_preferences: ^2.2.2
```

## 📝 Notas de Desenvolvimento

- O aplicativo utiliza `SharedPreferences` para salvar as tarefas localmente
- As tarefas são armazenadas em formato JSON
- A interface segue as diretrizes do Material Design 3
- O código está organizado seguindo boas práticas do Flutter
- Todos os testes passam sem erros

## 👨‍💻 Autor

Desenvolvido como trabalho acadêmico individual.

## 📄 Licença

Este projeto é para fins educacionais.
