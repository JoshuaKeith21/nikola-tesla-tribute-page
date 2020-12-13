<!DOCTYPE html>
<html>
<head>
  <title>Nikola Tesla</title>
<meta chartset="UTF-8">
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

  </head>

  <style>

    .content {
      max-width: 700px;
      margin:auto;

    }
    .img-container{
      text-align: center;
    }
    img {
      width: 50%;
      height: auto;

    }

    .row {
      display: flex;
    }

    .column {
      flex: 25%;
      padding: 5px;
    }

    #img-caption {
      font-size: 20px;
    }


</style>

  <body>

    <div id="main" class="content" style="padding:20px; width:auto; height:auto; background:#ff02ff; display:block; border-radius: 25px;">
     <h1 id="title" class="img-container"><u> Nikola Tesla</u> </h1>

  <div id= "img-div" class="img-container">
    <div class="row">

    <div class="column">
        <img src="images/nikola_tesla_portrait.JPG" alt="Nikola Tesla portrait" id="img" style="width:100%">
        </div>

    <div class="column">
      <img src="images/nikola_tesla_portrait2.JPG" alt="nikola tesla portrait number 2" id="img" style="width:100%">
      </div>

    <div class="row"
    <div class="column">
          <img src="images/nikola_tesla_electric.jpg" alt="Nikola Tesla lightning electric image" id="img" style="width:100%">
          </div>
    <div class="row">
    <div class="column">
      <img src="images/nikola_tesla_vivid.JPG" alt="Nikola Tesla tribute painting" id="img"style="width:100%">
      </div>
    </div>
    </div>

    <p id="img-caption"><em>World famous inventor</em></p>
    </div>
    <div id="tribute-info" class="content">
      <div style="padding:20px; width:auto; height:auto; background:#dda0dd; display:block; border-radius: 25px;">
        <p>Nikola Tesla was an engineer and scientist known for designing the
        alternating-current (AC) electric system, which is the predominant
        electrical system used across the world today. He also created the
        "Tesla coil," which is still used in radio technology.</p>
      </div>
    </div>

    <div class="content">
    <p>To learn more about Nikola Tesla
    <a href="https://en.wikipedia.org/wiki/Nikola_Tesla" target="_blank" id="tribute-link">
    Click Here</a>
  </p>
</div>
</div>
</body>
</html>
