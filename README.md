# Hotel Project

This project simulates a hotel with different types of rooms, including Single Rooms and Suites. It demonstrates the use of inheritance, polymorphism, and sorting of room lists based on price.

## Classes

### Room

The `Room` class represents a basic room and implements the `Comparable` interface. It has properties:

- `roomNo`: Room number.
- `price`: Price of the room.

### SingleRoom

The `SingleRoom` class extends `Room` and represents a single occupancy room. It has additional properties:

- `bedType`: Type of bed in the room.
- `smoking`: Smoking status.

### Suite

The `Suite` class extends `Room` and represents a suite. It has additional properties:

- `numRoom`: Number of rooms in the suite.
- `hasKitchen`: Kitchen availability.
- `rating`: Rating of the suite.

## Running the Project

The `HotelProject` class is the main class that demonstrates the functionality of the hotel. It creates lists of `SingleRoom` and `Suite`, sorts them based on price, and prints out the hotel information.

To run the project, execute the `main` method in the `HotelProject` class.

## Sample Output

The program will display the sorted lists of Single Rooms and Suites with relevant information, including room number, price, bed type, smoking status, rating, and kitchen availability.

### Sample Output:

# Hotel Information

| Room No | Price | Bed Type | Smoking Status |
| ------- | ----- | -------- | --------------- |
| 1       | $140.5| Queen    | Smoking         |
| 2       | $130.5| Twin     | No Smoking      |
| 3       | $150.5| King     | Smoking         |

# Suite Information

| Room No | Price | Rating | Kitchen         |
| ------- | ----- | ------ | --------------- |
| 6       | $500  | 3      | No Kitchen      |
| 4       | $600  | 5      | With Kitchen    |
| 5       | $800  | 5      | No Kitchen      |
