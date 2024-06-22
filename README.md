# Pizza Hut Sales Analysis

This repository contains an analysis of Pizza Hut sales data, along with solutions to various case study questions using SQL.

## Introduction

This project analyzes the sales data of Pizza Hut to answer a set of case study questions. The analysis is performed using SQL to gain insights into the business performance, customer preferences, and other key metrics.

## Project Structure

The repository is structured as follows:

- `data/` - Contains the sales data used for the analysis.
- `questions.txt` - Contains the case study questions.
- `README.md` - This file.

## Data

The data used in this project includes various aspects of Pizza Hut sales, such as order details, customer information, and product information. The dataset is stored in the `data/` directory.

## Schema

The database schema used in this project includes the following tables:

1. **Order_details**
   - `order_details_id`: The unique identifier for the order detail.
   - `order_id`: The unique identifier for the order.
   - `pizza_id`: The unique identifier for the pizza.
   - `quantity`: The quantity of the pizza ordered.

2. **Orders**
   - `order_id`: The unique identifier for the order.
   - `order_date`: The date of the order.
   - `order_time`: The time of the order.

3. **Pizzas**
   - `pizza_id`: The unique identifier for the pizza.
   - `pizza_type_id`: The unique identifier for the pizza type.
   - `size`: The size of the pizza.
   - `price`: The price of the pizza.

4. **Pizza_types**
   - `pizza_type_id`: The unique identifier for the pizza type.
   - `name`: The name of the pizza type.
   - `category`: The category of the pizza type (e.g., Vegetarian, Non-Vegetarian).
   - `ingredients`: The ingredients of the pizza type.

## Case Study Questions

The case study questions are addressed in this project and are listed in the `questions.txt` file:

## SQL Queries

The SQL queries used to answer the case study questions are stored in the `queries/` directory. Each query is saved in a separate `.sql` file, named according to the question it addresses.

## Results

The results of the SQL queries are documented and explained in the presentation.

## Conclusion

The analysis provides insights into the sales performance of Pizza Hut, highlighting key trends and customer preferences. These insights can be used to make informed business decisions.

## How to Use

To run the SQL queries and analyze the data:

1. Clone this repository to your local machine.
2. Ensure you have a SQL database set up with the sales data loaded.
3. Execute the SQL scripts in the presentation to get the results.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
