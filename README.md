@import url('https://fonts.googleapis.com/css2? family= Open+Sans:ital,wght@0,300;0,400;1,500 & display=swap');

  {
     margin: 0;
     padding: 0;
     font-family: 'Open Sans', sans-serif;
}

body {
    height: 100vh;
    background: linear-gradient(120deg, #ffe53bd8, #ff2525da);
    display: flex;
    align-items: center;
    justify-content: center;
}

.relogio {
    display: flex;
    align-items: center;
    justify-content: space-around;
    height: 200px;
    width: 550px;
    background: transparent;
    border-radius: 3px;
    box-shadow: 0px 8px 10px rgba(0, 0, 0, .5);
}

.relogio div {
    height: 170px;
    width: 150px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: #fff;
    background: rgba(5, 5, 5, .9);
    box-shadow: 5px 5px 15px rgba(0, 0, 0, .7);
    border-radius: 7px;
    letter-spacing: 3px;
}

.relogio span {
    font-weight: bolder;
    font-size: 60px;
}

.relogio span.tempo {
    font-size: 10px;

}
