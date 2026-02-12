# 🪂 Far Away 💼

**Far Away** is a React-based travel packing list application designed to help you organize your luggage for trips. It allows users to add items, manage quantities, and track packing progress with a fun and interactive interface.

## ✨ Features

- **Add Items**: Quickly add items with quantities (1-10) to your packing list.
- **Track Progress**: Mark items as packed and view real-time statistics on your packing percentage.
- **Sort Options**: Sort your list by:
  - Input Order
  - Description (Alphabetical)
  - Packed Status
- **List Management**: Delete individual items or clear the entire list with a confirmation prompt.
- **Responsive Design**: Simple and clean UI.

## 🛠️ Technologies Used

- **React**: Functional components, Hooks (`useState`).
- **Vite**: Fast development build tool.
- **CSS**: Custom styling.

## 🚀 Getting Started

1. **Clone the repository**
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Run the application**:
   ```bash
   npm run dev
   ```

## 📂 Project Structure

- `App.jsx`: Main application component managing state.
- `Logo.jsx`: Header component.
- `Form.jsx`: Component for adding new items.
- `PackingList.jsx`: Component displaying the list of items with sorting functionality.
- `Item.jsx`: Individual item component.
- `Status.jsx`: Footer component displaying packing stats.
