#Análise de Tarefas

-------------------------------------------------

##O que é uma análise de tarefas e sua utilidade?

* A análise de tarefas é uma das ferramentas que você pode usar durante a fase de definição do processo do UX Design. O entregável mais frequente de uma análise de tarefas é um diagrama que explica as etapas que um usuário deve realizar para alcançar um certo objetivo.

* A análise de tarefas pode ser útil útil para o entendimento de algumas coisas, como:

	* Quais são os objetivos dos seus usuários e o que eles estão tentando alcançar;

	* Quais são os passos que seus usuários realizam atualmente para alcançar seus objetivos, o que é útil para ver como eles seguem as instruções ou criam maneiras de contornar problemas nas práticas atuais;

	* Qual é a influência do ambiente físico nos usuários ao tentar atingir uma meta.

* Um entendimento claro dos fatores acima irá ajudá-lo a definir e enquadrar os problemas dos usuários, para que você possa criar maneiras de ajudar a melhorar a experiência de uso.
<br>

##O que é um diagrama HTA?

* Envolve quebrar uma tarefa em subtarefas, e estas em sub-sub-tarefas, e assim sucessivamente. Estas são agrupadas em planos que especificam como as tarefas são executadas na prática.

* HTA foca nas ações físicas e observáveis, e inclui ações não relacionadas ao software ou ao dispositivo de interação

* Começa com um objetivo do usuário, que é examinado e as principais tarefas para atingir tal objetivo são identificadas

* Então as tarefas são divididas em sub-tarefas
<br>

###**Análise de tarefas 1**

![](https://raw.githubusercontent.com/Interacao-Humano-Computador/2020.2-Grupo5/main/Imagens/hta.jpeg)
<br>

##O que é um CTT?

O modelo de árvores de tarefas concorrentes (ConcurTaskTrees – CTT) foi criado para auxiliar a avaliação e o design e avaliação de IHC (Paternò, 2000). Nesse modelo, existem quatro tipos de tarefas:

* tarefas do usuário, realizadas fora do sistema;

* tarefas do sistema, em que o sistema realiza um processamentos em interagir com o usuário;

* tarefas interativas, em que ocorrem os diálogos usuário–sistema;

* tarefas abstratas, que não são tarefas em si, mas sim uma representação de uma composição de tarefas que auxilie a decomposição.

Assim como na análise hierárquica de tarefas, os diferentes níveis hierárquicos devem ser lidos como “para considerar T1 como tendo sido realizada, as tarefas T2 e T3 de- vem ter sido realizadas”.

![](https://raw.githubusercontent.com/Interacao-Humano-Computador/2020.2-Grupo5/main/Imagens/ctt1.png)

Além da hierarquia, o CTT permite representar diversas relações entre as tarefas, que aumentam a expressividade da notação. Os significados dssas relações são os seguintes:

* ativação: T1 >> T2 significa que a segunda tarefa (T2) só pode iniciar após a primeira tarefa (T1) terminar;
* ativação com passagem de informação: T1 [ ] >> T2 especifica que, além de T2 só poder ser iniciada após T1, a informação produzida por T1 é passada para T2;
* escolha (tarefas alternativas): T1 [] T2 especifica duas tarefas que estejam ha- bilitadas num momento, mas que, uma vez que uma delas é iniciada, a outra é desabilitada;
* tarefas concorrentes: T1 ||| T2 especifica que as tarefas podem ser realizadas em qualquer ordem ou ao mesmo tempo;
* tarefas concorrentes e comunicantes: T1 | [ ] | T2 especifica que, além de as ta- refas poderem ser realizadas em qualquer ordem ou ao mesmo tempo, elas podem trocar informações;
* tarefas independentes: T1 |=| T2 especifica que as tarefas podem ser realiza- das em qualquer ordem, mas quando uma delas é iniciada, precisa terminar para que a outra possa ser iniciada;
* desativação: T1 [> T2 especifica que T1 é completamente interrompida por T2;
* suspensão/retomada: T1 |> T2 especifica que T1 pode ser interrompida por T2 e é retomada do ponto em que parou assim que T2 terminar.

![](https://raw.githubusercontent.com/Interacao-Humano-Computador/2020.2-Grupo5/main/Imagens/ctt2.png)

A Figura abaixo apresenta um exemplo de modelo de tarefas representado em CTT para um objetivo de marcar um compromisso em uma agenda.

![](https://raw.githubusercontent.com/Interacao-Humano-Computador/2020.2-Grupo5/main/Imagens/ctt3.png)


Dentre as vantagens do CTT com relação a outros modelos de tarefas, destacamos a possibilidade do registro explícito das relações entre as tarefas. Observamos que, uma vez que há tarefas interativas, do sistema e do usuário, o CTT vai além da aná- lise de tarefas tradicional para representar uma solução de design da interação. Uma desvantagem com relação a modelos especificamente projetados para a interação é a ausência de elementos destinados à representação de mecanismos de prevenção e tratamento de erros na interação usuário–sistema


### Tabela de versionamento

  Data    | Versão      | Descrição              | Responsável
--------  | --------    | -------------          | --------
07/04/21  | 1.0         | Elaboração da Análise  | Henrique
27/05/21  | 1.1         | CTT					 | Henrique

#### Referências:

* Livro: BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. 1ª edição, Rio de Janeiro: Elsevier, 2010.

* Site oficial da Berkshire Hathaway. Disponível em <https://www.berkshirehathaway.com/> acesso em 7 de abril 2021.

* Site DesignR. Disponível em <http://designr.com.br/como-melhorar-experiencia-do-usuario-com-analise-de-tarefas/>
acesso em 07 de abril 2021.
