# WHMCS Domain Reseller Module
Global Domain Reseller for WHMCS with 1100+ tld's listed.

API Request : https://nivohost.com/ ( We are ready to join you as domain reseller )
- Create a account on nivohost then create a support ticket for api.

## 📦 Installation

### 1. Download & Extract

* Download and extract the ZIP file.
* Inside the archive, you’ll find:

  ```
  /modules/registrars/nivohostdomainreseller/
  ```

### 2. Upload Files

* Upload the contents to your WHMCS installation directory:

  ```
  /your-whmcs-root/modules/registrars/nivohostdomainreseller/
  ```

---

## ⚙️ Module Activation

1. Login to your WHMCS Admin Panel.
2. Go to:

   ```
   Setup > Products/Services > Domain Registrars
   ```
3. Find **Nivohost Domain Reseller** and click **Activate**.
4. Enter the required API details:

   * **API Key**
   * **Reseller Email or ID**
   * **Endpoint URL** (e.g., `https://api.nivohost.in/`)
5. Click **Save Changes**.

---

## 🌍 Adding TLDs

1. Go to:

   ```
   Setup > Products/Services > Domain Pricing
   ```
2. Click **Add New TLD**.
3. Enter TLDs like `.com`, `.in`, `.xyz`, etc.
4. Set **Auto Registration** to `nivohostdomainreseller`.
5. Set pricing and save.

---

## 🔁 (Optional) Sync Pricing

If the module supports syncing:

* Go to:

  ```
  Addons > Nivohost Domain Reseller
  ```
* Click **Sync Prices** to fetch live TLD pricing.

---

## ✅ Features

* ✅ Domain availability check
* ✅ Domain registration and transfer
* ✅ WHOIS contact management
* ✅ DNS management (if API allows)
* ✅ EPP code management
* ✅ Lock/unlock domain
* ✅ Nameserver updates

---

## 🧪 Testing

1. Go to the WHMCS client area.
2. Search for a domain.
3. Place a test domain order to verify everything works.

---

## 🛠 Troubleshooting

| Problem                 | Solution                                             |
| ----------------------- | ---------------------------------------------------- |
| Module not appearing    | Ensure correct folder path and permissions           |
| API error               | Verify API key and endpoint                          |
| Domain not registering  | Check required fields and TLD setup                  |
| Blank page or 500 error | Check PHP error logs, permissions, and compatibility |

---

## 📬 Support

For support, please contact [Nivohost](https://nivohost.in) via your partner dashboard or email.

---

## 📝 License

This module is intended only for **Nivohost Resellers**. Redistribution without authorization is strictly prohibited.

