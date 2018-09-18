# jscode
on cliking anywhere in body close topbar dropdown in mvc

<script>
        $(document).ready(function () {
            $("#body").mouseup(function (e) {
                var subject = $("#mySidenav1");
                if (e.target.id != subject.attr('id') && !subject.has(e.target).length) {
                    subject.hide();
                }
            });
        });
    </script> 
    Loudo function
   
   <script>
     var temp=0;
function myFunction() {
    var x = Math.floor((Math.random() * 6) + 1);
    document.getElementById("demo").innerHTML = "You Got " + x;
    temp=temp+x;
  document.getElementById("demo1").innerHTML = "Proceed BY "+temp;
  if (temp>50){
 document.getElementById("demo1").innerHTML = "Won ";
 document.getElementById("demo").innerHTML = "Completed ";
}
}

</script>
