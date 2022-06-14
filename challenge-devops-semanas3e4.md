Boas-vindas a mais uma semana do **Challenge de DevOps**. Primeiro, gostaria de te dar os parabéns por concluir as tarefas da semana 1 e 2. Já fizemos bastante coisa, mas ainda não acabou, pois temos a terceira semana com alguns afazeres para você se desafiar.

O tema principal da terceira semana vai ser as **rotinas de CI/CD: Integração Contínua e Entrega Contínua**. Vamos começar pelo card "Para saber mais" do Trello, em que se encontra os planos de estudos de duas ferramentas: **Jenkins** e **GitLab CI**. 

Existem outras ferramentas que realizam a parte de CI/CD, por exemplo, o **Github Actions** e o **Circle CI**. Mas separamos essas duas por termos mais conteúdos disponíveis sobre elas, contudo sinta-se à vontade para escolher o seu recurso.

Inclusive, escolher a ferramenta é o primeiro passo para o desafio dessa semana. É importante estar ciente que, ao optar por uma ferramenta específica para desenvolver o seu projeto, é difícil mover o que fez para outra. Como, por exemplo, do Github Actions para o GitLab CI, isso ocorre porque elas não utilizam a mesma linguagem. 

O ideal é optar por uma que tenhamos familiaridade, ou caso não haja com nenhuma, escolhemos uma que já possua bastante conteúdo disponível. O Jenkins e o GitLab CI são boas opções por isso. Mencionamos no card "Escolhendo uma ferramenta" o **Azure CI**, que também é uma possibilidade.

A próxima tarefa está no card "Criando a rotina para a Integração Contínua (CI)". Essa rotina vai precisar pegar o código e executar verificações. Por exemplo, se tiver um teste automatizado, vai ter que executar esses testes e, em seguida, criar o *container docker*. 

Uma dica é que a rotina de CI não necessariamente precisa ser a mais rápida, não é preciso focar em desempenho, cortar linha ou algo nesse sentido, mas ela precisa ser fácil de adicionar novas funcionalidades.

Por exemplo, em uma rotina que faz testes automatizados unitários e cria o seu *container docker*, é fundamental que seja fácil adicionar outros tipos de testes nela ou outras funcionalidades dentro dessa rotina. Isto é, precisa ser **customizável**. 

A terceira parte está no card "Criando a rotina de entre contínua (CD)", em que pegaremos o *container* que saiu da sua rotina de CI e faremos o *deploy* dele em um provedor de *cloud* (“provedor de nuvem”). As rotinas de CI geralmente podem ter alguma vulnerabilidade referente à segurança, por isso o ideal é **não** deixar senhas e chaves dos provedores de nuvem abertas na rotina de CD.

A maioria das ferramentas contém um tipo de segredo em que podemos colocar as senhas e chaves para utilizar nas rotinas sempre que elas aparecerem, assim ninguém terá acesso quando estiver olhando o repositório. 

Com tudo isso pronto, podemos analisar a aplicação dentro do provedor e verificar se está respondendo às requisições e, de novo, se não implementou nenhum tipo de *bug* enquanto estava subindo essa aplicação.

Por fim, novamente, não iremos conseguir mover os cards no quadro que vamos disponibilizar. Portanto, será necessário copiar esse quadro para a sua conta pessoal. No canto superior direito, você selecionará a opção “Mostrar menu > Mais” e em seguida “Copiar quadro”.

Esse é o conteúdo da nossa terceira semana, espero que você consiga implementar tudo o que foi proposto. Qualquer dúvida, basta nos enviar mensagem no Discord que vamos te ajudar ou até mesmo alguém comunidade conseguirá te orientar.

Bom Challenge, bons estudos e boa sorte!
