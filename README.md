This project is a simple Java console-based application that prints out a formatted invoice.
It demonstrates the use of basic Java syntax, including the main method, System.out.println() statements, and string formatting for console output.


---

Project Overview

The program outputs a fully formatted invoice containing:

Billing and shipping details

Contact information

Product list with HSN codes, quantities, rates, and tax

Summary section with total, discounts, and grand total


The invoice is displayed directly on the console.


---

Features

Clear and structured invoice layout

Simple console-based output

Demonstrates formatting techniques using print statements

Easy to customize with additional items or details



---

Technologies Used

Java SE

No external libraries

Runs on any standard JDK (Java Development Kit)



---

File Structure

Invoice/
└── Invoice.java      // Main program that prints the invoice


---

How to Run the Program

1. Install Java (JDK 8 or above).


2. Save the file as Invoice.java.


3. Open a terminal or command prompt and navigate to the file location.


4. Compile the program:



javac Invoice.java

5. Run it:



java Invoice

The invoice will be displayed in the console.


---

Sample Output

The program prints a structured invoice similar to this (truncated sample):

----------------------------------------------------------------------------------------
                                    INVOICE
----------------------------------------------------------------------------------------
Bill To:                                                                 Ship To:
C026-01-0787/2024                                                         NDUNG'U MOREENE WANDIA
...
----------------------------------------------------------------------------------------
S.No   Product Code   Product Name        HSN code    Quantity   Units   Rate    Tax   Amount
----------------------------------------------------------------------------------------
1      105            Surf Excel 5 kg     34019011    20         nos     600.00  5%    12600.00
...
----------------------------------------------------------------------------------------
                                                           Total               22141.00
                                                           Discounts             141.00
                                                           Grand total         22000.00
----------------------------------------------------------------------------------------


---

Learning Outcomes

Console text formatting

Java program structure

Managing static invoice data

Understanding how printed output can form structured layouts
