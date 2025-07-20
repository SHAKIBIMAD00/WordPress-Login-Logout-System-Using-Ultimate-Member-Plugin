
# 🔐 WordPress Login/Logout System Using Ultimate Member Plugin

Easily integrate frontend login, logout, and registration pages into your WordPress website using the [Ultimate Member](https://wordpress.org/plugins/ultimate-member/) plugin — no coding required!

---

## 📁 Project Structure

```
📂 your-wordpress-site
 ┣ 📁 wp-content
 ┃ ┗ 📁 plugins
 ┃   ┗ 📁 ultimate-member
 ┣ 📄 wp-config.php
 ┣ 📄 .htaccess
 ┗ 📁 public_html
```

---

## ✅ Features

- Frontend login & registration pages
- Custom user roles & profile pages
- Redirect after login/logout
- Password reset functionality
- Shortcode-based integration

---

## 🚀 Getting Started

### 1. Install Ultimate Member Plugin

Go to your WordPress dashboard:

```
Plugins → Add New → Search “Ultimate Member” → Install → Activate
```

---

### 2. Automatically Create Required Pages

Once activated, Ultimate Member will prompt you to create default pages:

- Login (`/login`)
- Register (`/register`)
- Account/Profile (`/account`)
- Logout (automatically logs out user)

You can also create manually:

```
Pages → Add New → Title: Login → Add Shortcode: [ultimatemember form_id="ID"]
```

Default shortcodes:

```php
[ultimatemember form_id="login"]       // Login Form
[ultimatemember form_id="register"]    // Registration Form
[ultimatemember form_id="logout"]      // Logout Button
[ultimatemember_account]               // Account/Profile Page
```

---

### 3. Add Menu Links for Login & Logout

Go to:

```
Appearance → Menus → Add Custom Links
```

Use:

- Login Page: `/login`
- Register Page: `/register`
- Account Page: `/account`
- Logout Page: `/logout` *(no actual page needed, this URL logs user out)*

**Dynamic Menu Suggestion (Optional Plugin):**  
Use **"If Menu"** plugin to show/hide menu items based on login state.

---

### 4. Set Redirects (Optional)

Go to:

```
Ultimate Member → Settings → General → Login Options
```

Customize:

- After Login: `/account`
- After Logout: `/login`
- After Registration: `/welcome` (optional)

---

## 🔒 Security Tips

- Use reCAPTCHA on login/registration
- Enable email verification
- Restrict access to certain pages via Ultimate Member settings

---

## 💡 Use Cases

- Membership sites  
- Client dashboards  
- Custom user profiles  
- Private content access  

---

## 🧩 Optional Add-ons

- Ultimate Member - User Role Editor  
- Ultimate Member - reCAPTCHA  
- Ultimate Member - WooCommerce Integration  

---

## 🧰 Tech Stack

- WordPress 6.x  
- Ultimate Member Plugin  
- Optional: Elementor for styling forms/pages  

---

## 👨‍💻 Author

**Shakibul Hasan**  
[Portfolio](https://shakibulhasanimad.com) • [LinkedIn](https://www.linkedin.com/in/shakibulhasan-wordpress-seo)

---

## 📜 License

MIT – Feel free to fork & customize for your own projects.
