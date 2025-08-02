# Healthcare-app
 Objective
Build a simple Healthcare Appointment Booking Interface that allows users to view doctors, check their availability, and book an appointment.
You'll be building a **responsive web application** primarily using **React.js**. While **TypeScript is preferred** for its type safety and improved developer experience, you can use JavaScript if you're not yet comfortable with TypeScript. The user interface should be **clean, intuitive, and functional**.

For the backend, you have flexibility:

- **Mock Backend:** You can use static JSON data to simulate API responses. This is a good option if you want to focus primarily on the frontend.
- **Node.js/Express:** If you're comfortable with backend development, you can create a simple Node.js/Express API to serve your data.
### Core Requirements

Here's a breakdown of the essential features your application must include:

### Frontend (React + TypeScript Preferred)

1. **Landing Page:**
    - Display a clear list of doctors.
    - For each doctor, show their **name, specialization, and a profile image**.
    - Indicate their **availability status** (e.g., "Available Today," "Fully Booked," "On Leave").
    - Implement a **search functionality** to filter doctors by name or specialization.
2. **Doctor Profile Page:**
    - When a user clicks on a doctor from the landing page, navigate to a dedicated profile page.
    - This page should display more detailed information about the doctor.
    - Clearly show their **availability schedule**.
    - Include a prominent **"Book Appointment" button**.
3. **Book Appointment:**
    - Clicking the "Book Appointment" button should lead to a simple form.
- The form needs to collect: **Patient Name, Email, and desired Date/Time for the appointment.**
- Upon submission, provide a **confirmation message** to the user.
### Technical Constraints

Adhering to these constraints will help you build a modern and maintainable React application.

- **React:** Use React for your frontend. You can choose to use it with or without Next.js.
- **TypeScript:** While not strictly mandatory, **TypeScript is strongly preferred** for its benefits in larger applications and team environments.
- **Functional Components & Hooks:** Leverage React's functional components and hooks (e.g., `useState`, `useEffect`, `useContext`) for state management and side effects.
- **State Management:** Use **React Context API** or **local component state** for managing your application's data. Avoid external state management libraries like Redux for this assignment unless you are very comfortable with them.
