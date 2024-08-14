Instructions for Running the Project
Clone the Project
After cloning the project to your local machine, you need to run Tailwind CSS to process the styles. Use the following command to do that:

bash
Copy code
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
This command tells Tailwind CSS to watch for changes in your input.css file and compile them into output.css whenever you make updates.
Opening the Project

The project has two pages: the index page and the about page. Since HTML doesn't support reusable components directly, there may be some repeated code across these pages.

Navigating the Pages

Option 1: Using Live Server
You can open either page using Live Server. To do this:

Start by opening the index.html file with Live Server. This will launch the index page in your browser.
To navigate to the about page, manually change the URL in your browser’s address bar to about.html.
For example, if your index.html page is being served at http://localhost:5500/, change the URL to http://localhost:5500/about.html.
Option 2: Open Directly
You can also open the about.html page directly using Live Server without going through the index page.
