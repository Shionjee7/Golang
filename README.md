
# Golang Conference Ticket Booking

This Go program simulates a simple ticket booking system for a conference. Users can enter their information and the number of tickets they want to purchase. The program will validate the user input, book the tickets if valid, and simulate sending a confirmation email asynchronously.

## Features
- **User input validation** for name, email, and number of tickets.
- **Asynchronous simulation** of sending a confirmation email.
- Displays the first names of the users who have booked the tickets.
- Provides feedback if the conference is booked out.

## Prerequisites
- **Go programming language** installed. You can download it from [here](https://golang.org/dl/).

## How to Run
1. **Clone** this repository to your local machine.
2. Navigate to the directory containing the `main.go` file.
3. Run the program using the following command:
    ```sh
    go run main.go
    ```

## User Input
The program will prompt you to enter the following information:
- First name
- Last name
- Email address
- Number of tickets

## Validation
The program validates the user input based on the following criteria:
- The first name and last name must not be too short.
- The email address must contain the "@" symbol.
- The number of tickets requested must be valid.

## Output
If the input is valid, the program will **book the tickets**, display the updated list of bookings, and simulate sending a confirmation email asynchronously. If the conference is booked out, the program will inform the user.

## Notes
- This is a simulation, and **no actual email is sent**.
- The program uses a simulated total of 50 tickets for the conference.

## License
This project is open source and available under the [MIT License](LICENSE).
