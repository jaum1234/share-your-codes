# Share Your Codes - Alura Challange

<h2>Acesse o site: <a href="https://shareyourcodes.com/comunidade" target="_blank">https://shareyourcodes.com/comunidade</a></h2>

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
        <a href="deployment.md" target="_blank">Deployment</a>
    </li>
    <li>
        <a href="#" target="_blank">Projeto Full Laravel</a>
    </li>
</ul>

## Contatos

<a href="https://www.linkedin.com/in/joao-v%C3%ADtor-de-souza-coura-b435381a9/" target="_blank">Linkedin</a>
<br>
<a href="mailto:joaovitorsouzacoura@gmail.com" target="_blank">joaovitorsouzacoura@gmail.com</a>

![editor](https://i.gyazo.com/19129d091c33d922fe89aee361c1623a.png)
![comunidade](https://i.gyazo.com/7696ca0a0676521fc1448d64138c7ff2.png)
![pagina-do-projeto](https://i.gyazo.com/8abe9d44a1b1c4a01fc6df83a5b65e37.png)
![user-page](https://i.gyazo.com/fa3946706f5b13f49778fa9518b98433.png)

## Tecnologia utilizadas

- Laravel
- VueJS & Vuex
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





