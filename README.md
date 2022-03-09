# Desafio: Explorando Padrões de Projeto na Prática com Java da [DIO](https://web.dio.me/)
#### Projeto API Rest com Spring Framework - Cadastro de Cliete consumindo os dados de endereço de API externa.
Instrutor [venilton](https://github.com/falvojr)

## - Padrões aplicados 

- Padrão de criação: **Singleton**
  Explorado com uso da anotação @Autowired que auxilia para realizar injeção de dependência.
  Ao instanciar um objeto por padrão utiliza sempre a mesma instância quando requisitada.
  
- Padrão comportamental: **Strategy**
  Eplorado utilizando a interface CrudRepository, que provê estratégias de implementação para acesso
  ao banco de dados.
- Padrão Estrutural: **Facade**
  Foi aplicado unificando a manipulação de dados com dois subsistemas através de uma interface mais amigável.
  Classe ClienteServiceImpl - contendo funções para interação com banco de dados e comunicação com API viaCep.
  

