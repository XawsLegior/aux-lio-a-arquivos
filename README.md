##### Esse script auxilia na manipulação de arquivos, os comandos são semelhantes ao um banco de dados relacional, e a estrutura é semelhante a um banco de dados não relacional.

### Configuração inicial
As configurações são feitas no arquivo Config.ini
- extensao, formato do arquivo, por padrão é .ini
- path, caminho onde todos as pastas serão geradas
- pastas, nesse list deve ser informado as pastas que devem ser geradas<br>
-- deve ser informado o caminho completo, ignorando o path
 
**Exemplo:**
- pastas = ["Servidores/Config"]<br>
 -- Dentro da pasta path (Database) vai ser gerado a pasta Servidores<br>
 -- Dentro da pasta Servidores vai ser gerado a pasta Config<br>


### Comandos
- Insert<br>
 -- insert into(**caminho**) values(l**inha1/linha1, linha2**)<br>

- Select<br>
 -- select **posição** from **caminho**<br>
 -- select **posição** from **caminho** where **posição**=**valor**<br>

- Update<br>
 -- update **posição** from **caminho/arquivo**='**novo valor**' where **posição**=**valor**<br>
 -- update *  from **caminho/arquivo=novo_valor** where **posição**=**valor**<br>