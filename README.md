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
	"uf": "RJ",
	"cep": "20560904",
	"qsa": [
		{
			"pais": null,
			"nome_socio": "PAULO FERNANDO BARCELLOS VILLAREJO",
			"codigo_pais": null,
			"faixa_etaria": "Entre 31 a 40 anos",
			"cnpj_cpf_do_socio": "***200677**",
			"qualificacao_socio": "Sócio",
			"codigo_faixa_etaria": 4,
			"data_entrada_sociedade": "2017-04-24",
			"identificador_de_socio": 2,
			"cpf_representante_legal": "***000000**",
			"nome_representante_legal": "",
			"codigo_qualificacao_socio": 22,
			"qualificacao_representante_legal": "Não informada",
			"codigo_qualificacao_representante_legal": 0
		},
		{
			"pais": null,
			"nome_socio": "ANA CAROLINA VILLAREJO MALAGUTI",
			"codigo_pais": null,
			"faixa_etaria": "Entre 31 a 40 anos",
			"cnpj_cpf_do_socio": "***200667**",
			"qualificacao_socio": "Sócio-Administrador",
			"codigo_faixa_etaria": 4,
			"data_entrada_sociedade": "2017-04-24",
			"identificador_de_socio": 2,
			"cpf_representante_legal": "***000000**",
			"nome_representante_legal": "",
			"codigo_qualificacao_socio": 49,
			"qualificacao_representante_legal": "Não informada",
			"codigo_qualificacao_representante_legal": 0
		},
		{
			"pais": null,
			"nome_socio": "MARIA EDUARDA BARCELLOS VILLAREJO",
			"codigo_pais": null,
			"faixa_etaria": "Entre 31 a 40 anos",
			"cnpj_cpf_do_socio": "***243377**",
			"qualificacao_socio": "Sócio-Administrador",
			"codigo_faixa_etaria": 4,
			"data_entrada_sociedade": "2017-04-24",
			"identificador_de_socio": 2,
			"cpf_representante_legal": "***000000**",
			"nome_representante_legal": "",
			"codigo_qualificacao_socio": 49,
			"qualificacao_representante_legal": "Não informada",
			"codigo_qualificacao_representante_legal": 0
		},
		{
			"pais": null,
			"nome_socio": "ANTONIO AUGUSTO BARCELLOS VILLAREJO",
			"codigo_pais": null,
			"faixa_etaria": "Entre 41 a 50 anos",
			"cnpj_cpf_do_socio": "***200687**",
			"qualificacao_socio": "Sócio",
			"codigo_faixa_etaria": 5,
			"data_entrada_sociedade": "2017-04-24",
			"identificador_de_socio": 2,
			"cpf_representante_legal": "***000000**",
			"nome_representante_legal": "",
			"codigo_qualificacao_socio": 22,
			"qualificacao_representante_legal": "Não informada",
			"codigo_qualificacao_representante_legal": 0
		}
	],
	"cnpj": "33050246003142",
	"pais": null,
	"email": null,
	"porte": "DEMAIS",
	"bairro": "ANDARAI",
	"numero": "00236",
	"ddd_fax": "",
	"municipio": "RIO DE JANEIRO",
	"logradouro": "BARAO DE SAO FRANCISCO",
	"cnae_fiscal": 4782202,
	"codigo_pais": null,
	"complemento": " SHOPPING LOJAS 1047 E 1048.",
	"codigo_porte": 5,
	"razao_social": "SHEHRAZADE MODAS E ARTEFATOS DE COUROS LTDA",
	"nome_fantasia": "",
	"capital_social": 1275312,
	"ddd_telefone_1": "2132654950",
	"ddd_telefone_2": "",
	"opcao_pelo_mei": null,
	"descricao_porte": "",
	"codigo_municipio": 6001,
	"cnaes_secundarios": [
		{
			"codigo": 4781400,
			"descricao": "Comércio varejista de artigos do vestuário e acessórios"
		}
	],
	"natureza_juridica": "Sociedade Empresária Limitada",
	"situacao_especial": "",
	"opcao_pelo_simples": null,
	"situacao_cadastral": 2,
	"data_opcao_pelo_mei": null,
	"data_exclusao_do_mei": null,
	"cnae_fiscal_descricao": "Comércio varejista de artigos de viagem",
	"codigo_municipio_ibge": 3304557,
	"data_inicio_atividade": "2017-08-07",
	"data_situacao_especial": null,
	"data_opcao_pelo_simples": null,
	"data_situacao_cadastral": "2017-08-07",
	"nome_cidade_no_exterior": "",
	"codigo_natureza_juridica": 2062,
	"data_exclusao_do_simples": null,
	"motivo_situacao_cadastral": 0,
	"ente_federativo_responsavel": "",
	"identificador_matriz_filial": 2,
	"qualificacao_do_responsavel": 49,
	"descricao_situacao_cadastral": "ATIVA",
	"descricao_tipo_de_logradouro": "RUA",
	"descricao_motivo_situacao_cadastral": "SEM MOTIVO",
	"descricao_identificador_matriz_filial": "FILIAL"
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


