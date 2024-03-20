# Projeto Blog Pessoal - Implementação de Segurança 🔒
## Neste projeto, foi implementada a segurança no backend do Blog Pessoal, utilizando a plataforma Java com Spring Boot. Abaixo estão os passos realizados:
______________________________________
Dependências Necessárias: Foram adicionadas as seguintes dependências:

Spring Security 🔐
jjwt-api 📦
jjwt-impl 🛠️
jjwt-jackson 📚
Camada Model: Foram criadas as classes de modelo Usuario e UsuarioLogin, contendo os atributos necessários, anotações e métodos Get e Set. Também foram estabelecidos os relacionamentos necessários para a Spring Security.

Execução da Aplicação: A aplicação foi executada no Spring Tool Suite (STS) e verificado se a tabela foi corretamente criada no MySQL Workbench.

Camada Repository: Foi criada a interface UsuarioRepository com a capacidade de se comunicar com o banco de dados MySQL. Além disso, foi adicionado o método de busca específica findByUsuario().

Camada Security: Foram criadas as classes BasicSecurityConfig, UserDetailsImpl, UserDetailsServiceImpl, JwtService e JwtAuthFilter para lidar com a segurança da aplicação.

Camada Service: Foi criada a classe UsuarioService, na qual foram implementados os métodos cadastrarUsuario(), atualizarUsuario() e autenticarUsuario().

Camada Controller: Foi criada a classe UsuarioController, contendo os métodos getAll(), getById(), post(), put() e logar() para lidar com as requisições relacionadas aos usuários.

Teste dos Métodos CRUD: Todos os métodos do CRUD foram testados utilizando a ferramenta Insomnia para garantir seu funcionamento adequado.

Envio das Atualizações: Após concluir as implementações, as atualizações do projeto foram enviadas para o repositório remoto.

Validação das Classes e Interfaces: As classes e interfaces desenvolvidas para o recurso Usuario foram validadas nas respectivas camadas: model, repository, controller e service.
