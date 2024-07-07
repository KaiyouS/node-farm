# Node Farm Application

This is a simple Node.js application that demonstrates the use of file reading, HTTP server, and template rendering. It serves as an example of a basic e-commerce website for basic goods.

## Installation

To run this application, you need to have Node.js installed on your system. You can download it from [https://nodejs.org/](https://nodejs.org/).

Once you have Node.js installed, follow these steps:

1. Clone or download the repository.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run `npm install` to install the required dependencies.

## Usage

To start the server, run `node index.js` in the project directory. The server will start listening on port 8000.

You can access the following pages:

- Home page: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- Product page: [http://127.0.0.1:8000/product?id=0](http://127.0.0.1:8000/product?id=0) (replace `0` with the desired product ID)
- API endpoint: [http://127.0.0.1:8000/api](http://127.0.0.1:8000/api)

## File Structure

- `index.js`: The main entry point of the application.
- `modules/replaceTemplate.js`: A helper function for replacing template placeholders with data.
- `templates/template-overview.html`: The template for the overview page.
- `templates/template-card.html`: The template for a product card.
- `templates/template-product.html`: The template for the product page.
- `dev-data/data.json`: The JSON file containing the product data.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
