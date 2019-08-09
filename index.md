<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script>document.getElementsByTagName("html")[0].className += " js";</script>
  <link rel="stylesheet" href="assets/css/style.css">
  <style>
.hidden { display: block; display: none; }
.btn { transition: all 0.5s; }
.more { transform:rotate(-180deg); }
  </style>
  <script>
function openMore(el) {
	$(el).toggleClass('more');
	$(el).parent().next().slideToggle();
}
  </script>
  <title>Responsive Vertical Timeline | CodyHouse</title>
</head>
<body>
	<header class="cd-main-header text-center flex flex-column flex-center">
    <h1>Responsive Vertical Timeline</h1>
    <p class="margin-top-sm">👈<a class="color-inherit" href="https://docs.google.com/forms/d/e/1FAIpQLScUQGrfgleucQU70fvNvY9KhLyt54wG6Y1awdkLK-c2FVbuSA/viewform">form</a></p>
  </header>

  <section class="cd-timeline js-cd-timeline">
    <div class="container max-width-lg cd-timeline__container">
      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--picture">
          <img src="assets/img/cd-icon-picture.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>白衫人喺天橋底嗰鳳攸北街休憩處聚集</h2>
          <p class="color-contrast-medium">盡在元朗live</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">8:49pm</span>
            <a onclick="openMore(this);" href="javascript:void(0);" class="btn btn--subtle">⇲</a>
          </div>
          <div class="hidden">[img]</div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--movie">
          <img src="assets/img/cd-icon-movie.svg" alt="Movie">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>元朗站中間5-6個白衫阿伯在閘外，有人講「係咪返上水？」</h2>
          <p class="color-contrast-medium">網友提供照片</p>
          
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">9:09pm</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--picture">
          <img src="assets/img/cd-icon-picture.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>有人喺休憩處被打</h2>
          <p class="color-contrast-medium">有線新聞</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">9:20pm</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--location">
          <img src="assets/img/cd-icon-location.svg" alt="Location">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>有人喺休憩處、渠附近被打</h2>
          <p class="color-contrast-medium">Now新聞</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">9:50pm</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--location">
          <img src="assets/img/cd-icon-location.svg" alt="Location">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>有人喺月台聽到兩個白衫WhatsApp同人講「班人唔敢出黎，匿埋咗喺月台」</h2>
          <p class="color-contrast-medium">民間社福界資訊地球post</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">10:33pm</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--movie">
          <img src="assets/img/cd-icon-movie.svg" alt="Movie">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>Final Section</h2>
          <p class="color-contrast-medium">This is the content of the last section</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Feb 26</span>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->
    </div>
  </section> <!-- cd-timeline -->
  <script src="assets/js/main.js"></script>
</body>
</html>
