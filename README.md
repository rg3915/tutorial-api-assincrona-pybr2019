# tutorial-api-assincrona-pybr2019

Tutorial de API assíncrona com Tyrone e Genilson - Python Brasil 2019

https://github.com/jgdsfilho/pybr

```
curl -X POST \
  http://localhost:8000/roles \
  -H 'Content-Type: application/json' \
  -d '{
    "nome": "Weird Barrel",
    "endereco": "onde tiver gela",
    "data": "amastarde",
    "preco_da_cerveja": 5.50
}'
```