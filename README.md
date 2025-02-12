# Car Rental System  

## Overview  
The **Car Rental System** is a modular, console-based application developed in C. It provides both **Admin** and **User** panels to manage car rentals efficiently. Admins can add or remove cars, while users can sign up, browse available cars, and rent them.  

## Features  

### **Admin Panel**  
- Add new cars to the system.  
- Delete cars from the inventory.  
- View the list of available cars.  

### **User Panel**  
- User signup and authentication.  
- Browse available cars for rent.  
- Rent a car and generate a rental receipt.  

## Technologies Used  
- **Programming Language**: C  
- **File Handling**: Stores user data, car inventory, and rental records.  
- **Modular Programming**: Organized into separate modules for better maintainability.  

## How to Use  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-name/car-rental-system.git
   cd car-rental-system
   ```
2. Compile the program:  
   ```sh
   gcc main.c admin/*.c user/*.c -o CarRentalSystem
   ```
3. Run the program:  
   ```sh
   ./CarRentalSystem
   ```
4. Choose either **Admin** or **User** mode to perform actions.  

## Future Enhancements  
- Implement a **database** for better data storage.  
- Add a **payment system** for online transactions.  
- Develop a **GUI version** for improved usability.  

## License  
This project is open-source and available under the **MIT License**.
