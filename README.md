@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}
main {
     width:100%;
     height:100vh;
     display: flex;
     background-color:rgb(89, 73, 76);
     justify-content: center;
     align-items: center;
   
}
.box {
    width:320px ;
    height: 400px;
    background-color: white;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0px 0px 1px rgb(99, 80, 95);
}
#items{
    width: 100%;
    padding: 10px;
    border-color:rgb(121, 114, 114);
    box-shadow: 0px 0px 2px rgb(60, 54, 54);
    font-size: 20px;
    display: block;
    border-radius: 10px;
}
#to-do-box{
     margin-top: 20px;
     list-style: none;
}
#to-do-box li{
    position: relative;
    background-color: gray;
    color: white;
    padding: 10px;
    border-radius: 5px;
    padding-right:30px;
    text-align:justify;
    margin-top:10px;
    user-select:none;
 }
   
 #to-do-box li i{
    position: absolute;
    right: 10px;
    top: 10px;
} 

.done {
    text-decoration: line-through;
    color: black;
    background-color: #95a5a6 !important;
}
