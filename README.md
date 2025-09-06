# Ticket Sales Management System

A Python based ticket system.  
Supports ticket entry, search, reporting, and visualization.

## Features
- Admin login system
- Automatic ticket ID generation
- Add new ticket sales with validation
- No past purchase dates allowed
- Per event capacity limit (default: 1000 tickets)
- View all tickets in a table format
- Search by ticket ID
- Includes reports and charts (daily, monthly, per event)

## Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
```


### Dependencies
- Python 3.8+
- pandas
- matplotlib
- tabulate

## How to Run
From the `src` folder, run:

```bash
 app.py
```

- Enter username: admin 

- Enter password: admin123

## Reports
- Bar chart: tickets sold per event
- Line chart: sales over time
- Console statistics: daily & monthly summary
