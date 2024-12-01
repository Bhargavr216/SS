# SS Services Web Application

## Description

This is a multi-page web application for managing and tracking services provided by SS Services. The application includes a login page, a homepage with options to navigate to different sections (including a billing page, payment records, and a list of logged-in users). It also includes features for searching users, viewing payment records, and logging out.

### Features:
- **Login Page**: Secure login page where users must provide valid credentials to access the service options.
- **User Navigation**: After logging in, users can navigate to various pages, including:
  - Billing page with payment records
  - List of logged-in users
  - Payment status and records
  - Search bar to find specific users
- **Logout Option**: Option to log out from the session.
- **Search Bar**: Easily search for users across different sections.
  
## Screenshots

#Login page
![image](https://github.com/user-attachments/assets/c71a3428-e772-4b6f-bfce-d9af4f5027ac)

#Home Page
![image](https://github.com/user-attachments/assets/417f62b1-e8cd-451d-bc00-5eab59ecb947)

#Bill entry
![image](https://github.com/user-attachments/assets/c51d5633-c3fc-49f0-ae3d-141c3085576c)

#Bill records in Excel
![image](https://github.com/user-attachments/assets/5e192878-4782-4048-8777-2295076f25fb)

#List of login users
![image](https://github.com/user-attachments/assets/c845c45e-4d80-4492-b838-91eb370c7af2)




## How to Use

1. **Login Page**:
   - Enter your **Username** and **Password** and click **LOGIN**.
   - Valid usernames include: `SS Works`, `nuthan`, `bhadri`, `muni`, and `admin`.
   
2. **Home Page**:
   - After a successful login, you will be redirected to the home page.
   - The home page contains various options with buttons. Clicking on any of these buttons will navigate you to the respective pages (such as the Billing Page, Payment Records, etc.).
   
3. **Navigation**:
   - Navigate through the website and explore features like payment records and viewing the list of logged-in users.
   
4. **Logout**:
   - A logout option is provided to securely log out from the session.

## Technologies Used

- **HTML5**: For the structure and content of the website.
- **CSS3**: For styling the web pages and ensuring a clean, responsive design.
- **JavaScript**: For handling form validations, showing/hiding password functionality, and managing dynamic content like the time and login attempts.
- **Bootstrap**: For responsive design and ensuring compatibility across devices.
- **Google Forms API**: For submitting login details to a Google Sheet for backend processing (if applicable).

## File Structure

```
/index.html            # The main login page
/home.html             # Homepage after successful login
/billing.html          # Billing page with payment records
/search.html           # Search page to find users
/logout.html           # Logout page
/ss.png                # Background image used on login page
```

## How to Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ss-services.git
   ```
2. Navigate to the project directory:
   ```
   cd ss-services
   ```
3. Open `index.html` in your web browser to start the application.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a new pull request.

## Contact

For more information or questions, feel free to reach out to:
- Bhargavr216

## Acknowledgments

- Inspired by V Bhargav Reddy's work on SS Services.
- Uses Google Sheets for backend data storage.
