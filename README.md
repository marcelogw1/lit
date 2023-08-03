<!DOCTYPE html>
<html>
<head>
  <title>Little Lemon Restaurant - Table Bookings</title>
</head>
<body>
  <h1>Table Booking Form</h1>
  <form id="bookingForm">
    <label for="name">Name:</label>
    <input type="text" id="name" required>
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email" required>
    <br>
    <label for="guests">Number of Guests:</label>
    <input type="number" id="guests" min="1" max="10" required>
    <br>
    <label for="date">Date:</label>
    <input type="date" id="date" required>
    <br>
    <label for="time">Time:</label>
    <input type="time" id="time" required>
    <br>
    <input type="submit" value="Submit Booking">
  </form>
</body>
</html>
# lit
