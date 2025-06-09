
<!DOCTYPE html>
<html>
  <head>
    <title>My Favorite Book</title>
    <style>
      body {
        font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
          sans-serif;
        background-image: linear-gradient(to right, #f3e4e45d, #f3942fcb);
        padding: 0% 3% 0% 2%;
        margin: 0;
      }
      h1,
      h2 {
        text-align: center;
      }
      img {
        display: block;
        margin: 0 auto;
        width: 200px;
        padding: 1%;
        border: solid transparent;
        border-radius: 30%;
        text-align: center;
        height: auto;
        box-shadow: 0px 6px 8px 0px rgba(141, 11, 11, 0.2);
      }
      .author {
        text-align: center;
      }
      p {
        text-align: justify;
      }
      button {
        background-color: #ce1a1a;
        color: white;
        padding: 14px 20px;
        margin: 8px 0;
        border: solid transparent;
        cursor: pointer;
        width: 100%;
        border-radius: 50%;
        transition: background-color 0.3s ease;
      }
      button:hover {
        background-color: #f3942fcb;
        color: white;
      }
      footer {
        text-align: center;
        padding: 12px 0;
        font-size: 14px;
      }
      a {
        color: black;
        text-decoration: underline;
      }
      .name {
        color: #ce1a1a;
        text-decoration: none;
      }
    </style>
  </head>
  <body>
    <h1>Reclaim Your Heart🧡</h1>
    <h2>My Favorite Book📙</h2>

    <div>
      <p>
        Reclaim Your Heart by
        <span>
          <a href="https://en.wikipedia.org/wiki/Yasmin_Mogahed">
            Yasmin Mogahed
          </a>
        </span>
        is not only a self-help guide. It is a handbook about the journey of the
        heart throughout the expanse of this life. It is a book about how to
        hold your heart back from sinking to the depths of that ocean, and what
        to do when it does. It is a book about recovery, about trust, about
        hope, about renewal.
        <br />
        <br />
        Each heart can recover, and every moment is made to carry us closer to
        that great return. Reclaim Your Heart is about finding that moment when
        everything stops and suddenly seems different. It is about discovering
        your own awakening and then returning to the better, truer, and freer
        version of yourself. Many of us live our lives entangled by the same
        repeated patterns of heartbreak and disappointment. Many of us have no
        idea why this happens. <br />
        <br />
        Reclaim Your Heart is about freeing the heart from this bondage. It is
        about the journey in and out of life’s most deceptive traps. This book
        was composed to stir the heart and give another point of view on love,
        loss, joy, and pain. Providing a manual of sorts, Reclaim Your Heart
        will show readers how to live in this existence without allowing life to
        possess you. It is a handbook on how to secure your most valued
        possession,“the heart”.
      </p>
    </div>
    <br />
    <div class="author" style="text-align: center">
      <img
        src="https://myonlinebookshop.pk/cdn/shop/products/IMG_20211206_211528_341_1024x1024@2x.jpg?v=1642140720"
      />
    </div>
    <br />
    <button>Get a Quote</button>
    <br />
    <footer>
      Linkedin:
      <a href="http://www.linkedin.com/in/hadia-rahmani-52b7b3232" class="name"
        >Hadia Rahmani</a
      >
    </footer>
    <script>
      function quote() {
        let number = prompt("Choose a number between 1 - 5");
        if (number == 1) {
          alert(
            "“Times of difficulty test our faith, our fortitude and our strength. During these times, the level of our Imaan becomes manifest.” -Yasmin Mogahed, Reclaim Your Heart"
          );
        } else if (number == 2) {
          alert(
            "“If you seek Him, God can raise you up, and replace the darkness of the ocean, with the light of His Sun.” - Yasmin Mogahed, Reclaim Your Heart"
          );
        } else if (number == 3) {
          alert(
            "“The greatest victory is to rise from the ashes and rebuild yourself with love and resilience.” - Yasmin Mogahed, Reclaim Your Heart"
          );
        } else if (number == 4) {
          alert(
            "“You are never alone, for your heart is forever connected to the beating rhythm of the universe.” - Yasmin Mogahed, Reclaim Your Heart"
          );
        } else if (number == 5) {
          alert(
            "“Sometimes the very thing that breaks you can also heal you.” - Yasmin Mogahed, Reclaim Your Heart"
          );
        }
      }
      let qouteButton = document.querySelector("button");
      qouteButton.addEventListener("click", quote);
    </script>
  </body>
</html>
