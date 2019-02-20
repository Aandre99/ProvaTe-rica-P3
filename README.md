# Prova Teórica P3

## <h2/>  Funcionalidades: <br/>
  # <h4/> 1 - Adicionar Usuário;
  # <h4/> 2 - Remover Usuário; 
  # <h4/> 3 - Associar Usuário;
  # <h4/> 4 - Alterar Status Usuário;
  # <h4/> 5 - Consulta;
  # <h4/> 6 - Relatório;
  
## <h2/>  1 - Classes: <br/>
 - # <h4/> 1.1 Sistema
      - **Motivação**: Criar uma classe capaz de armazenar as informações principais, sendo esta encarregada de gerenciar todo o sistema.
      - **Solução**: A classe criada possui atributos gerais do sistema, tais com listas de Projetos, Listas de Usuários e Listas de Atividades, itens que caracterizam o sistema como estabelecido.
      - **Vantagens**: Uma vez que a configuração do sistema e feita mediante a esta classe, é de facil acesso as informações necessárias para cada função acima citadas.
      - **Desvantagens**: Maior acúmulo de código.
 - # <h4/> 1.2 Usuário
      - **Motivação**: Inicialmente era desejado cria uma classe que comportasse todas as informações partilhadas dos diferentes tipos de "colaboradores" do sistema, com esse intuito e o a aplicação da herança isto pode ser efetuado e aplicado para a construção da classe "Usuario".
      - **Solução**: Criou-se atributos gerais tais como: nome, endereco, email, telefone, Listas de Projetos e Listas de atividade de um Usuario genérico. 
      - **Vantagens**: Uso da herença como forma de tornar o codigo mais enxuto e evitar repetições desnecessárias de código.
      - **Desvantagens**: 
 - # <h4/> 1.3 Aluno
      - **Motivação**: Distribuir caracterizadamente os atributos e funções referentes a um aluno cadastrado no sistema.
      - **Solução**: A classe Aluno é uma subclasse de Usuario, tendo com diferencial o tipo do aluno que se deseja cadastrar no sistema, podendo este ser graduando, mestrando ou doutorando.A classe Aluno é uma subclasse de Usuario;
      - **Vantagens**: Melhor distribuição e aplicação dos conceitos de POO a fim de caracterizar o objeto "Aluno" de forma correta e simplificada.
      - **Desvantagens**: 
 - # <h4/> 1.4 Professor
      - **Motivação**: A figura do professor como contribuidor ou coordenador de um projeto era de tamanha necessidade, pois sem isso não seria possivel atender todas as necessidades do que foi pedido na descrição do projeto.
      - **Solução**: Criou-se a classe professor a fim de representar de forma segura as possibilidades e funções de um professor. A classe Professor é uma subclasse de Usuario;
      - **Vantagens**: Fácil acesso e distribuição das atributos/funcionalidades de um professor cadastrado no sistema.
      - **Desvantagens**: 
 - # <h4/> 1.5 Profissional
      - **Motivação**: Buscava-se uma forma de representar o individuo que fosse caracterizado por ser um funcionário, sendo resposável por um atividade em particular que lhe for alocada.
      - **Solução**: Criou - se uma classe que representasse o profissional definido na descrição do projeto, visando atribuir-lhe todas as caracteristicas e funções necessarias para o correto desempenho no projeto o qual estaja alocado.A classe Profissional é uma subclasse de Usuario;
      - **Vantagens**: Utilização da herença de forma a amenizar o codigo, visando aumentar o desempenho do sistema.
      - **Desvantagens**: 
 - # <h4/> 1.6 Pesquisador
      - **Motivação**: Visava-se contruir uma firme representação o Usuario Pesquisador, pois assim como o Professor este e de fundamental importancia para a criação e conclusão de um projeto. Pesquisador é uma subclasse de Usuario.
      - **Solução**: Um pesquisador possui caracteristicas de um coordenador , ou seja, pode assumir esse papel em um determinado projeto o qual esteja vinculado. Pesquisador é uma subclasse de Usuario.
      - **Vantagens**: Melhor distribuição do codigo e das caracteristicas possuidas por um pesquisador.
      - **Desvantagens**: 
 - # <h4/> 1.7 Informacao
      - **Motivação**: Visava-se contruir uma classe que armazenasse os atributos comuns entre um projeto e uma atividade, ambos estruturas do sistema em questao.
      - **Solução**: 
      - **Vantagens**: 
      - **Desvantagens**: 
