<html>
<!DOCTYPE html>
<div lang="en">
<head>
    <style>

        body {
	margin:0;
	color:#6a6f8c;
	background:#c8c8c8;
	font:600 16px/20px 'Open Sans',sans-serif;
}

*,:after,:before{box-sizing:border-box}
.clearfix:after,.clearfix:before{content:'';display:table}
.clearfix:after{clear:both;display:block}
a{color:inherit;text-decoration:none}

.login-wrap{
    width:100%;
  margin:auto;
	max-width:100%;
	min-height:670px;
    position:relative;
	background:url(Kartinki_na_rabochiy_stol_dlya_geymerov_29_19123056.jpg) no-repeat center;
	box-shadow:0 12px 15px 0 rgba(0,0,0,.24),0 17px 50px 0 rgba(0,0,0,.19);
}
.login-html{
	width:100%;
	height:100%;
	position:absolute;
	padding:90px 70px 50px 70px;
	background: rgba(31, 107, 22,.1);;
}
.login-html .sign-in-htm,
.login-html .sign-up-htm{
	top:0;
	left:0;
	right:0;
	bottom:0;
	position:absolute;
	transform:rotateY(180deg);
	backface-visibility:hidden;
	transition:all .4s linear;
}
.login-html .sign-in,
.login-html .sign-up,
.login-form .group .check{
	display:none;
}
.login-html .tab,
.login-form .group .label,
.login-form .group .button{
	text-transform:uppercase;
}
.login-html .tab{
	font-size:22px;
	margin-right:15px;
	padding-bottom:5px;
	margin:0 15px 10px 0;
	display:inline-block;
	border-bottom:2px solid transparent;
}
.login-html .sign-in:checked + .tab,
.login-html .sign-up:checked + .tab{
	color:#fff;
	border-color:#1161ee;
}
.login-form{
	min-height:345px;
	position:relative;
	perspective:1000px;
	transform-style:preserve-3d;
}
.login-form .group{
	margin-bottom:15px;
}
.login-form .group .label,
.login-form .group .input,
.login-form .group .button{
	width:100%;
	color:#fff;
	display:block;
}
.login-form .group .input,
.login-form .group .button{
	border:none;
	padding:15px 20px;
	border-radius:25px;
	background:rgba(255,255,255,.1);
}
.login-form .group input[data-type="password"]{
	text-security:circle;
	-webkit-text-security:circle;
}
.login-form .group .label{
	color:#aaa;
	font-size:12px;
}
.login-form .group .button{
	background:#1161ee;
}
.login-form .group label .icon{
	width:15px;
	height:15px;
	border-radius:2px;
	position:relative;
	display:inline-block;
	background:rgba(255,255,255,.1);
}
.login-form .group label .icon:before,
.login-form .group label .icon:after{
	content:'';
	width:10px;
	height:2px;
	background:#fff;
	position:absolute;
	transition:all .2s ease-in-out 0s;
}
.login-form .group label .icon:before{
	left:3px;
	width:5px;
	bottom:6px;
	transform:scale(0) rotate(0);
}
.login-form .group label .icon:after{
	top:6px;
	right:0;
	transform:scale(0) rotate(0);
}
.login-form .group .check:checked + label{
	color:#fff;
}
.login-form .group .check:checked + label .icon{
	background:#1161ee;
}
.login-form .group .check:checked + label .icon:before{
	transform:scale(1) rotate(45deg);
}
.login-form .group .check:checked + label .icon:after{
	transform:scale(1) rotate(-45deg);
}
.login-html .sign-in:checked + .tab + .sign-up + .tab + .login-form .sign-in-htm{
	transform:rotate(0);
}
.login-html .sign-up:checked + .tab + .login-form .sign-up-htm{
	transform:rotate(0);
}

.hr{
	height:2px;
	margin:60px 0 50px 0;
	background:rgba(255,255,255,.2);
}
.foot-lnk{
	text-align:center;
}

    </style>

    <style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@300&display=swap');
{
  margin:0;padding: 0;box-sizing: ;
  font-family: 'Roboto Mono', monospace;
}
body {
position: relative;
margin:0;
  padding: 0;
justify-content:center;
  align-items:center;background: #000;
}
.container
{
  justify-content:space-around;
}
.container .btn {
  position:relative;
  width: 220px;
  height: 50px;
  margin:16px;
}
.container .btn a
{
  position:absolute;
  top:0;
  left:0;
  width:100%;
  height:100%;
  display:flex;
  justify-content:center;
  align-items:center;
  background: rgba(255,255,255,0.07);
  box-shadow: 0 15px 35px rgba(.2);
  border-top: 5px solid rgba(255,255,255,0.1);
  border-bottom:6px solid rgba(255,255,255,0.1);
  border-radius: 30px;
  color: #fff;
  z-index: 1;
  letter-spacing: 1px;
  text-decoration: none;
  overflow: hidden;
  transition: 0.4s;
  backdrop-filter: blur(20px);
}
.container .btn:hover a
{
  letter-spacing: 4px;
}
.container .btn a::before
{
  content: '';
  position: absolute;
  top: 0;
  left: 0;width: 50%;height: 100%;
  background: linear-gradient(to left, rgba(255,255,255,0.15),
  transparent);
  transform: skewX(45deg) translateX(0);transition: 0.4s;
}

