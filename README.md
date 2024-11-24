# Home Rental Web Application

## Team Members

1. **Neelraj.S** - **310121104068**
2. **Naraayanan.T** - **310121104067**
3. **Sri Arvind** - **310121104100**
4. **Rajesh.D** - **310121104080**
5. **Nandha Kumar.S** - **310121104066**

---

## Overview

The Home Rental Web App is a platform developed using the MERN stack (MongoDB, Express.js, React, and Node.js) to help users find, list, and manage rental properties. The application enables property owners to post rental listings and potential renters to search for properties that match their preferences. This web app streamlines the rental process by connecting landlords and renters in one platform, making it easy to find or advertise rental properties.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Setup and Installation](#setup-and-installation)
5. [License](#license)

---

## Features

- **User Authentication**: Secure login and registration for landlords and renters.
- **Property Listings**: Landlords can post new listings with details like property type, location, price, and photos.
- **Property Search**: Renters can search properties based on location, price range, and other filters.
- **Booking Requests**: Allows renters to submit booking requests directly through the app.
- **Favorites List**: Renters can save properties they’re interested in.
- **Responsive Design**: Ensures usability on both desktop and mobile devices.

---

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Styling**: CSS
- **Authentication**: JWT (JSON Web Tokens)

---

## Setup and Installation

Follow these steps to set up the project locally:

### 1. Clone the Repository
   ```bash
   git clone https://github.com/your-repo/House-Rental.git
   cd House-Rental


# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install


PORT=8000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret


# Start the backend server
cd backend
npm start

# Start the frontend server
cd ../frontend
npm start


http://localhost:3000

## License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at:

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
