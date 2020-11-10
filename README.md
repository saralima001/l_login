<h1 align="left">
  <img alt="L" title="L" src="./imagens/logo.png" width="100px" heigth="100px"/>
</h1>

# L Login
Uma tela simples de login responsivo com título ou imagem na parte superior dos inputs.

## Opções
Você pode escolher utilizar um título ou imagem na parte superior dos inputs.

### Utilizando o título

No arquivo index.html (linhas 18 e 19): 
<!--
> 18 <!--h1 class="titulo"> Login </h1><br/>-->  
> 19 <img src="imagens/logo.png" width="100px" height="100px"> <br/>
-->

Remova os comentários '<!-- -->' da linha 18 e adicione a linha 19:
<!--
> 18 <h1 class="titulo"> Login </h1><br/>  
> 19 <!--img src="imagens/logo.png" width="100px" height="100px"> <br/>-->
-->

No arquivo style.css (linhas 39 ao 46):
> 39   
> 40 .titulo {  
> 41   
> 42 font-family: 'Dancing Script', cursive;  
> 43 font-size: 50px;  
> 44 color: #2B8EA3;  
> 45 }  
> 46 

Remova os comentários /* da linha 39 e /* da linha 46.

Está pronto para o título.

### Utilizando a imagem

No arquivo index.html (linhas 18 e 19): 
<!--
> 18 <h1 class="titulo"> Login </h1><br/>  
> 19 <!--img src="imagens/logo.png" width="100px" height="100px"> <br/>-->
-->

Remova os comentários '<!-- -->' da linha 19 e adicione a linha 18:
<!--
> 18 <!--h1 class="titulo"> Login </h1><br/>-->  
> 19 <img src="imagens/logo.png" width="100px" height="100px"> <br/>
-->

No arquivo style.css (linhas 39 ao 46):
> 39 /*  
> 40 .titulo {  
> 41   
> 42 font-family: 'Dancing Script', cursive;  
> 43 font-size: 50px;  
> 44 color: #2B8EA3;  
> 45 }  
> 46 */

Adicione comentários /* na linha 39 e /* na linha 46.

Está pronto para a imagem.

## Créditos
Imagem utilizada para o fundo da tela: https://cutewallpaper.org/download.php?file=/21/wallpaper-5k/Wallpaper-Canada,-4k,-5k-wallpaper,-mountains,-sky,-night-.jpg


## Licença
[MIT](https://choosealicense.com/licenses/mit/)
