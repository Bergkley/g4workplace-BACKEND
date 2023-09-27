# g4workplace-BACKEND

Execução do Projeto: O projeto pode ser iniciado com o comando npm run start-dev.

Banco de Dados PostgreSQL: Requer a configuração de um banco de dados PostgreSQL usando uma ferramenta como o DBEAVER.

Autenticação de Usuários: Permite que os usuários se registrem fornecendo informações como nome, email, senha e uma resposta a uma pergunta de segurança. Os dados dos usuários são validados e armazenados no banco de dados após criptografia da senha.

Autenticação com JWT: Após o login bem-sucedido, é gerado um token JWT (JSON Web Token) que é armazenado em um cookie seguro. Esse token é usado para autenticar as solicitações subsequentes dos usuários.

Recuperação de Senha: Inclui um mecanismo de recuperação de senha que permite aos usuários redefinirem suas senhas fornecendo a resposta correta à pergunta de segurança.

Gerenciamento de Funcionários: Recupera dados de funcionários, setores e sub-setores do banco de dados e os exibe em uma página. A autenticação com JWT é utilizada para proteger essas páginas, garantindo que apenas usuários autenticados tenham acesso.

Outras Páginas e Funcionalidades: O projeto inclui outras páginas, como a página de perfil do usuário, e outras relacionadas a clientes, contatos e outros recursos 

Segurança: A segurança é uma preocupação central, com o uso do algoritmo bcrypt para armazenar senhas de forma segura e a proteção de rotas usando autenticação JWT. O uso de cookies seguros também é implementado.

Configuração de Ambiente: Variáveis de ambiente são configuradas usando o dotenv para armazenar informações sensíveis, como chaves JWT e configurações do banco de dados
