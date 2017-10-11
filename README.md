# Invoice-Converter
A python code for converting Invoice in PDF format to Excel file.

Businesses today often share their Billing Invoices in the pdf format via email, in order to reduce the cost of printing. But further the goods & service receiver who gets the invoice has to read the pdf and type the data manually into his records.

Here is a quick solution to that, where we convert our pdf file directly to .xlsx format, saving the labour of typing.  :D

## Libraries Used
**1.PyPDF2 -** A library with functions of reading and writing pdf files.

**2.Openpyxl -** A python library for creating an excel workbook and performing tasks on it.

## invoice converter.py
Python module that uses the mentioned libraries and creates Excel entries for every invoice page in the pdf.

## Sample Test Files
**1.invoice(single).pdf**-  A single invoice containing various fields.

**2.invoice.pdf**- A bunch of 5 invoives with similar fields, but different values.

## Sample Output Files
**1.invoice(single).xlsx**-  Resulting excel file with single row entry for the one invoice.

**2.invoice.xlssx**- Resulting excel file with mutiple entries for the various invoices.

## Conversion Procedure

1. Before running the module, install the two required libraries.
```
pip install PyPDF2
pip install openpyxl
```

2. Enter the name of your input pdf and output excel files in the variables, **input_file** and **output_file** rrespectively.

3. Choose the fields that you wish to extract from your PDF invoice and mention them in the array **main_list**.

4. Now run the program in your Python environment. **Invoice Converted Successfully...!!!**, shows that file conversion was completed.

5. Test your output **.xlsx** file to see if conversion is acceptable.


## Limitations
The required condition for the module to give good results is that the data should be structured in tabular formats. Also the field and its value should be adjacent to each other.

For any queries and suggestions, mail at:
apurvatripathi13@gmail.com
