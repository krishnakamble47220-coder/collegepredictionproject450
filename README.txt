NETLIFY DEPLOYMENT

1. Extract this ZIP file.
2. Open https://app.netlify.com/drop
3. Drag the extracted folder (the folder containing index.html) into the Netlify Drop area.
4. Wait for Netlify to publish the site and open the generated URL.

Important:
- This is a static HTML site; index.html is at the folder root.
- The page references external Google Fonts, Font Awesome, EmailJS, and Razorpay scripts, so those services require an internet connection.
- Before accepting real payments, configure Razorpay with a LIVE key and verify payments on a secure server. The current page contains a TEST Razorpay key and client-side UTR unlocking, which is not secure for real paid access.
- Review EmailJS settings before publishing; do not use email to collect passwords or sensitive login information.
