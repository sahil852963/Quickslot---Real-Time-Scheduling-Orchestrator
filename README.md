Quickslot - Real-Time Scheduling Orchestrator
Quickslot is a lightweight, front-end appointment booking application designed to demonstrate real-time scheduling logic and modern UI design. It simulates a live booking environment where users can browse provider availability, sync with network time, and manage appointments seamlessly.

Key Features
Dynamic Roster: Fetches a list of random providers from a mock API (JSONPlaceholder) to simulate a live directory.
Network Time Sync: Integrates with WorldTimeAPI to enforce server-side time validation (IST), preventing booking of past slots regardless of the user's local device time.
Conflict-Free Booking: Logic to automatically disable past time slots and prevent double-booking of the same slot for a specific provider.
Local Persistence: Uses localStorage to save and retrieve bookings, allowing the application to maintain state across page reloads without a backend database.
Modern UI/UX: Features a polished interface with gradient typography, soft shadows, interactive hover states, and a responsive grid layout built on Bootstrap 5 and custom CSS.

Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)
Styling: Bootstrap 5 + Custom CSS Variables
APIs: JSONPlaceholder (User Data), WorldTimeAPI (Time Sync)

How to Run
Clone the repository.
Open index.html in any modern web browser.
Select a provider and date to view available slots.