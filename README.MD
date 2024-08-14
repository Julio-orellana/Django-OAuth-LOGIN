# DJANGO OAuth Login

## Basic OAuth 2.0 Login App made with Django.

This is a Basic OAuth Login App with django that you ca use for your future projects.

### How to Use the OAuth Login app?
1. Clone this repository using `git clone https://github.com/Julio-orellana/Django-OAuth-LOGIN.git` in your terminal. 

1. Move to the directory of the project.

    Optional: Create a new Python Virtual Environment to install the dependencies of the project.

2. Install the project dependencies using `pip install -r requirements.txt`

3. Create the DB using `python3 manage.py migrate` for MacOS or `python manage.py migrate` for Windows.

4. Create your OAuth Apps for the project. 
    <ul>
        <li>Google, Twitter, Facebook, Github, etc </li>
    </ul>
    
5. Add your OAuth Keys to a .env File using the structure of the `.env.example` file.

6. Run the server using: `python3 manage.py runserver_plus --cert-file cert.crt` for MacOS or `python manage.py runserver_plus --cert-file cert.crt` for Windows. This will generate a generic certified for a local HTTPS server.
    - *You must set your localhost to a domain such as `mysite.com:8000`*

7. Try the app in the next url: *https://**your localhost domain**/account/login/*

8. Once you logged in succesfuly, you can logout using the following link: *https://**your localhost domain**/account/logout/*