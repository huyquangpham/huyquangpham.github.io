<!DOCTYPE html>
<html lang="en">

  {% include head.md %}

  <body class="post-page">
    <div class="wrapper">
      <section class="container container-post">
        {{ content }}
        <div class="wrapper wrapper-btn">
          <a href="#" class="btn btn-tran" onclick="window.backBtn()">BACK</a>
        </div>
      </section>
      <footer></footer>
    </div>
  </body>
  <script>
  ;(function(){
    window.backBtn = function() {
      if (history.length && history.length > 0) {
        window.history.back();
      } else {
        window.location.href = '{{ site.url }}'
      }
    }
    })();
  </script>
</html>
