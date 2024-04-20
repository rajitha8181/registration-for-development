<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">
    <h2>Registration Form</h2>
    <form id="registration-form">
        <div class="form-group">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" placeholder="Enter your username" required>
            <small class="hint">Choose a unique username</small>
        </div>
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email address" required>
            <small class="hint">We'll never share your email with anyone else</small>
        </div>
        <div class="form-group">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <small class="hint">Use at least 8 characters</small>
        </div>
        <button type="submit">Submit</button>
    </form>
</div>

</body>
</html>
# registration-for-development
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

.container {
    max-width: 400px;
    margin: 50px auto;
    padding: 20px;
    border-radius: 8px;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

h2 {
    text-align: center;
    margin-bottom: 20px;
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
}

input[type="text"],
input[type="email"],
input[type="password"],
button[type="submit"] {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
}

button[type="submit"] {
    background-color: #4CAF50;
    color: white;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #45a049;
}

.small {
    font-size: 0.8em;
    color: #777;
}

@media (max-width: 600px) {
    .container {
        width: 90%;
    }

    input[type="text"],
    input[type="email"],
    input[type="password"],
    button[type="submit"] {
        width: calc(100% - 20px);
        /* Adjusting width for smaller screens */
    }
}
