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

#### Link para a collection usada no postan de exemplo
https://www.postman.com/henriquehcl/workspace/public-henriquehcl/collection/14894565-d66d4342-f8d6-41c0-9b2e-3c40c8ccbbb5?action=share&creator=14894565


## Import/Export CSV and PDF

First, it is necessary to configure the .ENV file with the environment variables:


```
DATABASE_NAME=
DATABASE_PORT=
DATABASE_HOST=
DATABASE_USER=
DATABASE_PASSWORD=
DATABASE_DIALECT=


PORT=3000

```

Install the packages using the command:

```
npm Install
```

There are two example files in the root directory for testing:

***PDF*** modelos_pdf.pdf
***CSV*** boletos.csv

The generated files are saved in the uploads and relatoriosPDF folders.

The CSV-PDF.postman_collection.json file is the exported Postman collection that can be used as an example.

``` 
/importar-csv/importar-cs 
```
#### Route to send the CSV file

```
/boletos
```
#### Route to list all the invoices. It is also possible to filter them based on the provided parameters.

```
/boletos/relatorio
```
#### Route to search for the invoice using the parameter relatório=1. It returns the invoice in base64 format and generates a PDF of the invoice.

```
/pdf/upload
```
#### Route to upload the PDF file.


### Link to the collection used in the example Postman
https://www.postman.com/henriquehcl/workspace/public-henriquehcl/collection/14894565-d66d4342-f8d6-41c0-9b2e-3c40c8ccbbb5?action=share&creator=14894565"
