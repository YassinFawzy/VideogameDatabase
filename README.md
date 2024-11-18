# 🎮 Video Game Database

A robust application designed to manage and display data for video game items, players, locations, and more. This project features an intuitive GUI and leverages MongoDB for data storage.

## 📑 Features

- **Graphical User Interface**:
  - Interactive web interface built using Python.
  - Organized sections for various game components like Players, Weapons, Locations, and Skills.
  
- **Database Integration**:
  - MongoDB for storing structured data.
  - Includes BSON files for importing game data.

- **Customizable Assets**:
  - Static assets like icons and images for a rich user experience.
  - Pre-styled CSS for polished visuals.

## 🛠️ Project Structure

```
Video Game Database/
├── GUI/
│   ├── app.py                    # Main application script
│   ├── static/
│   │   ├── assets/               # Images and icons
│   │   ├── css/                  # Styling files
│   └── templates/                # HTML templates
├── Mongo Database/
│   ├── *.bson                    # Database dump files
│   ├── *.metadata.json           # Metadata for BSON files
└── README.md                     # Project documentation
```

## 🚀 How to Run

### Prerequisites
- Python 3.8+
- MongoDB installed locally or accessible remotely
- Required Python libraries (`Flask`, etc.)

### Steps
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd Video-Game-Database
   ```

2. **Set up the database**:
   - Import `.bson` files into MongoDB:
     ```bash
     mongorestore --db <database_name> Mongo\ Database/
     ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python GUI/app.py
   ```

5. **Access the GUI**:
   - Open a browser and navigate to `http://127.0.0.1:5000`.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.
