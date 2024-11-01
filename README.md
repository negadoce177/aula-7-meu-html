# aula-7-meu-html
 background: black;
    margin: 1px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
@@ -32,20 +33,9 @@ p {
    font-size: 20px;
}

img {
    height: 300px;
}
.categoria-videos {
    display: flex;
    overflow-x: auto;
@@ -45,4 +44,19 @@ img {
.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}
.categoria-videos img {
    opacity: 0.6;
    height: 200px;
}
.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}
.categoria h2 {
    color: rgb(62, 144, 220);
}
