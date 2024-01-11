# FullStack E-Commerce App

Welcome to our FullStack E-Commerce App! This application is built using Ruby on Rails and aims to provide a seamless and feature-rich e-commerce experience.

## Features

- **User Authentication:** Secure user authentication system with registration, login, and logout functionality.

- **Product Management:** Add, edit, and delete products with ease. Include product images, descriptions, and pricing information.

- **Shopping Cart:** Users can add products to their shopping cart, review their selections, and proceed to checkout.

- **Order Processing:** Complete order processing with real-time updates on order status. Confirmation emails are sent to users upon successful purchase.

- **Payment Integration:** Secure payment processing using [Payment Gateway]. Currently supports [Payment Method].

- **Responsive Design:** A responsive and mobile-friendly design ensures a seamless experience across devices.

- **Admin Dashboard:** Exclusive admin dashboard for managing products, orders, and user accounts.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Deadtargaryen/E-Commerce-with-Ruby-on-rails.git
   ```

2. Navigate to the project directory:

   ```bash
   cd fullstack-ecommerce-app
   ```

3. Install dependencies:

   ```bash
   bundle install
   ```

4. Set up the database:

   ```bash
   rails db:create db:migrate db:seed
   ```

5. Start the server:

   ```bash
   rails server
   ```

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## Configuration

- Configure your database settings in `config/database.yml`.
- Set up your environment variables for sensitive information

## Dependencies

- Ruby version [Your Ruby Version]
- Rails version [Your Rails Version]
- Here is a list of dependencies I used in this project

1. **rails (~> 7.1.2)**
   - Purpose: The Ruby on Rails framework for building web applications.

2. **sprockets-rails**
   - Purpose: The original asset pipeline for Rails, managing and serving static assets.

3. **pg (~> 1.1)**
   - Purpose: PostgreSQL adapter for Active Record, allowing Rails to interact with PostgreSQL databases.

4. **sqlite3 (~> 1.4)**
   - Purpose: SQLite adapter for Active Record, allowing Rails to interact with SQLite databases.

5. **puma (>= 5.0)**
   - Purpose: A web server for running Rails applications.

6. **importmap-rails**
   - Purpose: Allows the use of JavaScript with ECMAScript module (ESM) import maps in Rails applications.

7. **turbo-rails**
   - Purpose: Hotwire's Single Page Application (SPA)-like page accelerator, enabling faster page transitions.

8. **stimulus-rails**
   - Purpose: Hotwire's modest JavaScript framework for enhancing interactivity in Rails views.

9. **tailwindcss-rails**
   - Purpose: Integrates Tailwind CSS, a utility-first CSS framework, with Rails.

10. **jbuilder**
    - Purpose: Helps in building JSON APIs in a simple and flexible way.

11. **redis (>= 4.0.1)**
    - Purpose: Enables the use of Redis as an adapter for running Action Cable in production.

12. **tzinfo-data**
    - Purpose: Provides timezone data for platforms that don't include zoneinfo files, such as Windows and JRuby.

13. **bootsnap**
    - Purpose: Reduces boot times through caching; typically required in the `config/boot.rb` file.

14. **image_processing (~> 1.2)**
    - Purpose: Supports Active Storage variants for transforming images.

15. **debug (development, test)**
    - Purpose: Debugging tool for Ruby applications.

16. **web-console (development)**
    - Purpose: Provides a console on exception pages for debugging in development.

17. **capybara (test)**
    - Purpose: A testing utility for simulating user interactions with web applications.

18. **selenium-webdriver (test)**
    - Purpose: A browser automation framework often used in conjunction with Capybara for testing.

19. **devise (~> 4.9)**
    - Purpose: A flexible authentication solution for Rails applications.

20. **font-awesome-sass (~> 6.5.1)**
    - Purpose: Integrates Font Awesome icons with the Sass stylesheet.

21. **stripe (~> 10.3)**
    - Purpose: A gem for integrating with the Stripe payment gateway.

22. **pagy (~> 6.2)**
    - Purpose: A fast and lightweight pagination library for Rails.

23. **aws-sdk-s3 (require: false)**
    - Purpose: Allows integration with Amazon S3 for storage, but it's not loaded by default.


## License

This project is licensed under the MIT License
