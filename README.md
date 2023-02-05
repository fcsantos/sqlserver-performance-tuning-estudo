
## Resumo:

  1-Indexação adequada: Certifique-se de que suas tabelas estejam indexadas corretamente para melhorar o desempenho de consultas.

  2- de Stored Procedures: As Stored Procedures são compiladas e otimizadas, o que ajuda a melhorar a performance do banco de dados.

  3-Tabelas temporárias: Use tabelas temporárias para consultas intermediárias em vez de usar várias consultas individuais.

  4-Consultas efetivas: Escreva consultas de forma efetiva, evitando operações de junção desnecessárias e usando as condições WHERE corretamente.

  5-Utilização de variáveis: Use variáveis em vez de expressões calculadas na cláusula WHERE de suas consultas.

  6-Atualização de estatísticas: Certifique-se de atualizar as estatísticas do banco de dados com frequência para garantir que o SQL Server tome decisões de otimização corretas.

  7-Uso de consultas parametrizadas: Use consultas parametrizadas em vez de concatenar strings para construir consultas dinamicamente.

  8-Utilização de NOLOCK ou LOCK: Entenda a diferença entre o uso de NOLOCK e LOCK e escolha a opção correta de acordo com as suas necessidades.
    * A diferença entre o uso de NOLOCK e LOCK no SQL Server é que o uso de LOCK respeita os bloqueios de tabelas e linhas, o que garante a integridade dos dados           durante as consultas. Por outro lado, o uso de NOLOCK ignora os bloqueios e pode resultar em dados inconsistentes, mas aumenta a velocidade das consultas. O uso       de NOLOCK é adequado em cenários onde há poucas alterações nos dados, enquanto o uso de LOCK é adequado em cenários onde a integridade dos dados é uma                 prioridade.

  9-Otimização de índice: Certifique-se de que os índices estejam otimizados e não sejam redundantes.

  10-Utilização de memória adequada: Certifique-se de que o SQL Server tenha acesso a quantidade adequada de memória para melhorar o desempenho.
  
  11-Utilize planos de consulta adequados, incluindo a revisão frequente do histórico de planos de consulta para identificar problemas de desempenho.

  12-Evite a utilização de cursores, pois eles são geralmente mais lentos do que soluções baseadas em conjunto de dados.

  13-Mantenha a limpeza dos dados, removendo ou arquivando dados antigos e não utilizados.

  14-Utilize a funcionalidade de fragmentação de tabela para melhorar o desempenho em grandes tabelas.


Referencias para estudar:

https://eximia.co/insights/melhorando-ainda-mais-a-performance-de-consultas-sql-com-abordagens-set-based/

https://eximia.co/insights/otimizando-stored-procedures-2/

https://sql-do-jeito-certo.online/

https://desenvolvedor.io/curso/sql-para-desenvolvedores/

https://imasters.com.br/banco-de-dados/sql-server-estudo-de-performance-tuning

https://www.luiztools.com.br/post/11-dicas-de-performance-com-sql-server/

https://www.freecodecamp.org/news/how-to-improve-sql-server-performance/
