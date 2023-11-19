<html>
<head>
<title>klik klik gabut</title>
<style>
body {
  font-family: fantasy;
  text-align: center;
}

button {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  background-color: #af4c4c;
  color: white;
  border: 2px solid black;
 
32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size:
  font-family: fantasy;
16px;
  margin: 4px
 
2px;
  cursor: pointer;
}
</style>

</head>

<body bgcolor="#b8b4b4">

<h1>tombol gabut</h1>

<button onclick="randomVideo()">musik random</button>
<button onclick="randomWebsite()">game random</button>
<p>ya ini theodore cdm yang buat, ga ngambil punya orang kok</p>
<script>
function randomVideo() {
  var videos = [
    "https://music.youtube.com/watch?v=YVybFaCnqVg&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=dawrQnvwMTY&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=pRfmrE0ToTo&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=EkHTsc9PU2A&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=-QgC3AzdVo0&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=EkHTsc9PU2A&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=6csDMmqJ_QY&list=RDTMAK5uy_lk350Ugi2s9N7ZEJ3hM1SkVl2D3keV9es",
    "https://music.youtube.com/watch?v=wLkKL9AgWYU&list=RDCLAK5uy_mIY1OIxvwlIkS_U3MX6O5uHZXkB-LiJu8",
    "https://music.youtube.com/watch?v=VcB2MgNi8_E&list=RDCLAK5uy_mIY1OIxvwlIkS_U3MX6O5uHZXkB-LiJu8",
    "https://music.youtube.com/watch?v=PG76ZJ0foJs&list=RDCLAK5uy_mIY1OIxvwlIkS_U3MX6O5uHZXkB-LiJu8",
    "https://music.youtube.com/watch?v=2pH0-32fHU8&list=RDCLAK5uy_mIY1OIxvwlIkS_U3MX6O5uHZXkB-LiJu8",
    "https://music.youtube.com/watch?v=PG76ZJ0foJs&list=RDCLAK5uy_mIY1OIxvwlIkS_U3MX6O5uHZXkB-LiJu8",
    "https://music.youtube.com/watch?v=A9hcJgtnm6Q&list=RDCLAK5uy_mIY1OIxvwlIkS_U3MX6O5uHZXkB-LiJu8",
    "https://music.youtube.com/watch?v=O-s4oOnjVCU&list=PL-Qw0a2XWv1ckEJ5qtniJliq6egMFnxmL",
    "https://music.youtube.com/watch?v=_6Nr6ezfrLI&list=PL-Qw0a2XWv1ckEJ5qtniJliq6egMFnxmL",
    "https://music.youtube.com/watch?v=ojlObzwgx5E&list=PL-Qw0a2XWv1ckEJ5qtniJliq6egMFnxmL",
    "https://music.youtube.com/watch?v=WZEnrupePJw&list=PL-Qw0a2XWv1ckEJ5qtniJliq6egMFnxmL",
    "https://music.youtube.com/watch?v=Z1TZIQcuvCQ&list=PL-Qw0a2XWv1ckEJ5qtniJliq6egMFnxmL",
    "https://music.youtube.com/watch?v=_6Nr6ezfrLI&list=PL-Qw0a2XWv1ckEJ5qtniJliq6egMFnxmL",
    "https://music.youtube.com/watch?v=iJcPiVwpy54&list=RDCLAK5uy_kqQ1zj3L4fZK6ye75srlXMLYXdh2jMFPQ",
    "https://music.youtube.com/watch?v=7iS0fawNZZ0&list=RDCLAK5uy_kqQ1zj3L4fZK6ye75srlXMLYXdh2jMFPQ",
    "https://music.youtube.com/watch?v=05hXltD4qkY&list=RDCLAK5uy_kqQ1zj3L4fZK6ye75srlXMLYXdh2jMFPQ",
    "https://music.youtube.com/watch?v=waU75jdUnYw&list=RDCLAK5uy_kqQ1zj3L4fZK6ye75srlXMLYXdh2jMFPQ",
    "https://music.youtube.com/watch?v=XutKfAL7wx8&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=ws5K_5G_xvI&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=8NstorpFnjM&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=ltIozO0pBms&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=Nd-A-iiPoLg&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=3w68krri0bw&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=GnkzvAXWV-0&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=XutKfAL7wx8&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=eAWGFo0ScGs&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=wGF7PswOENQ&list=RDCLAK5uy_kTgC4HnOI3u2_HgrS_x6D9n3gyImsgnh0",
    "https://music.youtube.com/watch?v=hsLiJP2rqS8&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=FPNmQmpqpI8&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=QT1Da26s-UA&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=H6BpZG97cnI&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=rumGRADiap0&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=_MlYUgZnZcU&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=y-STe_g795o&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=srVxyCcsTKY&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=FkPOuwwIRhY&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=gQTnLK03zXU&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=IW_-y1lAEMM&list=PLg4sYsutzCyo58-R7rOVHyK0xS16dSpRP",
    "https://music.youtube.com/watch?v=aXIHMeb1W3Q&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=KsDZix4ZSlU&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=yMlKJGKyoCo&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=2S24-y0Ij3Y&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=9TQKyDD9Yig&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=ZAfAud_M_mg&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=Mgfe5tIwOj0&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=gNi_6U5Pm_o&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=zlJDTxahav0&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=LH4Y1ZUUx2g&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=aS1no1myeTM&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=G7KNmW9a75Y&list=RDCLAK5uy_nU67GE7pONSBJf0BR9n9bb_wp517NO6wo",
    "https://music.youtube.com/watch?v=NMNgbISmF4I&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=r3Pr1_v7hsw&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=9n3A_-HRFfc&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=FTQbiNvZqaY&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=1Cw1ng75KP0&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=9BMwcO6_hyA&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=1Cw1ng75KP0&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=Qq4j1LtCdww&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=mh8MIp2FOhc&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=3wxyN3z9PL4&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=k04tX2fvh0o&list=RDCLAK5uy_lzsHknmo26P5nkGiogVYHmdZPwreFtwwg",
    "https://music.youtube.com/watch?v=WFsAon_TWPQ&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=ffxKSjUwKdU&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=MKFuvUE-rn0&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=adLGHcj_fmA&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=ru0K8uYEZWw&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=pBkHHoOIIn8&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=PMivT7MJ41M&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=GxldQ9eX2wo&list=RDCLAK5uy_kPR9usfd5aQ8n4rTcEv7y1VLvMm1ewig4",
    "https://music.youtube.com/watch?v=90RLzVUuXe4&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=oygrmJFKYZY&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=GsF05B8TFWg&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=YXt0Nw8xWh0&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=1QYBiNRu1ok&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=4NRXx6U8ABQ&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=9HDEHj2yzew&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=cSqOY5nktfg&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=EXIWlRrkjKE&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=L8eRzOYhLuw&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=Il0S8BoucSA&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=VI9gIPBH_dM&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=kTJczUoc26U&list=RDCLAK5uy_kPqJ_FiGk-lbXtgM4IF42uokskSJZiVTI",
    "https://music.youtube.com/watch?v=mqiH0ZSkM9I&list=RDCLAK5uy_njvsGKIUycy_a4h7zTS8upbKhHcMVzHFM",
    "https://music.youtube.com/watch?v=dvgZkm1xWPE&list=RDCLAK5uy_njvsGKIUycy_a4h7zTS8upbKhHcMVzHFM",
    "https://music.youtube.com/watch?v=uJ_1HMAGb4k&list=RDCLAK5uy_njvsGKIUycy_a4h7zTS8upbKhHcMVzHFM",
    "https://music.youtube.com/watch?v=8UVNT4wvIGY&list=RDCLAK5uy_njvsGKIUycy_a4h7zTS8upbKhHcMVzHFM",
    "https://music.youtube.com/watch?v=B-FWhcNvNhA&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=Qhn8myo2eDw&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=HL__UmTlamk&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=nwta9P9Zlfg&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=oa1YHlv29zI&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=u0wX3RywOOs&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=2PGAqpADfEM&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=1YnGq3UfnZI&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=Ql13IeqrW90&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=B-FWhcNvNhA&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=_flLHJ0YrgU&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=9uZese57-tM&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4",
    "https://music.youtube.com/watch?v=jC6H1-wpG2Q&list=RDCLAK5uy_kL57PLcOmExjhzqGfGhvA82ZWe4fPH2c4"
  ];

  var randomIndex = Math.floor(Math.random() * videos.length);
  var randomVideo = videos[randomIndex];

  window.location.href = randomVideo;
}

