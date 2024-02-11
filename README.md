README.md Content for Financial Analysis and Calculator App

Introduction
This app combines a versatile financial calculator with an in-depth stock market analysis platform, designed to assist users in making informed investment decisions. It features calculation tools for various financial metrics and comprehensive stock market insights, including real-time data visualization, financial statements, and predictive analysis.

Features
Financial Calculations: Discounts, percentages, EPS ratio, net profit margin, ARV, etc.
Stock Market Analysis: Graphs, charts, financial statements, and quarterly earnings insights.
Real-time Market News: Latest news and articles on stock companies.
Subscription Access: Advanced features available with a subscription after a 7-day trial.
Live Chat Support: Real-time assistance using WebSocket for communication, implemented with Next.js for an efficient, scalable solution.
Secure Authentication: Robust login and authentication system.
Technology Stack
Frontend: Vue.js for UI interactions, Next.js for WebSocket communication and SSR benefits.
Backend: Spring Boot for RESTful API services, ASP.NET for authentication and subscription management. Laravel Php for web socket communication., crypto currency coming soon
Microservices: Utilized for modular development and deployment.
DevOps & CI/CD: Jenkins, integrated with GitHub for continuous integration and delivery, Terraform for infrastructure management.
Cloud Services: AWS Lambda for serverless operations.

dotnet new webapp -o MyRazorApp
cd into app && dotnet run

use only spring boot online 
https://start.spring.io/
only web services, rest deps.. others will break the app when running
download the zip file and extract it
cd into the folder and run mvn spring-boot:run
port 8080

in src/main/java in the demo file
add 
import org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration;

@SpringBootApplication(exclude = {DataSourceAutoConfiguration.class })

./gradlew bootRun

laravel new example-app
cd app
composer install --ignore-platform-reqs (if neccessary)
php artisan key:generate (for the first time only)
php artisan serve

npm init vite@latest client --template vue
cd into app
npm i
npm run dev

