# WhiteLagoon - Hotel Reservation System

WhiteLagoon is a hotel reservation system designed to provide users with a seamless experience for searching, booking, and managing hotel reservations. Built with **Clean Architecture**, this project ensures scalability, maintainability, and efficient separation of concerns.

---

## 🏨 Features

- **Room Search**: Browse available rooms with filters for price, amenities, and availability.
- **Reservation Management**: Book rooms, view reservation details, and make modifications as needed.
- **Payment Integration**: Secure payment processing using Stripe.
- **Interactive UI**: User-friendly design with modern tools like Bootstrap and Syncfusion.
- **Data Visualization**: Charts and grids for admin insights powered by Syncfusion.
- **Responsive Design**: Fully responsive UI for mobile and desktop users.

---

## 🛠️ Technologies Used

- **Languages & Frameworks**:  
  - C#  
  - ASP.NET Core MVC  

- **Frontend**:  
  - JavaScript  
  - HTML, CSS  
  - Bootstrap  
  - Syncfusion (charts, grids, etc.)

- **Backend**:  
  - ASP.NET Core MVC
  - Stripe API (Payment Gateway)  

- **Database**:  
  - MS SQL Server  

---

## 📂 Project Structure

This project is built following **Clean Architecture** principles, ensuring modularity and maintainability. The structure includes:

WhiteLagoon/ 

├── WhiteLagoon.Application/ # Application layer (services, contracts, shared logic)

├── WhiteLagoon.Domain/ # Core domain entities and business logic 

├── WhiteLagoon.Infrastructure/ # Data access, migrations, repository, email services 

├── WhiteLagoon.Web/ # Presentation layer (UI, controllers, views, models)


### Key Layers

- **Application Layer**: Contains application-specific services, contracts, and common logic.  
- **Domain Layer**: The core layer housing business entities and domain logic, independent of other layers.  
- **Infrastructure Layer**: Implements data access, migrations, and communication with external systems like email and payment gateways.  
- **Web Layer**: The presentation layer for handling HTTP requests and rendering views.

---

## ⚙️ Installation and Setup

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [MS SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
  
### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/white-lagoon.git
   cd white-lagoon
  
2. Configure the environment:
   - Update the database connection string in `appsettings.json` under the `WhiteLagoon.Web` project.
   - Add your Stripe API keys to the configuration.

3. Apply database migrations:
   ```bash
   dotnet ef database update --project WhiteLagoon.Infrastructure
   ```

4. Run the application:
   ```bash
   dotnet run --project WhiteLagoon.Web
   ```

---

## 🚀 Usage

1. **Search for Rooms**: Use filters to find rooms based on your preferences.
2. **View Details**: Check room amenities, availability, and pricing.
3. **Make a Booking**: Reserve rooms and process payments securely via Stripe.
4. **Admin Panel** (if applicable): Use Syncfusion charts and grids for data visualization and insights.

---

## 🧑‍💻 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Submit a pull request.

---