function randomWebsite() {
  var videos = [
    "https://suikagame.com/",
    "https://trap-thecat.com/",
    "https://neal.fun/perfect-circle/",
    "https://nomisio.itch.io/cat",
    "https://jellymar.io/",
    "https://krunker.io/",
    "https://songtrivia2.io/",
    "https://wordlegame.org/id",
    "https://sandspiel.club/",
    "https://musiclab.chromeexperiments.com/kandinsky/",
    "https://kuku-kube.com/",
    "https://neal.fun/auction-game/",
    "https://www.thewikigame.com",
    "https://paint.toys/",
    "https://sliding.toys/mystic-square/8-puzzle/daily/",
    "https://id.akinator.com/",
    "https://maze.toys/mazes/mini/daily/",
    "https://gartic.io/",
    "https://www.foddy.net/Athletics.html",
    "https://www.linerider.com/",
    "https://gridland.doublespeakgames.com/",
    "https://freepacman.org/",
    "https://quickdraw.withgoogle.com/",
    "https://www.cbc.ca/kids/games/play/color-pipes",
    "https://www.agame.com/game/snail-bob",
    "https://chromedino.com/",
    "https://abagames.github.io/crisp-game-lib-games/?flipo",
    "https://slowroads.io/",
    "https://www.helicopter-game.org/",
    "https://ncase.itch.io/wbwwb",
    "http://Geo-fs.com",
    "https://neal.fun/password-game/",
    "https://humanbenchmark.com/",
    "https://dood.al/pinktrombone/",
    "https://www.autodraw.com/",
    "https://framesynthesis.com/drivingsimulator/maps/",
    "https://littlealchemy2.com/",
    "https://stein.world/",
    "https://ev.io/",
    "https://armorgames.com/street-skater-game/18047",
    "https://classic.minecraft.net/?join=FLC9UnPzhSq7v4AT",
    "https://shellshock.io/",
    "https://betrayal.io/",
    "https://www.silvergames.com/do/time-shooter",
    "https://hexanaut.io/",
    "https://minigolfclub.io/",
    "https://acikgoz.itch.io/under-the-sun",
    "https://www.sushiparty.io/",
    "https://www.nanobrowserquest.com/",
    "https://graebor.itch.io/sort-the-court",
    "https://hole-io.com/"
    ];

  var randomIndex = Math.floor(Math.random() * videos.length);
  var randomWebsite = videos[randomIndex];

  window.location.href = randomWebsite;
}
</script>

</body>
</html>