.container .btn:hover a::before
{
  transform: skewX(45deg) translateX(200%);
}
.container .btn::before
{
  content: '';
  position: absolute;
  left: 50%;
  transform: translateX(-50%);bottom: -5px;width:30px;height:10px;
  background: #42008e;border-radius: 10px;transition: 0.2s;transition-delay: 0s;
}
.container .btn:hover::before
{
  bottom: 2;
  height: 50%;width: 80%;border-radius: 10px;transition-delay: 0.01s;
}

.container .btn::after

<!-- hack -->
    #container2 {
    background-color: #2e2e2e;with: 100%; margin: 0 auto;border: 3px solid blue;
    }
    .hr-vertical-gradient {
	margin: 10px 0;padding: 0;height: 5px;border: none;
	background: linear-gradient(#3500e5, #44009c, #3500e5);
}
hr {
    border: none;height: 3px;margin: 40px 0;
    background-image: linear-gradient(to right, #3500e5, #44009c, #3500e5);
}
hr:before,
hr:after {
    content: '';height: 40px;border: 3px solid #44009c;position: absolute;left: 50%;transform: translate(-50%, -50%);background: #000000;
    display: inline-block;
    border-radius: 100%;
    width: 40px;

}
hr:after {
    animation: anim-hr 0.8s linear infinite;
}
@keyframes anim-hr {
    0% {
        width: 30px;
        height: 30px;
    }
    100% {
        width: 0;
        height: 0;
    }
}
    </style>
    <style>
.square {
  border: 10px solid ;
  border-image: linear-gradient(90deg, #1200b2 20%, #6e00b2 80%) 20% / 1 / 0 stretch;
  /*  border-image-source: linear-gradient(90deg, #00C9FF 0%, #92FE9D 100%);
    border-image-slice: 20%;    00C9FF
    border-image-width: 1;  92FE9D
    border-image-outset: 0;
    border-image-repeat: stretch; */

}
</style>

    <style>
        .relative {
        position: relative;
        width:100%;
  margin:auto;
	max-width:100%;
	min-height:670px;
    position:relative;
	background:url(Kartinki_na_rabochiy_stol_dlya_geymerov_29_19123056.jpg) no-repeat center;
        background-size:cover;
        }
        .absolute{
        top: 50px;
        }

.block-left{width:50%;height:470px;overflow:auto;float:left;}
.block-right{width:50%;height:470px;overflow:auto;}
    </style>

    <meta charset="UTF-8">
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <link rel="stylesheet" href="style.css" />
</div>
</head>
<!-- hack -->
<!-- hack -->
<!-- hack -->
<body>
<div class="square">
    <center style="color: #008500;"><h1 ><i>bio-server</i></h1></center>
    </div>


<div class="relative"width="100%">
    <div class="absolute">

    </div>
</div>




















<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
<!--  hack   -->
        <div class="container1">
            <div class="container">
            <div class="hr-vertical-gradient">
            <hr width="100%" >

            </div>

                <center style="color: green"><h2><i>MAP</i></h2></center>
                <div class="square">
                    <center>
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d84419767.69739866!2d100!3d28.999999999999996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38aef4cbd5591e2b%3A0x31a0279a22a206bb!2z0YPQu9C40YbQsCDQntGB0LjRkSwg0KLQsNGI0LrQtdC90YIsINCj0LfQsdC10LrQuNGB0YLQsNC9!5e1!3m2!1sru!2s!4v1648269183891!5m2!1sru!2s"
                                    width="100%" height="500" style="border:0px solid: #008500;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </center>
                </div>


            <center><div class="btn"><a style="color: #008500;" href="https://geekprank.com/hacker/" target="_blank" class="btn" ><h2>hack simulator</h2></a></div>
            </center>

            <center><div class="btn"><a style="color: #008500;" href="https://hackertyper.net/" target="_blank" class="btn"><h2>typer</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://threatmap.checkpoint.com/" target="_blank" class="btn"><h2>cyber map 1</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://www.fireeye.com/cyber-map/threat-map.html" target="_blank" class="btn"><h2>cyber map 2</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://cybermap.kaspersky.com/" target="_blank" class="btn"><h2>cyber map 3</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/" target="_blank" class="btn"><h2>cyber hack</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/tegnio/" target="_blank" class="btn"><h2>geek typer</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/cyberpunk/" target="_blank" class="btn"><h2>input</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/shield/" target="_blank" class="btn"><h2>sheild</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/biohazard/" target="_blank" class="btn"><h2>bioxazard</h2></a></div>
            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/scp/" target="_blank" class="btn"><h2>scp</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/aperture/" target="_blank" class="btn"><h2>aperture</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/matrix/" target="_blank" class="btn"><h2>matrix</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://www.sites.google.com/site/kaksozdatytrojanvirus/" target="_blank" class="btn"><h2>virus</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://www.tor.com/" target="_blank" class="btn"><h2>tor</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://tor-browser.softok.info/" target="_blank" class="btn"><h2>tor download</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/fallout/" target="_blank" class="btn"><h2>fallout</h2></a></div>

            </center>
            <center><div class="btn"><a style="color: #008500;" href="https://geektyper.com/anon/" target="_blank" class="btn"><h2>anonymous</h2></a></div>

            <center><div class="btn"><a style="color: #008500;" href="https://ru.freeaccount.biz/accounts/cyber-hub.net" target="_blank" class="btn"><h2>cyberhup</h2></a></div>
            </center>

            <center><div class="btn"><a style="color: #008500;" href="https://threatmap.fortiguard.com/" target="_blank" class="btn"><h2>fortinet</h2></a></div>
            </center>

                <center><div class="btn"><a style="color: #008500;" href="https://www.guns.com/firearms" target="_blank" class="btn"><h2>gun shop 1</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="https://www.gunbroker.com/" target="_blank" class="btn"><h2>gun shop 2</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="https://www.impactguns.com/" target="_blank" class="btn"><h2>gun shop 3</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="https://www.flightradar24.com/41.16,66.67/6" target="_blank" class="btn"><h2>flyght trador</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="https://market.yandex.ru/search?clid=703&text=%D0%BF%D0%B5%D1%82%D0%B0%D1%80%D0%B4%D0%B0%20%D0%BA%D0%BE%D1%80%D1%81%D0%B0%D1%80%20100000%20%D0%BA%D1%83%D0%BF%D0%B8%D1%82%D1%8C&local-offers-first=0" target="_blank" class="btn"><h2>bomb</h2></a></div>
                </center>



                        <center> <div class="btn">
                            <a href="https://google.com" class="btn" style="color: #008500;" target="_blank"><h2>google search:</h2></a>
                        </div> </center>


                        <center>  <div class="btn">
                            <a href="https://yandex.com" class="btn" style="color: #008500;" target="_blank"><h2>yandex search:</h2></a>
                        </div></center>

                <div class="square">
                    <center style="color: #008500;"><h1 ><i>Note that these sites only work in the Tor browser</i></h1></center>

                </div>
                </center>
                <div class="block-left">
                    <center><div class="btn"><a style="color: #008500;" href="https://thehiddenwiki.org/" target="_blank" class="btn"><h2>hidden wiki</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://enxx3byspwsdo446jujc52ucy2pf5urdbhqw3kbsfhlfjwmbpj5smdad.onion" target="_blank" class="btn"><h2>end chan</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://picochanwvqfa2xsrfzlul4x4aqtog2eljll5qnj5iagpbhx2vmfqnid.onion" target="_blank" class="btn"><h2>pico chan</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://nanochanqzaytwlydykbg5nxkgyjxk3zsrctxuoxdmbx5jbh2ydyprid.onion" target="_blank" class="btn"><h2>nano chan</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://4usoivrpy52lmc4mgn2h34cmfiltslesthr56yttv2pxudd3dapqciyd.onion/" target="_blank" class="btn"><h2>8 chan</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://porf65zpwy2yo4sjvynrl4eylj27ibrmo5s2bozrhffie63c7cxqawid.onion" target="_blank" class="btn"><h2>smoces</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://4p6i33oqj6wgvzgzczyqlueav3tz456rdu632xzyxbnhq4gpsriirtqd.onion" target="_blank" class="btn"><h2>Peoples Drug Store</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://dumlq77rikgevyimsj6e2cwfsueo7ooynno2rrvwmppngmntboe2hbyd.onion" target="_blank" class="btn"><h2>de dope</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://wges3aohuplu6he5tv4pn7sg2qaummlokimim6oaauqo2l7lbx4ufyyd.onion" target="_blank" class="btn"><h2>eucanna</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://7bw24ll47y7aohhkrfdq2wydg3zvuecvjo63muycjzlbaqlihuogqvyd.onion" target="_blank" class="btn"><h2>hidden wiki</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://c5xoy22aadb2rqgw3jh2m2irmu563evukqqddu5zjandunaimzaye5id.onion" target="_blank" class="btn"><h2>psy shop 3</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://gkcns4d3453llqjrksxdijfmmdjpqsykt6misgojxlhsnpivtl3uwhqd.onion/" target="_blank" class="btn"><h2>dr chronic</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://wms5y25kttgihs4rt2sifsbwsjqjrx3vtc42tsu2obksqkj7y666fgid.onion/" target="_blank" class="btn"><h2>dc psy shop</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://wosc4noitfscyywccasl3c4yu3lftpl2adxuvprp6sbg4fud6mkrwqqd.onion" target="_blank" class="btn"><h2>face passwords</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://7wsvq2aw5ypduujgcn2zauq7sor2kqrqidguwwtersivfa6xcmdtaayd.onion" target="_blank" class="btn"><h2>card id</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://grams4onnyb67i3v4hl7l6ri5lwgmu2z2om3xtromrhlszcsaydbfcqd.onion/" target="_blank" class="btn"><h2>grams</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://bvten5svsltfpxrxl72ukqxixwo2m5ek5svmcxgrmkta4tbmiemuibid.onion/" target="_blank" class="btn"><h2>Beneath VT</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://potatoynwcg34xyodol6p6hvi5e4xelxdeowsl5t2daxywepub32y7yd.onion/" target="_blank" class="btn"><h2>Go Beyond</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://anonyradixhkgh5myfrkarggfnmdzzhhcgoy2v66uf7sml27to5n2tid.onion/" target="_blank" class="btn"><h2>Deep Web Radio</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://blackhost7pws76u6vohksdahnm6adf7riukgcmahrwt43wv2drvyxid.onion/" target="_blank" class="btn"><h2>hack games</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://lpiyu33yusoalp5kh3f4hak2so2sjjvjw5ykyvu2dulzosgvuffq6sad.onion/" target="_blank" class="btn"><h2>Tech Learning Collective</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://stormwayszuh4juycoy4kwoww5gvcu2c4tdtpkup667pdwe4qenzwayd.onion/" target="_blank" class="btn"><h2>cryptostorm</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://nehdddktmhvqklsnkjqcbpmb63htee2iznpcbs5tgzctipxykpj6yrid.onion/" target="_blank" class="btn"><h2>LocalMonero</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://njallalafimoej5i4eg7vlnqjvmb6zhdh27qxcatdn647jtwwwui3nad.onion/" target="_blank" class="btn"><h2>Njalla</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://vvedndyt433kopnhv6vejxnut54y5752vpxshjaqmj7ftwiu6quiv2ad.onion/" target="_blank" class="btn"><h2>PsychonauticsWIKI</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://2jopbxfi2mrw6pfpmufm7smacrgniglr7a4raaila3kwlhlumflxfxad.onion/" target="_blank" class="btn"><h2>AgoraDesk</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://ciadotgov4sjwlzihbbgxnqg3xiyrg7so2r2o3lt5wz5ypk4sxyjstad.onion/" target="_blank" class="btn"><h2>The CIA</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://ncidetfs7banpz2d7vpndev5somwoki5vwdpfty2k7javniujekit6ad.onion/" target="_blank" class="btn"><h2>NCIDE Task Force</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://tcecdnp2fhyxlcrjoyc2eimdjosr65hweut6y7r2u6b5y75yuvbkvfyd.onion/" target="_blank" class="btn"><h2>National Police</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://elfqv3zjfegus3bgg5d7pv62eqght4h6sl6yjjhe7kjpi2s56bzgk2yd.onion/" target="_blank" class="btn"><h2> ID Generator</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://elfqv3zjfegus3bgg5d7pv62eqght4h6sl6yjjhe7kjpi2s56bzgk2yd.onion/binfo_check_anonymity.php" target="_blank" class="btn"><h2>Check your anonymity online</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://protonmailrmez3lotccipshtkleegetolb73fuirgj7r4o4vfu7ozyd.onion/" target="_blank" class="btn"><h2>ProtonMail</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://tp7mtouwvggdlm73vimqkuq7727a4ebrv4vf4cnk6lfg4fatxa6p2ryd.onion/" target="_blank" class="btn"><h2>Alt Address</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://secmail63sex4dfw6h2nsrbmfz2z6alwxe4e3adtkpd4pcvkhht4jdad.onion/" target="_blank" class="btn"><h2>secMail</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://torbox36ijlcevujx7mjb4oiusvwgvmue7jfn2cvutwa6kl6to3uyqad.onion/" target="_blank" class="btn"><h2>TorBox</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://oq7t5ihk4qew5t5s4zghicigokh2ktt575amirsbnilmyawpme6xmyyd.onion/" target="_blank" class="btn"><h2>Elude.in</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://escrowkwttyhfyab3clkln7lfveyg7pfdwsv5vner35mhg7oaqz5uiid.onion/" target="_blank" class="btn"><h2>the escrow</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://million5utxgrxru4rqmjwn7jji6bf44jkdqn3xyav6md5ebwy5l2ryd.onion/" target="_blank" class="btn"><h2>21 million club</h2></a></div>
                    </center>

                <center><div class="btn"><a style="color: #008500;" href="http://psyshopshweetovp4em654waimmcjsf7eqifwe2d4qhnluk2b24r6dqd.onion/" target="_blank" class="btn"><h2>psy shop</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://caribcc5jik7maeqfit7h34af7ntatggbmlfhyxjnqnrhij7gjt5vtid.onion/" target="_blank" class="btn"><h2>Caribbean Cards</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://blackma6xtzkajcy2eahws4q65ayhnsa6kghu6oa6sci2ul47fq66jqd.onion/" target="_blank" class="btn"><h2>blackmart</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://metagerv65pwclop2rsfzg4jwowpavpwd6grhhlvdgsswvo6ii4akgyd.onion/" target="_blank" class="btn"><h2>metager</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://juhanurmihxlp77nkq76byazcldy2hlmovfu2epvl5ankdibsot4csyd.onion/" target="_blank" class="btn"><h2>ahmia</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://tordexu73joywapk2txdr54jed4imqledpcvcuf75qsas2gwdgksvnyd.onion/" target="_blank" class="btn"><h2>tordex</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://3bbad7fauom4d6sgppalyqddsqbf5u5p56b5k5uk2zxsy3d6ey2jobad.onion/" target="_blank" class="btn"><h2>onion lend</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://oniondxjxs2mzjkbz7ldlflenh6huksestjsisc3usxht3wqgk6a62yd.onion/" target="_blank" class="btn"><h2>onion index</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://xmh57jrknzkhv6y3ls3ubitzfqnkrwxhopf5aygthi7d6rplyvk3noyd.onion/cgi-bin/omega/omega" target="_blank" class="btn"><h2>torch</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://wiki47qqn6tey4id7xeqb6l7uj6jueacxlqtk3adshox3zdohvo35vad.onion/" target="_blank" class="btn"><h2>hidden wiki onion</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://s57divisqlcjtsyutxjz2ww77vlbwpxgodtijcsrgsuts4js5hnxkhqd.onion/" target="_blank" class="btn"><h2>card shop</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://55niksbd22qqaedkw36qw4cpofmbxdtbwonxam7ov2ga62zqbhgty3yd.onion/" target="_blank" class="btn"><h2>Acc market</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://prjd5pmbug2cnfs67s3y65ods27vamswdaw2lnwf45ys3pjl55h2gwqd.onion/" target="_blank" class="btn"><h2>Dark Web Hackers</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://jbtb75gqlr57qurikzy2bxxjftzkmanynesmoxbzzcp7qf5t46u7ekqd.onion/" target="_blank" class="btn"><h2>Darkmining</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://jhi4v5rjly75ggha26cu2eeyfhwvgbde4w6d75vepwxt2zht5sqfhuqd.onion/" target="_blank" class="btn"><h2>Bitcoin Investment</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://rxmyl3izgquew65nicavsk6loyyblztng6puq42firpvbe32sefvnbad.onion/" target="_blank" class="btn"><h2>mobile stories</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://ymvhtqya23wqpez63gyc3ke4svju3mqsby2awnhd3bk2e65izt7baqad.onion/" target="_blank" class="btn"><h2>OnionIdentityServices</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://k6m3fagp4w4wspmdt23fldnwrmknse74gmxosswvaxf3ciasficpenad.onion/" target="_blank" class="btn"><h2>uk guns and ammo</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://gd5x24pjoan2pddc2fs6jlmnqbawq562d2qyk6ym4peu5ihzy6gd4jad.onion/" target="_blank" class="btn"><h2>US Acitve</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://t43fsf65omvf7grt46wlt2eo5jbj3hafyvbdb7jtr2biyre5v24pebad.onion/" target="_blank" class="btn"><h2>euro guns</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://okayd5ljzdv4gzrtiqlhtzjbflymfny2bxc2eacej3tamu2nyka7bxad.onion/" target="_blank" class="btn"><h2>Apples 4 Bitcoin</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://xykxv6fmblogxgmzjm5wt6akdhm4wewiarjzcngev4tupgjlyugmc7qd.onion/" target="_blank" class="btn"><h2> PayPals, Ebays, i</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://kq4okz5kf4xosbsnvdr45uukjhbm4oameb6k6agjjsydycvflcewl4qd.onion/" target="_blank" class="btn"><h2>web hackers</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://wk3mtlvp2ej64nuytqm3mjrm6gpulix623abum6ewp64444oreysz7qd.onion/" target="_blank" class="btn"><h2>buy coins</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://answerszuvs3gg2l64e6hmnryudl5zgrmwm3vh65hzszdghblddvfiqd.onion/" target="_blank" class="btn"><h2>hidden answer</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://zgeajoabenj2nac6k5cei5qy62iu5yun5gm2vjnxy65r3p3amzykwxqd.onion/" target="_blank" class="btn"><h2>darkweb block</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://45tbhx5prlejzjgn36nqaxqb6qnm73pbohuvqkpxz2zowh57bxqawkid.onion/" target="_blank" class="btn"><h2>Parckwart’s Website</h2></a></div>
                </center>
            </div>
                <div class="block-right">
<!--xxxxx -->
<!--xxxxx -->
<!--xxxxx -->
<!--xxxxx -->
                    <center><div class="btn"><a style="color: #008500;" href="https://thehidden.wiki/" target="_blank" class="btn"><h2>onion hidden</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://lainwir3s4y5r7mqm3kurzpljyf77vty2hrrfkps6wm4nnnqzest4lqd.onion" target="_blank" class="btn"><h2>qorg11.net</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://protonmailrmez3lotccipshtkleegetolb73fuirgj7r4o4vfu7ozyd.onion/" target="_blank" class="btn"><h2>Proton mail</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://sonarmsng5vzwqezlvtu2iiwwdn3dxkhotftikhowpfjuzg7p3ca5eid.onion" target="_blank" class="btn"><h2>tor messenger</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://eludemailxhnqzfmxehy3bk5guyhlxbunfyhkcksv4gvx6d3wcf6smad.onion" target="_blank" class="btn"><h2>edule</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://xdkriz6cn2avvcr2vks5lvvtmfojz2ohjzj4fhyuka55mvljeso2ztqd.onion" target="_blank" class="btn"><h2>cock</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://titanxsu7bfd7vlyyffilprauwngr4acbnz27ulfhyxrqutu7atyptad.onion" target="_blank" class="btn"><h2>email tracker</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://privacy2zbidut4m4jyj3ksdqidzkw3uoip2vhvhbvwxbqux5xy5obyd.onion" target="_blank" class="btn"><h2>Privacy Tools</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="stormwayszuh4juycoy4kwoww5gvcu2c4tdtpkup667pdwe4qenzwayd.onion" target="_blank" class="btn"><h2>Cryptostorm VPN</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://7sk2kov2xwx6cbc32phynrifegg6pklmzs7luwcggtzrnlsolxxuyfyd.onion" target="_blank" class="btn"><h2>SystemLi.org </h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://wnrgozz3bmm33em4aln3lrbewf3ikxj7fwglqgla2tpdji4znjp7viqd.onion" target="_blank" class="btn"><h2>Vyempire.xyz</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://vww6ybal4bd7szmgncyruucpgfkqahzddi37ktceo3ah7ngmcopnpyyd.onion" target="_blank" class="btn"><h2>rise up</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://cct5wy6mzgmft24xzw6zeaf55aaqmo6324gjlsghdhbiw5gdaaf4pkad.onion" target="_blank" class="btn"><h2>snopyta</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://theendgtso35ir6ngdtyhgtjhhbbprmkzl74gt5nyeu3ocr34sfa67yd.onion" target="_blank" class="btn"><h2>the end</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://dngtk6iydmpokbyyk3irqznceft3hze6q6rasrqlz46v7pq4klxnl4yd.onion" target="_blank" class="btn"><h2>256 chan</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://jaz45aabn5vkemy4jkg4mi4syheisqn2wn2n4fsuitpccdackjwxplad.onion/" target="_blank" class="btn"><h2>onion links</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://bepig5bcjdhtlwpgeh3w42hffftcqmg7b77vzu7ponty52kiey5ec4ad.onion/" target="_blank" class="btn"><h2>Kamagra 4</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://sa3ut5u4qdw7yiunpdieypzsrdylhbtafyhymd75syjcn46yb5ulttid.onion" target="_blank" class="btn"><h2>HQER</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://jn6weomv6klvnwdwcgu55miabpwklsmmyaf5qrkt4miif4shrqmvdhqd.onion/" target="_blank" class="btn"><h2>rent a hacker</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://7wsvq2aw5ypduujgcn2zauq7sor2kqrqidguwwtersivfa6xcmdtaayd.onion/" target="_blank" class="btn"><h2>USfakeIDs US</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://pliy7tiq6jf77gkg2sezlx7ljynkysxq6ptmfbfcdyrvihp7i6imyyqd.onion/" target="_blank" class="btn"><h2>Counterfeit USD</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://hyxme2arc5jnevzlou547w2aaxubjm7mxhbhtk73boiwjxewawmrz6qd.onion/" target="_blank" class="btn"><h2>CannabisUK</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://c5xoy22aadb2rqgw3jh2m2irmu563evukqqddu5zjandunaimzaye5id.onion/" target="_blank" class="btn"><h2> Cocaine, Heroin, MDMA</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://wms5y25kttgihs4rt2sifsbwsjqjrx3vtc42tsu2obksqkj7y666fgid.onion/ " target="_blank" class="btn"><h2>DCdutchconnectionUK</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://gn74rz534aeyfxqf33hqg6iuspizulmvpd7zoyz7ybjq4jo3whkykryd.onion/" target="_blank" class="btn"><h2>NLGrowers</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://rbcxodz4socx3rupvmhan2d7pvik4dpqmf4kexz6acyxbucf36a6ggid.onion/" target="_blank" class="btn"><h2>420prime</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://gkcns4d3453llqjrksxdijfmmdjpqsykt6misgojxlhsnpivtl3uwhqd.onion/" target="_blank" class="btn"><h2>DrChronic Weed</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://5kpq325ecpcncl4o2xksvaso5tuydwj2kuqmpgtmu3vzfxkpiwsqpfid.onion/" target="_blank" class="btn"><h2>bitcoin</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://vu3miq3vhxljfclehmvy7ezclvsb3vksmug5vuivbpw4zovyszbemvqd.onion/" target="_blank" class="btn"><h2>EasyCoin</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://zwf5i7hiwmffq2bl7euedg6y5ydzze3ljiyrjmm7o42vhe7ni56fm7qd.onion/" target="_blank" class="btn"><h2>Onionwallet</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://hidden.wiki" target="_blank" class="btn"><h2>hidden wiki 01</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://sejnfjrq6szgca7v.onion/" target="_blank" class="btn"><h2>Debain OS</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://nzh3fv6jc6jskki3.onion/" target="_blank" class="btn"><h2>rise up</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://relateoak2hkvdty6ldp7x67hys7pzaeax3hwhidbqkjzva3223jpxqd.onion/" target="_blank" class="btn"><h2>RelateList</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://bcloudwenjxgcxjh6uheyt72a5isimzgg4kv5u74jb2s22y3hzpwh6id.onion/" target="_blank" class="btn"><h2>BlackCloud</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://fhostingineiwjg6cppciac2bemu42nwsupvvisihnczinok362qfrqd.onion/" target="_blank" class="btn"><h2>freedom hosting</h2></a></div>
                    </center>


                    <center><div class="btn"><a style="color: #008500;" href="http://ijeeynrc6x2uy5ob.onion/" target="_blank" class="btn"><h2>The Calyx Institute</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://notbumpz34bgbz4yfdigxvd6vzwtxc3zpt5imukgl6bvip2nikdmdaad.onion/" target="_blank" class="btn"><h2>Ableonion</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://thestock6nonb74owd6utzh4vld3xsf2n2fwxpwywjgq7maj47mvwmid.onion/" target="_blank" class="btn"><h2>The Stock Insiders</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://wbi67emmdx6i6rcr6nnk3hco3nrvdc2juxrbvomvt6nze5afjz6pgtad.onion/" target="_blank" class="btn"><h2>MadIRC</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://c32zjeghcp5tj3kb72pltz56piei66drc63vkhn5yixiyk4cmerrjtid.onion/" target="_blank" class="btn"><h2>Raddle</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://enxx3byspwsdo446jujc52ucy2pf5urdbhqw3kbsfhlfjwmbpj5smdad.onion/" target="_blank" class="btn"><h2>Endchan</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://mnwverhclu56p2zofu7iotkh2quucwev2f47hh5g5xdtme7ddne2jzqd.onion/" target="_blank" class="btn"><h2>lolita city</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://rutordeepkpafpudl22pbbhzm4llbgncunvgcc66kax55sc4mp4kxcid.onion/" target="_blank" class="btn"><h2>Rutor</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://suprbaydvdcaynfo4dgdzgxb4zuso7rftlil5yg5kqjefnw4wq4ulcad.onion/" target="_blank" class="btn"><h2>PirateBay </h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://germany2igel45jbmjdipfbzdswjcpjqzqozxt4l33452kzrrda2rbid.onion/" target="_blank" class="btn"><h2>deep web forum</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://dreadytofatroptsdj6io7l3xptbet6onoyno2yv7jicoxknyazubrad.onion/" target="_blank" class="btn"><h2>dread</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://underwood2hj3pwd.onion/" target="_blank" class="btn"><h2>Underwood’s Mail</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://mail2torjgmxgexntbrmhvgluavhj7ouul5yar6ylbvjkxwqf6ixkwyd.onion/" target="_blank" class="btn"><h2>mail tor</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://cwu7eglxcabwttzf.onion/" target="_blank" class="btn"><h2>Confidant Mail</h2></a></div>
                    </center>

                    <center><div class="btn"><a style="color: #008500;" href="http://j3bv7g27oramhbxxuv6gl3dcyfmf44qnvju3offdyrap7hurfprq74qd.onion/" target="_blank" class="btn"><h2>adunanza OnionMail Server</h2></a></div>
                    </center>

                <center><div class="btn"><a style="color: #008500;" href="http://lldan5gahapx5k7iafb3s4ikijc4ni7gx5iywdflkba5y2ezyg6sjgyd.onion/" target="_blank" class="btn"><h2>onion share</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://7sk2kov2xwx6cbc32phynrifegg6pklmzs7luwcggtzrnlsolxxuyfyd.onion/" target="_blank" class="btn"><h2>system link</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://killnod2s77o3axkktdu52aqmmy4acisz2gicbhjm4xbvxa2zfftteyd.onion/" target="_blank" class="btn"><h2>kill 9</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://digdeep4orxw6psc33yxa2dgmuycj74zi6334xhxjlgppw6odvkzkiad.onion/" target="_blank" class="btn"><h2>DigDeeper</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://meynethaffeecapsvfphrcnfrx44w2nskgls2juwitibvqctk2plvhqd.onion/" target="_blank" class="btn"><h2>May Vane Day</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://zsxjtsgzborzdllyp64c6pwnjz5eic76bsksbxzqefzogwcydnkjy3yd.onion/" target="_blank" class="btn"><h2>shadow wiki</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://darkzzx4avcsuofgfez5zq75cqc4mprjvfqywo45dfcaxrwqg6qrlfid.onion/" target="_blank" class="btn"><h2>darknet life</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://archivebyd3rzt3ehjpm4c3bjkyxv3hjleiytnvxcn7x32psn2kxcuid.onion/" target="_blank" class="btn"><h2>internet archive</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://keybase5wmilwokqirssclfnsqrjdsi7jdir5wy7y7iu3tanwmtp6oid.onion/" target="_blank" class="btn"><h2>key baza</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://ovai7wvp4yj6jl3wbzihypbq657vpape7lggrlah4pl34utwjrpetwid.onion/" target="_blank" class="btn"><h2>virgin bitcoins</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://hqfld5smkr4b4xrjcco7zotvoqhuuoehjdvoin755iytmpk4sm7cbwad.onion/" target="_blank" class="btn"><h2>bitcoin mixer</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://y22arit74fqnnc2pbieq3wqqvkfub6gnlegx3cl6thclos4f7ya7rvad.onion/" target="_blank" class="btn"><h2>anonymous</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://jgwe5cjqdbyvudjqskaajbfibfewew4pndx52dye7ug3mt3jimmktkid.onion/" target="_blank" class="btn"><h2>ultimate dark web</h2></a></div>
                </center>

                <center><div class="btn"><a style="color: #008500;" href="http://s4k4ceiapwwgcm3mkb6e4diqecpo7kvdnfr5gg7sph7jjppqkvwwqtyd.onion/" target="_blank" class="btn"><h2>onion links</h2></a></div>
                </center>

                </div></div>

<!-- sig in -->
<!-- sig in -->
<!-- sig in -->
<!-- sig in -->
            <div class="square">
    <div class="login-wrap">
        <div class="login-html">
            <input id="tab-1" type="radio" name="tab" class="sign-in" checked><label for="tab-1" class="tab">Sign In</label>
            <input id="tab-2" type="radio" name="tab" class="sign-up"><label for="tab-2" class="tab">Sign Up</label>
            <div class="login-form">
                <div class="sign-in-htm">
                    <div class="group">
                        <label for="user" class="label">Username</label>
                        <input id="username" type="text" class="input">
                    </div>
                    <div class="group">
                        <label for="pass" class="label">Password</label>
                        <input id="password" type="password" class="input" data-type="password">
                    </div>
                    <div class="group">
                        <input id="check" type="checkbox" class="check" checked>
                        <label for="check"><span class="icon"></span> Keep me Signed in</label>
                    </div>
                    <div class="group">
                        <a href=""><input type="submit" class="button" value="Sign In"></a>
                    </div>
                    <div class="hr"></div>
                    <div class="foot-lnk">
                        <a href="#forgot">Forgot Password?</a>
                    </div>
                </div>
                <div class="sign-up-htm">
                    <div class="group">
                        <label for="user" class="label">Username</label>
                        <input id="user" type="text" class="input">
                    </div>
                    <div class="group">
                        <label for="pass" class="label">Password</label>
                        <input id="password1" type="password" class="input" data-type="password">
                    </div>
                    <div class="group">
                        <label for="pass" class="label">Repeat Password</label>
                        <input id="pass" type="password" class="input" data-type="password">
                    </div>
                    <div class="group">
                        <label for="pass" class="label">Email Address</label>
                        <input id="password12" type="text" class="input">
                    </div>
                    <div class="group">
                        <a href=""><input type="submit" class="button" value="Sign Up"></a>
                    </div>
                    <div class="hr"></div>
                    <div class="foot-lnk">
                        <label for="tab-1">Already Member?</label>
                    </div>
                </div>
            </div>
        </div>
    </div>
            </div>
</div>

</body>
</html>

