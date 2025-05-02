# belly_button_challenge_25

🧬 Belly Button Biodiversity Dashboard.
This project was created as part of the Data Analytics Bootcamp at the University of California, Irvine. It is an interactive dashboard designed to visualize and explore the microbial biodiversity found in human belly buttons using a public dataset provided in the course.

📊 Project Overview
The dashboard allows users to:
- Select a test subject ID from a dropdown menu
- View demographic information about the selected subject
- See a horizontal bar chart of the top 10 operational taxonomic units (OTUs) found
- Explore a bubble chart representing the full OTU sample set
The dataset is sourced from a JSON file and rendered dynamically using D3.js and Plotly.js.

🧪 How to Use
  1) Open the index.html file using Live Server in VS Code.
  2) Use the dropdown menu to select a test subject ID.
  3) Watch the charts and metadata panel update dynamically!
 
🛠️ Development Notes
- The data is fetched from an external JSON file using D3's .json() method.
- DOM elements are manipulated using D3's select and append methods.
- Charts are rendered using Plotly's newPlot() function.
- If changes to app.js don’t appear immediately, try doing a hard refresh in the browser.

- 💡 Technologies Used
- HTML/CSS
- JavaScript
- D3.js (for data loading and DOM manipulation)
- Plotly.js (for charts)
- Live Server (for development and testing)
- ChatGPT
- Xpert Learning Assistant Chat+
