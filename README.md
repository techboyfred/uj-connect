# UJConnect
An application designed for UJ students to connect with each through an online market and use a plethora of relevant community features
---

## Features

- Online student market
- Apply to be a tutor
- Find a tutor or study partner
- Join offical UJ Clubs and Societies

---

## Technologies Used
- UI: HTML & CSS
- Language: Java
- Database: MySQL (hosted on [Aiven](https://aiven.io)) |
- DB Connectivity: MySQL Connector (via NuGet Packages)
- Password Security: BCrypt (via NuGet Packages)
- IDE: Visual Studio (2019)

---
## Project Structure
```
ProductivityTracker/
├── Program.cs
├── README.md
├── docs/
│   ├── changeLog.md
│   ├── erd.pdf
│   ├── modelsUMLDesign.pdf
│   └── daoUMLDesign.pdf
├── Models/
│   ├── ActionType.cs
│   ├── Administrator.cs
│   ├── AvailabilitySlot.cs
│   ├── CampusLocation.cs
│   ├── CampusName.cs
│   ├── Club.cs
│   ├── ClubMembership.cs
│   ├── ModerationAction.cs
│   ├── ModuleRegistration.cs
│   ├── Product.cs
│   ├── ProductEnquiry.cs
│   ├── ProductPackage.cs
│   ├── ProductType.cs
│   ├── Rate.cs
│   ├── RatePeriod.cs
│   ├── Report.cs
│   ├── ReportStatus.cs
│   ├── ReportType.cs
│   ├── TutorApplication.cs
│   ├── UJModule.cs
│   └── User.cs
├── Data/
│   ├── ProductDAO.cs
│   ├── ProductPackageDAO.cs
│   ├── ProductEnquiryDAO.cs
│   └── UserDAO.cs
├── Controllers/
│   ├── HomeController.cs
│   ├── MarketLoginController.cs
│   ├── MarketLoginByEmailController.cs
│   ├── ProfileController.cs
│   └── RegisterController.cs
├── wwwroot/
│   ├── css/
│   |   └── style.css
│   ├── fonts/
│   ├── footer/
│   ├── Header/
│   └── images/
└── Views/
    ├── Home/
    |   └── Home.cshtml
    ├── Register/ 
    |   └── Register.cshtml
    ├── MarketLogin/ 
    |   └── MarketLogin.cshtml
    ├── MarketLoginByEmail/ 
    |   └── MarketLoginByEmail.cshtml
    ├── MarketHome/ 
    |   └── MarketHome.cshtml
    ├── Profile/ 
    |   └── Profile.cshtml
    ├── Shared/
    |   ├── _Layout.cshtml
    |   ├── _Layout.cshtml.css
    |   └── Error.cshtml
    ├── _ViewStart.cshtml
    └── _ViewImports.cshtml
```

## Main Functionality
1. Login or register an account
2. View all products added to the student market
3. Buyer: Enquire with seller about buying (a) product(s)
4. Buyer: search for a specific product
5. Buyer: Control product views by either filtering or sorting the products by their preffered arrangement
6. Seller: Add products they sell
7. Seller: Specify availability times to simplify meeting arrangements
8. Seller: Confirm meetup with the buyer
9. User in general: Verify or delete account
10. User in general: Report other users and/or products
11. User in general: Apply to be a module tutor
12. User in general: Find tutor(s) and/or study partner(s)
13. User in general: Join clubs and societies
14. Admin: Handle reports
15. Admin: Add new meetup location spots across campuses
16. Admin: View all users and their (sensitive) information
17. Admin: Approve tutor applications
18. Admin: Add new clubs and societies
19. Admin: Change roles of members in clubs
20. System: Automatic validation of products in the market
21. System: Automatic and Admin-handled manual fraud detection

## Future Enhancements
- [ ] Improve and modernize the GUI, especially when the application is used on a mobile device
- [ ] Implent or Improve fraud detection methods

## Authors
### **Freddy Senamela**
- University of Johannesburg
- freddymailula@gmail.com
- www.linkedin.com/in/freddy-senamela-0b0417190

###  **Delton Novela**
- University of Johannesburg
- deltonovela@gmail.com
- www.linkedin.com/in/delton-novela-820541402

##  License
This project is open source and available under the MIT License.

## Acknowledgements

## Screenshots
