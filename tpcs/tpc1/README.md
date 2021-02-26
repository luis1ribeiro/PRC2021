***Para correr:***

* Primeiro correr o script flex. Usar a nossa database *db.json*, e fazer redirect do output para um ficheiro *individuals.ttl*.
- *> flex filter-json2ttl.l*
- *> gcc lex.yy.c*
- *> ./a.out < ./database/db.json > individuals.ttl*

* Adicionar o resultado do *individuals.ttl* à secção ***INDIVIDUALS*** do ficheiro *template.ttl*