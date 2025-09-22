# Splitwise Clone

A web application inspired by Splitwise, designed to help users track shared expenses, manage group payments, and settle balances efficiently.

## Features

- Create groups for shared expenses
- Add, edit, and delete expenses
- Track who owes whom
- Settle balances between users
- User authentication and authorization

## Local Setup

1. **Clone the repository**
    ```bash
    git clone https://github.com/rmahajan466/splitwise.git
    ```

2. **Setup**
    - Navigate to the splitwise folder:
      ```bash
      cd splitwise
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Put the below keys inside `.env.local`
    ```
    CONVEX_DEPLOY_KEY=

    CONVEX_DEPLOYMENT=

    NEXT_PUBLIC_CONVEX_URL=

    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

    CLERK_JWT_ISSUER_DOMAIN=

    RESEND_API_KEY=

    GEMINI_API_KEY=
    ```
    - Start the Development Server:
      ```bash
      npm run dev
      ```

4. **Access the App**
    - Open your browser and go to
    - Local: `http://localhost:3000`
    - Network: `http://192.168.29.18:3000`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License.
