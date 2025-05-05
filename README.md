Core Features:
Train Search & Booking:

    Train Availability: Users can view a list of predefined trains along with departure and arrival stations, timings, and seat availability.

    Search Functionality: Users can search for trains by entering departure and destination stations, travel date, seat class (First Class/Sleeper), and number of seats.

    The system then filters and displays available trains based on the user's input.

Seat Availability:

    The system allows users to choose between First Class and Sleeper seats. It checks the availability of seats and displays only those trains with available seats for the selected class.

    The number of seats requested by the user must be less than or equal to the available seats.

Booking Process:

   Once the user selects a train and seats, they are directed to the Payment Page, where they can review the booking details and proceed with the simulated payment process.

  The total cost is calculated based on the selected seat class and number of seats.

Simulated Payment System:

  Payment Details: Users enter card details (simulated), and the system displays the total amount based on the selected class and seats.

  Once the payment is successfully processed (simulated), a confirmation page is shown, and the booking details are saved in the browser’s localStorage for future reference.

Booking History:

  After completing a booking, the system stores the booking details (e.g., train name, travel date, seats, price) in localStorage.

  Users can view their past bookings by visiting the Booking History Page, where the saved details are displayed.

Responsive Design:

  The system is built with CSS to ensure that it is responsive and adapts to different screen sizes (mobile, tablet, desktop), providing a seamless experience across devices.

Technology Used:
Frontend Technologies:

  HTML: Provides the structure of the web pages, including the homepage, payment page, and booking history page.

  CSS: Styles the pages to make them visually appealing, ensuring an easy-to-use and consistent interface.

  JavaScript: Adds interactivity to the pages, such as filtering available trains, calculating the total fare, handling the payment process, and storing booking data in localStorage.

How the System Works:
Home Page:

  Users can enter their departure and destination stations, travel date, seat class, and number of seats in the search form.

  The system then filters available trains and displays the search results based on the user’s criteria.

Search Results:

  After selecting a train, users can proceed to the Payment Page, where the booking details are displayed, including the selected class, number of seats, and total fare.

Payment Process:

  On the Payment Page, users are asked to enter payment details (simulated) and confirm the booking.

  The total fare is calculated based on the class and seat number selected.

Booking Confirmation:

  Once the payment is confirmed, the system displays a Booking Confirmation Page with details of the booking, including the train, seats, and total cost.

  The booking details are then saved to the browser’s localStorage.

Booking History:

  Users can check their booking history by visiting the Booking History Page, where the details of past bookings are retrieved from localStorage and displayed.

Limitations of the System:
  No User Authentication: Since the system operates entirely on the frontend, there is no user login or authentication process.

  No Real Backend: The system uses localStorage to simulate the saving and retrieval of booking data. It is device-dependent, meaning the data will only be available on the same device/browser where it was saved.

  Simulated Payment: The payment process is not real; it only demonstrates the steps involved in completing a booking. There is no actual payment gateway integration.

  
