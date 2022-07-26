# node-impulse-api


### Projeto desenvolvido durante o impulse da rocketseat. Para o funcionamento do projeto, é necessário que você instale o [`yarn`](https://yarnpkg.com/lang/en/docs/install/). A autenticação é feita pela API do [`github`](https://developer.github.com/v3/).

 **Também é necessário criar um .env com as seguintes variáveis:**

```
GITHUB_CLIENT_SECRET=#
GITHUB_CLIENT_ID=#

JWT_SECRET=#
```

Para mais informações sobre oauth, veja o [`github`](https://docs.github.com/pt/developers/apps/building-oauth-apps/creating-an-oauth-app).

**Caso precise gerar o `JWT_SECRET`, utilize um gerador de hash como [`md5`](https://www.md5hashgenerator.com/)**


Depois disso, é só rodar o comando `yarn start` para iniciar o servidor.