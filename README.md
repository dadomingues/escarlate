# escarlate
Governaça coletiva para estoque de sangue

## proposta
A criação de uma ferramenta que permita a governaça colaborativa do estoque de sangue pela comunicação efetiva de hemocentros e da sociedade. Com o envio tempestivo do estoque, a população, assim como meios de comunicação e entidades responsáveis, podem analisar e avaliar por si a necessidade de docação de sangue além da escolha do local ideal para este nobre ato.

## tecnologia
A comunicação entre os hemocentros e a aplicação central, assim como as consultar pelos clientes, se dá pela arquitetura **REST** utilizando **JSON**. O projeto é escrito em **PHP** com o micro-framework **Slim** que permite perfeita e facilmente a criação de aplicações deste tipo.

## pré-requisitos
- PHP 5.3+;
- MongoDB 2.6+;
- Composer.

## instalação
- Copie/baixe o projeto;
- Certifique-se da aplicação rodar no diretório em que está;
- No diretório raiz do **escarlate**, execute o composer para instalar as dependências:
    `php composer.phar install`
- Execute o script **instalar.php** para que o banco e as coleções sejam criados;
- Apague o script **instalar.php** após sua execução bem sucedida para que não haja problemas.
