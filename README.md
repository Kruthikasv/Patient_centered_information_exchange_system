# Patient Centered Information Exchange System

## Overview

The Patient Centered Information Exchange System is a healthcare application designed to facilitate secure and efficient sharing of patient information among healthcare providers and patients. This system aims to enhance the quality of care by providing accurate and timely access to patient records, enabling better diagnosis, treatment, and coordination among medical professionals.

## Features

- **User Authentication**: Secure login for patients, doctors, and administrators.
- **Patient Records Management**: Store, update, and retrieve patient medical records.
- **Appointment Scheduling**: Manage and schedule appointments between patients and healthcare providers.
- **Secure Messaging**: Enable secure communication between patients and doctors.
- **Data Encryption**: Ensure the privacy and security of patient information through encryption.
- **Access Control**: Define and manage access levels for different users.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: React.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Encryption**: AES-256

## Installation

### Prerequisites

- Node.js
- npm (Node Package Manager)
- MongoDB

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Kruthikasv/Patient_centered_information_exchange_system.git
   ```

2. **Set Up Backend**
   - Navigate to the backend directory.
     ```bash
     cd backend
     ```
   - Install dependencies.
     ```bash
     npm install
     ```
   - Configure environment variables in a `.env` file.
     ```env
     PORT=5000
     MONGODB_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     ```

3. **Set Up Frontend**
   - Navigate to the frontend directory.
     ```bash
     cd ../frontend
     ```
   - Install dependencies.
     ```bash
     npm install
     ```

4. **Run the Application**
   - Start the backend server.
     ```bash
     cd ../backend
     npm start
     ```
   - Start the frontend server.
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application**
   - Open your web browser and navigate to `http://localhost:3000`.

## Usage

### Patient Functions

- **Register/Login**: Patients can register and log in using their credentials.
- **View Records**: Access personal medical records.
- **Schedule Appointments**: Book appointments with healthcare providers.
- **Secure Messaging**: Communicate with doctors securely.

### Doctor Functions

- **Register/Login**: Doctors can register and log in using their credentials.
- **Manage Appointments**: View and manage scheduled appointments.
- **Access Patient Records**: Access and update patient medical records.
- **Secure Messaging**: Communicate with patients securely.

### Admin Functions

- **Register/Login**: Admins can log in using their credentials.
- **Manage Users**: Add, update, or delete user accounts (patients and doctors).
- **Monitor System**: Oversee system operations and ensure data integrity.

## Database Schema

- **Users**: Stores user information (patients, doctors, and admins).
- **Records**: Stores patient medical records.
- **Appointments**: Stores appointment details.
- **Messages**: Stores secure messages exchanged between users.

## Contributions

Contributions to the project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add your feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any inquiries or support, please contact:

- **Name**: Kruthika Vasisht
- **Email**: kruthikasvasisht@gmail.com
