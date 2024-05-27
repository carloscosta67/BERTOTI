Exercicio 01  
Texto 01 - 
Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming. 

No Google, às vezes dizemos: “Engenharia de software é programação integrada ao longo do tempo”. A programação é certamente uma parte significativa da engenharia de software: afinal, a programação é como você gera um novo software. Se você aceitar essa distinção, também ficará claro que talvez seja necessário delinear entre tarefas de programação (desenvolvimento) e tarefas de engenharia de software (desenvolvimento, modificação, manutenção). A adição de tempo acrescenta uma nova dimensão importante à programação. Cubos não são quadrados, distância não é velocidade. Engenharia de software não é programação.

Texto 02  - 
We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play. On a software engineering project, engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth.

Vemos três diferenças críticas entre programação e engenharia de software: tempo, escala e as compensações em jogo. Em um projeto de engenharia de software, os engenheiros precisam estar mais preocupados com a passagem do tempo e com a eventual necessidade de mudanças. Numa organização de engenharia de software, precisamos de estar mais preocupados com a escala e a eficiência, tanto para o software que produzimos como para a organização que o produz. Finalmente, como engenheiros de software, somos solicitados a tomar decisões mais complexas com resultados de maior risco, muitas vezes baseados em estimativas imprecisas de tempo e crescimento.

Resposta :
Pelo que eu entendi engenharia de software é o setor que envolve todo um processo de planejamento, desenvolvimento, teste e manutenção de softwares de forma eficiente e confiável,criando Softwares bem projetados e desenvolvidos são mais confiáveis e seguros, no qual podem ajudar as empresas a serem mais produtivas e competitivas.

Exercicio 2  

Citar 03 exemplos de trade-offs 
resposta 
A) Python e JavA 
Python - Vantagen - Estrutura simples e intuitiva, permitindo um desenvolvimento mais ágil.
         desvantagen- o que pode resultar em menor velocidade de execução em comparação com linguagens compiladas.
Java - Vantagen - Compilado, proporcionando maior performance em tempo de execução.
       Desvantagen - Curva de aprendizado mais íngreme para iniciantes em programação.

B) linux x Windows 
   Linux - O Linux oferece maior segurança, personalização e flexibilidade 
   Windows - oferece maior compatibilidade de software, facilidade de uso e suporte oficia

C) VS Code   NetBeans
   Vs Code - Mercado com uma ampla gama de extensões disponíveis para várias linguagens de programação, frameworks e funcionalidades.
   NetBeans - Menor número de extensões disponíveis em comparação ao VS Code.
             foco principal em extensões para desenvolvimento Java e tecnologias relacionadas.
             

Exercicio 3
Para cada arquitetura, escolha 2 requisitos não funcionais (um bom e outro ruim) e explique escolhendo um sistema para ser desenvolvido seguindo essa arquitetura

Arquitetura, slides 24 - 29  ( trade-offs ) 
Slide 24
Estilo de Arquitetura em camadas  ( sao usados em aplicações do dia a dia ) ( são base da internet, navegador).
Estilo de Arquitetura em camadas, também conhecida como Arquitetura em Camadas, é um padrão de design de software que organiza um sistema em camadas distintas e independentes.
Ponto positivo: Alta simplicidade, barato e confiável.
Ponto Negativo: Dificil de escalar , menos tolerancia a erros, devido ao alto isolamento, visto que uma 
camada só pode conversar com a camada acima e abaixo. 
Analise : 
Usado em protocolos de rede , devido á segurança no processo, Cada camada possui um conjunto de funcionalidades coesas e bem delimitadas, facilitando o desenvolvimento, teste e manutenção do código.
novas camadas acrescentam mais funcionalidades, acrescentando generalidade ao sistema, à custa de perder (em cada nível) um certo grau de desempenho
 
