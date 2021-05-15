# Wallet app for Platzi Master

This app is the third project for Platzi Master to keep improving the skillset as a backend developer. It is a small app that helps with the managing of your personal finances by adding your expenses and income and showing you a monthly and/or weekly graphic that includes this information.

As for now, the app is not yet complete, it lachs the authentication system and the means of adding a user and the income/outcome to firestore, the selected database to store the information.

This app was created using Flask v1.1.2. The reason to use this framework was to be able to connect the app to a non-relational database, as well as to know how to use a different framework than the one I have been using to create the previous projects. It uses the Jinja2 template system included with Flask and pure HTML All the requirements can be found in the requirements.txt file. To install them, you can do it manually (which is not recommended) or you can run the following command in your preferred Windows, Linux or Mac CLI: "pip install -r requirements.txt". After having installed the requirements, you can start the proyect by running the command "flask run" and it will start a local server in "127.0.0.1:5000" and you are good to go.

The app can be improved by connecting it to a non-relational database, as well as generating an API that can be consumed by the frontend instead of using the Jinja2 template system.

This project was created along with Leonardo Rincón Botache. https://bitbucket.org/leobotache7/
