**IQCandidate**

IQCandidate is a web-based application designed to assist job seekers in preparing professional CVs, crafting tailored cover letters, and automatically applying to suitable job postings on platforms like LinkedIn and Indeed.
**Features**
1.CV Builder: Prebuilt templates for creating professional CVs.

2.Cover Letter Generator: Tools to craft personalized cover letters.

3.Automated Applications: Automatically apply for relevant job postings on LinkedIn and Indeed.

4.Job Matching: Smart algorithms to identify suitable job opportunities.

5.User Profiles: Manage and update user information efficiently.

**Tech Stack**
1.Frontend: Razor Pages, HTML, CSS, JavaScript

2.Backend: ASP.NET Core MVC

3.Database: SQL Server

4.Automation: Integration with LinkedIn and Indeed APIs

**Requirements**
.NET SDK: Version 6.0 or higher

SQL Server: Local or remote instance

Git: For version control

LinkedIn and Indeed Developer Accounts: For API integrations

**Installation**
Clone the repository:

git clone https://github.com/YourUsername/IQCandidate.git
cd IQCandidate

Set up the database:

Update the connection string in appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=IQCandidateDB;User Id=YOUR_USERNAME;Password=YOUR_PASSWORD;"
}

Run migrations to create the database:

dotnet ef database update

Run the application:

dotnet run

Access the application at http://localhost:5000.

Usage

Register or log in to create a profile.

Use the CV builder to generate a professional CV.

Write or customize a cover letter.

Enable LinkedIn and Indeed integrations to auto-apply for job postings.

Monitor application progress through the dashboard.

Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

License

This project is licensed under the MIT License.

Contact

For inquiries or support, contact unathinxasana14@gmail.com.
