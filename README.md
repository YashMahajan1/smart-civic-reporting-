# smart-civic-reporting-
Developed a Smart Civic Reporting Platform that allows citizens to submit location-based civic complaints with image evidence,role-based dashboards for citizens, workers, and administrators, automated complaint assignment, interactive map integration, Cloudinary image storage, and real-time complaint tracking using the MERN Stack.

 Crowdsourced Civic Issue Reporting and Resolution System
A web-based platform that enables citizens to report civic issues (potholes, garbage overflow, water leakage, etc.) and allows municipal authorities to manage and resolve them efficiently through automated worker assignment.

📌 Problem Statement
Citizens lack a centralized, transparent system to report civic problems. Complaints are manually assigned, leading to delays, duplicate efforts, and no accountability in resolution.

💡 Solution
This system automates the entire lifecycle of civic complaints — from reporting to resolution:

Citizens report issues with photo, description, and auto-captured GPS location
System automatically assigns the complaint to the nearest worker within a 5km service radius
Workers resolve issues and upload completion proof
Citizens receive real-time status updates throughout the process

👥 User Roles
Role	Capabilities
Citizen	Report issues, track complaint status, receive notifications
Worker	View assigned tasks, update status, upload resolution proof
Department Admin	Manage department complaints, register workers, verify resolution
Super Admin	Oversee all departments, manage users, view analytics, generate reports

⚙️ Key Features
📸 Issue reporting with image upload and description
📍 Automatic GPS location capture
🤖 Auto-assignment of issues to nearest department worker
🔄 Real-time status tracking (Submitted → Assigned → In Progress → Resolved → Closed)
📊 Role-based dashboards for all user types
✅ Photo proof verification for issue resolution
🗺️ Map integration for location visualization
🔔 Notification system for status updates
🛠️ Tech Stack

Layer	Technology
Frontend	React.js
Backend	Node.js, Express.js
Database	MongoDB
Authentication	JWT (JSON Web Token)
Map Integration	Leaflet / OpenStreetMap
Image Storage	Cloudinary
🚀 Getting Started
