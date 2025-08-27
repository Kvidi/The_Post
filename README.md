# The Post

## Description
A modern news web application built with .NET 8 and ASP.NET Core project utilizing both MVC and Razor Pages. The Post delivers a rich, responsive experience for readers and provides advanced features for editors and administrators.

## Project Status
This project was developed as a team exercise at Lexicon. It's a fully functional news web app prototype. The project is not in production and is no longer under active development.

## Features
- **News Categories:** Local, Sweden, World, Weather, Sports, Economy
- **Search:** Full-text search for articles
- **Live Features:** Real-time weather and electricity spot prices via external APIs
- **User Accounts:** Registration, login, and role-based access (Admin, Employee, Reader)
- **Subscriptions:** Monthly subscription with payment tracking (Stripe integration)
- **Newsletter:** Automated weekly newsletters (Azure Functions), including Editor's Choice and category-based articles
- **Admin Dashboard:** Article management, employee and role management, subscription statistics
- **Responsive Design:** Mobile-friendly layouts using Bootstrap
- **Privacy & Cookies:** GDPR-compliant privacy policy and cookie consent

## Technology Stack
- **Backend:** C#, .NET 8, ASP.NET Core Razor Pages and MVC, Entity Framework Core, LINQ, SQL Server  
- **Frontend:** Razor Pages & Razor Views, HTML, CSS, Bootstrap, JavaScript
- **Libraries / APIs:** MailKit, MimeKit, X.PagedList, Toastr.js, Chart.js, Stripe, Identity, LexiconWeatherApi, LexLink SpotPrices API
- **Azure Functions:** Automated newsletter, article archiving, image resizing, blob storage

## My Contribution
I developed frontend and backend designs for the Admin panel with features like article management with an Azure Blob Storage for the article images, Employee, Roles and Subscription management, Subscription statistics with Chart.js and the Dashboard. Designed and implemented the front page, the monthly subscriptions with payment through Stripe and some database structures.
- Admin panel, front- & Backend
- Article, employee, role and subscriptions management
- Dashboard & statistics with Chart.js
- Subscription with Stripe payment integration
- Front page & database designs

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Kvidi/The_Post.git 
``` 
2. Open the solution in Visual Studio 2022 (`The_Post.sln`).
3. Restore NuGet packages.
4. Ensure your local `appsettings.json` contains your own secrets, SQL connection string and is ignored by Git. 
5. Run the database migrations to set up the database schema.
   - Open the Package Manager Console in Visual Studio.
   - Run the command:
		```powershell
		Update-Database
		```
6. Build and run the application.

## Usage

### For Users
- Register a new account
- Log in to access more features
- Subscribe for full access
- Browse, read, and like articles
- View real-time weather and electricity prices
- Sign up for the weekly newsletter
- Manage your profile

### For Administrators
- Access the dashboard for site statistics
- Manage articles: view, create, edit, delete, archive, set Editor's Choice
- Manage employees: register, edit, delete
- Manage roles: create, edit, delete, assign roles
- Manage subscriptions: create, edit, delete, view details
- View subscription statistics

## License
This project is licensed under the MIT License.

## Authors
- Team Post
