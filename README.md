# url-shortener

This project aims to develop a URL shortener application using Python and Flask. The application will provide the following functionalities:

1. **Create Short Codes**: Users can generate short codes for long URLs and files, making it easier to share and access specific webpages/files.

2. **Redirect Functionality**: When a user accesses the generated shortened link, they will be redirected to the original long URL.

3. **File Upload Support**: The application will also support file uploads, enabling users to share files using shortened links.

4. **User Tracking with Cookies**: Users will have the ability to track and view their previously created short codes using cookies.

5. **API Integration**: The project will include an API with minimal code to retrieve information about the generated short codes.

6. **Bootstrap Styling**: The application will be styled using Bootstrap, resulting in a visually appealing and user-friendly interface.

7. **Duplicate Name Handling**: If a user tries to create a short code with a name that already exists, a warning message will be displayed using Flask's flashing system.

The uploaded file will be given a newname and saved in the project directory's urlshort/static/user_files folder

And the urls.json file is specific to each user as it contains the codes and URLS/Files created by them.

# To Run the URL Shortener locally:

1. Clone the repository:

```
git clone https://github.com/SwethaVoora/url-shortener.git
```

2. navigate to the project directory
3. run the application and access the URL Shortener in your web browser at '[127.0.0.1:5000](http://127.0.0.1:5000)'
