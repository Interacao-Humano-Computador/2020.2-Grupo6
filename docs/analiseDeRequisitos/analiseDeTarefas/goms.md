## 1. Introdução

No início, propuseram um conjunto de modelos chamado de família GOMS para analisar o desempenho de usuários competentes de sistemas computacionais, realizando tarefas dentro da sua competência e sem cometer erros. Os modelos GOMS têm se mostrado úteis para prever o desempenho, ou seja, predizer o impacto de decisões de design no desempenho competente.

## 2. O método

O GOMS é um método para descrever uma tarefa e o conhecimento do usuário sobre como realizá-la em termos de objetivos (&quot;Goals&quot;), operadores (&quot;Operators&quot;), métodos (&quot;Methods&quot;) e regras de seleção (&quot;Selection Rules&quot;). Sendo os objetivos as tarefas propriamente ditas, aquilo que o usuário deseja efetuar, os operadores as ações necessárias para atingir determinado objetivo, os métodos são um conjunto de operações, uma série de etapas, e por fim, as selecções são os diferentes modos que o usuário pode interagir com o sistema.

## 3. Motivos da Escolha

O GOMS foi adotado como nosso método de análise e decomposição de tarefas devido sua aplicabilidade em situações onde os usuários já tenham conhecimento dos métodos para a realização de tarefas, podendo ser usado tanto para prever e analisar a performance de usuários em suas realizações quanto para melhorar a eficácia em processos rotineiros.

Tudo isso o faz uma ótima escolha para o projeto, pois estamos trabalhando sobre uma plataforma já construída, e com ele podemos, por meio de uma lista de objetivos de usuário, obtermos aqueles que podem estar utilizando métodos ineficientes de interação, inconsistências e outros problemas de design.

## 4. Objetivos

- 4.1 Resolver problemas de programação

    - <span style="color:blue">GOAL 0:</span> Resolver questão

        - <span style="color:blue">GOAL 1:</span> Acessar conta pessoal

        - <span style="color:gray">METHOD 1.A:</span> Acessar com uma conta já criada

            - <span style="color:blue">GOAL 2:</span> Efetuar Login

                - <span style="color:red">OP 2.1:</span> Deslocar o mouse até o topo direito da página;

                - <span style="color:red">OP 2.2:</span> Apertar com botão esquerdo do mouse em &quot;Login&quot;;

                - <span style="color:red">OP 2.3:</span> Preencher o campo de &quot;Usuário&quot;;

                - <span style="color:red">OP 2.4:</span> Preencher o campo de &quot;Senha&quot;;

                - <span style="color:red">OP 2.5:</span> Deslocar o mouse até o botão &quot;Login&quot;;

                - <span style="color:red">OP 2.6:</span> Apertar com o botão esquerdo do mouse.

        - <span style="color:gray">METHOD 1.B:</span> Acessar sem ter conta criada

            - <span style="color:blue">GOAL 3:</span> Se cadastrar

                - <span style="color:red">OP 3.1:</span> Deslocar o mouse até o topo direito da página;

                - <span style="color:red">OP 3.2:</span> Apertar com botão esquerdo do mouse em &quot;Register&quot;;

                - <span style="color:red">OP 3.3:</span> Preencher o campo de &quot;Usuário&quot;;

                - <span style="color:red">OP 3.4:</span> Preencher o campo de &quot;Senha&quot;;

                - <span style="color:red">OP 3.5:</span> Preencher o campo para confirmar &quot;Senha&quot;;

                - <span style="color:red">OP 3.6:</span> Preencher o campo de &quot;Apelido&quot;;

                - <span style="color:red">OP 3.7:</span> Preencher o campo de &quot;Escola/Universidade&quot;;

                - <span style="color:red">OP 3.8:</span> Preencher o campo de &quot;QQ&quot;;

                - <span style="color:red">OP 3.9:</span> Preencher o campo de &quot;E-mail&quot;;

                - <span style="color:red">OP 3.10:</span> Preencher o campo de &quot;Captcha&quot;;

                - <span style="color:red">OP 3.11:</span> Deslocar o mouse até o botão &quot;Register&quot;;

                - <span style="color:red">OP 3.12:</span> Apertar com o botão esquerdo do mouse.

            - <span style="color:blue">GOAL 4:</span> Visualizar questão

                - <span style="color:red">OP 4.1:</span> Deslocar o mouse até o topo da página;

                - <span style="color:red">OP 4.2:</span> Apertar com botão esquerdo do mouse em &quot;Problems&quot;;

                - <span style="color:red">OP 4.3:</span> Selecionar um juízo específico (ou todos) em &quot;OJ&quot;;

                - <span style="color:red">OP 4.4:</span> Deslocar o mouse até o título ou número do problema a ser visualizado;

                - <span style="color:red">OP 4.5:</span> Apertar com botão esquerdo do mouse.

            - <span style="color:blue">GOAL 5:</span> Submeter resposta

                - <span style="color:red">OP 5.1:</span> Deslocar o mouse até o topo esquerdo da página;

                - <span style="color:red">OP 5.2:</span> Apertar com botão esquerdo do mouse em &quot;SUBMIT&quot;;

                - <span style="color:red">OP 5.3:</span> Deslocar o mouse até o botão &quot;Select Language&quot;.

                - <span style="color:red">OP 5.4:</span> Apertar com botão esquerdo do mouse na linguagem de programação quista;

                - <span style="color:red">OP 5.5:</span> Apertar com botão esquerdo do mouse na opção &quot;Yes&quot; ou &quot;No&quot; em &quot;Share&quot;.

                - <span style="color:red">OP 5.6:</span> Colocar código programado em &quot;Solution&quot;.

