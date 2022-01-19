# Regex úteis

Expressões Regurales Úteis

Usar o site [regex101](https://regex101.com/) para testes

1. **Grupos**: exemplo, procurar pela primeira ocorrência de "," (útil parra arquivos CSV).
```
Localizar: ([^,]*),(.*)
Substituir: $1,$2
```
