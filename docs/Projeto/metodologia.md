## Metodologia, processo e abordagem

## Introdução

Para uma organização eficaz, a equipe adotou uma metodologia própria adaptada com princípios inspirados na metodologia Scrum e na técnica Kanban. Com essa abordagem o time visa otimizar o fluxo de trabalho e monitorar o progresso das tarefas, evidenciando possíveis impedimentos, necessidades de revisão e validações, além de garantir o acompanhamento rigoroso de cada etapa até a conclusão das atividades.

## Objetivo

Este artefato tem como objetivo esclarecer a compreensão da equipe acerca das metodologias abordadas no material disponibilizado na disciplina, demonstrar a preocupação com a fundamentação conceitual na escolha das práticas adotadas e evidenciar como a equipe implementou, de forma estruturada, a teoria dessas metodologias.

## Metodologia

A escolha da metodologia foi feita em uma reunião presencial, na qual esteve presente uma quantidade significativa do grupo. Desde o início, foi acordado o uso de uma adaptação da metodologia Scrum, uma vez que vários membros possuem familiaridade com essa abordagem. A natureza do produto também foi considerada por se tratar de um jogo com diversas funcionalidades, sendo, portanto, conveniente para a equipe trabalhar com entregas contínuas e frequentes, como estabelecem metodologias iterativas e incrementais.

No entanto, ao longo das discussões, todos os membros presentes concordaram que a aplicação completa do Scrum seria inviável. Devido à grande quantidade de integrantes no grupo, realizar dailies frequentes seria impraticável por questões de disponibilidade de horários. Além disso, foi descartada a retrospectiva da sprint (Sprint Retrospective), uma vez que o grupo deseja maximizar o pouco tempo disponível para focar em aspectos relacionados à revisão da sprint.

Para agregar ao Scrum, a metodologia Kanban será utilizada para controle do desenvolvimento, permitindo compreender de forma prática o andamento, tanto quanto de cada atividade, como do projeto como um todo. Tal acompanhamento também permitirá um controle de qualidade sobre cada card, o que é fundamental devido ao tamanho da equipe de desenvolvimento.

Embora metodologias orientadas a plano não sejam o foco central, incorporamos algumas de suas práticas e princípios que contribuem para a estruturação do projeto. Algumas dessas características podem ser visualizadas na Tabela 1 , que mostra a relação de cada prática e cada princípio adotados com as metodologias estudadas em sala.

<center>
<b>Tabela 1 -</b> Princípios e práticas adotados e suas relações conceituais

<div style="margin: 0 auto; width: fit-content;">

|        Etapa/prática        | RUP | OpenUP | XP  | Scrum | SAFe | Lean | Kanban |
| :-------------------------: | :-: | :----: | :-: | :---: | :--: | :--: | :----: |
|  Reuniões diárias (Daily)   |     |        |  X  |   X   |  X   |      |        |
|      Análise de riscos      |  X  |   X    |     |       |      |      |        |
|          Iterativo          |  X  |   X    |  X  |   X   |  X   |  X   |        |
|         Incremental         |  X  |   X    |  X  |   X   |  X   |  X   |        |
|            Ágil             |  X  |   X    |  X  |   X   |  X   |  X   |   X    |
|         Mapeamento          |     |        |     |       |      |      |   X    |
|    Visualização de fluxo    |     |        |     |       |      |  X   |   X    |
|          Flexível           |  X  |   X    |     |       |      |  X   |   X    |
|         Verificação         |  X  |   X    |  X  |       |  X   |      |        |
|          Validação          |  X  |   X    |  X  |       |  X   |      |        |
|     Integração contínua     |     |        |  X  |       |  X   |      |   X    |
|   Planejamento e backlog    |     |        |  X  |   X   |      |      |        |
| Sprints e ciclos de revisão |     |        |  X  |   X   |  X   |      |        |

<b>Fonte:</b> Lemos, Sandes, Carvalho (2024)

</center>

