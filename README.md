# Kanban Board Application

A responsive and interactive Kanban board application built using React JS. This application fetches ticket data from an API and allows users to group and sort tickets based on different criteria like status, user, and priority. The application retains the user’s view state even after a page reload and is designed with pure CSS to match the provided visual design.

## Features

* **Dynamic Grouping**: Group tickets by **status**, **user**, or **priority**.
* **Sorting Options**: Sort tickets by **priority** (descending) or **title** (ascending).
* **Responsive Design**: Fully responsive UI that works on various screen sizes.
* **View State Persistence**: The user’s selected view state is saved even after a page reload.
* **No CSS Libraries**: Styled using pure CSS for customizability and to match the design perfectly.

## API

The application fetches data from the following API:

https://api.quicksell.co/v1/internal/frontend-assignment


## Priority Levels

The priority levels for the tickets are as follows:

| Priority Level | Description   |
| -------------- | ------------- |
| **4**          | Urgent        |
| **3**          | High          |
| **2**          | Medium        |
| **1**          | Low           |
| **0**          | No Priority   |

## Technologies Used

* **React JS**: For building the user interface and handling state management.
* **Pure CSS**: For styling the application without using any CSS libraries like Bootstrap or Tailwind.
* **JavaScript (ES6)**: For implementing business logic and API calls.

## File Structure

The project is organized as follows:

kanban-board-app/ ├── public/ ├── src/ │ ├── Assets/ │ ├── Components/ │ │ ├── LOADER.js │ │ ├── selection_pane.js │ │ ├── TICKET.js │ ├── Page/ │ │ ├── Dashboard.js │ ├── Styles/ │ ├── App.js │ ├── Config.js │ ├── FETCH_URL.js │ ├── index.js ├── .gitignore ├── package-lock.json ├── package.json ├── README.md


### Explanation

* **Assets/**: Contains all images, icons, and other static assets.
* **Components/**: Contains reusable components such as `LOADER`, `selection_pane`, and `TICKET`.
* **Page/**: Contains the main page component (`Dashboard.js`) for the application.
* **Styles/**: Stores all CSS files for styling the components and the overall application.
* **Config.js**: Configuration file for setting up constants or environment-specific settings.
* **FETCH_URL.js**: Handles the API call logic to fetch data from the API.
* **App.js**: The main entry component that initializes and renders the application.
* **index.js**: The main file that renders the `App` component into the DOM.

## Installation and Setup

Follow these instructions to set up the application locally:

### Prerequisites

* **Node.js** (v14 or above) and **npm** installed on your machine.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/s11saurabh/kanban-board-app.git


 2.Navigate into the Project Directory:
cd kanban-board-app

 3.Install Dependencies:
npm install


4. Start the Development Server:
npm start

5.Open your browser and navigate to http://localhost:3000 to view the application.

## Usage
1.Grouping Options:
Users can group the tickets by status, user, or priority using the "display" button.

2.Sorting Options:
Users can sort tickets by priority (in descending order) or title (in ascending order).

3.View State Persistence:
The application automatically saves the user's selected view state, so the same view is displayed upon page reload.


## Deployment

1.To build and deploy the application:
Build the Production Version:

npm run build

2.The optimized build files will be created in the build directory. You can then deploy these files on any static hosting provider like Netlify, Vercel, or GitHub Pages.

## Contributing
Feel free to contribute to the project. Here's how you can get started:

1.Fork the repository.
2.Create a new branch
git checkout -b feature/your-feature-name

3.Make your changes.

4.Commit your changes:
git commit -m 'Add new feature'

5.Push the branch:
git push origin feature/your-feature-name

6.Open a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

```bash
1.The API used for fetching ticket data: https://api.quicksell.co/v1/internal/frontend-assignment
2.Assets used in the design are stored in the Assets directory.
Contact
If you have any questions or issues, please feel free to open an issue on GitHub or contact me directly.
