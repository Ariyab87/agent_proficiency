# Agent Proficiency Analysis

## Overview
This project calculates the proficiency of customer support agents based on customer ratings, number of customers handled, and resolution time. The results are visualized using a **bar chart** for proficiency scores and a **pie chart** for customer distribution among agents.

## Features
- **Automatic CSV File Creation:** Generates a dataset for analysis.
- **Proficiency Score Calculation:** Based on customer ratings, number of customers, and resolution time.
- **Bar Chart:** Visualizes agent proficiency scores.
- **Pie Chart:** Displays customer distribution among agents.

## Dataset Structure
The dataset consists of the following columns:
- `Agent Name` - The name of the customer support agent.
- `Customer Rating` - Rating given by customers (scale of 1-5).
- `Number of Customers` - The number of customers handled by each agent.
- `Resolution Time` - The average time taken to resolve an issue (in minutes).

## Formula for Proficiency Score
```
Proficiency Score = (Customer Rating * Number of Customers) / Resolution Time
```

## Installation & Usage
### Prerequisites
- Python 3.x
- Required Libraries: `pandas`, `matplotlib`

### Steps to Run the Code
1. Clone this repository or download the script.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib
   ```
3. Run the script in Google Colab or a local Python environment.
4. The script will generate a CSV file, calculate proficiency scores, and display graphs.

## Output
### Bar Chart: Agent Proficiency
A bar chart showing proficiency scores for each agent.

### Pie Chart: Customer Distribution
A pie chart displaying the percentage of customers handled by each agent.

## Example Output Table
| Agent Name | Customer Rating | Number of Customers | Resolution Time | Proficiency Score |
|------------|----------------|----------------------|-----------------|------------------|
| Agent 1    | 4.5            | 120                  | 15              | 36.0            |
| Agent 2    | 4.2            | 150                  | 18              | 35.0            |
| Agent 3    | 4.8            | 130                  | 14              | 44.57           |
| Agent 4    | 4.3            | 110                  | 20              | 23.65           |
| Agent 5    | 4.1            | 140                  | 17              | 33.76           |

## License
This project is open-source and available for use under the MIT License.

