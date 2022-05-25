Olá, eu sou o Leonardo Sartorello, instrutor de DevOps na Alura e hoje vou trazer para vocês uma novidade: o primeiro challenge de DevOps.

Os challenges são desafios que vamos propor para vocês testarem seus conhecimentos e sentirem como é o cotidiano de uma pessoa que está trabalhando na área de DevOps em uma empresa.

Vamos dar uma olhada no site da <a href="https://www.alura.com.br/challenges"> Alura Challenges </a>, pois já tivemos alguns challenges anteriores, como, por exemplo, o de Back-End, de Front-End, UX, BI e assim por diante. 

Esse vai ser o nosso primeiro challenge de DevOps. O que vamos aprender nele?

Vamos dar uma olhada em *containers docker*, provedor de cloud, redes, um pouco de CI/CD, entre outros temas. Então, se você tem interesse nesses temas e já chegou a estudar um pouco, te convido para o challenge.

Durante nosso challenge utilizaremos duas ferramentas diferentes. A primeira é o Trello, que vai ser disponibilizado um por semana para guiá-los no trajeto, com algumas dicas de tarefas a serem cumpridas. 

A segunda ferramenta é o Discord, onde você vai poder se juntar com outras pessoas para estudar, montar grupos de estudos e tirar dúvidas. 

O projeto está em nosso Trello, no card "Sobre o desafio". Precisaremos fazer o *deploy* de uma aplicação na nuvem através de um *container docker*, e para isso teremos que desenvolver um *docker file*, colocar esse container em um repositório e, depois, colocar esse projeto em um provedor de *cloud*.  Por fim, vamos automatizar todo esse processo usando rotinas de CI/CD. 

Teremos quatro semanas para desenvolver esse projeto, sendo as 3 primeiras com algumas tarefas diferentes e a quarta e última semana focada em polir o projeto ou completar alguma tarefa não cumprida anteriormente.

O Trello vai ser dividido em algumas colunas. A primeira,"Pronto para iniciar", é onde temos as tarefas da semana. 

Logo após temos a coluna "Desenvolvendo", onde você vai pode colocar, por exemplo, a primeira tarefa enquanto estiver trabalhando nessa função. Caso tenha travado  por algum motivo, não precisa perder muito tempo nela, você pode arrastar o card para a coluna "Pausado" e começar outra função. 

Ao terminar uma função, basta arrastar o card para a coluna "Concluído". Se achar a solução para o problema que estava ocorrendo, pode voltar o card para a coluna "Desenvolvendo" e, ao terminar, movê-lo para "Concluído". É assim que funciona.

Você vai utilizar o Trello para se organizar, e ele não será usado para nenhuma avaliação. Se você não quiser usar o Trello, não é obrigatório.

Mas como você usar o Trello? Ao entrar no link que vai ser disponibilizado, não será possível arrastar os cards como estou fazendo no vídeo. Será necessário copiar esse Trello para sua conta pessoal.

No canto superior direito, você selecionará a opção "Mostrar menu > Mais" e depois "Copiar quadro". Na aba que se abrirá, basta dar um nome para esse quadro - por exemplo, "semana 1" - e, em seguida, clicar no botão "Criar" para copiar o quadro para a sua conta. Agora, com o quadro copiado, você vai conseguir arrastar os cards como preferir.

Vamos dar uma olhada no nosso "Para saber mais: planos de estudos". Começaremos com um plano de estudos focado em ***Docker***, já que esse vai ser o tema principal dessa semana. Ele consiste em como criar, gerir e subir *containers docker*. 

Na primeira semana o objetivo será se familiarizar com a aplicação, e as instruções estão no card "Familiarizando com a aplicação" da coluna "Backlog".

Vamos disponibilizar uma aplicação e você terá que subi-la pelo menos uma vez, analisar a interface, o que ela responde, quais portas ela utiliza e assim por diante. 

Feito isso, podemos começar a criar o nosso container, onde vamos incluir a aplicação. Nesse caso, indicamos que você use o Docker mover a sua aplicação para a forma de container. 

Entretanto, não é necessário usar o Docker. Você pode utilizar outros tipos de containers, como o containers Podman ou OCI (*Open Container Initiative*, ou em português "Iniciativa de containers abertos"). Nós indicamos o Docker por ser o que possui mais conteúdo disponível para você poder estudar e te ajudar caso tenha alguma dúvida, mas fica à sua escolha. 

Em seguida, teremos que testar o container que criamos (como orienta o card "Testando o Container"). Vamos subir o container localmente na nossa máquina para verificarmos se a aplicação foi iniciada corretamente, se a conexão com o banco de dados está funcionando e se a aplicação está respondendo às requisições, ou se erramos algo, como as configurações de porta ou algo nesse sentido que pode gerar algum problema.

Por fim, é interessante salvar o container que criamos em um repositório (como indicado no cartão "Salvar o container em um repositório"). Indicamos a utilização do Docker Hub, mas você é livre para usar algum outro repositório da sua preferência.

Esse vai ser o nosso primeiro challenge de DevOps! Convido você para participar dessa experiência, como se você estivesse colocando em prática o dia a dia em uma empresa. Vamos lá?

