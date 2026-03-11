🖥️ Gygabite Shop - Sistema de E-commerce de Hardware

Este é um projeto acadêmico desenvolvido para o curso de Análise e Desenvolvimento de Sistemas (ADS) da UNISUAM. O sistema consiste em uma plataforma completa de vendas de componentes de PC, com áreas distintas para clientes e administradores.

Autor: Italo Rômulo

🚀 Funcionalidades:

👤 Área do Cliente

Catálogo Dinâmico: Visualização de produtos organizados por categorias (Destaques, Periféricos, Computadores).

Sistema de Busca: Consulta de produtos por nome.

Carrinho de Compras: Adição, remoção e controle de quantidade de itens.

Checkout Completo: Integração com a API ViaCEP para preenchimento automático de endereço e opções de pagamento (Cartão, Pix, Boleto).

Gestão de Conta: Cadastro de usuários com validação de CPF e recuperação de senha segura via hash.

Acessibilidade: Menu flutuante com ajuste de tamanho de fonte e alternância entre Modo Claro e Modo Escuro.

🛠️ Área do Administrador (Restrita)

Dashboard: Painel com faturamento total e gráfico de barras dos 5 produtos mais vendidos (usando Chart.js).

CRUD de Produtos: Cadastro (com upload de imagem), edição, consulta e exclusão de itens no inventário.

Relatórios em PDF: Geração dinâmica de relatórios de vendas utilizando a biblioteca FPDF.

🛠️ Tecnologias Utilizadas

Front-end: HTML5, CSS3, JavaScript (ES6+), Bootstrap 5.

Back-end: PHP 8.x.

Banco de Dados: MySQL.

Bibliotecas: * FPDF: Para geração de documentos PDF.

Chart.js: Para visualização de dados no painel administrativo.

Font Awesome: Para ícones da interface.


🔧 Como Executar o Projeto

Clone este repositório.

Certifique-se de ter um ambiente PHP (como XAMPP, WAMP ou Laragon).

Importe o arquivo avformadora3.sql para o seu gerenciador de banco de dados MySQL.

Configure as credenciais do banco em conexao.php, se necessário.

Coloque a pasta do projeto no diretório htdocs ou www.

Acesse localhost/nome-da-pasta/login.php no seu navegador.

Nota: Para acessar como administrador, utilize o login admin e rededina a senha na parte (esqueceu a senha?).

📝 Licença

Este projeto foi desenvolvido estritamente para fins acadêmicos na Universidade UNISUAM.

Italo Rômulo Estudante de Análise e Desenvolvimento de Sistemas
