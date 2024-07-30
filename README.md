# .NET-React-Clone-Instagram
O clone do Instagram é um aplicativo de mídia social totalmente responsivo que é uma imitação do Instagram construído usando ReactJS e ASP.Net Core.


<h1>Clone do Instagram</h1>

O clone do Instagram é um aplicativo de mídia social totalmente responsivo que é uma imitação do Instagram construído usando ReactJS e ASP.Net Core.

## Nota Importante
> Ainda estou a trabalhar no projeto, esta não é a versão final do mesmo, apenas o tornei público para obter feedback e melhorá-lo ... Happay-Eid 🎉🐏

## Sobre
> Instanews é um aplicativo de mídia social totalmente responsivo que é uma imitação do [Instagram](https://www.instagram.com/) construído usando [ReactJS](https://reactjs.org/) e [ASP.NET Core](https://dotnet.microsoft.com/en-us/apps/aspnet)

### Construir com
- [ReactJS](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Redux Saga](https://redux-saga.js.org/)
- [Axios](https://github.com/axios/axios)
- [ViteJS](https://vitejs.dev/)

- [ASP.NET Core](https://dotnet.microsoft.com/en-us/apps/aspnet)
- [Entity Framework](https://docs.microsoft.com/en-us/ef/)
- [Armazenamento de Blobs do Azure](https://azure.microsoft.com/en-us/services/storage/blobs/)
- [Mapeador automático](https://automapper.org/)
- [Token JWT](https://jwt.io/)

## Introdução
> Esta é uma lista de instruções necessárias para configurar o seu projeto localmente, para obter uma cópia local em funcionamento, siga estas instruções.

### Instalação

1. **_Clonar o repositório_**

```sh
$ git clone https://github.com/Rodrigo-Mesquitaa/.NET-React-Clone-Instagram
```
2. **_Navegar para o diretório do repositório_**
```sh
$ cd instagram-clone
```

3. **_Instalar dependências_**

```sh
$ cd cliente -> npm install
$ npm install
```

3. **_Altere sua string de conexão_**

```sh
No arquivo instagram-clone/server/Instagram.API/appsettings.json, altere seu postgresSqlConnection para sua ConnectionString.
```


### Em execução

**_Compila e faz hot-reloads para desenvolvimento_**
```sh
$ cd cliente -> npm run dev
$ cd servidor/Instagram.API -> dotnet watch
```
### Esquema do banco de dados

![image](https://user-images.githubusercontent.com/95377982/185882103-1c14f4eb-10ad-4156-8d08-33a59f511ab3.png)


### Características

### Entrar e inscrever-se (segurança com o token de portador JWT)

![signin](https://user-images.githubusercontent.com/95377982/185363735-37feac8a-ffb5-433a-b2ed-40dcf1cd3086.gif)
![image](https://user-images.githubusercontent.com/95377982/185367659-e7a30a28-20bc-4afe-afae-7709871c4d5e.png)


### Publicar mídia (armazenamento com o armazenamento de blob do Azure)

![postgif](https://user-images.githubusercontent.com/95377982/185365502-c4b7127b-9271-4ea3-9f53-e5aaf2e92fae.gif)

### Detalhe do perfil

![image](https://user-images.githubusercontent.com/95377982/185367466-7c887f62-2441-417f-9b93-184032ca0bf8.png)

### Comentário de paginação e NewFeed

![image](https://user-images.githubusercontent.com/95377982/185366255-cdd4c1d7-1f89-4715-a813-44792d7b6359.png)

### E mais (Follow, UnFollow, Inbox, ...) 

Já terminei a API mas ainda não terminei a parte da interface. :joy:
