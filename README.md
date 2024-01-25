
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
    <style>
        body{
            background-color: rgb(17, 206, 206)
        }
        input#AC:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#AC {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            border-radius: 50%;
            position: absolute; top: 150px; left: 60px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px;}
           input#back:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#back {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            border-radius: 50%;
            position: absolute; top: 150px; left: 140px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; } 
        input#cento:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#cento {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            border-radius: 50%;
            position: absolute; top: 150px; left: 220px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }
           input#dividir:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#dividir {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            opacity: 0.6 ;
            border-radius: 50%;
            position: absolute; top: 150px; left: 300px;
           height: 60px;
           width: 60px;}
           input#sete:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);  
        }
        input#sete {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 220px; left: 60px;
           height: 60px;
           opacity: 0.6 ;
           width: 60px; }
           input#oito:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);          
        }
        input#oito {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 220px; left: 140px;
           height: 60px;
           opacity: 0.6 ;
           width: 60px; }
           input#nove:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);          
        }
        input#nove {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 220px; left: 220px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }
           input#vezes:hover {
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color:rgb(20, 0, 90);
        }
        input#vezes {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            opacity: 0.6 ;
            border-radius: 50%;
            position: absolute; top: 220px; left: 300px;
            height: 60px;
            width: 60px;
        }
           input#quatro:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);  
        }
        input#quatro {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            opacity: 0.6 ;
            border-radius: 50%;
            position: absolute; top: 290px; left: 60px;
           height: 60px;
           width: 60px; }
           input#cinco:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);  
        }
        input#cinco {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 290px; left: 140px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }
           input#seis:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);  
        }
        input#seis {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            opacity: 0.6 ;
            position: absolute; top: 290px; left: 220px;
           height: 60px;
           width: 60px; }
           input#menos:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#menos {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            border-radius: 50%;
            position: absolute; top: 290px; left: 300px;
           height: 60px;
           opacity: 0.6 ;
           width: 60px; }
           input#um:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);  
        }
        input#um{
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 360px; left: 60px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }
           input#dois:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(33, 66, 66);  
        }
        input#dois {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 360px; left: 140px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }
           input#tres:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(33, 66, 66);  
        }
        input#tres {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 50%;
            position: absolute; top: 360px; left: 220px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }
           input#mais:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#mais {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            border-radius: 50%;
            position: absolute; top: 360px; left: 300px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }

           input#zero:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 10px; color: rgb(0, 0, 0);}
        input#zero {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius: 30px; 
            opacity: 0.6 ;
            position: absolute; top: 430px; left: 60px;
           height: 60px;
           width: 140px; }

           input#vir:hover { 
            border: 1px solid;
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(142, 146, 146);  }
        input#vir {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(133, 76, 184);
            border-radius:  50%;
            opacity: 0.6 ;
            position: absolute; top: 430px; left: 220px;
           height: 60px;
           width: 60px; }
           input#igual:hover { 
            border: 1px solid rgb( 0, 0, 0);
            box-shadow: 0px 0px 0px, 0px 0px 18px; color: rgb(20, 0, 90);
        }
        input#igual {
            font-size: 130%;
            color: rgb(0, 0, 0);
            background-color: rgb(74, 128, 182);
            border-radius: 50%;
            position: absolute; top: 430px; left: 300px;
            opacity: 0.6 ;
           height: 60px;
           width: 60px; }

           div#res {
            text-align-last: right;
            position: absolute; top: 70px; left: 50px;
            border-radius: 50px;
            z-index: 2;
            width: 300px;
            height: 50px;
            background-color: rgb(235, 217, 217);
            border-top: 3px solid rgb(59, 25, 88);
            border-right: 7px solid rgb(59, 25, 88);
            border-bottom: 7px solid rgb(59, 25, 88);
            
               
            }
        div#area {
            position: absolute; top: 150px; left: 50%; transform: translate(-50%, -50%);
            margin-top: 150px; 
            width: 400px;
            height: 525px;
            background-color: rgb(221, 195, 199);
            border-radius: 10%; 
            border-top: 5px solid rgb(59, 25, 88);
            border-right: 20px solid rgb(59, 25, 88);
            border-bottom: 15px solid rgb(59, 25, 88);
            z-index: 1;
            }
            
            div#num {
                position: relative; top: 15px; right: 20px;
                font: 20pt arial;
            }

            
            body{
            background-color: rgb(21, 83, 83)
            }
       
    </style>
    <div id="area">
        <input type="reset" value="AC" id="AC" onclick="limpar()">
        <input type="button" value="⌫" id="back" onclick="back()">
        <input type="button" value="%" id="cento" onclick="porcento()">
        <input type="button" value="=" id="igual" onclick="resultado()">
        
        <input type="button" value="-" id="menos" onclick="menos()">
        <input type="button" value="+" id="mais" onclick="mais()">
        <input type="button" value="x" id="vezes" onclick="mult('*')">
        <input type="button" value="7" id="sete" onclick="sete()">
        
        <input type="button" value="8"id="oito" onclick="oito()">
        <input type="button" value="9" id="nove" onclick="nove()">
        <input type="button" value="4" id="quatro" onclick="quatro()">
        <input type="button" value="5" id="cinco" onclick="cinco()">
        <input type="button" value="6" id="seis" onclick="seis()">
        <input type="button" value="1" id="um" onclick="um()">
        <input type="button" value="2" id="dois" onclick="dois()">
        <input type="button" value="3" id="tres" onclick="tres()">
        <input type="button" value="0" id="zero" onclick="zero()">
        <input type="button" value="." id="vir" onclick="virgula('.')">
        <input type="button" value="/" id="dividir" onclick="dividir('/')">
    
           <div id="res">
            <div id="num">
                
            </div>
    </div>
    <script>
   
        function um(){
                let numbe = document.getElementById('num')
                numbe.innerHTML += 1
            }
        function dois(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 2
        }
        function tres(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 3 
        }
        function quatro(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 4
        }
        function cinco(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 5
        }
        function seis(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 6
        }
        function sete(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 7
        }
        function oito(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 8 
        }
        function nove(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 9
        }
        function zero(){
            let numbe = window.document.getElementById ('num')
            numbe.innerHTML += 0
        }
        function limpar(){
            window.document.getElementById ('num').innerHTML = '';
        }
        function mult(){
            let nve = window.document.getElementById ('num')
            nve.innerHTML += '*'
            
        }
         
        function dividir(){
            let nd = window.document.getElementById ('num')
            nd.innerHTML += '/'
        }
      
        function menos(){
            let nme = window.document.getElementById ('num')
            nme .innerHTML += '-'
        }
        function mais(){
            let nma = window.document.getElementById ('num')
            nma.innerHTML += '+'
        }
        function virgula(){
            let nv = window.document.getElementById ('num')
            nv.innerHTML += '.'
        }
        function back(){
            let numb = window.document.getElementById ('num').innerHTML
            window.document.getElementById ('num').innerHTML = numb.substring(0 ,  wnumb.length -1)
            }
        function resultado(){
            let numr = window.document.getElementById ('num').innerHTML
            if (numr){
                window.document.getElementById ('num').innerHTML = eval(numr)
            } else {
                window.document.getElementById ('num').innerHTML = '0'
            }}
        
            function porcento(){
            let np = window.document.getElementById ('num').innerHTML
            if (np => 1) { 
                document.getElementById ('num').innerHTML = eval(np) / 100 
            } else { document.getElementById ('num')= '0'
        }
            }
        
        
       
        
    </script>
    
</body>
</html>
![image](https://github.com/Diogoxxs/It-is/assets/156117644/47419894-c665-4a2f-a219-5b97a7cd15f0)
