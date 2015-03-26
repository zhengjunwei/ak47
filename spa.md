## 结构 of spa

### spa.html

<!doctype html>
<html>
  <head>
   
    <style src="spa.init.css"></style>
   <script src="spa.js"></script> 
  <script src="spa.util.js"></script>
  <script src="spa.shell.js"></script>
  <script src="spa.caht.js"></script>
  </head>
  <body>
    <div id="spa"></div>
  </body>
</html>

### spa.shell.js
jquery.ready(function(){
  var jquery_parameters = {};
  var state_map = {};
  var global_parameters = {};
  
 function init(){};
});



加载顺序约定:根->核心工具方法->Model->浏览器端工具方法->Shell->功能模块
