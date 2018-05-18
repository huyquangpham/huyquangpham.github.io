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
      console.log(history.length);
      if (history.length && history.length > 0) {
        console.log('back');
        window.history.back();
      } else {
        console.log('redirect')
        window.location.href = '{{ site.url }}'
      }
    }
    })();
  </script>
</html>
