# Paradise Nursery Shopping Application

Welcome to the Paradise Nursery Shopping Application! This is a React-based e-commerce application for browsing and shopping for plants.

## Setup and Running Instructions

Follow these step-by-step instructions to set up and run the application on your local machine.

### Step 1: Open a Terminal

To get started, you'll need to open a terminal window:
- In most IDEs or code editors, you can open a terminal by navigating to the **top-right corner** and selecting **Terminal tab > New Terminal**.
- Alternatively, you can use your system's terminal application.

### Step 2: Clone the Repository

Clone the forked repository to your local machine using the following command:

```bash
git clone https://github.com/Aung-Yadanar-Oo/e-plantShopping.git
```

### Step 3: Navigate to the Project Directory

Once the repository is cloned, navigate into the project directory:

```bash
cd e-plantShopping
```

### Step 4: Install Dependencies

Install all the required dependencies using npm:

```bash
npm install
```

This will download and install all necessary packages listed in `package.json`.

### Step 5: Run the Application

Start the application in preview mode:

```bash
npm run preview
```

**Important:** The application will run on port **4173** by default. After running the command, you should see output indicating the server is running, typically showing a URL like `http://localhost:4173`.

### Step 6: For IBM Skills Network Toolbox Users

If you are using IBM Skills Network Toolbox, follow these additional steps to access the application:

1. After running `npm run preview`, note that the application is running on port **4173**.
2. In the IBM Skills Network Toolbox interface, click on the **"Skills Network"** button.
3. Select **"Launch Application"**.
4. Enter **4173** as the port number.
5. Click the button to launch the application in a new browser window.

### Step 7: Understanding the Initial User Interface

When you first open the application, you will see:

#### Landing Page
- **Background Image**: A beautiful nature-themed background representing the nursery
- **Welcome Message**: "Welcome To Paradise Nursery" with the tagline "Where Green Meets Serenity"
- **Get Started Button**: A prominent button to enter the shopping area

#### Navigation Bar (after clicking "Get Started")
Once you click the "Get Started" button, you'll see the main navigation bar with the following elements:

1. **Paradise Nursery Logo and Name** (Left side):
   - Clicking this will take you back to the landing page/home screen
   
2. **Plants Link** (Center):
   - This link allows you to browse through different categories of plants
   - Categories include: Air Purifying Plants, Aromatic Fragrant Plants, Insect Repellent Plants, Medicinal Plants, and Low Maintenance Plants
   
3. **Cart Icon** (Right side):
   - Clicking the shopping cart icon displays your shopping cart
   - Shows all items you've added to your cart
   - Allows you to review your selections, adjust quantities, and proceed to checkout

### Step 8: Using the Shopping Cart

- Click on the **cart icon** in the navigation bar to view your shopping cart
- The cart section will display all items you've added
- You can continue shopping by using the navigation options or modify your cart as needed

---

## Additional Information

- **Technology Stack**: React, Redux Toolkit, Vite
- **Styling**: CSS with custom styles
- **State Management**: Redux for cart management

Happy Shopping at Paradise Nursery! 🌱