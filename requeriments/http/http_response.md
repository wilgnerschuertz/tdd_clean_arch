# HTTP


> ## SUCESSO
1. ✅ Request com verbo http válido (post)
2. ✅ Passar nos headers o content type JSON
3. ✅ Chamar request com body correto
4. ✅ OK - 200 e resposta com dados
5. ✅ No content - 204 e resposta sem dados

> ## ERROS
1. Bad Request - 400
2. Unauthorized - 401
3. Forbidden - 403
4. Not Found - 404
5. Internal Server Error - 500

> ## EXCEÇÃO - STATUS CODE DIFERENTE DOS CITADOS ACIMA
1. Internal Server Error - 500

> ## EXCEÇÃO - HTTP REQUEST DEU ALGUMA EXCEÇÃO
1. Internal Server Error - 500

> ## EXCEÇÃO - VERBO HTTP INVÁLIDO
1. Internal Server Error - 500