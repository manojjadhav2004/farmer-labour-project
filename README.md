# 🌾 Labour & Farmer Management System

A web-based platform designed to connect **farmers** and **labourers** for agricultural work. This system simplifies job postings, labour hiring, wage tracking, and improves communication in rural/agro-based communities.

## 🚀 Features

### 👤 User Roles
- **Admin**
  - Manages users (farmers/labourers)
  - Verifies registrations
  - Monitors job activities
- **Farmer**
  - Registers & logs in
  - Posts jobs (e.g., sowing, harvesting)
  - Views applications from labourers
  - Assigns tasks and manages schedules
- **Labourer**
  - Registers & logs in
  - Views available jobs
  - Applies to jobs
  - Tracks assigned tasks and wages

### 📲 Core Modules
- ✅ User Authentication (Login/Register)
- 📋 Job Posting and Application
- 🗓️ Task Scheduling
- 💰 Wage/Payment Tracking
- 🔔 Notifications (Optional/Future scope)
- 🌐 Responsive Frontend UI

## 💻 Tech Stack

| Layer        | Tech Used            |
|--------------|----------------------|
| Frontend     | HTML, CSS, JavaScript |
| Backend      | PHP                  |
| Database     | MySQL (via XAMPP/WAMP) |

## 🏗️ Folder Structure

```

/labour-farmer-management/
│
├── /admin/              # Admin panel
├── /farmer/             # Farmer dashboard & features
├── /labour/             # Labour dashboard & features
├── /assets/             # CSS, JS, images
├── db\_config.php        # Database connection file
├── index.php            # Home/Login page
└── README.md            # You're here!

````

## ⚙️ Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/manojjadhav2004/labour-farmer-system.git
````

2. Paste the folder into your `htdocs/` directory (XAMPP).

3. Start Apache & MySQL in XAMPP Control Panel.

4. Import `labour_farmer.sql` into **phpMyAdmin**.

5. Visit `http://localhost/labour-farmer-system` to run the project.

## 🧠 Future Enhancements

* 🌍 Location-based job matching
* 📱 Mobile app version
* 📨 SMS/Email alerts
* 🌐 Multilingual support

## 🤝 Contributing

Pull requests are welcome! If you have ideas to improve rural job matching or UI upgrades, let’s collab.

## 📷 Screenshots

> Add some UI screenshots here for extra ✨drip✨



