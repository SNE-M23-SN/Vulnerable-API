 # Vulnerable API 

Intentionally Very Vulnerable API with Extremely Poor Coding Practices

**Note** This application is intentionally vulnerable and primarily used to demonstrate poor coding practices (in Python 3) and operations (Docker, etc.), showcasing specific vulnerabilities that may not be well presented in other projects. Another use case is to have an application for demonstrating various DevSecOps methods.

Do Not Use Any Part of This Code in Production! It is highly vulnerable to remote code execution. Do not leave it exposed.

Current Implemented Vulnerabilities:

* Data exposure through logic issues
* Mass assignment vulnerabilities
* Broken object-level authorization
* Broken authentication
* Remote Code Execution (RCE) via deserialization
* SQL injection
* File inclusion/path traversal
* Server-Side Template Injection

![image](https://github.com/SNE-M23-SN/Vulnerable-API/assets/174135229/fa911618-d42b-487e-8d69-4ebd54e1bb5e)


**Usage:**
* Build the Docker image:
```docker build --tag vulnapi .```
* Run the Docker container: 
```docker run -it --rm -p8000:8000 vulnapi```
* Open the API documentation in a web browser:
``` open http://IP_OF_HOST:8000/docs```


**Pull requests are welcome, especially for interesting and subtle bugs or bad practices. FastAPI makes it easy to implement examples.**
