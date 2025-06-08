# Food Tour 🍽️

Explore global culinary adventures with immersive, guided tours

## Features ✨

- REST API for managing food items (Create, Read, Update, Delete) 🍲
- Integration with SQL Server for data persistence 💾
- Spring Boot application with Hibernate for database management 🌱
- Extensible for adding tour features and more culinary data 🔄

## Getting Started 🛠️

1. **Clone the repository**:

   ```bash
   git clone https://github.com/BaoPhuc1311/FoodTour.git
   ```

2. **Open in Eclipse**:

   - Import as Maven project: `File > Import > Maven > Existing Maven Projects` 📂
   - Ensure JDK 22 is configured (required for Spring Boot 3.5.0) ☕

3. **Run the app**:
   - Right-click `FoodTourApplication.java` > `Run As > Java Application` ▶️
   - Access the API at `http://localhost:8082/api/home` or `http://localhost:8082/api/foods` 🖱️

## Requirements 📋

- Java JDK 22 or higher
- Eclipse IDE with Maven Integration
- SQL Server running with database `FoodTourDB` and `sa` user

## Project Structure 📁

- `src/main/java/com/foodtour/FoodTourApplication.java`: Main application class
- `src/main/java/com/foodtour/controller/HomeController.java`: REST API endpoints
- `src/main/java/com/foodtour/entity/Food.java`: Food entity with Lombok
- `src/main/java/com/foodtour/repository/FoodRepository.java`: JPA repository
- `src/main/java/com/foodtour/service/FoodService.java`: Business logic
- `src/main/resources/application.properties`: Configuration file
- `.gitignore`: Excludes `target`, `.settings`, `.classpath`, `.project`

## Contributing 🤝

Feel free to fork, add features, or submit pull requests!

## License 📝

This project is licensed under the [MIT License](LICENSE).
