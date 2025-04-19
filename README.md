# Sky-Reserve ✈️  
**Airline Management System**  

A complete web-based airline management system for flight bookings, passenger management, and administrative tasks.  

## Features ✨  
- **User Authentication**: Login/register system (`login_register.php`).  
- **Flight Booking**: Book tickets with seat selection (`book_ticket.php`).  
- **PNR Enquiry**: Check booking status (`pnr_enquiry.php`).  
- **Ticket Cancellation**: Cancel existing bookings (`cancel_ticket.php`).  
- **Admin Dashboard**: Manage flights, passengers, and vacancies (`dashboard.php`, `chart_vacancy.php`).  
- **Payment Integration**: Secure payment processing (`payment.php`).  
- **Responsive UI**: Custom CSS/JS (`style.css`, `aero1.css`, `script.js`).  

## Tech Stack 💻  
- **Frontend**: HTML5, CSS3, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (via `config.php` and `tables/`)  
- **Data**: CSV-based airport list (`airports.csv`)  

## Installation 🛠️  
1. **Prerequisites**:  
   - Web server (Apache/Nginx)  
   - PHP 7.4+  
   - MySQL  

2. **Setup**:  
   ```bash
   git clone https://github.com/Bhargav221287/Sky-Reserve-Airline-mangement-system.git
   cd Sky-Reserve-Airline-mangement-system
   ```  
3. **Database**:  
   - Import MySQL tables from `/tables` directory.  
   - Configure `config.php` with your database credentials.  

4. **Run**:  
   - Place the project in your web server's root (e.g., `htdocs` or `/var/www/html`).  
   - Access via `http://localhost/Sky-Reserve-Airline-mangement-system`.  

## File Structure 📂  
```
├── accounts.html          # User account management
├── aero.html             # Flight UI  
├── book_ticket.php       # Ticket booking logic  
├── dashboard.php         # Admin dashboard  
├── login_register.php    # Auth system  
├── payment.php           # Payment gateway  
└── tables/               # Database schemas  
```

## Contributing 🤝  
1. Fork the repository.  
2. Create a new branch for your feature.  
3. Test changes thoroughly.  
4. Submit a pull request.  

```

---

### Key Enhancements:  
1. **Tech Stack Clarity**: Explicitly mentions PHP/MySQL based on your files.  
2. **Setup Guide**: Added detailed steps for local deployment.  
3. **File Structure**: Helps contributors navigate the repo.  
4. **Placeholder for Screenshots**: Replace `screenshot1.png` with actual images later.  

**To complete the README**:  
- Upload 1-2 screenshots of your UI (e.g., booking page, dashboard).  
- Update `config.php` details if sensitive data exists (mention `.gitignore` in future projects).  
