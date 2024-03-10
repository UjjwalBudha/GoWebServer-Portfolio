Portfolio Website Documentation
This is a simple web server application written in Go (Golang) to host a portfolio website. The server handles static files, serves a basic form, and responds with a "hello" message.

Features
Static File Serving: Static files like HTML, CSS, JavaScript, images, etc., are served efficiently using Go's built-in HTTP server.
Form Handling: A basic form is implemented to collect user data such as name and address.
HTTP Handlers:
/hello: Responds with a "hello" message.
/form: Handles POST requests to submit form data.
Usage
Clone Repository: Clone this repository to your local machine.

bash
Copy code
git clone <repository_url>
Navigate to Project Directory: Go to the directory where the project is cloned.

bash
Copy code
cd <project_directory>
Run the Server: Execute the Go program to start the web server.

bash
Copy code
go run main.go
Alternatively, you can build and run the executable file.

bash
Copy code
go build main.go
./main
Access the Website: Open your web browser and navigate to http://localhost:8080 to view the portfolio website.

Configuration
You can customize the content of your portfolio by editing the static files located in the ./static directory. HTML, CSS, JavaScript, and other static resources can be modified to tailor the appearance and functionality of your website.
