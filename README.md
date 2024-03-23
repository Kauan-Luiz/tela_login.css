# tela_login.css
o css da tela de login


html, body {
    min-height: 100%;
    @import url('https://fonts.googleapis.com/css2?family=Fjalla+One&family=Oswald:wght@200..700&display=swap')
     


}
body {
    background-image: url(https://images.hdqwalls.com/wallpapers/retrowave-neon-4k-aa.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

.caixaDeLogin {
    margin-top: 170px;
    width: 400px;
    height: 500px;
    background: linear-gradient(135deg, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border-radius: 10px 0 0 10px;
    border:1px solid rgba(255, 255, 255, 0.18);
    box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
    backdrop-filter: blur ;
  
}

.loginDireita {
    margin-top: 170px;
    background-color: black;
    width: 400px;
    height: 500px;
    border-radius: 0 10px 10px 0;
    border:1px solid rgba(255, 255, 255, 0.18);

}

.login_mae {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: auto;
    margin-right: auto;
}

h1 {
   margin-top: 30px;
    font-size: large; 
    font-size: 18pt;
    display: flex;
    justify-content: center;
    font-family: "Fjalla One", sans-serif;
    font-weight: 750;
    font-style: normal;
      
      
}

.usuario {
    width: 320px;
    border-radius: 10px;
    box-shadow: blueviolet 0 0 20px;
    background: #201b2c;
    font-size: 12pt;
    color: aliceblue;
    padding: 8px;
    box-sizing: border-box;
    margin-bottom: 20px;
    margin-top: 30px;
}


.senha {
    width: 320px;
    border-radius: 10px;
    box-shadow: blueviolet 0 0 20px;
    background: #201b2c;
    font-size: 12pt;
    color: aliceblue;
    padding: 8px;
    box-sizing: border-box;
    margin-bottom: 20px;
    margin-top: 30px;
}

.textfield {
    margin-left: 45px;
    
}
p {
    margin-top: 50px;
    font-size: 15pt;
    color: #87CEFA;
    display: flex;
    justify-content: center;
    cursor: pointer;

}

.botoes {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    
}

.botao_login {
    margin-top: 20px;
    width: 130px;
    padding: 10px 0px;
    color: aliceblue;
    border-radius: 10px;
    background: #201b2c;
    border: none;
    cursor: pointer;
    box-shadow: blueviolet 0 0 20px;
   
}

.botao_registro {
    margin-top: 20px;
    width: 130px;
    padding: 10px 0px;
    color: aliceblue;
    border-radius: 10px;
    background: #201b2c;
    border: none;
    cursor: pointer;
    box-shadow: blueviolet 0 0  20px;
    
}

