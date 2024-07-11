# IT Inventory Management Program

**Note:** This project involves proprietary data from a real company. Due to privacy and confidentiality agreements, the datasets used in this project cannot be shared publicly.

## Overview
The Inventory Management Program is designed to streamline and automate the tracking of container stock across different clients. The program handles monthly data inputs and produces detailed reports on container transactions and inventory levels. This system uses a series of Jupyter Notebooks to execute the necessary data processing and analysis.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Numpy, Openpyxl
- **Tools**: Jupyter Notebook, Microsoft Excel

## Project Details
### Data Description
This project involves proprietary data from a real company. Due to privacy and confidentiality agreements, the datasets used in this project cannot be shared publicly.

### Data Exploration and Preprocessing
- **Consistent Naming**: Ensured daily delivery records follow a consistent naming convention.
- **Client Name Changes**: Updated the change_name Excel file with old and new client names before execution.
- **Manual Adjustments**: Allowed for manual updates in output files to correct any discrepancies.

### Components of the Program
1. **Jupyter Notebook Execution**:
    - The program is implemented through a series of Jupyter Notebooks, which are run in sequence to perform data processing tasks.
    - Users must first launch Jupyter Notebook from their system and navigate to the specific notebooks located in the Python -> 거래처재고 -> 프로그램코드 directory.

2. **Folder Structure and Usage**:
    - **Data Folder**: Stores the input data files required for the program to run. Users must place the relevant daily delivery records and updated results from the previous month in this folder before execution.
    - **Result Data Folder**: Contains the output files generated after running the program, including the final container stock reports.
    - **Program Code Folder**: Houses the Jupyter Notebooks that contain the code for the program.
    - **Backup and Temp Folders**: Used by the program during execution for intermediate processing and storage.

### Preparation Steps
1. **Data Input**: Users must ensure that the daily delivery records for the target month are placed in the data folder and named consistently (e.g., 2022.03 일일납품내역).
2. **Name Changes**: If there are any changes in client names, users must update the change_name Excel file with the old and new names and save the changes before running the program.

### Program Execution
The program consists of multiple notebooks that need to be executed in a specific order:
1. **1. 거래처별용기수불 Baseline 01.22 최종.ipynb**: Sets up the baseline for container transactions.
2. **2. 거래처별용기수불 최종 01.22.ipynb**: Processes the transactions to produce the final container stock report.
3. **3. 값다른것검토작업 01.22 최종.ipynb**: Reviews discrepancies and ensures data consistency.

### Program Features and Updates
The updated program eliminates the need for manual comparison of daily delivery records with container stock data, thereby reducing redundancy. Enhancements include error handling for direct trade recognition and adjustments for transactions not recorded in the previous month.

### Common Errors and Solutions
- **Direct Trade Not Recognized**: Users must manually adjust the data to ensure direct trades are correctly processed.
- **Manual Adjustments**: Any manual corrections in the Excel files should be saved and updated in the result files.
- **Missing Previous Month Transactions**: The program now tracks transactions from the previous nine months to avoid discrepancies.

### Program Execution Workflow
1. **Pre-Execution**: Ensure all required data is placed in the data folder and any name changes are updated.
2. **Execution**: Run the notebooks in the specified order, ensuring each step completes successfully before moving to the next.
3. **Post-Execution**: Verify the results in the result_data folder, make any necessary manual adjustments, and save the final output back to the data folder for future reference.

### Results and Discussion
- **Error Handling**: Addressed issues with direct trade recognition by manually adjusting data. Implemented a tracking system for transactions over the past nine months to avoid discrepancies.
- **Output**: Generated accurate monthly container stock reports, which can be used without additional manual comparisons.

### Conclusion
The automated Inventory Management Program significantly reduces manual effort, minimizes errors, and provides timely, accurate reports. Enhancements and error-handling mechanisms ensure reliable performance and ease of use.

### Reflection
This project demonstrates the effectiveness of automation in inventory management, emphasizing the importance of robust data preprocessing and error handling.

## Project Achievements
1. **Automated Workflow**: Successfully automated the tracking and reporting of container stocks, reducing the need for manual input and verification.
2. **Error Mitigation**: Implemented effective error-handling strategies to ensure data consistency and accuracy.
3. **Efficient Data Processing**: Utilized Python libraries to process large datasets efficiently, ensuring timely generation of reports.
4. **User-Friendly Interface**: Developed a user-friendly interface in Jupyter Notebook, making it easy for users to execute and manage the program.

## Notion Portfolio Page
- [Notion Portfolio Page Link](#) (Replace with actual link)


