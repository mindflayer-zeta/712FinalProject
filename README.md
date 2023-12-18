---Gene Search Project---
This project is a web-based application that allows users to search for genes based on specific thresholds and displays the search results in a tabular format. It includes functionality to copy the generated gene names as unformatted text.

---Features---
Search Form: Users can input thresholds for output quantity and PV size to search for genes.
Search Results: Displays the searched genes along with their corresponding PV values in a table format.
Copy Genes: Provides a button to copy the generated gene names as unformatted text separated by spaces.

---Technologies Used---
R: Calculate p-value of each gene.
SQL: Create database including gene name and pv for further uses.
Python (CGI): Backend scripting language used to handle server-side requests and database interactions.
HTML: Structure and content of the web pages.
CSS: Styling for the web pages (make "Copy Genes" button more striking - Go Blue Jay).
JavaScript: Provides functionality for the "Copy Genes" button.

---File Structure---
final.cgi: Python script handling the server-side logic, fetching data, and generating the HTML output.
gene_search_template.html: HTML template file containing the structure of the search page and results display.
styles.css: CSS file defining the styles for the web pages.
scripts.js: JavaScript file implementing the "Copy Genes" functionality.

---Usage---
Ensure the Python environment with MySQL connector is set up.
Configure the database connection details in the Python script (final.cgi).
Place the files (final.cgi, gene_search_template.html, styles.css, scripts.js) in a web server's directory.
Access the application url (http://bfx3.aap.jhu.edu/ywang710/final/search.html) via a web browser with JHU VPN and enter desired thresholds in the search form.
Click the "Search" button to display the results.
Use the "Copy Genes" button to copy the gene names as text.

---Development---
Feel free to contribute to the project by improving the code, adding new features, or enhancing the user interface. You can fork the repository, make changes, and create a pull request for review. 
This process test uses the "GDS287" DataSet (https://www.ncbi.nlm.nih.gov/sites/GDSbrowser?acc=GDS287). Due to its applicability, we can expect it to work on other similar DataSets in NCBI GEO.

---Acknowledgements---
This project was developed as a part of AS.410.712.81.FA23 Advanced Practical Computer Concepts for Bioinformatics Fianl Project.
