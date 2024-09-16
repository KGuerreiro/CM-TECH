# CM-TECH
Desafio Mobile - Gerenciador de Tarefas

Equipe Mobile

Explanação do Projeto

O projeto é um aplicativo móvel de gerenciamento de tarefas, 
desenvolvido com o objetivo de proporcionar uma interface intuitiva e funcional para usuários que desejam organizar e acompanhar suas atividades diárias. 
O aplicativo foi desenvolvido utilizando o framework Jetpack Compose para criar uma experiência de usuário moderna e responsiva, além de Retrofit para as chamadas à API.

Funcionalidades Principais

1. Tela de Login: Permite que os usuários façam login no aplicativo utilizando suas credenciais.
2. Tela de Lista de Tarefas: Exibe uma lista de tarefas do usuário, com a opção de visualizar detalhes de cada tarefa.
3. Tela de Detalhes da Tarefa: Mostra informações detalhadas sobre uma tarefa específica selecionada na tela de lista.
4. Tela de Criação/Atualização de Tarefa**: Permite que os usuários criem novas tarefas ou editem tarefas existentes.
5. Tela de Perfil do Usuário: Mostra as informações do perfil do usuário e permite a visualização de dados pessoais.

Arquitetura do Projeto

O projeto segue uma arquitetura modular organizada da seguinte forma:

src
└── main
    └── java
        └── com
            └── example
                └── challenge
                    ├── data
                    │   ├── model
                    │   │   ├── Task.kt
                    │   │   └── User.kt
                    │   └── repository
                    │       └── TaskRepository.kt
                    ├── network
                    │   └── ApiService.kt
                    ├── ui
                    │   ├── login
                    │   │   └── LoginScreen.kt
                    │   ├── tasklist
                    │   │   └── TaskListScreen.kt
                    │   ├── taskdetails
                    │   │   └── TaskDetailScreen.kt
                    │   ├── taskeditor
                    │   │   └── TaskEditorScreen.kt
                    │   └── profile
                    │       └── UserProfileScreen.kt
                    └── viewmodel
                        ├── LoginViewModel.kt
                        ├── TaskListViewModel.kt
                        ├── TaskDetailViewModel.kt
                        ├── TaskEditorViewModel.kt
                        └── UserProfileViewModel.kt

Tecnologias Utilizadas

- Jetpack Compose: Framework para construir interfaces de usuário no Android.
- Retrofit: Biblioteca para gerenciamento de chamadas à API.
- Kotlin: Linguagem de programação utilizada para o desenvolvimento.

Integrantes

- Carlos Eduardo Guedes Alcoforado - RM94787
- Cayque Pereira dos Santos - RM551353
- Kauan Guerreiro Carraro - RM99891
- Matheus Estevo Pereira Santos - RM550913 

 Instruções de Execução

1. Clone o repositório:
   
   git clone <URL_DO_REPOSITORIO>


