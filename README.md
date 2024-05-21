## Introduction
User Management Dashboard is a webpage in which all the users with their id, name, email and website are being displayed in the form of cards. One can manupulate the data i.e perform CRUD operation onto the website.  
## Directory Structure

├── src/

├──├── assets/

├──├── components/

├──├──├── UserList.jsx

├──├──├── UserListItem.jsx

├──├──├── UserModal.jsx

├──├── utils/

├──├──├── api.js

├──├── app.js

├──├── index.js

├── .gitignore

├── package-lock.json

├── package.json

├── README.md

## Features

- New user can be added.
- Every user is editable.
- One can delete any user.
- Pagination is being implemented with infinite scrolling features.

## Installation & Getting started

```bash
npm install 
```

```bash
npm start
```

## APIs Used

https://jsonplaceholder.typicode.com/

## API Endpoints

"/users" endpoint is being used for performing CRUD operation.

## Technology Stack

- React.js
- Chakra UI
