# NEXT.js TailwindCSS and Flask Boilerplate

This is a boilerplate project that combines Next.js for the main app, Tailwind CSS for styling, and Flask for extending the functionality. It is designed to help you quickly kickstart web development projects that require a modern, responsive user interface and a Python-based backend. Naturally Next can be used to create a full stack application, but python brings a much more powerful interaction with AI and ML as well as many libraries which can be relayed to the next app using the flask server.

## Next.js

Next.js is a popular React framework for building web applications. It offers several advantages for web development, including:

Server-side rendering (SSR): Next.js allows you to pre-render pages on the server, which can improve performance and SEO.

Routing: Next.js provides a straightforward and easy-to-use routing system for creating client-side navigation.

Fast development: With features like hot module reloading, you can see the results of your changes in real-time during development.

Static site generation (SSG): You can pre-build and export your pages to static HTML files, making them easy to deploy on various hosting platforms.

Large ecosystem: Next.js has a large and active community, with numerous plugins and extensions available.

## Tailwind CSS
Tailwind CSS is a utility-first CSS framework that makes it easy to style web applications. Key features of Tailwind CSS include:

Utility classes: Tailwind provides a set of utility classes that allow you to apply styles directly to your HTML elements, making it easy to create responsive and consistent designs.

Customization: You can customize the framework to match your project's design requirements by editing the tailwind.config.js file.

Rapid development: Tailwind CSS speeds up development by eliminating the need to write custom CSS styles for every element.

Responsive design: The framework comes with built-in responsive design classes, helping you create responsive web applications with ease.

## Flask
Flask is a lightweight web framework for Python that is known for its simplicity and ease of use. Some key features of Flask are:

Minimalistic: Flask provides just what you need to build web applications, making it easy for developers to get started quickly.

Extensible: Flask has a vast ecosystem of extensions that can be easily integrated to add functionality like authentication, database integration, and more.

Werkzeug and Jinja2: Flask is built on top of Werkzeug, a WSGI library, and uses Jinja2 as the template engine. This combination offers a solid foundation for web application development.

RESTful API support: Flask is often used to build RESTful APIs, making it a versatile choice for both web applications and APIs.

Python: Being based on Python, Flask allows you to leverage Python's extensive libraries and ecosystem for various tasks.

By combining these technologies, you get a powerful and flexible stack for developing web applications. Next.js handles the frontend with a React-based framework, Tailwind CSS simplifies styling, and Flask provides the backend using Python. This combination is well-suited for building modern, responsive, and efficient web applications.

# Running the Application

Make sure you have
- Git
- Python 3.11.x higher
- Node 19.x or higher
- NPM
- 
First you need to clone the repository

  ```
  git clone https://github.com/Shreedhar-Raj/nextjs-tailwind-flask-boilerplate.git
  ```


   ```
   cd nextjs-flask-boilerplate
   ```
## To run the client
```
cd client && npm install
```

2. Build App
   ```npm run build```
3. Run Dev mode
   ```npm run dev```
4. Run App mode
   ```npm run start```

## To run the server

```
cd server
```

1. Initiate virtual environment
   ```
   python3 -m pip install --user virtualenv
   python3 -m venv venv
   source venv/bin/activate
   ```
2.  Install dependancies
   
   ```
   python3 -m pip install -r requirements.txt
   ```
3. Run server with flask
   ```
   flask run
   ```
   or
   ```
   flask run --debug
   ```
5. Run server using gunicorn
   ```
   gunicorn --config gunicorn_config.py app:app
   ```
