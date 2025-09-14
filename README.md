 Hospital Medical Information System (HMIS)
This project is a web-based Hospital Medical Information System for AIIMS Jammu, designed to streamline appointment booking and provide comprehensive dashboards for different user roles. It features a modern, responsive UI and a robust backend for managing user data and appointments.

Features
User Authentication: Secure sign-in and sign-up with role-based access control.

Patient Portal: Users can book new appointments and view their past and upcoming appointments.

Appointment Booking: A detailed form for patients to schedule appointments with specific departments and doctors.

Admin Dashboard: A comprehensive dashboard for administrators to monitor and manage appointments, users, and hospital statistics in real-time.

Super Admin Panel: A specialized dashboard for a Super Admin to review and act on critical appointments forwarded by regular admins, with options to approve, reject, or comment.

Real-time Updates: Dashboards automatically refresh to show the latest data.

Data Visualization: The Admin Dashboard includes interactive charts (Line, Bar, Area, Pie) to visualize key metrics like weekly appointments, department breakdown, and monthly trends.

Form Validation: Client-side form validation is implemented using zod and react-hook-form to ensure data integrity.

Tech Stack
Frontend: Next.js, React

Styling: Tailwind CSS

Components: Shadcn/ui

State Management: React's useState and useEffect hooks

Form Management: react-hook-form with zod for validation

Animation: framer-motion

Charting: recharts

Notifications: sonner and react-hot-toast
