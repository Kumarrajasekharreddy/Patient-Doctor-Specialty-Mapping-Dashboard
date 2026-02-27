# Patient-Doctor-Specialty-Mapping-Dashboard
An interactive geospatial dashboard built using Python, Dash, Plotly, and Leaflet to visualize patient distribution and their connection to specific doctors based on specialty, location, and time filters.

 Project Overview
![Dashboard Main Page](https://github.com/Kumarrajasekharreddy/Patient-Doctor-Specialty-Mapping-Dashboard/blob/main/Images/Screenshot%20Main%20Page.jpg)

📍 Location (Jubilee Hills, Secunderabad, Visakhapatnam, etc.)

🩺 Doctor Specialty (Cardiology, Neurology, etc.)

📅 Year and Month

👨‍⚕️ Specific Doctor (optional)

Based on the selected filters, the dashboard dynamically displays:
![Dashboard Main Page](https://github.com/Kumarrajasekharreddy/Patient-Doctor-Specialty-Mapping-Dashboard/blob/main/Images/Screenshot%20Main%20Doctor%20View.jpg)

![Dashboard Main Page](https://github.com/Kumarrajasekharreddy/Patient-Doctor-Specialty-Mapping-Dashboard/blob/main/Images/Screenshot%20From%20Patient%20Side.jpg)


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





🧩 Technologies Used

Python

Dash

Plotly

Dash Leaflet

Pandas

SQL

🏥 Real-World Application

This project was developed for hospital analytics to help management:

Understand patient inflow

Analyze doctor demand

Optimize healthcare resource allocation









