# Share Your Codes - Alura Challange

<h2>Site: <a href="https://shareyourcodes.com/comunidade">https://shareyourcodes.com/comunidade</a><h2>

<ul>
    <li>
        <a href="funcionalidades.md" target="_blank">Funcionalidades</a>
    </li>
    <li>
        <a href="https://github.com/jaum1234/editor-de-codigo" target="_blank">Laravel API</a>
    </li>
    <li>
        <a href="https://github.com/jaum1234/share-your-codes-vuejs" target="_blank">VueJS Interface</a>
    </li>
    <li>
        <a href="#" target="_blank">Projeto Full Laravel</a>
    </li>
</ul>

![editor](https://i.gyazo.com/00ece030b6655ce923bca591e355e8b2.png)
![comunidade](https://i.gyazo.com/dc33f4dfa2062f61551465505d20a2fa.png)
![pagina-do-projeto](https://i.gyazo.com/7234d2415ddfebbf737a7537a87bd473.png)
![user-page](https://i.gyazo.com/c8b861bec97963efbd431509bcaa5795.png)

## Contatos

<a href="https://www.linkedin.com/in/joao-v%C3%ADtor-de-souza-coura-b435381a9/">Linkedin</a>
<br>
<a href="mailto:joaovitorsouzacoura@gmail.com">joaovitorsouzacoura@gmail.com</a>

## Tecnologia utilizadas

- Laravel
- VueJS
- AWS
- Bootstrap
- jQuery
- MySQL
- Sass

## Sobre o projeto

O "Share Your Codes" se propõe a ser uma plataforma em que usuários podem criar e postar trechos de código e compartilha-los com a comunidade ou em suas redes sociais.

O projeto faz parte da primeira edição do Alura Challange, evento relizado pela platafora de ensino Alura, visando fortaceler 3 pilares essencias para um desenvolvedor:

1. Engajar
2. Investigar
3. Agir

## Executando no localhost

### Pre requisitos:

- Ter o Composer instalado
- Ter o Node instalado

### Passo a passo:

#### Laravel API: 

1. Clone o repositório 
``` 
    git clone https://github.com/jaum1234/editor-de-codigo.git 
```

2. Instale as dependencias
``` 
    composer install 
```

3. Copie o arquivo .env.example para o arquivo .env e faça as configuraçoes necessárias.
``` 
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_db
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
```
4. Gere sua chave secreta
``` 
    php artisan key:generate 
```

5. Rode as migrations
```
    php artisan migrate
```


6. Inicie o servidor local
```
    php artisan serve
```

7. Acesse o localhost:8000

#### VueJS Interface: 





