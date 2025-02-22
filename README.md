<p id="message">Click the button to change this text.</p>
<button id="btn">Click Me</button>

<script>
document.getElementById("btn").addEventListener("click", function() {
    let message = document.getElementById("message");
    
    if (message.innerText === "Click the button to change this text.") {
        message.innerText = "Text changed";
        message.style.color = "Green";
    } else {
        message.innerText = "Click the button to change this text.";
        message.style.color = "black";
    }
});
</script>
