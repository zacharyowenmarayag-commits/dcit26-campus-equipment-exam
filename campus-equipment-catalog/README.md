# Campus Equipment Catalog
 
React and Vite starter application for browsing shared campus laboratory equipment.
 
## Run locally
 
1. Run `npm install`.
2. Run `npm install react-router-dom`.
3. Run `npm run dev`.
 
Complete the EquipmentCard component as the practical examination task.
src/main.jsx
import React from "react";
import ReactDOM from "react-dom/client";
import { BrowserRouter } from "react-router-dom";
import App from "./App.jsx";
import "./index.css";
 
ReactDOM.createRoot(document.getElementById("root")).render(
  <React.StrictMode>
    <BrowserRouter>
      <App />
    </BrowserRouter>
  </React.StrictMode>
);
