# matera-plsql
Exercícios para Analista de Desenvolvimento de Sistemas (Foco em PL/SQL)‬

Essa é a prova de seleção prática para Analista de Desenvolvimento de Sistemas com foco em PL/SQL

O objetivo da dessa prova esta descrito no arquivo Prova tecnica...pdf

Segue abaixo os passos para a resolução:

1 - Montar o ambiente (estou partindo do principio que ja esteja instalado o docker)
    ![Docker instalado](dockerInstalled.png)
    Docker Instalado
    
## Baixar a image do OracleXE
**docker pull container-registry.oracle.com/database/express:latest**
    ![Baixando a image do OracleXE](dockerPullOracleXE.png)
    Processo de baixar a image OracleXE

## Rodar a imagem docker
**docker run --name oracle-xe -p 1521:1521 -e ORACLE_PWD=1234 container-registry.oracle.com/database/express:latest**
    ![Docker run da imagem baixada](dockerRunOracleXE.png)
    Docker run da image OracleXE
    ![Docker PS](dockerPs.png)
    Confirmando que a image esta rodando



