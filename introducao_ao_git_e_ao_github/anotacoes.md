# Anotações :nerd_face:

## Git

O Git é um sistema de versionamento de arquivos. 

Um versionamento possibilita que várias pessoas trabalhem no mesmo repositório ao mesmo tempo, sem gerar conflitos entre as alterações. Ele permite que tenhamos controle sobre tudo o que foi escrito, apagado, enfim, todas as alterações feitas em um determinado projeto.



## GitHub

O Github é uma plataforma onde se pode hospedar os arquivos. Ele trabalha com os repositórios do Git para que seja possível o armazenamento dos projetos.

Podemos dizer que o GitHub é como se fosse uma rede social de desenvolvedores, onde os códigos são compartilhados (ou não, se preferir deixar no privado).

Conceitos básicos do GitHub:

- Commit: este comando move os arquivos da *state area* para um repositório local;
- Push: é utilizado para enviar os commits feitos no repositório local para o repositório remoto (Github).
- Pull: traz o que está no repositório remoto (Github) para o repositório local.
- Branch: cópia do projeto (ramificação feita no projeto).
- Merge: serve para unir arquivos alterados ao arquivo original de um projeto, faz a junção da Branch com a Branch principal.



Pontos positivos do GitHub:

- Poder se inspirar nos códigos de outros desenvolvedores;
- Codificar em equipe;
- Acompanhar e até colaborar com projetos de outras equipes;
- Outros desenvolvedores podem te auxiliar nas dificuldades dos seus projetos;
- Ver o seu próprio desenvolvimento conforme for salvando novos códigos;
- E o mais legal é que ele pode ser usado de portfólio, onde as empresas poderão ver seus projetos.



#### Procedimento ao clonar o repositório

Criar repositório;

Editar o README, ou fazer isso pelo Typora anteriormente;

Clonar o código;

Ir até a pasta correta e utiliza o GitBash Here para facilitar;

$ git clone link_copiado

$ cd pasta_clonada

Realizar alterações;

$ ls -> observar os itens listados

$ git status -> vai informar em vermelho que há um novo item não commitado

$ git add . -> vai add tudo 

$ git commit -m "descrição"

$ git status -> vai informar que é necessário realizar o push

$ git push origin main







### Links legais:

https://www.markdownguide.org/basic-syntax/

https://pet.leg.ufpr.br/blog/guia-rapido-de-git-e-github/

https://www.youtube.com/watch?v=xEKo29OWILE&list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA&ab_channel=CursoemV%C3%ADdeo



