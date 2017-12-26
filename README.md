# scrollTop
scrollTop
 <body>
	<div id="toTop">
		<a href="#">返回顶部</a>
	</div>
  <script>
    document.addEventListener('scroll',
      function(){
        var scrollTop=document.body.scrollTop;
        document.getElementById("toTop")
                .style.display=
                  scrollTop>500?"block":"none";
      }
    );
	</script>
 </body>
