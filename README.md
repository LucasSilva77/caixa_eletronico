# Caixa eletronico

Neste projeto eu utilizei javascript para poder desenvolver mais as minhas habilidades com essa linguagem
segue o passo a passo para abrir o projeto e deixar ele rodando tranquilamente:

1- Primeiro você deve instalar o Visual Studio na sua maquina pelo seguinte link: https://code.visualstudio.com/

2- baixe também o arquivo do caixa_eletronico em sua maquina, ele ira vir compactado então certifique-se que você tenha o winrar instalado em sua maquina. (caso não tenha utilize esse link para o download: https://www.win-rar.com/start.html?&L=9 )  <br>
3- no seu visual studio code você deve baixar a extensão live server para que possa ser executado o seu codigo (no caso o caixa_eletronico) <br>
4- extraia o seu arquivo caixa_eletronico, apertando com o botão direito em cima do arquivo e clickando em Extrair aqui <br>
5- após extrair, arraste o arquivo caixa_eletronico para o visual studio  <br>
6- ao arrastar você ira paerceber que o projeto foi passado para o visual studio <br>
7- aperte na parte inferior direita do seu visual studio o seguinte botão (LIVE SERVER) <br>
8- pronto o seu navegador ira abrir e as funções iram ser exibidas com uma janelinha. <br>

# funções 


 - Saudação inicial: Ao acessar o sistema, será solicitado ao usuário que informe seu nome. Em seguida, será exibida a mensagem "Olá {Nome}, é um prazer ter você por aqui!" para recepcionar o usuário.
 
 - Validação de opção escolhida: Na função "inicio", utilizamos o escolha/caso (switch/case) para validar a opção escolhida pelo usuário no menu principal. Isso permite executar a ação correspondente à opção selecionada.

 - Restrição de saldo insuficiente: Ao realizar um saque de dinheiro, o valor restante não pode ser negativo. Se o usuário tentar sacar mais do que possui em saldo, a operação não será autorizada. Nesse caso, será exibida a mensagem "Operação não autorizada".
 
 - Validação de valor de saque: Ao efetuar um saque, o valor a ser sacado não pode ser igual ou menor que zero. Se o usuário informar um valor inválido, a operação não será autorizada e será exibida a mensagem "Operação não autorizada".

 - Visualização de extrato: Foi adicionada a opção para visualizar o extrato da conta. Algumas transações fictícias, como compras ou depósitos, foram incluídas no extrato para exemplificar seu funcionamento.

 - Transferência entre contas: Agora é possível fazer transferências entre contas. Para isso, o usuário deve informar o número da conta de destino (obrigatoriamente um número) e o valor a ser transferido. Assim como no saque, se o usuário tentar transferir mais do que possui em saldo, a operação não será autorizada e será exibida a mensagem "Operação não autorizada".

 - Validação de valor de transferência: Ao efetuar uma transferência, o valor a ser transferido não pode ser igual ou menor que zero. Se o usuário informar um valor inválido, a operação não será autorizada e será exibida a mensagem "Operação não autorizada".

 - Ordem das opções no menu principal: A ordem das opções no menu principal foi atualizada para: Saldo, Extrato, Saque, Depósito, Transferência e Sair.

 - Atualização da função de erro: A função de erro foi atualizada para contemplar as novas opções do menu principal.

 - Restrição de depósito inválido: Caso o usuário informe um valor para depósito igual ou menor que zero, a operação não será autorizada e será exibida a mensagem "Operação não autorizada".

 - Validação de senha: Para acessar o saldo, realizar saques, visualizar extrato ou fazer transferências, é necessário que o usuário informe uma senha. A senha foi definida como "3589". Ela será validada através de uma condicional.

 - Tratamento de senha incorreta: Caso a senha informada pelo usuário não seja a correta, será necessário chamar a função atual novamente para que ele possa tentar novamente.

 - Mensagem de saída: Quando o usuário escolher sair do sistema, será exibida umamensagem de agradecimento: "{Nome}, foi um prazer ter você por aqui!".

 - Instruções de Uso
Ao acessar o sistema, informe seu nome quando solicitado.

 - No menu principal, escolha a opção desejada digitando o número correspondente.

 - Para realizar saques, depósitos, transferências ou acessar o saldo ou extrato, será necessário informar a senha (3589).

 - Siga as instruções exibidas na tela para cada operação escolhida.

 - Em caso de erros, mensagens de "Operação não autorizada" serão exibidas quando as restrições mencionadas acima não forem cumpridas.

 - Ao escolher sair do sistema, será exibida uma mensagem de agradecimento.
