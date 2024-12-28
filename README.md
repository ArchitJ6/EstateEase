# 🏡 EstateEase

EstateEase is a modern real estate app built to simplify property search and management. Designed with scalability and user experience in mind, this app helps users discover, list, and manage real estate properties seamlessly.

## 💻 Tech Stack

- **🚀 Expo**
- **⚛️ React Native**
- **📘 TypeScript**
- **🌈 Nativewind**
- **🛠️ Appwrite**
- **🎨 Tailwind CSS**

## ✨ Features

- **🔒 Authentication with Google**: Secure and seamless user sign-ins using Google’s authentication service.
- **🏠 Home Page**: Displays the latest and recommended properties with powerful search and filter functionality.
- **🔍 Explore Page**: Allows users to browse all types of properties with a clean and intuitive interface.
- **📋 Property Details Page**: Provides comprehensive information about individual properties, including images and key details.
- **👤 Profile Page**: Customizable user settings and profile management.
- **📡 Centralized Data Fetching**: Custom-built solution inspired by TanStack’s useQuery for efficient API calls.
- **🛠️ And many more**: Including enhanced code architecture and reusability.

## ⚡ Getting Started

### 🛠️ Prerequisites

Make sure you have the following installed on your machine:

- 🧰 Git
- 📦 Node.js
- 📌 npm (Node Package Manager)

### 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ArchitJ6/EstateEase.git
   cd EstateEase
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set Up Environment Variables:

   Create a new file named `.env.local` in the root of your project and add the following content:

   ```env
   EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
   EXPO_PUBLIC_APPWRITE_PROJECT_ID=
   EXPO_PUBLIC_APPWRITE_DATABASE_ID=
   EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
   EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
   EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
   EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
   ```

   Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the Appwrite website.

4. Start the app:
   ```bash
   npx expo start
   ```

## 🗂️ Folder Structure

```
EstateEase/
├── app/                # Main application files
├── assets/             # Static assets like fonts, icons, and images
├── components/         # Reusable React Native components
├── constants/          # Shared constants like data.ts, icons.ts, images.ts
├── lib/                # Libraries for Appwrite integration and data seeding
│   ├── appwrite.ts     # Appwrite configuration and data-fetching functions
│   ├── useAppwrite.ts  # Custom hooks for Appwrite
│   ├── seed.ts         # Data seeding scripts for Appwrite
│   ├── data.ts         # Sample data for seeding
│   └── global-provider.tsx # Global state provider
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## 🙌 Acknowledgements

- [🚀 Expo](https://expo.dev/) for simplifying app development
- [🛠️ Appwrite](https://appwrite.io/) for backend services
- 🌍 The open-source community for invaluable resources and tools