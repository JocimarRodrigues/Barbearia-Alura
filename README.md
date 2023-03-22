
<!DOCTYPE html> <!--o html é para especificar o versão do html, apartir do 5 não precisa mais especificar a versão, mas se eu quissese usar o html 3, teria que colocar:html3-->
<html lang="en"> <!-- O html é para abranger todo o contéudo da página! -->

Prestar atenção no lang, usar o pt-br para oferecer a opção de traduzir por usuários de outras línguas
<head><!--A tag head é onde tu vai guardar as informações que tu quer passar para o navegador, tu vai colocar os meta aqui!! -->
    <meta charset="UTF-8"> <!-- Isso aqui serve para escolher um dicionário de letras para usar na página, No caso do UTF-8 é o mais usado nas linguas da america central, sul, norte, europa -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- No Body vai ficar todas as informações que você quer exibir para o usuário! -->
</body>
</html>

- Quando tu precisar adicionar mais de um estilo em alguma tag inline HTML usa o ; para separar

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>Barbearia Alura</title>
    <style>
        p {
            text-align: center;
        }
    </style>
</head>


# Sobre Cores em CSS>>
##### Como é a representação numérica, ou em hexadecimal, para esses números? O zero é a ausência de cor, e o F é o máximo de cor. Então, se eu quiser representar, por exemplo, o preto, que é a ausência de todas as cores, coloco #000000. Ou seja, 00 para vermelho, 00 para verde e 00 para o azul. Se eu quiser representar o branco, coloco #FFFFFF. FF para o vermelho, FF para o verde e FF para o azul.

##### Como faríamos, por exemplo, para representar a cor vermelha em hexadecimal? Precisamos colocar # e precisamos que o vermelho seja completo, ou seja, no máximo, e que todas as outras cores não existam: #FF0000.

#####  importante saber também que existe outra forma de representar as cores, além das que já vimos. Temos as cores básicas, a linguagem hexadecimal e a RGB. O mesmo padrão RGB que falamos sobre as cores que conseguimos enxergar, temos um dicionário RGB. Um alfabeto. Ele vai do 0 até 255. Ou seja, ele tem 256 níveis de representação de cada cor. Para isso, o 0 também é a ausência e o 255 é o máximo. A representação no CSS é um pouco diferente. Ao invés de colocar #, eu coloco RGB( , , ), separando as cores por vírgula. Antes da primeira vírgula vem o vermelho. Então, se eu quiser representar o branco, coloco RGB(255, 255, 255). Se eu quiser representar só o azul, RGB(0, 0, 255)

# CSS COM IMAGENS

- CARA TU PODE ADICIONAR UM ID PARA A IMAGEM FICARIA ASSIM: 
- <*****img id="banner" src="./banner/banner.jpg" alt="">