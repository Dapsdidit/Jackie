Built with PHP in **OOP (Object-Oriented Programming)** style, this project uses a **MySQL database** for data management. It incorporates **AJAX** and **jQuery** to handle dynamic actions like follow/unfollow, likes, user searches, and interactive popups (e.g., comments, user lists) without page reloads.

---

## 🚀 Features

* User Authentication: **Sign In / Sign Up**
* Post tweets (text or images)
* **Retweet** or **Quote Tweet** (including nested quote tweets)
* Like tweets
* Add **comments** and **nested replies**
* Mention users and use **hashtags**
* Follow/Unfollow functionality
* Real-time **notifications** for interactions (likes, comments, follows, etc.)
* Update profile settings: **username, password, email**
* Search for users by **name or username**
* Edit profile: update **avatar, username, cover photo**, and more

---

## ⚙️ Running Locally

1. **Create a new MySQL database** and import the `jackie.sql` file.
2. Navigate to `core/classes/connection.php` and configure your database credentials:

```php
protected static $servername = "localhost";
protected static $db_name = "twitter";
protected static $username = "root";
protected static $password = "";
```

3. You're all set! Launch the project on your local server.

---

Let me know if you'd like a version with markdown styling for GitHub README or project documentation!
