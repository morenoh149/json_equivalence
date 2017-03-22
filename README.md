# json_equivalence
an npm module that can tell you if two json objects are equivalent

# Motivation
```
strObjA = '{
  "firstName": "Harry",
  "lastName": "Moreno"
}'
```

should be equivalent to

```
strObjB = '{
  "lastName": "Moreno",
  "firstName": "Harry"
}'
```

for use in comparing equivalence of api responses.
