## Running Club and Race Management MVC Project

This MVC project is a guide created by Teddy Smith for managing running clubs and races.

### Project Structure

- **Models**: Contains the data models for clubs and races.
- **Views**: Contains the HTML templates for rendering club and race information.
- **Controllers**: Handles user requests, retrieves data from the model, and returns the appropriate view.
- **wwwroot**: Contains static files such as images and stylesheets.
- **Startup.cs**: Configures services and the request processing pipeline.

### Models

#### Club Model

The `Club` model represents a running club and includes properties such as title, description, address, and category.

- **Properties**:
  - `Id`: Unique identifier for the club.
  - `Title`: Name of the club.
  - `Description`: Description of the club.
  - `Address`: Address details including city and state.
  - `ClubCategory`: Category of the club (e.g., recreational, competitive).

#### Race Model

The `Race` model represents a running race and includes properties such as title, description, location, and category.

- **Properties**:
  - `Id`: Unique identifier for the race.
  - `Title`: Name of the race.
  - `Description`: Description of the race.
  - `Location`: Location details including city and state.
  - `RaceCategory`: Category of the race (e.g., marathon, 5k).

### Views

#### Club Views

- **Index.cshtml**: Displays a list of all running clubs.
- **Detail.cshtml**: Shows detailed information about a specific club.
- **RelatedClubs.cshtml**: Displays related running clubs based on category.

#### Race Views

- **Index.cshtml**: Lists all upcoming races.
- **Detail.cshtml**: Shows detailed information about a specific race.
- **RelatedRaces.cshtml**: Displays related races based on category.

### Controllers

#### ClubController

Handles requests related to running clubs.

- **Index**: Retrieves a list of all running clubs.
- **Detail**: Retrieves detailed information about a specific club.
- **RelatedClubs**: Retrieves related clubs based on category.

#### RaceController

Handles requests related to running races.

- **Index**: Retrieves a list of all upcoming races.
- **Detail**: Retrieves detailed information about a specific race.
- **RelatedRaces**: Retrieves related races based on category.

### Getting Started

To run this project:

1. Clone this repository.
2. Ensure you have the necessary dependencies installed, including .NET Core SDK.
3. Open the project in your preferred IDE.
4. Build and run the application.

### Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your proposed changes.
