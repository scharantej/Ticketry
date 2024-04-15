## Web Application Design for Air Ticket Booking using Python Flask

### HTML Files

- **index.html**: The homepage that displays the flight search form.
- **search_results.html**: Displays the search results based on the user's input.
- **booking_details.html**: Displays the selected flight details and allows the user to book the tickets.
- **confirmation_page.html**: Confirms the booking and provides the necessary details.

### Routes

- **@app.route('/'):** Renders the index.html page with the flight search form.
- **@app.route('/search', methods=['POST']):** Handles the flight search form submission and redirects to the search_results.html page with the search parameters.
- **@app.route('/flight_results'):** Retrieves the flight results based on the search parameters and renders the search_results.html page.
- **@app.route('/book_flight'):** Handles the flight booking and redirects to the booking_details.html page with the selected flight details.
- **@app.route('/confirm_booking', methods=['POST']):** Confirms the booking and redirects to the confirmation_page.html page.