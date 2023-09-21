
<html>

  <head>

    <title>Guest Room Booking Application</title>

    <link rel="stylesheet" type="text/css" href="styles.css">

  </head>

  <body>

    <div class="container">

      <h1>Guest Room Booking</h1>

      <div class="form-container">

        <form id="booking-form">

          <div class="form-group">

            <label for="name">Guest Name:</label>

            <input type="text" id="name" name="name" required>

          </div>

          <div class="form-group">

            <label for="check-in">Check-in Date:</label>

            <input type="date" id="check-in" name="check-in" required>

          </div>

          <div class="form-group">

            <label for="check-out">Check-out Date:</label>

            <input type="date" id="check-out" name="check-out" required>

          </div>

          <div class="form-group">

            <label for="number-of-guests">Number of Guests:</label>

            <input type="number" id="number-of-guests" name="number-of-guests" min="1" required>

          </div>

          <div class="form-group">

            <label for="room-type">Room Type:</label>

            <select id="room-type" name="room-type" required>

              <option value="">Select a room type</option>

              <option value="standard">Standard</option>

              <option value="deluxe">Deluxe</option>

              <option value="suite">Suite</option>

            </select>

          </div>

          <button type="submit">Book Now</button>

        </form>

      </div>

      <div id="booking-details" class="booking-details-container"></div>

    </div>



    <script src="script.js"></script>

  </body>

</html>

