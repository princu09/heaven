## Heaven CSS Layout Free Source Code By NorthFox Developers

#### Join Our Telegram Channel [ProgHub09](http://t.me/ProgHub09) and Also Download Our App.

![Video Here](https://github.com/princu09/heaven/blob/master/Heaven%20NFG.gif?raw=true)

#### HTML File

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Heaven | NorthFox Developers</title>
    <link rel="icon" href="https://princu09.github.io/nfwebbuilder/img/logo.png" type="image/gif" sizes="16x16">
</head>

<body>
    <div class="container">
        <div class="banner">
            <h2 id="text">Heaven</h2>
            <div class="clouds">
                <img src="img/cloud1.png" alt="" style="--i:1;">
                <img src="img/cloud2.png" alt="" style="--i:2;">
                <img src="img/cloud3.png" alt="" style="--i:3;">
                <img src="img/cloud4.png" alt="" style="--i:4;">
                <img src="img/cloud5.png" alt="" style="--i:5;">
                <img src="img/cloud1.png" alt="" style="--i:10;">
                <img src="img/cloud2.png" alt="" style="--i:9;">
                <img src="img/cloud3.png" alt="" style="--i:8;">
                <img src="img/cloud4.png" alt="" style="--i:7;">
                <img src="img/cloud5.png" alt="" style="--i:6;">
            </div>
        </div>
    </div>

    <section>
        <h2>This is Truly Heaven-like Paradise.</h2>
        <p>
            &emsp;&emsp;&emsp;&emsp;Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit assumenda delectus praesentium minima repellendus voluptatum quasi sunt perspiciatis hic possimus autem non facilis similique obcaecati deserunt ipsa officia alias
            suscipit tenetur minus, ipsam reiciendis. Numquam aspernatur exercitationem modi est cum? Qui impedit iusto illum nisi laboriosam debitis possimus itaque aperiam commodi, quaerat incidunt eveniet omnis cumque voluptas cupiditate sunt? Ullam
            molestias nam quod aperiam esse aliquam, accusantium temporibus quasi exercitationem deleniti dolor error est asperiores itaque laborum suscipit! Maiores soluta amet veritatis sed modi atque tempore deleniti ut ratione! Ad consequatur adipisci,
            quibusdam animi esse laboriosam sed ratione consequuntur perferendis ut atque magni quisquam vero repudiandae eveniet praesentium, dolores facere! Temporibus, molestias, laborum consequatur, dolor omnis sit minima distinctio dignissimos dolorum
            ea excepturi quidem voluptate? Eveniet dolore error nisi facere. Consectetur corrupti dolores ducimus modi amet accusantium repellat nesciunt voluptatibus sapiente dignissimos, repudiandae maxime et perferendis quos inventore neque culpa,
            incidunt iste dolore! Aliquam odit voluptatum est voluptate in repellat velit dolore, quibusdam quam, laborum totam earum asperiores unde illum ea. Id ea ut expedita dolores temporibus laborum error deleniti mollitia, non corporis vel ducimus
            aperiam excepturi exercitationem? Nam eaque consequatur magnam nostrum nisi asperiores soluta. Hic nisi culpa voluptatum. Numquam beatae consequatur, quas ea quisquam aut dolorem cum fugit autem nam eos ducimus facilis voluptates odio ipsam
            dolore tempora tenetur. Perferendis sunt quasi doloremque error non modi aut eaque voluptate ea autem, dicta blanditiis quis, ratione magni deleniti nam. Ut error neque eius eveniet quae optio laboriosam nostrum repellendus doloribus consequatur
            libero, voluptas fuga ipsam cupiditate harum ratione excepturi architecto totam sunt veniam placeat tempore exercitationem sapiente. Delectus obcaecati voluptates fugit enim, doloribus porro veritatis sit veniam sunt eligendi saepe optio ea
            quia quas? Iste libero, optio, corrupti ab natus eligendi, accusamus porro eius esse delectus alias culpa rem? Pariatur eaque, iure, quidem itaque eos possimus animi harum recusandae veritatis, unde ad ullam inventore. Suscipit possimus alias
            consequatur asperiores? Hic commodi voluptates dolor sit nihil, velit necessitatibus mollitia pariatur voluptatum! Eaque animi explicabo dolor sunt deleniti ex tempore minima? Ducimus dicta explicabo natus consequatur. Impedit, blanditiis
            ratione cumque rem excepturi possimus. Delectus debitis ullam labore aspernatur cumque! Id nihil consequatur, iure explicabo corporis omnis nobis quidem amet quae in, delectus voluptatum asperiores velit. Dolores, voluptatem, nihil nostrum
            fugiat aspernatur reprehenderit beatae sed aut recusandae quas, itaque sunt in vel cumque odio placeat! Aliquid reprehenderit reiciendis impedit, placeat corporis, velit saepe repellat molestiae exercitationem dolore error. Sunt iure eaque
            quia, doloremque consequatur totam fugit exercitationem, possimus tenetur impedit numquam dolorum quaerat atque ipsum quisquam nostrum. Deleniti laborum nobis facilis sequi inventore quisquam quia reprehenderit, debitis voluptas atque molestias
            ea incidunt nostrum labore hic dolore sit cum sunt eius totam suscipit temporibus dignissimos! Voluptatibus unde ab illum quia perspiciatis ad, harum enim, dignissimos at incidunt itaque! Vero quod vel sapiente saepe animi eaque voluptates
            assumenda optio fugiat

        </p>
        <h6>
            Created By NorthFox Developers | NorthFox Group
        </h6>
    </section>

    <script type="text/javascript">
        let text = document.getElementById('text');
        window.addEventListener('scroll', function() {
            let value = window.scrollY;
            text.style.marginBottom = value * 2 + 'px';
        })
    </script>



    <!-- Created By NorthFox Group -->
</body>

</html>
```

#### CSS File

 ```
/* Owner: NorthFox Developers
Developer: Prince Patel
Oraganization: NorthFox Group
Code: Totally Free For Developing */

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');

/* Created By NorthFox Group */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

.banner {
    width: 100%;
    height: 100vh;
    background: url(img/bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: bottom;
    display: flex;
    justify-content: center;
    align-items: center;
}

.banner #text {
    position: relative;
    font-size: 12em;
    color: #fff;
}

.banner .clouds {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
    pointer-events: none;
}

.banner .clouds img {
    position: absolute;
    bottom: 0;
    max-width: 100%;
    animation: animate calc(1s * var(--i)) linear infinite;
}

@keyframes animate {
    0% {
        opacity: 0;
        transform: scale(1);
    }
    25%,
    75% {
        opacity: 1;
    }
    100% {
        opacity: 0;
        transform: scale(3);
    }
}

section {
    position: relative;
    padding: 75px 50px;
}

section h2 {
    position: relative;
    font-size: 2.5em;
    text-align: center;
    margin-bottom: 50px;
}

section p {
    font-weight: 400;
    line-height: 30px;
}

section h6 {
    position: relative;
    font-weight: unset;
    font-size: 1em;
    text-align: center;
    margin-top: 30px;
    color: #999;
}

@media (max-width: 720px) {
    .banner #text {
        position: relative;
        font-size: 5em;
        color: #fff;
    }
    .banner .clouds img {
        position: absolute;
        bottom: 0px;
        animation: animate calc(1s * var(--i)) linear infinite;
    }
    section {
        position: relative;
        padding: 50px 20px;
    }
    section h2 {
        position: relative;
        font-size: 1.4em;
        text-align: center;
        margin-bottom: 50px;
    }
}

@media (max-width: 300px) {
    .banner #text {
        position: relative;
        font-size: 2em;
        color: #fff;
    }
    .banner .clouds img {
        position: absolute;
        bottom: 0;
        animation: animate calc(1s * var(--i)) linear infinite;
    }
    section {
        position: relative;
        padding: 50px 20px;
    }
    section h2 {
        position: relative;
        font-size: 1.4em;
        text-align: center;
        margin-bottom: 50px;
    }
}
 ```
