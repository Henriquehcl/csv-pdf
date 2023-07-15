## Importar/exportar CSV e PDF

Primeiro é precio configurar o arquivo .ENV, com as variávei de ambiente


```
DATABASE_NAME=
DATABASE_PORT=
DATABASE_HOST=
DATABASE_USER=
DATABASE_PASSWORD=
DATABASE_DIALECT=


PORT=3000

```

Instalar os pacotes com o comando

```
npm Install
```

Existe doi arquivos na rais de exemplo para serem testados

***PDF*** modelos_pdf.pdf
***CSV*** boletos.csv

Os arquivos gerados ficam salvo nas pastas ***uploads*** e ***relatoriosPDF***

O arquivo ***CSV-PDF.postman_collection.json*** é a collection exportada do postman, para ser usada como exemplo

``` 
/importar-csv/importar-cs 
```
#### Rota para enviar o arquivo CSV

```
/boletos
```
#### Rota para listar todos os boletos, também é possível filtrar, conforme os parametros passado.

```
/boletos/relatorio
```
#### Rota para buscar o boleto por parametro ***relatório=1*** retorna em base64, e gera um PDF do boletos

```
/pdf/upload
```
#### Rota para fazer o upload do arquivo PDF

