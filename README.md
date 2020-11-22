# CUCUMBER

CUCUMBER_PUBLISH_TOKEN=cdde227c-394c-41bf-9338-12157c5ab7e4

# MAVEM COMMAND LINE
> Colocar no nome da classe runner o Test, ficando RunnerTest para que  mavem consigo ler o arquivo.

Para executar todos os cenários:
mvn test

Para exibir as opções de linha de comando:
mvn test -Dcucumber.options="-h"

Executar uma feature especifica:
mvn test -Dcucumber.options="caminho/da/feature/arquivo.feature"

