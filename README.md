URL Shortener Web Application (Go)

->Developed a lightweight web-based URL shortener using Golang’s net/http package, allowing users to generate and manage shortened links through an HTML interface.

->Implemented URL mapping logic using in-memory hash maps, and generated unique 6-character short keys via a random character generator.

->Designed a simple HTML frontend to accept user input and display original and shortened URLs using dynamic templating with fmt.Sprintf.

->Handled HTTP routing for shortening (/shorten) and redirecting (/short/{key}) links with appropriate HTTP status codes (301 redirects, 400/404 errors).

->Demonstrated strong understanding of REST principles, form handling, and dynamic content generation in Go.
