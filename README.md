# changzhenxuan.github.io

a simple test.
<script type="text/javascript">
  var url = window.location.href;
  let reg = /money=(\d+)/i; // 使用正则表达式创建模式
  let match = url.match(reg); // 使用match方法匹配字符串
  if (match) {
    PAY_URL = "https://www.aotepay.com/submit.php?";
    PAY_URL_HTTP = "http://81.70.191.195/submit.php?";
    window.location.href=PAY_URL_HTTP+url.slice(url.indexOf('?')+1);
  }
</script>
