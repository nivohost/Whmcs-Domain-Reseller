# WHMCS Domain Reseller Moudle
Global Domain Reseller for WHMCS with 1100+ tld's listed.

🔧 Step 1: Extract & Upload Files
Extract the ZIP File locally.

Inside you'll find a folder like:
/modules/registrars/nivohostdomainreseller/
Upload the contents to your WHMCS installation:

/your-whmcs-root/modules/registrars/nivohostdomainreseller/
🧩 Step 2: Activate the Module in WHMCS
Go to your WHMCS Admin Panel.

Navigate to:

Setup > Products/Services > Domain Registrars
Locate Nivohost Domain Reseller and click Activate.

You’ll be asked to enter:

✅ API Key

✅ Reseller Email or ID

Click Save Changes.

🌐 Step 3: Configure TLD Pricing
Go to:

Setup > Products/Services > Domain Pricing
Click Add New TLD.

Add TLDs like .com, .in, .xyz, etc.

Set:

Auto Registration to nivohostdomainreseller

Pricing (optional; WHMCS can sync prices using the module if supported)

Save changes.

🔁 Optional: Sync Domain Pricing (if supported)
If the module supports pricing sync:

Go to:

Addons > Nivohost Domain Reseller > Sync Prices
Click Sync All TLDs to pull the latest wholesale prices.

🔍 Step 4: Test a Domain Search
Go to WHMCS client area.

Try searching for a domain.

Check if availability is shown and if order flow works.

✅ Step 5: Go Live
Once domain registration and management (DNS, WHOIS, lock, etc.) work in test mode, you’re ready to start reselling domains via Nivohost.

Promote your domain pricing and offer via landing pages or WHMCS frontend customization.

📌 Troubleshooting Tips
Issue	Solution
Domain not registering -	Ensure correct API key and reseller credentials
Prices not updating -	Use the sync tool (if provided) or set manually
500 error or blank page -	Check file permissions (644 for files, 755 for folders) and PHP version compatibility
Module not showing -	Confirm upload path is modules/registrars/nivohostdomainreseller

📞 Support
For any issues or API credentials, contact <a herf="https://nivohost.com/">Nivohost</a> support directly
