# Java + Cucumber 

## CUCUMBER
CUCUMBER_PUBLISH_TOKEN=cdde227c-394c-41bf-9338-12157c5ab7e4

## MAVEN COMMAND LINE
Para executar todos os cenários:
```shell
mvn test
```

Para exibir as opções de linha de comando:
```shell
mvn test -Dcucumber.options="-h"
```

Executar uma feature especifica:
```shell
mvn test -Dcucumber.options="caminho/da/feature/arquivo.feature"
```
