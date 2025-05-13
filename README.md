# Scheduling Algorithm 

A web-based platform designed to facilitate the management and execution of scheduling algorithms, enabling users to visualize and analyze various scheduling techniques.

## Features

👩‍🎓 User Dashboard  
🔍 **Algorithm Selection**: Choose from various scheduling algorithms (e.g., FIFO, LIFO, LRU).  
📊 **Visualization**: Graphical representation of the selected scheduling algorithm in action.  
📈 **Performance Metrics**: View turnaround time, waiting time, and throughput for each algorithm.  

👨‍💼 Admin Dashboard  
👥 **User Management**: Add, remove, and assign roles to users.  
📝 **Algorithm Management**: Add or remove scheduling algorithms from the platform.  
🔑 **Full Access Control**: Manage users and algorithms efficiently.  

🔒 **Authentication**  
Secure login and signup pages. Role-based access control ensures restricted functionalities.

## Tech Stack

🖥 **Frontend**: HTML, CSS, JavaScript  
🖥 **Backend**: Node.js  
🗄 **Database**: MongoDB  

## Installation & Setup

1️⃣ **Clone the Repository**  
```bash
git clone git@github.com:Aditi7Singh/Scheduling-Algorithm-Project.git
```

2️⃣ **Set Up Local Server**  
Use Node.js or any suitable environment to run the application.

3️⃣ **Install Dependencies**  
Navigate to the project directory and run:  
```bash
npm install
```

4️⃣ **Start the Server**  
Run the application with:  
```bash
npm start
```

5️⃣ **Open the Project**  
Open the browser and visit:  
```
http://localhost:3000
```

## Code Overview

The project consists of an HTML interface and JavaScript implementation for three scheduling algorithms: FCFS (FIFO), LIFO, and LRU. The key components of the implementation include:

- **The PageReplacementAlgorithm Class**: This is the base class responsible for managing memory display and handling the basic functionality required for all scheduling algorithms. 
- **Specific Algorithm Classes**: Each algorithm (FIFO, LIFO, and LRU) inherits from the base class and implements its own logic for page replacement.
- **User Interface Elements**: The HTML structure allows for user input of page numbers, the simulation of algorithms, and the visualization of memory states.

### Main HTML Structure
The HTML contains a user-friendly interface with controls to input page numbers, buttons to start simulations for each scheduling algorithm, and areas to display the results and the memory state.

### JavaScript Functions
- **startSimulation(algorithm)**: Initializes the selected algorithm, reads user input, and starts the simulation, updating the UI accordingly.
- **deallocateMemory()**: Deallocates memory according to the selected algorithm.
- **resetSimulation()**: Resets the simulation and reloads the page.

## Future Enhancements

🔍 More scheduling algorithms (e.g., Priority, Multilevel Queue)  
📊 Detailed analytics and reports on scheduling performance  
🔔 Notification system for updates or new features  

## Contributors

👩‍💻 Aditi Singh  


Feel free to explore the code and run the application to visualize the impact of each scheduling algorithm on memory management!
