### SGDA2 - Front Wildfly

## Criação dos pacotes
```
1 - Fazer pull das últimas alterações;

2 - No front-end, executar o comando npm run build-<profile>, onde o <profile> pode ser sit, uat ou prod; (repositório: sgda2-front)

3 - No projeto java, gerar o pacote do wildfly;

4 - Copiar todo o conteúdo gerado na pasta dist/sgda2-front do front-end, para a pasta src/main/resources/public do java;

5 - No java, após copiar e colar os arquivos do front, executar o comando mvn clean package;

6 - Verificar se o arquivo gerado na pasta target está com o nome correto: sgda2-front.war;

7 - Executar o compilado, para validar se não há nenhum erro ocorrendo no pacote gerado.
```
