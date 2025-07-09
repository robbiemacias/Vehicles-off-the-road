GHG Offset: Vehicle Equivalency Calculator
This is a simple web-based calculator that helps estimate Greenhouse Gas (GHG) savings from using Renewable Natural Gas (RNG) compared to fossil fuels, and translates those savings into equivalent numbers of passenger vehicles or heavy-duty diesel trucks removed from the road for one year.

The calculator features a modern, responsive design built with Tailwind CSS.

Features
Energy Input: Enter the energy in Million British Thermal Units (MMBtu).

Selectable Baseline Fuel: Choose from pre-defined Carbon Intensity (CI) values for Fossil Gasoline, Fossil Diesel, and Fossil Natural Gas, based on California Air Resources Board (CARB) data.

RNG CI Input: Enter the Carbon Intensity of the Renewable Natural Gas (RNG).

GHG Savings Calculation: Calculates total GHG savings in pounds of CO₂e.

Vehicle Equivalency: Converts GHG savings into the equivalent number of passenger vehicles and heavy-duty diesel trucks.

Modern UI: Clean and responsive design using Tailwind CSS.

How to Use
Enter Energy (MMBtu): Input the total energy in MMBtu that you are analyzing.

Select Baseline Fuel: Choose the fossil fuel (Gasoline, Diesel, or Natural Gas) that your RNG is replacing from the dropdown menu. The corresponding Carbon Intensity (CI) value will be used in the calculation.

Enter CI of RNG (gCO₂e/MJ): Provide the Carbon Intensity of your Renewable Natural Gas. This value can often be negative, indicating a net reduction in emissions.

Click "Calculate GHG Savings": The results will be displayed below, showing the total GHG savings and the equivalent number of vehicles.

Installation and Deployment
This calculator is a single HTML file with inline CSS (Tailwind CSS via CDN) and JavaScript, making it very easy to deploy.

Local Setup
Save the file: Save the provided HTML code as index.html in a folder on your computer.

Open in browser: Simply open the index.html file in any web browser (e.g., Chrome, Firefox, Edge).

Deploying to GitHub Pages
You can easily host this calculator online using GitHub Pages.

Create a new GitHub Repository:

Go to GitHub and log in.

Click on the + sign in the top right corner and select New repository.

Give your repository a name (e.g., ghg-offset-calculator).

Choose Public or Private.

Do NOT initialize with a README, .gitignore, or license at this step (you'll add them manually).

Click Create repository.

Upload the files:

On the repository page, click on the uploading an existing file link.

Drag and drop your index.html file and this README.md file into the upload area.

Add a commit message (e.g., "Initial commit: Add calculator files").

Click Commit changes.

Enable GitHub Pages:

Go to the Settings tab of your repository.

In the left sidebar, click on Pages.

Under "Build and deployment", select Deploy from a branch.

For "Branch", choose main (or master if that's your default branch) and / (root) for the folder.

Click Save.

Access your calculator:

After a few moments (it might take a minute or two for GitHub Pages to build), refresh the Pages section in your repository settings.

You will see a message indicating "Your site is live at..." followed by the URL (e.g., https://yourusername.github.io/your-repository-name/). Click this link to access your live calculator!

Technologies Used
HTML5: Structure of the web page.

Tailwind CSS: For modern and responsive styling.

JavaScript: For the calculation logic and dynamic content updates.

Carbon Intensity (CI) Data Source
The baseline Carbon Intensity (CI) values for Fossil Gasoline, Fossil Diesel, and Fossil Natural Gas are based on data from the California Air Resources Board (CARB) Low Carbon Fuel Standard (LCFS) program. These values are subject to change based on CARB's updates.
