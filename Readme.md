# EV Charging Station Data Integration and Analysis Project

## Project Overview
This repository contains a comprehensive solution for processing, analyzing, and visualizing Electric Vehicle (EV) charging station data. The project includes data integration, cleaning procedures, MongoDB integration, and Power BI visualization capabilities.

## Repository Structure
```
EV--T3-2024/
├── EV.pbix                                                # Power BI dashboard file
├── EV_Charging_Station_Data_Integration_and_Cleaning.ipynb # Main Jupyter notebook for data processing
├── Enriched_charging_stations-1.csv                       # Enhanced dataset
├── cleaned_charging_stations.csv                          # Processed dataset
├── data_validation.py                                     # Data validation scripts
├── mongodb.py                                            # MongoDB connection and operations
├── mongodb_crud_tests.py                                 # MongoDB CRUD operation tests
├── powerbi_prep.py                                       # Power BI data preparation
└── setup_script.py                                       # Project setup script
```

## Features
- Data cleaning and preprocessing pipeline
- MongoDB integration for data storage
- Automated data validation checks
- Power BI integration for visualization
- CRUD operation testing framework
- Comprehensive data enrichment processes

## Requirements
- Python 3.x
- MongoDB
- Power BI Desktop
- Required Python packages:
  - pandas
  - pymongo
  - jupyter
  - numpy
  - (other dependencies specified in setup script)

## Installation and Setup
1. Clone the repository:
```bash
git clone https://github.com/Adesh-09/EV--T3-2024.git
cd EV--T3-2024
```

2. Run the setup script:
```bash
python setup_script.py
```

3. Configure MongoDB connection:
- Update MongoDB connection settings in `mongodb.py`
- Ensure MongoDB service is running

## Usage

### Data Processing
```python
# Run the Jupyter notebook
jupyter notebook EV_Charging_Station_Data_Integration_and_Cleaning.ipynb
```

### MongoDB Operations
```python
# Import the MongoDB module
from mongodb import MongoDBOperations

# Initialize connection
db_ops = MongoDBOperations()

# Perform CRUD operations
db_ops.insert_data(data)
```

### Data Validation
```python
# Run validation checks
python data_validation.py
```

### Power BI Visualization
1. Open `EV.pbix` with Power BI Desktop
2. Refresh data connections if needed
3. Interact with the dashboard

## Data Pipeline
1. Raw data ingestion
2. Data cleaning and standardization
3. Enrichment with additional features
4. Validation checks
5. MongoDB storage
6. Power BI preparation
7. Visualization and analysis

## Testing
Run the MongoDB CRUD tests:
```bash
python mongodb_crud_tests.py
```

## Documentation
- Detailed documentation is available in the Jupyter notebook
- MongoDB operations are documented in `Mongodb-1.pdf`
- Code includes inline documentation and comments

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
- Project Owner: Adesh-09
- GitHub Repository: https://github.com/Adesh-09/EV--T3-2024

## Acknowledgments
- Contributors to the project
- Data sources and providers
- Open source community for tools and libraries used

---
*Last updated: December 2024*
