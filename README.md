* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body, html {
    height: 100%;
    overflow: hidden;
    font-family: Arial, sans-serif;
}

.background {
    position: relative;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

.mountain {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: auto;
}

.donkey-container {
    position: absolute;
    bottom: 150px;
    left: 0;
    animation: run 5s linear infinite;
}

.donkey {
    width: 100px;
    height: auto;
}

@keyframes run {
    0% {
        left: -120px;
    }
    100% {
        left: 100%;
    }
}
