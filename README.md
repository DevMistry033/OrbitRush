## Environment Variables Setup

This project uses environment variables for configuration.

### Steps to configure:

1. Create a `.env` file in the root directory
2. Copy the contents of `.env.example` into `.env`
3. Fill in your own credentials

---

### Required Variables

| Variable              | Description                        |
| --------------------- | ---------------------------------- |
| PORT                  | Port on which the server runs      |
| MONGO_URL             | MongoDB connection string          |
| CLOUDINARY_CLOUD_NAME | Cloudinary cloud name              |
| CLOUDINARY_API_KEY    | Cloudinary API key                 |
| CLOUDINARY_API_SECRET | Cloudinary API secret              |
| RAZORPAY_KEY_ID       | Razorpay public key                |
| RAZORPAY_KEY_SECRET   | Razorpay secret key                |
| BREVO_SMTP_USER       | Brevo SMTP username (use `apikey`) |
| BREVO_SMTP_PASS       | Brevo SMTP API key / password      |
| JWT_SECRET            | Secret key for JWT authentication  |

---

### Email Configuration (Important)

This project uses **Brevo (Sendinblue) SMTP** for sending emails (OTP, enquiries, booking confirmations).

- Gmail SMTP is **not used** in production
- The sender email must be **verified in the Brevo dashboard**
- Emails will appear to be sent **from your email address**

---

⚠️ **Do not share your `.env` file publicly**
⚠️ Always restart the server after updating environment variables
