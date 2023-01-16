
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
            <p id="question"><span>Leslie gwapo ko dili?</span></p>
            <button class="btn" id="gwapo"><b>gwapo</b></button>
            <button class="btn" id="dili"><b>dili</b></button>
        </div>
    </div> 
<script>
    const noBtn = document.getElementById('dili');
    const yesBtn = document.getElementById('gwapo');
    const ques = document.getElementById('question');
    let btn = document.getElementById('btn');
        let position;
        noBtn.addEventListener('mouseover',() =>{
        let rand = Math.floor(Math.random() * (500 - 100) + 1);
        let rand2 = Math.floor(Math.random() * (-300 - 100) + 1);
        noBtn.style.transform = "translate("+rand+"px,"+rand2+"px)";
        });
    yesBtn.addEventListener("click",()=>{
        ques.innerHTML = "ayw nag palag gwapo lagi ko hahahahhaha"
    })
</script>
<div>
    <p1>Created by Ramil Baruiz</p1>
</div>