- 4.2 Participar de torneios

    - <span style="color:blue">GOAL 0:</span> Entrar no torneio

        - <span style="color:blue">GOAL 1:</span> Acessar conta pessoal

        - <span style="color:gray">METHOD 1.A:</span> Acessar com uma conta já criada

            - <span style="color:blue">GOAL 2:</span> Efetuar Login

                - <span style="color:red">OP 2.1:</span> Deslocar o mouse até o topo direito da página;

                - <span style="color:red">OP 2.2:</span> Apertar com botão esquerdo do mouse em &quot;Login&quot;;

                - <span style="color:red">OP 2.3:</span> Preencher o campo de &quot;Usuário&quot;;

                - <span style="color:red">OP 2.4:</span> Preencher o campo de &quot;Senha&quot;;

                - <span style="color:red">OP 2.5:</span> Deslocar o mouse até o botão &quot;Login&quot;;

                - <span style="color:red">OP 2.6:</span> Apertar com o botão esquerdo do mouse.

        - <span style="color:gray">METHOD 1.B:</span> Acessar sem ter conta criada

            - <span style="color:blue">GOAL 3:</span> Se cadastrar

                - <span style="color:red">OP 3.1:</span> Deslocar o mouse até o topo direito da página;

                - <span style="color:red">OP 3.2:</span> Apertar com botão esquerdo do mouse em &quot;Register&quot;;

                - <span style="color:red">OP 3.3:</span> Preencher o campo de &quot;Usuário&quot;;

                - <span style="color:red">OP 3.4:</span> Preencher o campo de &quot;Senha&quot;;

                - <span style="color:red">OP 3.5:</span> Preencher o campo para confirmar &quot;Senha&quot;;

                - <span style="color:red">OP 3.6:</span> Preencher o campo de &quot;Apelido&quot;;

                - <span style="color:red">OP 3.7:</span> Preencher o campo de &quot;Escola/Universidade&quot;;

                - <span style="color:red">OP 3.8:</span> Preencher o campo de &quot;QQ&quot;;

                - <span style="color:red">OP 3.9:</span> Preencher o campo de &quot;E-mail&quot;;

                - <span style="color:red">OP 3.10:</span> Preencher o campo de &quot;Captcha&quot;;

                - <span style="color:red">OP 3.11:</span> Deslocar o mouse até o botão &quot;Register&quot;;

                - <span style="color:red">OP 3.12:</span> Apertar com o botão esquerdo do mouse.

            - <span style="color:blue">GOAL 4:</span> Participar de um torneio

                - <span style="color:red">OP 4.1:</span> Deslocar o mouse até o botão &quot;Contest&quot;;

                - <span style="color:red">OP 4.2:</span> Apertar com o botão esquerdo do mouse;

                - <span style="color:red">OP 4.3:</span> Deslocar o mouse até o título do torneio;

                - <span style="color:red">OP 4.4:</span> Apertar com o botão esquerdo do mouse.

        - <span style="color:gray">METHOD 4.A:</span> Acessar um torneio privado.

            - <span style="color:red">OP 4.A.1:</span> Colocar &quot;Senha&quot; do torneio privado para visualizar e submeter questões.

            - <span style="color:red">OP 4.A.2:</span> Deslocar o mouse até o título dos problemas;

            - <span style="color:red">OP 4.A.3:</span> Apertar com o botão esquerdo do mouse para visualizá-las.

        - <span style="color:gray">METHOD 4.B:</span> Acessar um torneio privado.

            - <span style="color:red">OP 4.B.1:</span> Colocar &quot;Senha&quot; do torneio privado para submeter questões.

            - <span style="color:red">OP 4.B.2:</span> Deslocar o mouse até o título dos problemas;

            - <span style="color:red">OP 4.B.3:</span> Apertar com o botão esquerdo do mouse para visualizá-las.

        - <span style="color:gray">METHOD 4.C:</span> Acessar um torneio público.

            - <span style="color:red">OP 4.C.1:</span> Deslocar o mouse até o título dos problemas;

            - <span style="color:red">OP 4.C.2:</span> Apertar com o botão esquerdo do mouse para visualizá-las.

