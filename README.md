# QR Code Generator

A clean and simple web application that allows users to generate a QR code from any URL or text input instantly. This project is built with Vanilla JavaScript and uses the [qrserver.com](http://goqr.me/api/) API to create the QR codes on the fly.

![QR Code Generator Screenshot](https://i.imgur.com/8F1Jz9A.png)

### ✨ Features

-   **Instant Generation**: Creates a QR code as soon as the button is clicked.
-   **Text & URL Support**: Generate a QR code from any string of text or a valid URL.
-   **Dynamic UI**: The interface smoothly transitions to display the generated QR code.
-   **Responsive Design**: A mobile-first design that works seamlessly on any screen size.
-   **No Dependencies**: Built with pure HTML, CSS, and Vanilla JavaScript.

### 🛠️ Technologies Used

-   **Frontend**: HTML5, CSS3, Vanilla JavaScript
-   **API**: [QR Server API](http://goqr.me/api/doc/create-qr-code/) for QR code generation.

### 🚀 How to Use

No setup is required! Since this is a pure front-end project, you can run it by following these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/qr-code-generator.git](https://github.com/your-username/qr-code-generator.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd qr-code-generator
    ```

3.  **Open in browser:**
    -   Simply open the `index.html` file in your favorite web browser.

### 📝 How It Works

The application captures the user's input from the text field. When the "Generate QR Code" button is clicked, a JavaScript function makes a request to the QR Server API. The API URL is dynamically constructed with the user's input as a data parameter. The `src` attribute of the `<img>` tag is then set to this URL, which causes the browser to display the QR code image returned by the API.

---

_This project was created to practice DOM manipulation and asynchronous API integration with Vanilla JavaScript._
