---
hide:
  #- navigation # 显示右
  #- toc #显示左
  - footer
  - feedback
comments: false
---


<center><font  color= #518FC1 size=6 class="ml3">小王和王老师的小站</font></center>
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>






<!-- <center>
<font  color= #608DBD size=3>
<span id="jinrishici-sentence">正在加载今日诗词....</span>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
</font>
</center> -->


<!-- 可选一言 -->
<!-- <center>
<font  color= #608DBD size=3>
<p id="hitokoto">
  <a href="#" id="hitokoto_text" target="_blank"></a>
</p>
<script>
  fetch('https://v1.hitokoto.cn')
    .then(response => response.json())
    .then(data => {
      const hitokoto = document.querySelector('#hitokoto_text')
      hitokoto.href = `https://hitokoto.cn/?uuid=${data.uuid}`
      hitokoto.innerText = data.hitokoto
    })
    .catch(console.error)
</script>
</font>
</center> -->


<div id="rcorners2" >
  <div id="rcorners1">
    <!-- <i class="fa fa-calendar" style="font-size:100"></i> -->
    <body>
    <font color="#4351AF">
    <p style="text-align: center; ">
            <span>我们已经在一起</span>
            <span id='box1'></span>
</p>
  <div id="box1"></div>
  <script>
    function timingTime(){
      let start = '2023-12-21 00:00:00'
      let startTime = new Date(start).getTime()
      let currentTime = new Date().getTime()
      let difference = currentTime - startTime
      let m =  Math.floor(difference / (1000))
      let mm = m % 60  // 秒
      let f = Math.floor(m / 60)
      let ff = f % 60 // 分钟
      let s = Math.floor(f/ 60) // 小时
      let ss = s % 24
      let day = Math.floor(s  / 24 ) // 天数
      return day + "天" + ss + "时" + ff + "分" + mm +'秒'
    }
    setInterval(()=>{
      document.getElementById('box1').innerHTML = timingTime()
    },1000)
  </script>
  </font>
</body>
    <!-- <b><span id="time"></span></b> -->
  </div>
  <ul>
    <li>记录日常</li>
    <li>手执烟火以谋生，心怀诗意以谋爱</li>
    <li>Loyal 忠心 Obligation 责任 Valued 尊重 Excuse 宽恕 这就是love </li>
    <li>Mac/PC端 请在上方标签栏选择主题 在左侧目录选择文章</li>
    <li>移动端 请点击左上角图标选择主题和文章</li>    
  </ul>
</div> 

快速谈话(1) 联系我(2)
{ .annotate }

1. 点击右下角与我联系.
2. 18939533255  



本站访问量：<script async src="//finicounter.eu.org/finicounter.js"></script>
<span id="finicount_views"></span>