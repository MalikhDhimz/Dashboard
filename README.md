<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <link rel="stylesheet" type="text/css" href="{{ url_for('static', filename='styles.css') }}">
    <title>Portfolio Website</title>
</head>

<body>
    <header>
        <a href="https://reshanims.carrd.co/?fbclid=PAZXh0bgNhZW0CMTEAAaaGt6PeGqUcduluBfS5arJUgHD5IkKa60TnI3GAkAvZjTMebyRMMICmv34_aem_NS_CSKgJt0Xbx9g7ebtzFA"
            class="logo">ReshAnims</a>

        <nav>
            <a href="#home" class="active"> Home</a>
            <a href="#About">About</a>
            <a href="#Animations">Animations</a>
            <a href="#Shorts">Shorts</a>
            <a href="#home">Contact</a>
            <a href="/dashboard">Dashboard</a>
            <a
                href="https://reshanims.carrd.co/?fbclid=PAZXh0bgNhZW0CMTEAAaaGt6PeGqUcduluBfS5arJUgHD5IkKa60TnI3GAkAvZjTMebyRMMICmv34_aem_NS_CSKgJt0Xbx9g7ebtzFA">
                Support</a>
        </nav>
    </header>
    <section id="home" class="home pop-up-animation">
        <div class="home-img">
            <img src="https://64.media.tumblr.com/avatar_f09cbedcc3c3_128.pnj"
                style="max-height: 200px; max-width: 200px; border: 3px; border-style: solid; border-color:rgb(203, 116, 253);"
                alt="">
        </div>
        <div class="home-content">
            <h1>Hi, It's <span>Resh</span></h1>
            <h3 class="typing-text">I'm a <span></span></h3>
            <p></p>
            <div class="social-icons">
                <a href="https://reshanims.tumblr.com/"><i class="fa-brands fa-tumblr"></i></a>
                <a href="https://www.youtube.com/reshanims"><i class="fa-brands fa-youtube"></i></a>
                <a href="https://x.com/ReshAnims"><i class="fa-brands fa-x-twitter"></i></a>
                <a href="https://www.instagram.com/reshanimates/"><i class="fa-brands fa-instagram"></i></a>
            </div>
            <a href="mailto:reshanimscontact@gmail.com" class="btn">Hire me</a>
        </div>
    </section>

    <section id="About" class="About pop-up-animation">
        <div class="About-img">
            <img src="resh.jpg" alt="">
        </div>
        <div class="About-content">
            <h1>Who <span>am i?</span></h1>
            <p>I'm a content creator and animator that has over 221k subscribers on YouTube. I'm known for my work in
                animation, storytelling, and creative visuals.
                I also do other stuff like art commissions online.
            </p>

            <!-- Section for Full Videos -->
            <section id="Animations" class="Animations pop-up-animation">
                <h1>Videos</h1>

                <!-- Embed YouTube Video -->
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/FZSkFLJx4fE?si=arnvuGs2qkJIacW0"
                        title="YouTube video player" frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </div>
                <!-- Embed Another YouTube Video -->
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/Fe-IWFYd4Ps?si=XGpo0_FRt4SyoX6j"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/dxiE9OqJ2Sc?si=qNst-J8m6jvz9WF4"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>    
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/Zi5lS0sBbh0?si=qk637AW7Eq3ghNTj"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>                           
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/tudCWKkndc4?si=0yNBXWP51nO_gEQ1"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>                        
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/MHx1ychKwgs?si=PNh7SIsjaNp2PoS1"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>                        
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/X69QiVfq5pw?si=Bh1E28KU1V64Y7BP"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>                    
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/s1QP3RhHWt4?si=koVkQJM9FAB82mQA"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>                    
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/9HyzDwuAqog?si=0sqBbb9aNQ7FpH_e"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>    
                
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/bPp5XOku9_A?si=FLbmtw-QuGBv1VjC"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe></div>
                
                <div class="video-container">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/75PnoOxKrvM?si=PcLSBL8pseks0LKN"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>

            </section>

            <!-- Section for Shorts -->
            <section id="Shorts" class="Animations pop-up-animation">
                <h1>Shorts</h1>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/711433656459214848"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/187190405833"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/187189936669"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/711202992697819136"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/184792567090"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div></section>    
             <section id="Shorts" class="Animations pop-up-animation">
                <h1>Shorts</h1>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/165214338480"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/164996755229"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/700528277873475584"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>
                <div class="video-container">
                    <iframe width="560" height="315" src="https://embed.tumblr.com/embed/post/UG5J82GitCjtSOZkU8sqGw/687796665089998848"
                        frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                        allowfullscreen></iframe>
                </div>                         
            </section>
    <script src="script.js"></script>
</body>

</html>
