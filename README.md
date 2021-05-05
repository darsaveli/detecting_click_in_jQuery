# detecting_click_in_jQuery

<script type="text/javascript">
  
  document.getElementById("mybutton").onclick = function () {
  
  allert ("Button clicked!");
  
}

</script>

The following is the same in jQuery:

<script type="text/javascript">
            
            $("div").click(function() { //("div") or ("#circle") or(".square") --> depends with what we want to interact.
                
                alert("a div was clicked!");
                
            });
            

</script>

