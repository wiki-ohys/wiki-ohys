<html>
<head>
    <title>Saqib</title>
    <style>
        .gc {
            display: grid;
            grid-template-columns: auto auto auto auto;
            gap: 5px
        }
        .gi {
            background-color: aquamarine;
            border: 1px solid red;
            padding: 10px;
            text-align: center
        }
        .btn {
            background-color: red;
            width: 40px;
            border-radius: 7px;
            text-align: center;
            color: white;
            padding: 5px;
            margin: 10px auto;
        }
        .fb {
            display: flex;
            justify-content: space-around; 
        }
        .item {
            margin: 6px
        }
@media (max-width: 600px) {
    .gc {
        grid-template-columns: none;
    }
  }
</style>
    </head>
<body>
    <h1>Center Div</h1>
<div class="gc">
    <div class="gi">this is the first item
    <div class="btn">go</div>
         </div> 
    <div class="gi">this is the second item</div>
    <div class="gi">this is the third item</div> 
    <div class="gi">this is the fourth item</div>
    </div>
    </body>
</html>