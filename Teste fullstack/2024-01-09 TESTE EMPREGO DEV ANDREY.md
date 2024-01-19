Explicação: A empresa ClienteFeliz possui com uma base de clientes cada vez mais extensa. Como o gerenciamento desse clientes está se tornando cada vez mais difícil ela quer um sistema para gerenciar sua base com mais facilidade e rapidez.

Para isso, ele precisa de sistema  que permita cadastrar, editar, excluir e listar seus clientes com uma interface amigável e segura.

Sobre a aplição:

* Autenticação: A aplicação terá uma sistema de autenticação tradicional com usuario e senha que possibilitará que o usuario acesse o gerencimento de clientes.

Caso o usuário não tenho cadastro ele terá a opção de se cadastrar e confirmar seu cadastro via email, como tambem a opção de recuperar senha.

Sistema de gerenciamento de clientes (itens obrigatorio):

* O sistema terá uma única tela, onde haverá a opção de cadastrar novo cliente e onde os clientes cadastrados serão listados, com as opções de edita-los ou exclui-los.
- Todas as ações nesta pagina, com exceção do carregamento da mesma, se dará dinamicamente via AJAX.
- Nessa tela haverá uma pesquisa de clientes pelo ID ou pelo nome do mesmo.
- Nessa tela haverá um botão de exportação dos clientes listados, em PDF.

Detalhamento do sistema:
* É importante que ações critícas contem a confirmação do usuário
* Todas as tabelas deverão ser feitas com o plugin Jquery DatatablesJs (https://datatables.net) e os recursos de pesquisa, seleção e exportação devem ser deste plugin.
* Temas, cores, icones e qualquer outro ponto não citado neste documento são de livre escolha do desenvolvedor (use sua criatividade)

Tecnologias obrigatórias:

* Frontend
- HTML5
- Bootstrap/CSS3
- Jquery/Javascript

* Backend
- Laravel 6/PHP
- MariaDB/MySQL

Importante: Serão observados o uso de javascript moderno, boas praticas de desenvolvimento e as PSRs do PHP, relacionamentos de tabela mysql, aplicação do princípios SOLID de desenvolvimento. Tudo pontuado neste documento será considerado para aprovação do projeto e diferenciação do projeto dos demais. Por fim, cabe ressaltar que análise dos projetos será subjetiva por parte de quem irá analisá-lo.