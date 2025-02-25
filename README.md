# iQuiz

iQuiz é um aplicativo de quiz desenvolvido em Swift para iOS. O aplicativo permite que os usuários respondam a perguntas de múltipla escolha e vejam seu desempenho ao final do quiz.

## Funcionalidades

- Exibir uma pergunta de múltipla escolha
- Verificar se a resposta do usuário está correta
- Atualizar a pontuação do usuário
- Navegar para a tela de desempenho ao final do quiz

## Estrutura do Projeto

- `ViewController/QuestaoViewController.swift`: Controlador que gerencia a exibição das questões e a interação do usuário.
- `ViewController/DesempenhoViewController.swift`: Controlador que exibe o desempenho do usuário ao final do quiz.
- `Models/Questao.swift`: Modelo que representa uma questão do quiz.

## Como Executar

1. Certifique-se de ter o Xcode instalado em sua máquina. Para mais informações, consulte a [documentação do Xcode](https://developer.apple.com/xcode/).

2. Clone este repositório:

   ```sh
   git clone <https://github.com/Pedro-Santilli/iOS_app_iquiz>
3. Abra o projeto no Xcode:
   ```sh
   open iQuiz.xcodeproj
4. Selecione o dispositivo ou simulador desejado e execute o aplicativo:
   ```sh
   cmd + R
## Uso
O aplicativo exibirá uma pergunta de múltipla escolha.
O usuário deve selecionar uma das opções de resposta.
A cor do botão mudará para verde se a resposta estiver correta e para vermelho se estiver incorreta.
Após um breve intervalo, a próxima pergunta será exibida.
Ao final do quiz, o usuário será redirecionado para a tela de desempenho, onde poderá ver sua pontuação.
