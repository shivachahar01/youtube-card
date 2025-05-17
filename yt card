<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Website Builder</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: sans-serif;
    }

    .container {
      padding: 10px;
    }

    .card {
      display: flex;
      flex-direction: row;
      border-radius: 8px;
      overflow: hidden;
      width: 100%;
      max-width: 800px;
      margin: auto;
    box-shadow: 1px 0px 4px 1px #b8cfcf;
    }

   .image {
  width: 30%;
  min-width: 100px;
  padding: 5px;
  position: relative; /* Needed for absolute positioning inside */
  border-radius: 5px;
}

.image img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 5px;
}

.capsule {
  position: absolute;
  bottom: 8px;
  right: 8px;
  background-color: rgba(0, 0, 0, 0.75);
  color: #fff;
  padding: 2px 6px;
  font-size: 0.75rem;
  border-radius: 4px;
}


    .text {
      flex: 1;
      padding: 10px;
    }

    .text h1 {
      font-size: 1.2rem;
      margin: 0 0 10px;
    }

    .text p {
      font-size: 0.9rem;
      color: #555;
      margin: 0;
    }

    @media (max-width: 600px) {
      .card {
        flex-direction: column;
        align-items: center;
      }

      .image {
        width: 80%;
      }

      .text h1 {
        font-size: 1rem;
        text-align: center;
      }

      .text p {
        text-align: center;
      }
      .capsule{
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="image">
        <img src="sigma web dev.img" alt="img" />
        <div class="capsule">12:12</div>
      </div>
      <div class="text">
        <h1>JavaScript Exercise 13 - Solution & Shoutouts | Sigma Web Development Course</h1>
        <p>codewithharry • 727k views • 2 months ago</p>
      </div>
    </div>
    <br>
  </div>
 <script>function createCard(title, CName, views, monthsAgo, duration, thumbnail) {
  let viewStr;

  if (views >= 1000000) {
    viewStr = (views / 1000000).toFixed(1) + 'M';
  } else if (views >= 1000) {
    viewStr = (views / 1000).toFixed(1) + 'K';
  } else {
    viewStr = views;
  }

  let html = `
    <div class="card">
      <div class="image">
        <img src="${thumbnail}" alt="img" />
        <div class="capsule">${duration}</div>
      </div>
      <div class="text">
        <h1>${title}</h1>
        <p>${CName} • ${viewStr} views • ${monthsAgo} months ago</p>
      </div>
    </div>
    
  `
 document.querySelector(".container").innerhtml += html;

}

 createCard(
  "Mera Custom Video Title",
  "Shiva's Channel",
  123000,
  3,
  "9:30",
  "your-thumbnail.jpg"
);
</script>
</body>
</html>

