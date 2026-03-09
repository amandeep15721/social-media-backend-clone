# Social Media Backend API





\# Social Media Backend API



A backend REST API for a social media platform built using \*\*FastAPI\*\*.

This project implements core social media functionalities such as user authentication, post creation, and interaction with posts.



---



\## Tech Stack



\* Python

\* FastAPI

\* PostgreSQL

\* SQLAlchemy

\* JWT Authentication

\* Passlib (password hashing)



---



\## Features



\* User registration

\* Secure user authentication using JWT

\* Create, update and delete posts

\* Retrieve posts from the database

\* Password hashing for secure storage

\* Modular backend architecture



---



\## Project Structure



```

social-media-backend/

│

├── app/

│   ├── main.py

│   ├── database.py

│

│   ├── models/

│   │   └── models.py

│

│   ├── schemas/

│   │   └── schemas.py

│

│   ├── routers/

│   │   ├── users.py

│   │   ├── posts.py

│   │   └── auth.py

│

│   ├── utils/

│   │   ├── oauth2.py

│   │   └── security.py

│

│   └── services/

│

├── requirements.txt

├── README.md

└── .gitignore

```



---



\## Installation



Clone the repository:



```bash

git clone https://github.com/YOUR\_USERNAME/social-media-backend.git

cd social-media-backend

```



Create a virtual environment:



```bash

python -m venv venv

```



Activate the virtual environment:



Windows:



```bash

venv\\Scripts\\activate

```



Install dependencies:



```bash

pip install -r requirements.txt

```



---



\## Running the Server



Start the FastAPI server using:



```bash

uvicorn app.main:app --reload

```



The server will run at:



```

http://127.0.0.1:8000

```



---



\## API Documentation



FastAPI automatically generates interactive API documentation.



Swagger UI:



```

http://127.0.0.1:8000/docs

```



!\[Swagger UI](docs/swagger-ui.png)



---



\## Future Improvements



\* Add comments and likes functionality

\* Implement pagination

\* Add Redis caching

\* Integrate recommendation system using machine learning

\* Add Docker support



---



\## Author



Developed as a backend learning project to explore modern API development using FastAPI and PostgreSQL.













