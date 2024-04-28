# projeto_2_python_analitics_bootcamp

Etapas:

 Verificação de Cabeçalhos e Tipos de Dados:
 *  tipos de dados das colunas estão corretos

 Modificação de Valores Monetários:
 * salary foi convertido para  "double preciso" para garantir a precisão dos cálculos.

  Análise de Valores Nulos:
  * Foi removido valores nulos da tabela employee

 Identificação de Gerentes:
  * Foi identificado funcionario com valor nulo na coluna "Super_ssn". Ele não tinha gerente e o valor nulo foi removido.

 Separação de Colunas Complexas:
  * Tabela employee foi divido a coluna de endereço(rua, bairro, cidade e UF)	

 mistura de Consultas:
 * employee_department

 Mescla de Nomes:
 * foi mesclado Nome e Sobrenome

 Mescla de Departamentos e Localização:
 * "Departamento-Localização" 

 Justificativa para mistura:
  * A mescla é mais adequada que a atribuição por causa da necessidade de manter a unicidade das combinações departamento-localização.
    A atribuição resultaria em duplicatas caso existissem departamentos com o mesmo nome em diferentes localizações. 

 Agrupamento por Gerente:
  * Foi Agrupado os daos por  "Manager_id" 

 Eliminação de Colunas Desnecessárias:
  * Foi eliminado colunas desnecessárias de cada tabela 
