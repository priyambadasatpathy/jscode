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
