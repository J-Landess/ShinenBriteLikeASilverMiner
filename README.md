# 🪙 Silver Aureum – Static E-Commerce Prototype

A lightweight, zero-backend storefront built for rapid deployment using **GitHub Pages**. This project includes a landing page, cart system, checkout flow, and account system — all running entirely in the browser.

---

# 🚀 Live Concept

This project is designed to:

* Launch quickly
* Cost almost nothing
* Validate a product idea before scaling

No backend. No database. No hosting costs.

---

# 📁 Project Structure

```
/your-repo
  ├── index.html       # Landing page + product listing + cart
  ├── checkout.html    # Checkout flow + payment selection
  ├── account.html     # Login/register + subscription mock
```

---

# ⚙️ Features

## 🛒 Cart System

* Add/remove products
* Quantity controls
* Persistent cart via `localStorage`
* Shared across all pages

## 💳 Checkout (Demo)

* Shipping form
* Payment method selector:

  * Cash App
  * Venmo
  * Zelle
  * PayPal
* Dummy API endpoint (`fetch()` placeholder)

## 👤 Account System (Demo)

* Register with email/password
* Login/logout
* Stored locally in browser

⚠️ Not secure — prototype only

## 💎 Paid Membership Tier

* “Silver Circle” subscription UI
* Simulated subscribe flow
* Ready to connect to real billing later

---

# 🌐 Deployment (GitHub Pages)

## 1. Create Repo

Upload these files to a GitHub repository.

## 2. Enable Pages

Go to:

```
Settings → Pages
```

Select:

```
Source: main branch
```

Your site will be live at:

```
https://yourusername.github.io/repo-name/
```

---

# 🔗 Custom Domain Setup

## Step 1: Buy a domain

Recommended providers:

* Namecheap (cheap + simple)

## Step 2: Add domain in GitHub

```
Settings → Pages → Custom Domain
```

Enter:

```
yourdomain.com
```

## Step 3: Configure DNS

### A Records

```
@ → 185.199.108.153
@ → 185.199.109.153
@ → 185.199.110.153
@ → 185.199.111.153
```

### CNAME

```
www → yourusername.github.io
```

## Step 4: Enable HTTPS

Toggle:

```
Enforce HTTPS
```

---

# 🧠 How It Works (Important)

This project uses:

### `localStorage`

To store:

* Cart items
* User account
* Login session

### No backend

* No database
* No real authentication
* No real payments

---

# ⚠️ Limitations (Read This)

This is a **prototype only**.

### NOT secure

* Passwords stored in browser
* No encryption
* No server validation

### NOT real payments

* Checkout does NOT process money
* Only simulates flow

### NOT production ready

* No fraud protection
* No order management

---

# 🔌 Upgrade Path (When You’re Ready)

## Auth

* Supabase
* Firebase Auth

## Payments

* Stripe
* PayPal Checkout
* Lemon Squeezy

## Backend

* Supabase (recommended)
* Node.js API (Vercel)

## Forms

* Formspree

---

# 💡 Cheap Stack (Recommended)

| Component | Tool          | Cost                |
| --------- | ------------- | ------------------- |
| Hosting   | GitHub Pages  | Free                |
| Domain    | Namecheap     | ~$10/year           |
| Forms     | Formspree     | Free tier           |
| Auth      | Supabase      | Free tier           |
| Payments  | Stripe/PayPal | Pay per transaction |

---

# 🛠 Customization

Before launching, update:

* Brand name
* Product names & pricing
* Payment handles (Cash App, Venmo, etc.)
* Dummy API endpoint:

  ```js
  https://example.com/api/demo-checkout
  ```

---

# ⚖️ Compliance Note

Avoid making:

* medical claims
* disease treatment claims
* “cure” language

This helps prevent:

* account bans
* payment processor issues
* legal problems

---

# 🧪 Development Tips

* Test across multiple browsers
* Clear `localStorage` when debugging:

  ```js
  localStorage.clear()
  ```
* Use Chrome DevTools → Application → Storage

---

# 📌 Future Improvements

* Product images
* Order confirmation page
* Email receipts
* Real checkout integration
* Admin dashboard

---

# 🧠 Philosophy

Build fast → validate → upgrade later.

This project is intentionally:

* simple
* cheap
* hackable

---

# 🙌 Credits

Built as a rapid prototype using:

* HTML
* CSS
* Vanilla JavaScript
* GitHub Pages

---

# 🚀 Launch Checklist

* [ ] Update branding
* [ ] Add domain
* [ ] Set payment handles
* [ ] Test checkout flow
* [ ] Enable HTTPS
* [ ] Push to GitHub

---

**You’re
