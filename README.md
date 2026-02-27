# Patient-Doctor-Specialty-Mapping-Dashboard
An interactive geospatial dashboard built using Python, Dash, Plotly, and Leaflet to visualize patient distribution and their connection to specific doctors based on specialty, location, and time filters.

🚀 Project Overview

This application allows users to select:

📍 Location (Jubilee Hills, Secunderabad, Visakhapatnam, etc.)

🩺 Doctor Specialty (Cardiology, Neurology, etc.)

📅 Year and Month

👨‍⚕️ Specific Doctor (optional)

Based on the selected filters, the dashboard dynamically displays:

Patient locations on the map (Blue markers)

Doctor location (Red marker)

Connection lines between doctor and patients

Total number of patients linked to the selected doctor

🗺️ Map Features

🔵 Blue markers represent patient locations

🔴 Red marker represents doctor location

🟢 Green lines show connection between doctor and patients

🖱️ Hovering over blue marker displays:

Patient Name

UHID (Unique Hospital ID)

Location

⚙️ How It Works

User selects hospital location

Selects doctor specialty

Selects year and month

Optionally selects specific doctor

System filters patient records from database

Displays patient-doctor connections on interactive map

🧠 Technical Implementation

Frontend:

Dash

Plotly

Dash Leaflet

Backend:

Python

Pandas

PostgreSQL / Excel (based on data source)

Geospatial Processing:

Latitude and Longitude mapping

Dynamic marker rendering

Real-time filtering

📊 Key Use Cases

Patient distribution analysis

Doctor workload analysis

Healthcare operational analytics

Hospital decision support system

🏥 Real-World Application

This project was developed for hospital analytics to help management:

Understand patient inflow

Analyze doctor demand

Optimize healthcare resource allocation

🧩 Technologies Used

Python

Dash

Plotly

Dash Leaflet

Pandas

SQL

📷 Dashboard Preview

(Add your screenshots here in GitHub)




