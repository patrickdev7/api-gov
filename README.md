# api-gov
---

## CEP

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **findCep**   | GET    | `https://brasilapi.com.br/api/cep/v1/{cep}`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
  {
	"cep": "23042420",
	"state": "RJ",
	"city": "Rio de Janeiro",
	"neighborhood": "Campo Grande",
	"street": "Rua Soldado Berli Vieira",
	"service": "correios"
}
```
---

## CEP CORDINATES

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **findCepCordinates**   | GET    | `https://brasilapi.com.br/api/cep/v2/{cep}`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
{
	"cep": "23042420",
	"state": "RJ",
	"city": "Rio de Janeiro",
	"neighborhood": "Campo Grande",
	"street": "Rua Soldado Berli Vieira",
	"service": "viacep",
	"location": {
		"type": "Point",
		"coordinates": {
			"longitude": "-43.5582542",
			"latitude": "-22.9305831"
		}
	}
}
```
---

## CNPJ

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **findCnpj**   | GET    | `https://brasilapi.com.br/api/cnpj/v1/{cnpj}`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
{
	"cep": "23042420",
	"state": "RJ",
	"city": "Rio de Janeiro",
	"neighborhood": "Campo Grande",
	"street": "Rua Soldado Berli Vieira",
	"service": "viacep",
	"location": {
		"type": "Point",
		"coordinates": {
			"longitude": "-43.5582542",
			"latitude": "-22.9305831"
		}
	}
}
```
---

## DDD

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **findAllCities**   | GET    | `https://brasilapi.com.br/api/ddd/v1/{DDD}`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
{
	"state": "RJ",
	"cities": [
		"TERESÓPOLIS",
		"TANGUÁ",
		"SEROPÉDICA",
		"SÃO JOÃO DE MERITI",
		"SÃO GONÇALO",
		"RIO DE JANEIRO",
		"RIO BONITO",
		"QUEIMADOS",
		"PARACAMBI",
		"NOVA IGUAÇU",
		"NITERÓI",
		"NILÓPOLIS",
		"MESQUITA",
		"MARICÁ",
		"MANGARATIBA",
		"MAGÉ",
		"JAPERI",
		"ITAGUAÍ",
		"ITABORAÍ",
		"GUAPIMIRIM",
		"DUQUE DE CAXIAS",
		"CACHOEIRAS DE MACACU",
		"BELFORD ROXO"
	]
}
```
---

## TAXA GOV

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **findTaxaGov**   | GET    | `https://brasilapi.com.br/api/taxas/v1`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
[
	{
		"nome": "Selic",
		"valor": 13.75
	},
	{
		"nome": "CDI",
		"valor": 13.65
	},
	{
		"nome": "IPCA",
		"valor": 5.79
	}
]
```
---

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **findOneTaxaGov**   | GET    | `https://brasilapi.com.br/api/taxas/v1/{nome}`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
{
	"nome": "SELIC",
	"valor": 13.75
}
```
---

## BANKS

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **FidAllBanks**   | GET    | `https://brasilapi.com.br/api/banks/v1`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
[
  {
		"ispb": "00000000",
		"name": "BCO DO BRASIL S.A.",
		"code": 1,
		"fullName": "Banco do Brasil S.A."
	},
	{
		"ispb": "00000208",
		"name": "BRB - BCO DE BRASILIA S.A.",
		"code": 70,
		"fullName": "BRB - BANCO DE BRASILIA S.A."
	},
	{
		"ispb": "00038121",
		"name": "Selic",
		"code": null,
		"fullName": "Banco Central do Brasil - Selic"
	},
	{
		"ispb": "00038166",
		"name": "Bacen",
		"code": null,
		"fullName": "Banco Central do Brasil"
	},
	{
		"ispb": "00204963",
		"name": "CCR SEARA",
		"code": 430,
		"fullName": "COOPERATIVA DE CREDITO RURAL SEARA - CREDISEARA"
	}
]
```
---

| Função        | Método | Endpoint       |
| --------------| ------ | -------------- |
| **FidOneBank**   | GET    | `https://brasilapi.com.br/api/banks/v1/{code}`       |


### Exemplo

Requisição:
```json
GET
```

Resposta:
```json
{
	"ispb": "60701190",
	"name": "ITAÚ UNIBANCO S.A.",
	"code": 341,
	"fullName": "ITAÚ UNIBANCO S.A."
}
```


