# OWL Tube - OWL Carousel Youtube Playlist

    Options | default
    
    width:640
    height:340
    autoplay:1
    loop:1
    controls: 1
    iv_load_policy:3
    modestbranding:1
    rel:0
    showinfo:0

examle:
    ...

    <link rel="stylesheet" href="../vendors/bootstrap/bootstrap.min.css">
    <link rel="stylesheet" href="../vendors/owl-carousel/assets/owl.carousel.min.css">
    <link rel="stylesheet" href="../vendors/owl-carousel/assets/owl.theme.default.min.css">
    <link rel="stylesheet" href="../vendors/owl-carousel/assets/owl.theme.green.min.css">
    
    <body>
        <div class="owl-carousel owl-theme">
            <div class="item">
                    <iframe type="text/html" width="720" height="405"
                    src="https://www.youtube.com/embed/M7lc1UVf-VE?enablejsapi=1"
                    frameborder="0" allowfullscreen></iframe>
            </div>
            <div class="item">
                    <iframe type="text/html" width="720" height="405"
                    src="https://www.youtube.com/embed/eRiyV1Kan24?enablejsapi=1"
                    frameborder="0" allowfullscreen></iframe>
            </div>
            <div class="item">
                    <iframe type="text/html" width="720" height="405"
                    src="https://www.youtube.com/embed/9aipBufoJP8?enablejsapi=1"
                    frameborder="0" allowfullscreen></iframe>
            </div>

            <div class="item">
                    <iframe type="text/html" width="720" height="405"
                    src="https://www.youtube.com/embed/flU42CTF3MQ?enablejsapi=1"
                    frameborder="0" allowfullscreen></iframe>
            </div>
        </div>

        ...


        <!--vendors-files-->
        <script src="../vendors/jquery/jquery-3.3.1.min.js"></script>
        <script src="../vendors/bootstrap/popper.min.js"></script>
        <script src="../vendors/bootstrap/bootstrap.min.js"></script>
        <script src="../vendors/owl-carousel/owl.carousel.min.js"></script>

        <!--owl-tube-file-->
        <script src="../dist/assets/js/owl-tube.min.js"></script>

        <script>

        $(document).ready(function(){
            var carousel = $('.owl-carousel').owlCarousel({
                items:1,
                loop:1,
                nav:1,
                dots:1
            });
            window.owlTube = $(carousel).owlTube();
            
        });
        </script>