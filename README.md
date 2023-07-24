# Bookmarker App

The Bookmarker App is a simple web-based dashboard that allows users to manage bookmarks using basic CRUD (Create, Retrieve, Delete) operations. It is built using HTML, CSS, JavaScript, and Bootstrap.

## Features

- Add new bookmarks to the collection with a name and URL.
- View a list of existing bookmarks with their details.
- Delete bookmarks from the collection.
## Demo 
-- You can explore the App from <a href ="https://alhassan73.github.io/Bookmarker-CRUD-App/">Here</a>
## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/bookmarker-app.git
   ```
   
2. Navigate to the project directory:
   ```
   cd bookmarker-app
   ```
   
3. Open the `index.html` file in your web browser to run the app.

## Usage

1. Enter a valid bookmark name (at least 3 characters) in the "Bookmark Name" input field.

2. Enter a valid URL in the "URL" input field.

3. Click the "Submit" button to add the bookmark to the collection.

4. The newly added bookmark will appear in the table with its name, URL, and a "Delete" button.

5. To delete a bookmark, click the "Delete" button associated with the bookmark you want to remove.

## Validation using Regular Expressions

The app uses regular expressions to validate the input fields before adding a bookmark to the collection. The following validation rules are applied:

- Bookmark Name: The name must contain at least 3 word characters (letters, numbers, or underscores).

- URL: The URL must start with either "http://" or "https://".

Invalid inputs will display error messages, and the bookmark will not be added to the collection until valid inputs are provided.

## Contributing

Contributions are welcome! If you want to contribute to the project, follow these steps:

1. Fork the repository.

2. Create a new branch:
   ```
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:
   ```
   git commit -m 'Add some feature'
   ```

4. Push to the branch:
   ```
   git push origin feature/your-feature-name
   ```

5. Create a pull request.

Please ensure your code follows the project's coding guidelines and is well-documented.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
