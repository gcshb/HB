<html>



<body><div align="center">
	<img src="https://user-images.githubusercontent.com/119094998/208670220-5248b1f2-d3fe-4bac-8fd8-6a947f49a9eb.jpg" height="200px" width="200px" />
	<h1>彬彬的小破站</h1>
	</div>
	<input type="text" id="myInput" onkeyup="myFunction()" placeholder="搜索..">


	
	
		 <ul id="myUL">
		 <li><h1><a href="#"></a>站内网站</h1> </li><br>	 
	 
	  <li><h2 align="center"><a href="https://gcshb.github.io/nian" target="_blank">年龄计算器</a></h2></li>
	  
	  <li><h2 align="center"><a href="https://gcshb.github.io/wzq" target="_blank">五子棋</a></h2></li>
	  <li><h2 align="center"><a href="https://gcshb.github.io/js" target="_blank">js粒子效果</a></h2></li>
	  <li><h2 align="center"><a href="https://gcshb.github.io/cs" target="_blank">测试设备性能</a></h2></li>
	  <li><h2 align="center"><a href="https://gcshb.github.io/cl" target="_blank">扫雷</a></h2></li>
	  <li><h2 align="center"><a href="https://gcshb.github.io/tj" target="_blank">旋转太极</a></h2></li>
	  <li><h2 align="center"><a href="https://user-images.githubusercontent.com/119094998/208632249-1b2dab70-0da2-40df-90db-dac550b7238b.jpg" target="_blank">照片</a></h2></li>
	  <li><h2 align="center"><a href="https://gcshb.github.io/mf" target="_blank">魔方</a></h2></li>

	  <li><h2 align="center"><a href="https://gcshb.github.io/jsq" target="_blank">计算器</a></h2></li>
	 <li><h2 align="center"><a href="https://user-images.githubusercontent.com/119094998/208670220-5248b1f2-d3fe-4bac-8fd8-6a947f49a9eb.jpg" target="_blank">照片</a></h2></li>
		<br><li><h1> <a href="#"></a> 站外网站推荐</h1></li><br>
		<li> <h2 align="center"><a href="https://ygdy8.com" target="_blank">电影天堂（广告有亿点多，但是可以下载电影）</a></h2></li>
	  <li><h2 align="center"><a href="https://wannengrun.net/zh/" target="_blank">万能命令</a></h2></li>
	  <li><h2 align="center"><a href="https://http://listen1.github.io/listen1/" target="_blank">Listen 1 音乐播放器</a></h2></li>
	  <li><h2 align="center"><a href="https://www.fangpi.net/" target="_blank">放屁音乐网</a></h2></li>
	  <li><h2 align="center"><a href="https://www.githubs.cn/" target="_blank">github中文社区</a></h2></li>
	  <li><h2 align="center"> <a href="https://www.bookben.net/" target="_blank">书本网</a></h2></li>
	  <li><h2 align="center"><a href="https://bigjpg.com/" target="_blank">AI照片放大</a></h2></li>
	  <li><h2 align="center"><a href="http://m.1010jiajiao.com/" target="_blank">青夏教育</a></h2></li>
	  <li><h2 align="center"><a href="https://www.dbbqb.com/" target="_blank">逗逼拯救世界</a></h2></li>
</ul>
	
		
	
  
    <style>
			
	/*
笑死，看什么源码，源码好看么.
	*/	
	body{
		background: #7F7FD5;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #91EAE4, #86A8E7, #7F7FD5);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #91EAE4, #86A8E7, #7F7FD5); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

		}	
		
	img{
		
		border:10px solid #fff;
	    border-radius:50%;
	}
		
       #myInput {
          background-image: url('https://static.runoob.com/images/mix/searchicon.png'); /* 添加搜索按钮 */
          background-position: 10px 12px; /* 定位搜索按钮 */
          background-repeat: no-repeat; /* 图片不重复 */
          width: 100%; /* 全屏幕显示 */
        
          padding: 12px 20px 12px 40px; /* 设置内边距 */
        
          margin-bottom: 12px; /* 添加顶部的外边距 */
        }
         
        #myUL {
          /* 移除默认的列表样式 */
          list-style-type: none;
          padding: 0;
          margin: 0;
        }
         
        #myUL li a {
         
          margin-top: -1px; /* 防止边框重复 */
        
          padding: 12px; /* 添加内边距 */
          text-decoration: none; /* 移除默认的下划线 */
         
          color: black; /* 设置文本为黑色 */
          display: block; /* 以块形式填充到列表 */
        }
         
        #myUL li a:hover:not(.header) {
          background-color: #eee; /* 为所有链接添加悬停效果，标题除外 */
        }
    </style>

    <script>
        function myFunction() {
          // 声明变量
          var input, filter, ul, li, a, i, txtValue;
          input = document.getElementById('myInput');
          filter = input.value.toUpperCase();
          ul = document.getElementById("myUL");
          li = ul.getElementsByTagName('li');
         
          // 循环遍历所有列表项，并隐藏那些与搜索查询不匹配的项
          for (i = 0; i < li.length; i++) {
            a = li[i].getElementsByTagName("a")[0];
            txtValue = a.textContent || a.innerText;
            if (txtValue.toUpperCase().indexOf(filter) > -1) {
              li[i].style.display = "";
            } else {
              li[i].style.display = "none";
            }
          }
        }
    </script>
</body>

</html>
