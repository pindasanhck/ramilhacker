<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name='viewport' content='width=320' />
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="style.css">
    <title>Pindutin mo nalang yun Oo<3</title>
<body>
    <div class="ost-multi-header">
    <div class="w3-container w3-center w3-animate-zoom">
    <div class="wrapper">
        <div class="container">
            <p id="question"><span>Crush mo'ko no?</span></p>
            <button class="btn" id="Oo"><b>Oo</b></button>
            <button class="btn" id="Hinde"><b>Hinde</b></button>
        </div>
    </div> 
</body>
<script>
    const noBtn = document.getElementById('Hinde');
    const yesBtn = document.getElementById('Oo');
    const ques = document.getElementById('question');
    let btn = document.getElementById('btn');
        let position;
        noBtn.addEventListener('mouseover',() =>{
        let rand = Math.floor(Math.random() * (500 - 100) + 1);
        let rand2 = Math.floor(Math.random() * (-300 - 100) + 1);
        noBtn.style.transform = "translate("+rand+"px,"+rand2+"px)";
        });
    yesBtn.addEventListener("click",()=>{
        ques.innerHTML = "Ikaw Haaaaa HAHAHAHAHA <3"
    })
</script>
<div>
    <p1>Created by jnthn_hdlg</p1>
</div>
</html>
