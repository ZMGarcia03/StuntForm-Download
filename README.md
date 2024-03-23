# StuntForm-Download
With this update, users can save the data locally in a CSV file by clicking the "Download Data" button. The data will be formatted as CSV and downloaded to the user's device, where it can be accessed via File Explorer.

# How Inspect or Manage data in Browsers

****Google Chrome:****
1.Open Google Chrome and navigate to the webpage where the localStorage data is saved.
2.Right-click on the page and select "Inspect" or press Ctrl + Shift + I (Windows/Linux) or Cmd + Option + I (Mac) to open the Developer Tools.
3.In the Developer Tools window, navigate to the "Application" tab.
4.In the left sidebar, you'll see "Storage" section. Expand it, and you'll find "Local Storage". Click on it to view the stored data.

****Mozilla Firefox:****
1.Open Mozilla Firefox and navigate to the webpage where the localStorage data is saved.
2.Right-click on the page and select "Inspect Element" or press Ctrl + Shift + I (Windows/Linux) or Cmd + Option + I (Mac) to open the Developer Tools.
3.In the Developer Tools window, navigate to the "Storage" tab.
4.In the left sidebar, you'll see "Local Storage". Click on it to view the stored data.

****Microsoft Edge:****
1.Open Microsoft Edge and navigate to the webpage where the localStorage data is saved.
2.Right-click on the page and select "Inspect" or press Ctrl + Shift + I (Windows) or Cmd + Option + I (Mac) to open the Developer Tools.
3.In the Developer Tools window, navigate to the "Storage" tab.
4.In the left sidebar, you'll see "Local Storage". Click on it to view the stored data.

Keep in mind that localStorage data is tied to a specific domain (or "origin"), so you'll only see data saved by scripts from the same domain. If you want to access or manage the data programmatically or use it outside of the browser, you'll need to implement some method for exporting or synchronizing it with an external system.

# License
This project is protected by [MIT License].(LICENSE)
