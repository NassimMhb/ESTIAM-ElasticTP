TP ELASTIC SEARCH - MOUHOUBI NASSIM E4A

La question5 // Pas Fait

Pour la question 6, il faut autoriser le fielddata pour cela il faut entrer :

curl -H 'content-type: application/json' -XPUT 'http://localhost:9200/restaurants/_mapping/_doc' -d'
{
  "properties": {
    "borough": { 
      "type":     "text",
      "fielddata": true
    }
  }
}'

Pour la question 7, il faut autoriser le fielddata pour cela il faut entrer :

curl -H 'content-type: application/json' -XPUT 'http://localhost:9200/restaurants/_mapping/_doc' -d'
{
  "properties": {
    "cuisine": { 
      "type":     "text",
      "fielddata": true
    }
  }
}'

Pour la question 8, il faut autoriser le fielddata pour cela il faut entrer :

curl -H 'content-type: application/json' -XPUT 'http://localhost:9200/restaurants/_mapping/_doc' -d'
{
  "properties": {
    "name": { 
      "type":     "text",
      "fielddata": true
    }
  }
}'





