# wl-novel
<script>
    function showText() {
        const val = document.getElementById("matn").value;
        document.getElementById("natija").innerText = val;
    }
</script>

<h2>✍️ Yoz matnni — pastda chiqadi:</h2>
<textarea id="matn" rows="10" cols="60" placeholder="Bu yerga yoz..."></textarea><br>
<button onclick="showText()">Ko‘rsatish</button>

<h3>📖 Natija:</h3>
<div id="natija" style="border:1px solid gray; padding:10px;"></div>
