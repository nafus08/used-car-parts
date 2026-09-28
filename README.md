# UsedCarParts

UsedCarParts is an Android marketplace for buying and selling used car parts. Shoppers can browse listings and contact traders, while traders can publish parts and manage orders.

## Tech stack

- Kotlin and Android SDK
- AndroidX, Material Components, and View Binding
- Firebase Authentication
- Cloud Firestore
- Firebase Storage dependencies for listing media
- Kotlin Coroutines
- Gradle with Kotlin DSL

## Features

- Shopper and trader account roles
- Sign in and registration
- Browse and search used-parts listings
- Listing details with vehicle, condition, price, and image information
- Trader listing creation
- Buyer-to-trader chat
- Checkout and order status flow
- User profile and address data

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/nafus08/used-car-parts.git
   ```
2. Open the project root in Android Studio and allow Gradle to sync.
3. Configure a Firebase project with Authentication, Cloud Firestore, and any required Storage rules. Add the matching `google-services.json` to the `app/` directory if using your own Firebase project.
4. Select an emulator or connected Android device and run the `app` configuration.

The project uses Android `minSdk` 24. Firebase configuration and service access must be set up before Firebase-backed features can run.
