# StortVerkefni1
<!doctype html>
<html lang="is">
  <head>
    <meta charset="utf-8">
    <title> Stórtverkefni 6</title>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans|Roboto+Slab" rel="stylesheet">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styleguide.css">
    <link rel="stylesheet" href="Styleskaupa.css">
  </head>
  <body>
    <ul>
      <li><a class="active" href="#home">Fooþjónusta</a></li>
      <li><a class="active2" href="#news">Um</a></li>
      <li><a class="active3" href="#news">Kaupa</a></li>
    </ul>
    <header>
      <div class="content">
        <h1>Kaupa</h1>
      </div>
    </header>
    <main>
      <div class="col1">
        <h3>Persónuupplýsingar</h3>
        <div>
          <label for="name">Nafn:</label>
          <input type="text" name="name" id="name" required>
        </div>
        <div>
          <label for="text">Kennitala:</label>
          <input type="text" name="text" id="text" value="123456-7890">
        </div>

        <div>
          <p>Kyn:</p>
          <label>
            <input type="radio" name="satisfaction" value="1">Kona
          </label>

          <label>
            <input type="radio" name="satisfaction" value="2"> Karl
          </label>

          <label>
            <input type="radio" name="satisfaction" value="3"> Annað
          </label>
        </div>

        <div>
          <label for="text">Sími:</label>
          <input type="text" name="text" id="text" value="+354 812 3456">
        </div>

        <div>
          <label for="text">Heimilisfang:</label>
          <input type="text" name="text" id="text">
        </div>

        <div>
          <label>
            <input type="checkbox" name="continue" checked> Skrá mig á póstlista
          </label>
        </div>
      </div>
      <div class="col2">
        <h3>Greiðsluupplýsingar</h3>
        <div>
          <label for="service">Greiða með:</label>
          <select name="service" id="service">
            <option>Kreditkorti</option>
            <option>Millifærslu</option>
            <option>Reiðufé</option>
          </select>
        </div>

        <div>
          <label for="name">Nafn á korti:</label>
          <input type="text" name="name" id="name" required>
        </div>

        <div>
          <label for="text">Kortanúmer:</label>
          <input type="text" name="text" id="text" value="5999-9999-9999-9999">
        </div>

        <p>Gildistími:</p>
        <div>
          <label for="service">Mán</label>
          <select name="service" id="service">
            <option>01</option>
            <option>02</option>
            <option>03</option>
            <option>04</option>
            <option>05</option>
            <option>06</option>
            <option>07</option>
            <option>08</option>
            <option>09</option>
            <option>10</option>
            <option>11</option>
            <option>12</option>
          </select>

          <label for="service">Ár</label>
          <select name="service" id="service">
            <option>2017</option>
            <option>2018</option>
            <option>2019</option>
            <option>2020</option>
          </select>
        </div>
      </div>

      <div class="content2">
        <div class="button"><a> Panta</a></div>
      </div>
    </main>
    <section>
      <footer>
        <p>Fooþjónustan
          123-4567
        </p>
        <p>Opið 12-13 alla daga
          Bargata 1
          900 Foobar
        </p>
      </footer>
    </section>

    <section>
      <footer>
        <div class="footer">
          <p>© Fooþjónustan 2017</p>
        </div>
      </footer>
    </section>
  </body>
</html>
