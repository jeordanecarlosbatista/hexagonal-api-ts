# Autenticação

> ## Caso de sucesso
1. ✅ Receba uma requisição do tipo **POST** na rota **/api/login**
2. ✅ Valida se a requisição possui os dados de email e senha
2. ✅ Retorna **200** com os dados do **usuário** e o **token"" de autorização

> ## Exceções
1. ✅ Retorna erro **401** se usuário ou senha estiver inválido
1. ✅ Retorna erro **404** se a api não existir
3. ✅ Retorna erro **500** se der erro ao tentar fazer o cadastro de usuário
