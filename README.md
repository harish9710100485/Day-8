# Client Interaction Tracker

##  Description
The **Client Interaction Tracker** is a Python-based script that simulates client interactions regarding a product and logs the outcome of each attempt. The results are stored in a CSV file (`client_interactions.csv`).

##  Features
- Simulates client interactions with randomized outcomes.
- Logs each interaction attempt along with timestamps.
- Supports multiple interaction attempts before final acceptance or rejection.
- Saves all records in a CSV file for tracking purposes.

##  Installation
### 1 Clone the Repository
```sh
git clone https://github.com/your-username/client-interaction-tracker.git
cd client-interaction-tracker
```
### 2️ Install Dependencies
This script requires **Python 3** and the `pandas` library. Install dependencies using:
```sh
pip install pandas
```

##  Usage
Run the script using the command:
```sh
python client_interaction.py
```
Then, enter the **Client Name** and **Product Name** when prompted.

##  Outcome Probabilities
The script randomly determines the outcome of an interaction based on the following probabilities:

| Outcome                           | Probability |
|-----------------------------------|------------|
| Accepted in 1st Attempt           | 10%        |
| Rejected in 1st Attempt           | 20%        |
| Revised and Accepted              | 25%        |
| Revised and Rejected              | 25%        |
| Accepted after Multiple Attempts  | 20%        |

##  Data Logging
- Interaction records are stored in `client_interactions.csv`.
- Each record contains:
  - Client Name
  - Product Name
  - Attempt Number
  - Outcome
  - Timestamp

##  Contributing
Pull requests are welcome! Feel free to fork the repository and submit improvements.

##  License
This project is licensed under the **MIT License**. See `LICENSE` for more details.

---
Author:Harish
Intern:Minerva


