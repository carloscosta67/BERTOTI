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

slide 24 - Layered Architecture Style   ( sao usados em aplicações do dia a dia ) ( são base da internet, navegador, 
Layered Architecture, também conhecida como Arquitetura em Camadas, é um padrão de design de software que organiza um sistema em camadas distintas e independentes.
Podemos destacar a escalabilidade
A Layered Architecture facilita a escalabilidade do sistema, pois cada camada pode ser dimensionada separadamente,
Isso permite que o sistema suporte um maior número de usuários e um aumento na demanda sem comprometer o desempenho.
trade - offs  -  Novas camadas acrescentam mais funcionalidades, acrescentando generalidade ao sistema, à custa de perder (em cada nível) um certo grau de desempenho
 
slide 25  -  Pipeline Architecture Style ( é usado em aplicação ,chek out, dados de pgto )
Ótimo para processamento simples e unidirecional devido à simplicidade desse estilo de arquitetura.
Esse estilo de arquitetura é extensível e modular, pois novos filtros podem ser facilmente adicionados, substituídos e excluídos do sistema.
trade - offs - Por ser um estilo de arquitetura monolítica, as implantações e os testes são difíceis. Mesmo mudanças simples exigem que todo o sistema seja totalmente testado e reimplantado.

slide 26 - Microkernel Architecture Style ( é usado em sistema operacional, um sistema principal e diversos pluguins 

slide 27 Service-Based Architecture Style ( sao usados em aplicações do dia a dia )

slide 28 - Event-Driven Architecture Style ( são usados no sistema do pix , e intregar serviços )

slide 29 - Microservices Architecture 

 







