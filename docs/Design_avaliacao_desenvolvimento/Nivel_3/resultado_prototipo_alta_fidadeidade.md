# Resultados da Avaliação Protótipo de alta-fidelidade

-------------------------------------------------
## Introdução
<br>

O protótipo de alta-fidelidade se aproxima muito ao produto final, pois são feitos com materiais que se espera que estejam presentes no mesmo. Por isso, normalmente são muito trabalhosos, demorados e caros.  

Na confecção do protótipo de alta fidelidade de um software é necessário utilizar outro software, para esse projeto usamos a ferramenta figma.


## Objetivo da Avaliação
<br>

O objetivo é avaliar a apropriação de tecnologia pelos usuários, as ideias e alternativas de design, a conformidade com um padrão e problemas na interação e na interface.

## Metodologia Empregada
<br>

Para avaliar o prototipo de alta-fidelidade nós utilizaremos a avaliação por inspeção, mais especificamente, a avaliação heurística. Esse método de avaliação orienta os avaliadores a inspecionar sistematicamente a interface em busca de problemas que prejudiquem a usabilidade.  A avaliação heurística possui como base um conjunto de diretrizes de usabilidade, que descrevem características desejáveis da interação e da interface, chamadas por Nielsen de heurísticas.

## Dados coletados / Interpretação
<br>

Nielsen recomenda que uma avaliação heurística envolva de três a cinco avaliadores. Com isso, foram selecionados 3 (três) avaliadores, sendo todos eles graduandos de Engenharia de Software na Universidade de Brasília (UnB), com idade média de 22 anos e integrantes do grupo do presente projeto. Dentre os avaliadores, o Henrique, se encaixa no perfil de usuário do site. Cada um produziu uma lista com os problemas encontrados, indicando para cada um:

* local onde ocorre;
* descrição do problema; 
* diretriz(es) violada(s);
* severidade do problema;
* sugestões de solução.

#### Avaliador 1(Antonio Ruan):
* Problema 1:
    * Local onde ocorre: No cabeçalho da página.
    * Descrição do problema: Não possui nenhuma indicação em que página o usuário está, podendo deixar usuário confuso se perguntando se realmente entrou na tela correta.
    * Diretriz violada: Visibilidade do estado do sistema, prevenção de erros.
    * Severidade do problema: Problema Grande.
    * Sugestão de solução: Destacar no cabeçalho a aba que o usuário está navegando.
* Problema 2:
    * Local onde ocorre: Por todo o site
    * Descrição do problema: Baixo contraste entre o os textos e o fundo do site quanto está ativado o modo escuro, podendo causar dificuldades para ler o conteúdo do site.
    * Diretriz violada: flexibilidade e eficiência de uso
    * Severidade do problema: Problema Grande
    * Sugestão de solução: Mudança na cor dos textos quando for ativado o modo escuro para que o contraste seja aumentado.
* Problema 3:
    * Local onde ocorre: Por todo o site
    * Descrição do problema: Falta alguma funcionalidade para retornar onde o usuário estava, não dando uma possibilidade para o usuário voltar para onde ele estava caso clique, sem querer, para ir a outra página.
    * Diretriz violada: prevenção de erros
    * Severidade do problema: Problema Pequeno
    * Sugestão de solução: Implementação de botões para voltar e prosseguir na barra de navegação


#### Avaliador 2(Nathan Fernandes):
* Problema 1:
    * Local onde ocorre: No site todo
    * Descrição do problema: Não oferece uma parte de ajuda na documentação do site.
    * Diretriz violada: ajuda e documentação
    * Severidade do problema: Problema pequeno.
    * Sugestão de solução: Criar uma aba de instrução do site.

#### Avaliador 3(Henrique Amorim):
* Problema 1:
    * Local onde ocorre: Na barra de navegação.
    * Descrição do problema: O problema encontrado se refere a falta de identificação da página atual no site
    * Diretriz violada: visibilidade do estado do sistema.
    * Severidade do problema: Não é um problema muito complexo, possui severidade pequena, porém atrapalha a experiência do usuário.
    * Sugestão de solução:  implementação de um indicador de página atual, como por exemplo aumentar o tamanho ou mudar a cor do item respectivo do menu.
* Problema 2:
    * Local onde ocorre: Página de releases.
    * Descrição do problema: Não se tem acesso a informações relevantes sobre uma determinada release sem que você seja redirecionado para outra página mais específica.
    * Diretriz violada: flexibilidade e eficiência de uso
    * Severidade do problema: Problema possui severidade grande, pois é um tópico relevante para muitos usuários.
    * Sugestão de solução: Adicionar mais informações relevantes na própria página sobre cada release selecionada, sem que seja necessário clicar em uma release específica.

<br>

## Análise dos dados
<br>
O relato da interpretação e análise dos dados serão divididos nos seguintes tópicos:

* apropriação da tecnologia pelos usuários:
Os usuários interagem com facilidade com o site e são motivados a explorarem novas funcionalidades no site.
    
* ideias e alternativas de design:
A principal alternativa de design apontada pelos avaliadores foi acrescentar uma parte de ajuda ao usuário para que ele entenda o que cada página do site oferece.

* conformidade  com um padrão:
O site segue uma conformidade com um padrão, o padrão de acessibilidade seguido é de acordo com o W3C.

<br>

## Problemas Encontrados

<br>
De acordo com todos os dados coletados, os problemas de maior para menor severidade são, respectivamente:

* Falta de indicação na barra de navegação em qual tela o usuário está;
* Sem acesso a informações relevantes sobre uma determinada release dentro do próprio site;
* Baixo contraste entre o os textos e o fundo do site quanto está;
* ativado o modo escuro;
* Falta alguma funcionalidade para retornar onde o usuário estava;
* Falta alguma parte de ajuda na documentação do site.
<br>

## Ajustes a serem feitos

<br>
Os principais ajustes a serem feitos giram em torno dos problemas relatados, que seriam:

* Destacar na barra de navegação a página que está sendo exibida;
* Adicionar mais informações  relevantes na própria página sobre cada release selecionada;
* Alterar a cor do texto para aumentar o contraste;
* Inserir botão de back e next;
* Inserir alguma ajuda para o usuário na documentação do site.
<br>

## Referências
<br>

* Livro: BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. 1ª edição, Rio de Janeiro: Elsevier, 2010.

* Site oficial da Berkshire Hathaway. Disponível em <https://www.berkshirehathaway.com/> acesso em 7 de abril 2021.
<br>
## Versionamento

Tabela de versionamento

Data     |Versão              | Descrição                             | Responsável
-------- |          --------  |              -------------            | --------
28/04    |        1.0         | Introdução, objetivos                 | Carla
28/04    |        1.0         | Metodologia e dados coletados         | Carla, Felipe
29/04    |        1.1         | Dados coletados                       | Nathan, Henrique e Carla
29/04    |        1.1         | Problemas e Ajustes                   | Henrique