Slide 25
Estilo de arquitetura de ppeline: ( é usado em aplicação ,chek out, dados de pgto )
Ponto Positivo: Modularidade, simplicidade, barato, relativamente fácil de testar e confiavel.
Ponto Negativo: Dificil de escalar, menos tolerancia a erros devido ao alto isolamento, visto que uma camada só pode conversar com a camada acima e abaixo.
Analise:
Esse estilo de arquitetura é extensível e modular, pois novos filtros podem ser facilmente adicionados, substituídos e excluídos do sistema.
Por ser um estilo de arquitetura monolítica, as implantações e os testes são difíceis. Mesmo mudanças simples exigem que todo o sistema seja totalmente testado e reimplantado.

Slide 26
Estilo de arquitetura Microkernel (Arquitetura em camadas)( é usado em sistema operacional, um sistema principal e diversos pluguins.
Ponto Positivo: Modularidade, custo, segurança, simplicidade e testabilidade.
Ponto Negativo: Complexidade, tolerancia a erros.
Analise:
Sistema Operacional e embarcado, devido ao gerenciamento de memoria e á comunicação entre os processos principais e secundários.O sistema é dividido em módulos independentes, o que facilita o desenvolvimento, teste e manutenção.Os módulos são executados com privilégios mínimos, o que limita o dano que podem causar ao sistema.

Slide 27
Estilo de arquitetura baseada em serviços: ( sao usados em aplicações do dia a dia )
Ponto Positivo: Reutilização da solução criada e flexibilidade para mudanças.
Ponto Negativo: Complexidade na implementação, garantindo uma interação plena, a performance da arquitetura orientada a serviços dependentes do servidor em que os modulos se encontram hospedados, em conjunto com a disponibilidade da rede, causar lentidão e falahas no desempenho dos softwares instalados.
Analise:
Comercio eletronico, flexibilidade, confiabilidade e facil de dar manutenção.permite que as empresas desenvolvam e implantem aplicativos com mais rapidez, respondendo rapidamente às mudanças nas necessidades do mercado e da tecnologia.facilita a integração de sistemas díspares, permitindo que diferentes aplicações e bancos de dados comuniquem-se e compartilhem dados de forma transparente.

Slide 28 
Estilo de arquitetura orientada a eventos ( são usados no sistema do pix , e intregar serviços )
Ponto Positivo: Evolução de novas funcionalidades, tolerancia a falahs, performance e escalabilidade.
Ponto Negativo: Complexidade e testabilidade.
Analise:
Usado em sistemas de jogos online, devido a necessidade de atualização de status para todos os jogadores.Tambem usado na internet das coisas, sistemade sensores, na qual após disparo do sinal (trigger) uma lógica é feita com a entrada, para gerar uma saída, como a velocidade ou um sinal eletrico, permite que os sistemas processem eventos de forma assíncrona e em paralelo, o que aumenta a agilidade e a escalabilidade.permite que os sistemas sejam facilmente adaptados a novas necessidades e requisitos, pois os eventos podem ser facilmente adicionados, modificados ou removidos. 

Slide 29
Arquitetura de Microsserviços  
Ponto Positivo: Escabilidade, flexibilidadfe para lidar com sistemas mais complexos e padrões de design e implementação berm definidos.
Ponto Negativo: Complexidade de manutenção, por conta da sua natureza, um sistema baseado em micro serviços acaba tendo certas limitações em relação ao que cada serviço tem e envolve de informação, podendo ser de alta complexidade, adicionando uma nova funcionalidade.
Analise:
Amazon prime, devido á necessidade de estar constantemente alterando funcionalidades, para um grande numero de clientes. Se um microsserviço falhar, os outros serviços não serão afetados, o que torna o aplicativo mais resiliente a falhas, os microsserviços são mais fáceis de entender, depurar e manter do que um único aplicativo monolítico e podem ser reutilizados em diferentes aplicações, o que reduz o tempo e o custo de desenvolvimento.

Exercicio 4 
Defina sua arquitetura debatendo compensações com os requisitos não funcionais comentados em aula:
A arquitetura escolhida para ser usada em sistema para uma Adega de bebidas foi o :  “Estilo de arquitetura em camadas”, é um sistema simples de fácil manutenção aumentando a produtividade e diminuindo a complexidade e de baixo custo 

 







