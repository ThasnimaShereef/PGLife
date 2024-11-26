# PGLife - Student Accommodation Finder  

PGLife is a web-based platform designed to make the process of finding suitable accommodations easier for students joining colleges or universities. The application allows users to search for PGs (Paying Guest accommodations) based on city, view detailed property listings, and manage their preferences through a personalized dashboard.  

## Features  

1. **User Registration & Login**  
   - Users can sign up and log in securely using their email and password.  
   - Data is stored in the `users` table in the MySQL database.  

2. **City-Specific Search Functionality**  
   - Search for PG accommodations based on the city entered in the search bar.  
   - Redirects to a property list page showcasing available PGs in the selected city.  

3. **Property Details**  
   - View detailed information about a selected property, including amenities, pricing, and location.  
   - Data is dynamically fetched from the `properties` table in the database.  

4. **Personalized Dashboard**  
   - Users can access saved properties and manage personal details.  
   - Displays a list of 'interested' properties for each user.  

5. **Secure Logout**  
   - Logout functionality ensures user sessions are safely terminated.  

## Tech Stack  

- **Frontend:** HTML, CSS, Bootstrap, JavaScript, React  
- **Backend:** PHP, MySQL  

## Installation  

Follow these steps to set up the project locally:  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/YourUsername/PGLife.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd PGLife  
   ```  

3. Set up the MySQL database:  
   - Import the provided database file (`pglife.sql`) into your MySQL server.  
   - Ensure the `users` and `properties` tables are correctly created.  

4. Update database credentials in the PHP files:  
   - Modify the `db.php` file with your MySQL credentials.  

5. Start a local server:  
   - Use XAMPP, WAMP, or any local server tool to host the project files.  
   - Place the project in the `htdocs` folder (for XAMPP).  

6. Access the application:  
   - Open your browser and navigate to `http://localhost/PGLife`.  

## Usage  

1. Sign up with a new account or log in using an existing account.  
2. Search for accommodations by entering a city name in the search bar.  
3. View detailed property listings and save properties of interest.  
4. Access your dashboard to manage saved properties and personal details.  

## Future Enhancements  

- Add filters for property search (price range, amenities, etc.).  
- Include a messaging feature for direct communication with property owners.  
- Implement Google Maps integration for precise property locations.  
