<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script>document.getElementsByTagName("html")[0].className += " js";</script>
  <link rel="stylesheet" href="assets/css/style.css">
  <style>
.markdown-body > h1 { display: none; }
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
  <title>香港人抗爭時序</title>
</head>
<body>
	<header class="cd-main-header text-center flex flex-column flex-center">
    <h1>香港人抗爭時序</h1>
    <p class="margin-top-sm">2019年3月政府借陳同佳案為由，硬推《逃犯條例修訂》</p>
    <p class="margin-top-sm">多名手足被政權推下來，冷血政府卻漠視人命，至今仍然沒有回應。</p>
    <p class="margin-top-sm">整場社運被警方拘捕義士多達500人。</p>
  </header>

  <section class="cd-timeline js-cd-timeline">
    <div class="container max-width-lg cd-timeline__container">
      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--picture">
          <img src="assets/img/cd-icon-picture.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>103萬人上街遊行</h2>
          <p class="color-contrast-medium"></p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">9/6</span>
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
          <h2>政府漠視百萬人聲音，原訂照常二讀<br/>市民發動「三罷」，遭警方武力清場，林鄭稱示威者「暴動」</h2>
          <p class="color-contrast-medium"></p>
          
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">12/6</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--picture">
          <img src="assets/img/cd-icon-picture.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>200萬+1人上街遊行</h2>
          <p class="color-contrast-medium"></p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">16/6</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--location">
          <img src="assets/img/cd-icon-location.svg" alt="Location">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>響應不合作運動發起包圍警總，癱瘓政府大樓工作</h2>
          <p class="color-contrast-medium"></p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">6月中旬</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--location">
          <img src="assets/img/cd-icon-location.svg" alt="Location">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>全球登報讓世界看見反送中訴求</h2>
          <p class="color-contrast-medium"></p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">26/6</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--movie">
          <img src="assets/img/cd-icon-movie.svg" alt="Movie">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>包圍律政中心</h2>
          <p class="color-contrast-medium"></p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">27/6</span>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->
    </div>
  </section> <!-- cd-timeline -->
  <script src="assets/js/main.js"></script>
</body>
</html>
