<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

Payments App is a comprehensive payment solution tailored to streamline and secure business transactions. It efficiently manages multiple payment gateways and offers a customizable web form for facilitating payments.

- [Visit Our Website](https://empress.eco/)
- [Report Bug](https://github.com/empress-eco/payments/issues)
- [Request Feature](https://github.com/empress-eco/payments/issues)

## Table of Contents
- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License and Acknowledgements](#license-and-acknowledgements)

## About The Project

Payments App is designed to meet the needs of businesses by offering a hassle-free way of managing payments and payment gateways. Its unique features include:

- Management of multiple payment gateways like Razorpay, Stripe, Braintree, Paypal, PayTM.
- Customizable fields for Web Form facilitating payments.
- Hassle-free installation and uninstallation process.

## Getting Started

### Prerequisites

To get started with the Payments App, you need to have bench & Empress installed on your system. You can find the installation guide [here](https://Empressframework.com/docs/v14/user/en/installation).

### Installation

1. Clone the repository by running:  
```sh
$ git clone https://github.com/empress-eco/payments.git
```
2. Add the Payments App to your bench by running:  
```sh
$ bench get-app payments
```
3. Install the Payments App on the required site by running:  
```sh
$ bench --site <sitename> install-app payments
```

## Usage

The Payments App comprises two modules - Payments and Payment Gateways. The Payment Module contains the Payment Gateway DocType, which creates links for the payment gateways. The Payment Gateways Module contains all the Payment Gateway DocTypes.

The app adds custom fields to the Web Form for facilitating payments upon installation and removes them upon uninstallation.

## Contributing

We welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the MIT License. You can read the details in our [license file](license.txt).

Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.