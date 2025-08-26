# LIPA NA MPESA DARAJA API

This project is a PHP implementation for integrating with Safaricom's Lipa Na M-Pesa Daraja API. It allows you to initiate M-Pesa payments from your web application.

## Features
- Initiate STK Push requests to customer phones
- Handle M-Pesa payment callbacks
- Securely store and use API credentials

## Requirements
- PHP 7.0 or higher
- cURL extension enabled
- Safaricom Daraja API credentials (Consumer Key & Secret)

## Setup
1. Clone this repository.
2. Update your API credentials in the appropriate section of `index.php`.
3. Ensure your server is accessible via HTTPS (required by Safaricom).
4. Set your callback URL in the Safaricom developer portal to point to your server.

## Usage
- Run the project on your local or remote server.
- Access `index.php` to initiate an M-Pesa payment.
- Monitor the callback endpoint for payment results.

## References
- [Safaricom Daraja API Documentation](https://developer.safaricom.co.ke/daraja/apis/post/safaricom.safaricom/v1/mpesa/stkpush/processrequest)

## License
This project is for educational purposes. Please check Safaricom's terms for production use.
