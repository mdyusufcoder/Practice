*{
    margin: 0;
    padding: 0;
    width: 100%;

}

.header{
    background-color: red;
    width: 100%;
    display: flex;
}
.header nav ul li{
    display: flex;
    list-style: none;
}

.course-box {
    width: 33.33%;
    text-align: center;
    background-color: #C6C6C7;
    padding: 35px 15px;
    border-radius: 10px;
    /* margin: 10px; */
}

.courses-box {
    display: flex;
}

.ri-hospital-fill {
    background-color: red;
    
}

.title{
    margin-left: 15px;
    margin-right: 15px;
}

.courses{
   margin-top: 80px;
   margin-bottom: 80px;
    padding-top: 40px;
    padding-bottom: 30px;
    background-color: #F2F2F3;
}


/* Position Peoperties */
.normal {
 background-color: red;
    border: 5px solid green;
    left: 30px;
    /* margin-left: 30px;  - it is work */


}

.static {
    background-color: red;
    position: static;
    border: 5px solid green;
    left: 30px;
    
}

.relative {
    background-color: red;
    position: relative;
    border: 5px solid green;
    left: 50px;
    
}

.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 300px;
  height: 200px;
  border: 3px solid #73AD21;
}
