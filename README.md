# sd-data-concurrence-2
Exercício sobre concorrência na manipulação de dados

### Solução

Para implementação da pausa e reinicio do procedimento foi usado a estratégia de Lock.
Cada instância da aplicação pode ser pausada e depois ter o seu processamento retomado de forma independente de outras instâncias.
Juntamente com o Lock, foi usado uma Condition que define o momento de pausa/reinicio do processamento de acordo com a escolha do usuário.

### Para executar realize os seguintes passos:

> - crie as tabelas no banco de dados utilizando o **SQL** presente no arquivo **tables.sql**
> - execute **mvn package** na raiz do projeto
> - execute os arquivos **sh** **start-instance01.sh** e **start-instance02.sh**