Por fim, a metodologia, assim como suas etapas, atividades e processos foram devidamente documentados usando notação BPMN, para que seja de fácil acesso e compreensão para todos os integrantes e para qualquer interessado em acompanhar o desenvolvimento.

## Resultado

Para a aplicação da técnica do Kanban a equipe optou por utilizar a ferramenta do [Zenhub](https://www.zenhub.com/) divididas em raias que podem ser vistas na Figura 1. Um excelente material que funciona como guia da ferramenta pode ser encontrado [aqui](https://www.youtube.com/watch?v=FJBtFjZ55eY&list=PLFIGvQyXSp3CGS8X300Aj-hUZ-VLIhHbk).

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcVbTa6gBAWtL1vB_kfXoX3-L1Zvt0-Mg1TaFqXCSnxUscsUYm1C2sKW7j0SNnGyCzSEQfy7gOFIEcatBqN6MzOb_liIENe1aDqTbc1DCoKuOYxmVArzcwgCiIngIfxCieYld_00FbXgAoXIWkVaFCk5mdd?key=q6nVftqzVGw03OEQ1XfhaWVW)

As tarefas devem seguir o template disponível no repositório e são baseadas no material da disciplina e definidas durante a primeira etapa do Ciclo da Sprint, na qual haverá uma reunião realizada remotamente pela plataforma do Teams às quartas-feiras, às 20h, conforme o horário comum entre os membros da equipe. As reuniões serão gravadas e resumidas em atas para registro simplificado dos tópicos e presença dos integrantes e nela será estimado o esforço para cada tarefa, a formação das equipes e suas respectivas responsabilidades.

Em etapa intermediária da sprint, no decorrer de seu desenvolvimento e implementação, a equipe optou por realizar uma daily adaptada, na qual apenas os representantes de cada equipe compartilham o progresso de suas respectivas áreas pela principal plataforma de comunicação da equipe - o Whatsapp. Assim, será possível identificar empecilhos, caso haja, e realizar o remanejamento de equipes, se necessário.

No final do Ciclo da Sprint serão identificados os artefatos concluídos, revisados e não concluídos e o quadro do Zenhub será devidamente atualizado paralelamente ao desenvolvimento das atividades.

Após a revisão é realizada uma validação para confirmar que todos os critérios foram cumpridos e caso seja positiva, o processo avança para a Integração Contínua, caso contrário a tarefa retorna para ajustes adicionais.

Na integração contínua, os testes unitários serão realizados, e, em seguida, a qualidade do código será avaliada com a ferramenta SonarQube. Utilizaremos também as ferramentas Gradle - ou Maven - para compilação e empacotamento do software, para enfim gerar o pacote final e o release no repositório, tornando a nova versão do software disponível.

## Bibliografia

[1] SERRANO, Milene. Videoaula: [03b - VídeoAula - DSW - Metodologia - RUP](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EcEx3UfhmvlAliVpLUlXelQBfaD1EFsNIpL32EMWqRptYg?e=qeIjLP). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EcEx3UfhmvlAliVpLUlXelQBfaD1EFsNIpL32EMWqRptYg?e=qeIjLP](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EcEx3UfhmvlAliVpLUlXelQBfaD1EFsNIpL32EMWqRptYg?e=qeIjLP) . Acesso em: 02 nov. 2024.

[2] SERRANO, Milene. Videoaula: [03c - VídeoAula - DSW - Metodologia - OpenUp](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ea3mcLH9TMpDt5h3OqZJCrgBErMwxkLl_bKKCvuFKUKtqg?e=v51Pll). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ea3mcLH9TMpDt5h3OqZJCrgBErMwxkLl_bKKCvuFKUKtqg?e=v51Pll](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ea3mcLH9TMpDt5h3OqZJCrgBErMwxkLl_bKKCvuFKUKtqg?e=v51Pll) . Acesso em: 02 nov. 2024.