- 4.3 Visualizar status de questões submetidas

    - <span style="color:blue">GOAL 0:</span> Visualizar situação das respostas

        - <span style="color:blue">GOAL 1:</span> Encontrar submissões;

            - <span style="color:red">OP 1.1:</span> Deslocar o mouse até o topo da página;

            - <span style="color:red">OP 1.2:</span> Apertar com o botão esquerdo do mouse em &quot;Status&quot;;

            - <span style="color:red">OP 1.3:</span> Digitar o nome do seu &quot;Usuário&quot; na aba &quot;Username&quot;;

            - <span style="color:red">OP 1.4:</span> Deslocar o mouse até &quot;Result&quot;;

            - <span style="color:red">OP 1.5:</span> Apertar com o botão esquerdo do mouse.

- 4.4 Visualizar usuários do Virtual Judge

    - <span style="color:blue">GOAL 0:</span> Visualizar usuário;

        - <span style="color:blue">GOAL 1:</span> Encontrar usuário;

            - <span style="color:red">OP 1.1:</span> Deslocar o mouse até o topo da página;

            - <span style="color:red">OP 1.2:</span> Apertar com o botão esquerdo do mouse em &quot;User&quot;;

            - <span style="color:red">OP 1.3:</span> Digitar o nome do &quot;Usuário&quot; procurado na aba &quot;Username&quot; ou o &quot;Apelido&quot; na aba &quot;Nickname&quot;;

            - <span style="color:red">OP 1.4:</span> Pressionar a tecla &quot;Enter&quot;;

            - <span style="color:red">OP 1.5:</span> Apertar com o botão esquerdo do mouse no usuário encontrado.

- 4.5 Visualizar grupos do Virtual Judge

    - <span style="color:blue">GOAL 0:</span> Visualizar grupo;

        - <span style="color:blue">GOAL 1:</span> Encontrar grupo;

            - <span style="color:red">OP 1.1:</span> Deslocar o mouse até o topo da página;

            - <span style="color:red">OP 1.2:</span> Apertar com o botão esquerdo do mouse em &quot;Group&quot;;

            - <span style="color:red">OP 1.3:</span> Deslocar o mouse até a aba &quot;Explore&quot;;

            - <span style="color:red">OP 1.4:</span> Apertar com o botão esquerdo do mouse;

            - <span style="color:red">OP 1.5:</span> Digitar o nome do grupo procurado na aba &quot;Search by group name&quot;;

            - <span style="color:red">OP 1.6:</span> Apertar com o botão esquerdo do mouse em &quot;Search&quot;;

            - <span style="color:red">OP 1.7:</span> Apertar com o botão esquerdo do mouse no grupo encontrado.

- 4.6 Visualizar Fórum do Virtual Judge

    - <span style="color:blue">GOAL 0:</span> Visualizar fórum;

        - <span style="color:blue">GOAL 1:</span> Encontrar artigos;

            - <span style="color:red">OP 1.1:</span> Deslocar o mouse até o topo da página;

            - <span style="color:red">OP 1.2:</span> Apertar com o botão esquerdo do mouse em &quot;Forum&quot;;

            - <span style="color:red">OP 1.3:</span> Deslocar o mouse até a aba &quot;Title&quot;;

            - <span style="color:red">OP 1.4:</span> Apertar com o botão esquerdo do mouse;

            - <span style="color:red">OP 1.5:</span> Digitar o nome do artigo procurado;

            - <span style="color:red">OP 1.6:</span> Pressionar a tecla &quot;Enter&quot;;

            - <span style="color:red">OP 1.7:</span> Apertar com o botão esquerdo do mouse no artigo encontrado.

- 4.7 Sair da conta pessoal

    - <span style="color:blue">GOAL 0:</span> Sair da conta;

        - <span style="color:blue">GOAL 1:</span> Fazer Logout;

            - <span style="color:red">OP 1.1:</span> Deslocar o mouse até o topo da página;

            - <span style="color:red">OP 1.2:</span> Apertar com o botão esquerdo do mouse em &quot;Logout&quot;;

## Referências

> BARBOSA, Simone; SILVA, Bruno. &quot;Interação Humano-Computador&quot;. Elsevier Editora Ltda, 2010.

## Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 10/03/2021 | G.O.M.S. produzida | Caio e Gabriel |
| 1.0 | 13/03/2021 | G.O.M.S. adicionada | Ítalo |
| 1.0.1 | 16/03/2021 | G.O.M.S. revisada | Gabriel |