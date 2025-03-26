Vehicle Selector 🚗
A simple React-based vehicle selector that allows users to choose a vehicle based on the Manufacturer, Model, and Type. The data for these options is sourced from fixture files.

🔧 Features
Select a Manufacturer from the dropdown.

Based on the selected Manufacturer, choose a Model.

Based on the selected Model, choose a Vehicle Type.

Display the selected options (Manufacturer, Model, Power, Cubic Capacity) in a summary table.

Reset button to clear all selections.

Validation to ensure that the OK button is enabled only when all fields are selected.

🛠️ Technologies Used
React: Functional components with hooks (useState, useMemo, useEffect).

TypeScript: Type-safe component and state management.

Bootstrap: Responsive styling.

SCSS: Custom styles for enhanced UI.

📁 Folder Structure
pgsql
Copy
Edit
/src
│── components/
│   └── VehicleSelector.tsx
│── fixtures/
│   ├── manufacturers.json
│   ├── models.json
│   └── types.json
│── styles/
│   └── VehicleSelector.scss
🚀 How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/vehicle-selector.git
cd vehicle-selector
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start
