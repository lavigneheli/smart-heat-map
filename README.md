# Smart Heat Map

Ferramenta de estudo que transforma a prova em um mapa de calor: o aluno marca o que sabe, vê por onde começar e segue uma jornada guiada por temas (vermelho, amarelo e verde), com prompts prontos para IA, plano de estudo e conquistas.

Este repositório contém a **tela de login**. O aplicativo em si fica em um espaço privado do Supabase (Storage) e só é baixado depois que o login é aceito.

- Login com Supabase Auth (e-mail e senha), com cadastro fechado: só entra quem a autora cadastra.
- O aplicativo fica em um bucket privado e só usuários autenticados conseguem ler.
- O mapa de cada aluno é salvo apenas no navegador dele (localStorage), com exportação em um clique.
- A chave usada no front-end é a `anon` (pública). A `service_role` nunca é usada aqui.

Projeto independente de Helen Lavigne Almeida Martins.
