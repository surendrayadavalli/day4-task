<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    <script>
        // <!-- 1.how to compare two JSON have the same properties without order?
    var obj1={name:"person1",age:5};
    var obj2={age:5,name:"person1"}
    var a=JSON.stringify(obj1)==JSON.stringify(obj2)
    console.log(a)
    </script>
    </body>

</html>
