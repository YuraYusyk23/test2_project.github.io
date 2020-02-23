Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@YusykYura 
Learn Git and GitHub without any code!
Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.


YusykYura
/
tasks
1
00
 Code Issues 0 Pull requests 0 Actions Projects 0 Wiki Security Insights Settings
tasks/task 1/index.html
 yusyk.web@gmail.com init
3743edf on Nov 27, 2019
35 lines (35 sloc)  1.17 KB
  
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Task 1 </title>
    <script src="index.js"></script>
</head>
<body>
    <div>
        <form>
            <fieldset>
                <legend>Вирахування решти</legend>
                <p>
                    <label for="sum">Сума <em>*</em> </label>
                    <input type="text" id="sum">
                </p>
                <p>
                    <label for="price">Ціна <em>*</em> </label>
                    <input type="text" id="price">
                </p>
            </fieldset>
        </form>
        <div>
            <button onclick="calculateRest(document.getElementById('sum').value, document.getElementById('price').value)">Порахувати</button>
        </div>
        <div> Ваша решта:
            <span id="int" style="color: #355470;"></span>
            <span id="afterComa" style="color: #55a7ff;"></span>
        </div>
    </div>
</body>
</html>
