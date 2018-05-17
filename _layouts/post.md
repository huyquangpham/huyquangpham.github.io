<!DOCTYPE html>
<html lang="en">

  {% include head.md %}

  <body class="post-page">
    <div class="wrapper">
      <section class="container container-post">
        {{ content }}
        <div class="wrapper wrapper-btn">
          <input class="btn btn-tran" type="button" value="BACK" onclick="window.history.back()" />
        </div>
      </section>
      <footer></footer>
    </div>
  </body>
</html>
