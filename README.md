# jogo-da-naves
jogo
<!DOCTYPEhtml >
< html  lang =" pt-br " >
< cabeça >
    < meta  charset =" UTF-8 " >
    < meta  name =" viewport " content =" largura=largura do dispositivo, escala inicial=1.0 " >
    < title > Resgate </ title >

    < link  rel =" folha de estilo " href =" css/main.css " >
</ cabeça >
< corpo >
    < div  id =" recipiente " >
        < div  id =" fundoGame " >
            < div  id =" inicio " onclick =" start(); " >
                < h1 > Resgate </ h1 >
                < p > Utilize como direcionais para controlar o helicóptero e o espaço para atirar. </ p >
                < p > Clique aqui para iniciar!! </ p >
            </ div >
        </ div >
    </ div >

    < audio  src =" sons/missile.mp3 " preload =" auto " id =" somDisparo " > </ audio >
    < audio  src =" sons/explosao.mp3 " preload =" auto " id =" somExplosao " > </ audio >
    < audio  src =" sons/musica_fundo.mp3 " preload =" auto " id =" musica " > </ audio >
    < audio  src =" sons/gameover.mp3 " preload =" auto " id =" somGameover " > </ audio >
    < audio  src =" sons/perdido.mp3 " preload =" auto " id =" somPerdido " > </ audio >	
    < audio  src =" sons/resgate.mp3 " preload =" auto " id =" somResgate " > </ audio >

    < script  type =" text/javascript " src =" js/jquery-1.11.1.min.js " > </ script >
    < script  type =" text/javascript " src =" js/jquery-collision.min.js " > </ script >
    < script  type =" text/javascript " src =" js/main.js " > </ script >
</ corpo >
</ html >
