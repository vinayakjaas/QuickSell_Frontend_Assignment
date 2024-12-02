# QuickSell Frontend Assignment

This project is an **interactive Kanban board application** built with **ReactJS**. The application fetches data from an API and allows users to group and sort tickets dynamically, providing a user-friendly interface for managing tasks.

---

## **Features**

1. **Dynamic Grouping**:  
   Users can group the tickets in three different ways:
   - **By Status**: Based on the current status of the tickets.
   - **By User**: Based on the user assigned to each ticket.
   - **By Priority**: Based on the priority levels (e.g., Urgent, High, Medium, Low, No Priority).

2. **Sorting**:  
   Tickets can be sorted using:
   - **Priority**: In descending order (highest to lowest).
   - **Title**: In ascending alphabetical order.

3. **Persistence**:  
   The application's view state (grouping and sorting preferences) is retained even after the page is refreshed.

4. **Responsive Design**:  
   The Kanban board is fully responsive and adapts to different screen sizes.

5. **Visual Accuracy**:  
   The UI is designed to match the provided screenshots precisely, offering a clean and visually appealing interface.

---

## **Technologies Used**

- **ReactJS**: For building the frontend application.
- **Pure CSS**: For styling without using external CSS libraries (e.g., Bootstrap, Tailwind).
- **REST API**: Consumes data from the [QuickSell API](https://api.quicksell.co/v1/internal/frontend-assignment).

---

## **Installation**

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. **Install Dependencies**:
    ```bash
    Copy code
    npm install
    ```
3. **Start the Development Server**:
    ```bash
    Copy code
    npm start
    ```
4. **Open your browser and visit**:
    ```bash
    http://localhost:3000
    ```

## **How to Use**
**Display Options**:

Click on the Display button.

Select a grouping option: By Status, By User, or By Priority.

The Kanban board will update dynamically.

**Sorting Options**:

Use the sorting options to arrange tickets either by Priority (descending) or Title (ascending).

## **API Details**
The application interacts with the API endpoint:
[QuickSell API](https://api.quicksell.co/v1/internal/frontend-assignment)


**API Response Structure**

Each ticket object contains the following details:

- id: Unique identifier.

- title: Title of the ticket.

- status: Status of the ticket (e.g., Open, In Progress, Done).

- priority: Priority level (0 to 4).

- user: User assigned to the ticket.

## **Future Enhancements**
- Add drag-and-drop functionality to rearrange tickets within groups.
- Introduce user authentication to manage personalized boards.
- Implement detailed views or modals for each ticket.

## **Author**
This project was completed as part of the QuickSell Frontend Assignment.
- By Vinayak Raj Ranjan
- Final year student at IIT Jodhpur 
"# QuickSell_Frontend_Assignment" 
