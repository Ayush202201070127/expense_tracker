<h1 align="center" id="title">Expense Tracker</h1>

<p align="center"><img src="https://socialify.git.ci/5codeman/Expense_Tracker_SQL/image?custom_description=Tracking+expenses+is+directly+proportional+to+saving+money&amp;description=1&amp;font=KoHo&amp;forks=1&amp;issues=1&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Brick+Wall&amp;pulls=1&amp;stargazers=1&amp;theme=Dark" alt="project-image"></p>

<p id="description">Expense Tracker SQL is a web-based application that helps users efficiently track and manage their expenses. Built using Node.js Express.js MySQL and Sequelize it allows users to log their expenses categorize them and analyze their spending habits.</p>

<h2>🚀 Demo</h2>

[https://expense-tracker-jvy0.onrender.com/](https://expense-tracker-jvy0.onrender.com/)

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   User Authentication: Secure login and registration system.
*   Expense Management: Add edit and delete expenses.
*   Categories: Categorize expenses by date or category.
*   Insights & Reports: View spending trends and summaries by month or date.
*   Subscription Payments: Integrated Razorpay for managing subscription payments.
*   Password Reset: Uses Bravo for sending password reset emails.

<br>
<h2>🛠️ Installation Steps:</h2>
<p>1. Prerequisites</p>


```
Ensure you have the following installed: 

Node.js (v16 or later)

MySQL (latest version)
```
<br>
<p>2. Clone the Repository</p>

```
git clone https://github.com/5codeman/Expense_Tracker_SQL.git

cd Expense_Tracker_SQL
```
<br>

<p>3. Install Dependencies</p>

```
npm install
```
<br>
<p>4. Set Up Database</p>

```
Create a MySQL database.
```
<br>
<p>5. Setup .env file</p>

<p> NOTE: This project is integrated with Razorpay, Brevo and JWT authentication. Before creating the .env file you will need credentials for these services. Generate your own secret key and obtain the necessary Razorpay and Brevo credentials. Refer to the .env format provided below.</p>

```
# Server Configuration
PORT=your_port_number

# Database Configuration
DB_HOST=your_database_host
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_SCHEMA=your_database_schema

# API Keys
BREVO_API_KEY=your_brevo_api_key

# Payment Gateway (Razorpay)
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret

# Security
SECRET_KEY=your_secret_key

```
<br>
<p>6. Start the Application</p>

```
npm start
```

  <br>
  
<h2>💻 Built with</h2>

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MySQL with Sequelize ORM
- **Payment Gateway**: Razorpay
- **Email Service**: Brevo

<br>

## Contact
For any queries or feedback, feel free to reach out via GitHub Issues.


---

## Made with ❤️ by [CHIRAG RAJ](https://github.com/5codeman/)