[3] SERRANO, Milene. Videoaula: [03d - VídeoAula - DSW - Metodologia - XP](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Eflwz61lmvtGtMwMkl6jw1gBHIdbS8RYwA_BuxfXHLS4LA?e=UNrmfJ). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Eflwz61lmvtGtMwMkl6jw1gBHIdbS8RYwA_BuxfXHLS4LA?e=UNrmfJ](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Eflwz61lmvtGtMwMkl6jw1gBHIdbS8RYwA_BuxfXHLS4LA?e=UNrmfJ) . Acesso em: 02 nov. 2024.

[4] SERRANO, Milene. Videoaula: [03e - VídeoAula - DSW - Metodologia - Scrum](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ed9HYhvCWyNDs3qOmk95bdEBHp9Ju_BVskiXygWAoDHeeA?e=il6uk3). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ed9HYhvCWyNDs3qOmk95bdEBHp9Ju_BVskiXygWAoDHeeA?e=il6uk3](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ed9HYhvCWyNDs3qOmk95bdEBHp9Ju_BVskiXygWAoDHeeA?e=il6uk3) . Acesso em: 02 nov. 2024.

[5] SERRANO, Milene. Videoaula: [03f - VídeoAula - DSW - Metodologia - Safe](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EZzHyjCJ6TFOhRRIxhFaHFoBrTLCFFAGgm56qo0A3xDxSw?e=brjcfZ). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EZzHyjCJ6TFOhRRIxhFaHFoBrTLCFFAGgm56qo0A3xDxSw?e=brjcfZ](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EZzHyjCJ6TFOhRRIxhFaHFoBrTLCFFAGgm56qo0A3xDxSw?e=brjcfZ) . Acesso em: 02 nov. 2024.

[6] SERRANO, Milene. Videoaula: [03g - VídeoAula - DSW - Metodologia - Lean](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/ERNipaRz-DpKvs9AL64CmhgBqOovhXGQCEXAtARTDq0K8Q?e=bOCHFz). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/ERNipaRz-DpKvs9AL64CmhgBqOovhXGQCEXAtARTDq0K8Q?e=bOCHFz](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/ERNipaRz-DpKvs9AL64CmhgBqOovhXGQCEXAtARTDq0K8Q?e=bOCHFz) . Acesso em: 02 nov. 2024.

[7] SERRANO, Milene. Videoaula: [03h - VídeoAula - DSW - Metodologia - Kanban](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EQgLfvPQmp5KjkhWSaWEOmIBrLF4HlH0hN4-SnhpilojFw?e=dIP36g). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EQgLfvPQmp5KjkhWSaWEOmIBrLF4HlH0hN4-SnhpilojFw?e=dIP36g](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EQgLfvPQmp5KjkhWSaWEOmIBrLF4HlH0hN4-SnhpilojFw?e=dIP36g) . Acesso em: 02 nov. 2024.

## Participantes

<center>

## Participantes

</center>

<div style="margin: 0 auto; width: fit-content;">

| Matrícula | Aluno                             | Git                                               |
| --------- | --------------------------------- | ------------------------------------------------- |
| 221008024 | Eduardo Matheus dos Santos Sandes | [DiceRunner714](https://github.com/DiceRunner714) |
| 170010872 | Gabriela de Oliveira Lemos        | [Gabriela Lemos](https://github.com/heylisten64)     |
| 221008150 | João Antonio Ginuino Carvalho     | [João Carvalho](https://github.com/joaoseisei)       |

</div>

---

<center>

## Histórico de Versão

</center>

<div style="margin: 0 auto; width: fit-content;">

| Versão | Data da alteração |      Alteração       |                                                                   Responsável                                                                    | Revisor | Data de revisão |
| :----: | :---------------: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: | :-----: | :-------------: |
|  1.0   |       03/11       | Criação do documento | [Gabriela Lemos](https://github.com/heylisten64), [DiceRunner714](https://github.com/DiceRunner714), [joaoseisei](https://github.com/joaoseisei) |         |                 |
