# House Hunter Platform - Job Task

## Task Description

"House Hunter" is a platform that simplifies the house rental process by connecting house owners and house renters. The platform aims to provide a seamless experience for both parties, allowing owners to list their properties and renters to search and book their dream homes. The platform will be built using Node.js, React.js, and MongoDB, and will include the following features:

### 1. User Registration

<!-- [x] Create a registration form where users provide their full name, role (House Owner or House Renter), phone number, email, and password. -->
- [ ] Create a registration form where users provide their full name, role (House Owner or House Renter), phone number, email, and password.
- [ ] Store the registered user information in the database and ensure there are no duplicate users.
- [ ] Implement custom authentication using JWT (JSON Web Tokens) and MongoDB for user registration and login. Do not use any authentication service providers like Firebase.

### 2. House Owner Dashboard

- [ ] Upon successful registration as a House Owner, users should be redirected to their dashboard.
- [ ] Implement a dashboard where House Owners can manage their listed houses and bookings.
- [ ] Display a list of houses owned by the logged-in House Owner.
- [ ] Add an "Add New House" button that opens a form/modal for the House Owner to provide detailed information about the house (name, address, city, bedrooms, bathrooms, room size, picture, availability date, rent per month, phone number, and description). All fields are mandatory, and only Bangladeshi phone numbers are allowed.
- [ ] Implement functionality to add new houses to the database.
- [ ] Display the list of owned houses in a table with options to delete or edit each house. Deleting a house should remove it instantly from the table, while editing a house should populate the form with the existing information and show the updated information in the table.

### 3. House Renter Dashboard

- [ ] Upon successful registration as a House Renter, users should be redirected to their unique dashboard.
- [ ] Create a dashboard where House Renters can manage their bookings.
- [ ] House Renters should be able to book houses from the home page by providing their name, email, and phone number. Name and email should be automatically filled and cannot be modified.
- [ ] Implement functionality to store the booking details in the database and associate them with the House Renter.
- [ ] Display the booked houses on the House Renter dashboard, allowing House Renters to view their current bookings.
- [ ] House renters can book a maximum of two houses. Implement the option to remove or delete booked houses to free up space for new bookings.

### 4. Home Page and House Search

- [ ] Create a home page that displays all the listed houses.
- [ ] Any user can search for houses, but only House Renters can book houses for rent and need to log in to book a house.
- [ ] Implement functionality to search houses and filter by city, bedrooms, bathrooms, room size, availability, and rent per month. Filtering on the backend is preferred but not mandatory.
- [ ] Implement server-side pagination or infinite scroll to fetch and display a maximum of 10 houses at once.

## Additional Requirements

- [ ] Implement the website's color combination to create an aesthetically pleasing user interface.
- [ ] Consider using Mongoose (ODM) for interacting with the MongoDB database.
- [ ] Use Vite React for the front-end development.
- [ ] Handle errors, validate user input, and provide appropriate feedback throughout the application.

## Valid Palindrome

Write a JavaScript function called `isPalindrome` that takes a string as input and returns `true` if the string is a palindrome, otherwise `false`. A palindrome is a word, phrase, number, or other sequence of characters that reads the same forward and backward, ignoring punctuation, case, and spacing.

### Examples

```javascript
isPalindrome("level"); // Output: true
isPalindrome("hello"); // Output: false
isPalindrome("A man, a plan, a canal: Panama"); // Output: true
```

## Submission

Please deploy your site and provide the live link along with the GitHub link to your solution. Make sure to make meaningful commits while developing your solution.

**Note:** The submission deadline for this task is from 12 PM, July 17, 2023, to 11:59 PM, July 19, 2023.
