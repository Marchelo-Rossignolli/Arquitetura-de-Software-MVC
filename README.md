# Arquitetura-de-Software-MVC
MVC do grupo 04 - descrito por Marcelo Rossignolli

# Projeto VTM - League of Volunteers (LoV)

## Sobre o Projeto
Aqui no Projeto VTM, a gente quer fazer a diferença juntando gente que quer ajudar com quem precisa de uma mão. O site é tipo uma feirinha, só que de boas ações, onde ONGs mostram o que precisam e voluntários escolhem como querem contribuir.

## Como Funciona a Tecnologia Aqui
Nossa receita para fazer o site funcionar é usando algo chamado MVC, que é tipo separar as receitas (código) em partes que cuidam de coisas diferentes:
- **Modelos**: são os ingredientes, a parte que guarda as informações dos usuários e dos comentários que eles deixam.
- **Controladores**: são os chefs, a parte que decide o que fazer com os dados.
- **Views**: é a apresentação do prato, a parte que mostra tudo bonitinho na tela para as pessoas usarem.

E a gente desenha tudo isso com um programa chamado draw.io, que é tipo um papel digital para organizar nossas ideias.

## Modelos (Models)
Temos dois tipos principais de dados aqui:

- `Usuários`: São as pessoas que usam o site, sejam eles voluntários ou as ONGs.
  - Detalhes: Cada um tem um ID (tipo uma matrícula), nome de usuário e um tipo (se é voluntário ou ONG).
- `Comentários`: São as opiniões que os usuários deixam sobre as atividades de voluntariado.
  - Detalhes: Cada comentário tem um título, uma descrição do que foi a experiência, em qual área foi e quem escreveu.

E a relação entre eles é que um usuário pode deixar vários comentários, mas cada comentário é de um usuário só.

## Controladores (Controllers)
Os controladores são como os gerentes aqui. Eles têm tarefas específicas:

- `Gerenciador de Usuários`: Cuida dos perfis das pessoas.
  - O que faz: Adiciona novos perfis ou apaga os que não são mais necessários.
- `Gerenciador de Comentários`: Cuida dos comentários deixados no site.
  - O que faz: Deixa a gente adicionar novas opiniões e ver o que os outros falaram.

Eles fazem a ponte entre os dados e o que a gente vê na tela.

## Views (Visões)
As visões são as páginas que mostramos no site:

- `Lista`: Uma lista de tudo que tá disponível para fazer.
- `Cabeçalho`: A parte de cima do site onde você pode clicar para ir para outras páginas.
- `Carrossel de Imagens`: Um slide de fotos que muda sozinho mostrando coisas importantes.
- `Cards de Histórias`: Pequenas janelas que contam mais sobre cada atividade de voluntariado.
- `Perfil`: Onde você vê as informações de um usuário.
- `Login`: Onde você entra na sua conta.

## Infraestrutura
A infraestrutura é como o palco por trás das cortinas:

- Temos um servidor, que é como o computador central que faz o site funcionar.
- E um banco de dados, que é onde guardamos todas as informações tipo numa estante digital super organizada.

Buscamos sempre nos empenhar para seguir essa receita com o andamento do projeto
