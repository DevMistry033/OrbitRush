## Environment Variables Setup

This project uses environment variables for configuration.

### Steps to configure:

1. Create a `.env` file in the root directory
2. Copy the contents of `.env.example` into `.env`
3. Fill in your own credentials

### Required Variables

| Variable | Description |
|--------|------------|
| PORT | Port on which the server runs |
| MONGO_URL | MongoDB connection string |
| CLOUDINARY_CLOUD_NAME | Cloudinary cloud name |
| CLOUDINARY_API_KEY | Cloudinary API key |
| CLOUDINARY_API_SECRET | Cloudinary API secret |
| RAZORPAY_KEY_ID | Razorpay public key |
| RAZORPAY_KEY_SECRET | Razorpay secret key |
| GMAIL_ID | Gmail address for sending emails |
| GMAIL_PASSWORD | Gmail App Password (not normal password) |

⚠️ **Do not share your `.env` file publicly**
