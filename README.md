# <a href="javascript:alert('XSS Attack!');">Click me</a>
<div id="injected-content" style="display:none;"></div>
<script>
  document.getElementById("injected-content").innerHTML =
    "<a input='javascript:alert(\"XSS Attack!\")'>clickme</a>";
</script>
