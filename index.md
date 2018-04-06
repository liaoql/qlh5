<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title></title>

    <script language="JavaScript">
        <!--

        function upbookinto(titleinto){
            document.bookform.booktitle.value=titleinto
            document.bookform.bookauth.value=this.auth
            document.bookform.bookpublisher.value=this.publisher
        }


        function book ( title,auth ,pubilsher){
            this.title=title
            this.auth=auth
            this.publisher=pubilsher
            this.upinto=upbookinto
        }
        }
                -->



    </script>
</head>
<body>

<script language="JavaScript">
    var books = new Array()
    books[0]=new books("算法与数据结构","liao","qinghua")
    books[1]= new books("jspxml","qi","qinghua")
    books[2]=new books("字典","qqq","qqqq")

</script>

<font color="#faebd7" face="隶书" size="7">点击按钮查看信息

<form action="" name="bookform">

    <input type="button" value="算法与数据结构 "  onclick="books[0].Upinto('算法与数据结构')"/><p>
    <input type="button" value="jspxml "  onclick="books[1].Upinto('jspxml')"/><p>
    <input type="button" value="字典 "  onclick="books[2].Upinto('字典')"/><p>


    书名：<input type="text" name="booktitle"/><p>
    作者：<input type="text" name="bookauth"/><p>
    出版社：<input type="text" name="bookpublisher"/><p>


</font>
</form>
</body>
</html>
