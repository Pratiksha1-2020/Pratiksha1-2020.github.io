<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <link rel="stylesheet" href="CSS/form-css.css">
    <meta charset="utf-8">
    <title>forms</title>
  </head>
  <body>
    <div class="Heading">
    <h1 id="title">Food fest</h1>
    <h2>Free coupons are here</h2>
    <p>Veggies are amazing.</p>
    <br>
  </div>
    <div>
      <div class="des">
        <h3>Veggies are cool</h3>
    <p id="description">Who said veggies are uncool. Our food fest will prove them otherwise. Delicious mouth watering food will make you come back again and again.
      <br>
      Rich delicious meal that will reach your heart. Please fill the form for free coupons completely. Invalid forms will not be accepted.
    </p>
  </div>
    <form id="survey-form" action="index.html" method="post">
      <h2>Coupon Form</h2>
      <fieldset>
      <ol>
        <li>
          <label for="name">Name: </label>
          <input id="name" type="text" name="Name" placeholder="Enter your name" value="">
        </li>
        <br>
        <li>
          <label for="email">Email: </label>
          <input id="email" type="email" name="Number" placeholder="Enter your email">
        </li>
        <br>
        <li>
        <label for="number">Number: </label>
        <input id="number" type="number" name="number" placeholder="Enter your mobile">
        </li>
        <br>
        <li>
          What is your education?
          <select class="" name="edu">
            <option value="school">School</option>
            <option value="pre university">Pre-university</option>
            <option value="graduation">graduation</option>
            <option value="post graduation">post-grasduation</option>
          </select>
        </li>
        <br>

        <li>
          <p>What do you want to eat when you come here?</p>
          <ul>
          <li><input type="checkbox" name="food" value="Samosa">Samosa</li>
          <li><input type="checkbox" name="food" value="Aloo Tikki">Potato Chips</li>
          <li><input type="checkbox" name="food" value="VadaPav">vada Pav</li>
          <li><input type="checkbox" name="food" value="Manchuri">Gobi Manchuri</li>
          <li><input type="checkbox" name="food" value="Pani-puri">Pani Puri</li>
        </ul>
        </li>
        <br>
        <textarea name="extra" rows="8" cols="80" placeholder="Please leave us your thought on this"></textarea>
      </ol>

      <input type="submit" name="submit" value="submit">
      </fieldset>


    </form>
  </div>
  </body>
</html>
