# [Finals-Lab-Task-5]((https://github.com/user-attachments/files/20102685/Soguilon.Carl.Asnef.B.FINALS5.EDM.SQL.docx))
- This portfolio demonstrates the use of SQL views, stored procedures, and stored functions to manage and manipulate database data. It covers tasks such as filtering data with views, updating records with stored procedures, and retrieving data using functions.

## Step-by-Step Process:
1. **Setup MySQL Workbench:**

   * Open XAMPP and start the MySQL server.
   * Connect MySQL Workbench to the server.
   * Execute practice queries using the `democodes.sql` file.

2. **Use Inventory Database:**

   * Open the `inventory.sql` file to begin the tasks.

3. **Create Views:**

   * Create a view to display vendor information and products with in-date from 2002 onward.
   * Create a view for products with prices between 100-150.
   * Create a view to compute the total price for products sold by specific vendors.

4. **Create Stored Procedure:**

   * Create a stored procedure that updates the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Create Function:**

   * Create a function that takes vendor code and state as parameters to display product details.

6. **Execute and Document:**

   * Execute the SQL statements and capture screenshots of the commands and outputs.

# Screenshots of Codes and Outputs:
### 1. CREATE A VIEW that will display the vendors_code, vendors name, product
description p_indate, of all products with p_indate from 2002 onwards
- ![Image](https://github.com/user-attachments/assets/936efb6b-d2f6-4883-be4e-1c543882a7a6)

## Output
- ![Image](https://github.com/user-attachments/assets/450af108-05d1-499e-902a-aca579f8a400)

### 2. CREATE a VIEW that will display all products whose price range is between 100-150
- ![Image](https://github.com/user-attachments/assets/112c89dc-beb1-4e6b-8aa1-a2d6ff922ef9)

## Output
- ![Image](https://github.com/user-attachments/assets/4e3d6e94-881a-4b9a-a7a6-a07dbc98cc3e)

### 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL
PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with
the following v_code (21344, 23119 and 24288)
- ![Image](https://github.com/user-attachments/assets/5d8ae890-7b78-4220-9830-e8d864f17142)
## Output
- ![Image](https://github.com/user-attachments/assets/38b9f98c-dd3b-40b9-82fb-29c3afc66f53)

### 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and
UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.
- ![Image](https://github.com/user-attachments/assets/67b2f998-dc9f-4cdd-829d-f16ecfcb0a4b)
## Output
- ![Image](https://github.com/user-attachments/assets/523c4353-5e20-4b0a-98b4-51f73339471b)

### 5. CREATE A Function that will take 2 parameters(v_code and
v_state) and display All the product description and price based on
the parameters passed to the function
- ![Image](https://github.com/user-attachments/assets/447f52bb-16dc-44ba-ba2f-fd92e20ecb13)
## Output
- ![Image](https://github.com/user-attachments/assets/fbfc6956-a0da-402b-aa3e-da48c4da2dea)
