# Thrifty
Redefining Style, One Find at a Time.


# ThriftNest Ecommerce Website

ThriftNest is an ecommerce platform exclusively tailored for the second-hand clothing and footwear market. Our website simplifies online shopping with MPesa payment integration, ensuring a smooth, user-friendly experience for both buyers and administrators.

## Key Features

1. **Target Market**
   - Focused on the second-hand wear industry.
   - Offers a curated collection of clothes and shoes.

2. **User Experience**
   - Front-end interface for customers to browse, search, and purchase items.
   - Streamlined MPesa payment process.

3. **Admin Dashboard**
   - Two admin accounts for managing products, orders, and customer interactions.
   - Tools for tracking inventory and sales performance.

## Project Setup

### Prerequisites
- Node.js and npm
- A backend framework (e.g., Django, Laravel) installed and set up.
- Access to MPesa Developer API credentials.

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/thriftnest.git
   ```
2. Navigate to the project directory:
   ```bash
   cd thriftnest
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     MPESA_CONSUMER_KEY=your_consumer_key
     MPESA_CONSUMER_SECRET=your_consumer_secret
     BASE_URL=your_base_url
     ```

5. Start the development server:
   ```bash
   npm start
   ```

## MPesa Payment Integration

The payment process uses MPesa's API for seamless and secure transactions. Documentation and setup instructions are available in the `docs/mpesa-integration.md` file.

## Contribution Guidelines

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For inquiries or support, contact us at: **elishaawatii@gmail.com**
