Created a UiPath automation that performs the steps below.
Used the REFrameWork as the starting template and follow the UiPath development best practices.

Here are the steps performed by the Robot:
1. Log in to https://www.acme-test.com.
2. On the landing page, Dashboard, click on the Work items menu item. Scrape the data in all the pages of the table, page by page, ensuring error handling and recovery.
3. For each page:
- Filter the records where Status is 'Open';
- Filter the records where Type is 'WI5';
- Filter the records where WIID is less than 500000;
- Append the resulting datatable into an Excel worksheet; you shouldn't worry about the headers and format of the output file.
