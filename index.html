<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/intl-tel-input/17.0.8/css/intlTelInput.css">
    <style>
        /* Your existing CSS styles */
        body {
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
        }
        .form-container {
            background-color: silver;
            padding: 20px;
            border-radius: 8px;
            max-width: 500px;
            margin: 0 auto;
            box-sizing: border-box;
        }
        .form-container h2 {
            color: blue;
            text-align: center;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
            box-sizing: border-box;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input {
            width: calc(100% - 22px);
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            background-color: #e6e6e6;
            box-sizing: border-box;
        }
        .error {
            color: red;
            font-size: 0.875em;
        }
        .intl-tel-input {
            width: calc(100% - 22px);
            box-sizing: border-box;
        }
        .password-container {
            position: relative;
            width: 100%;
            box-sizing: border-box;
        }
        .password-container input {
            width: calc(100% - 50px);
            padding-right: 40px;
            box-sizing: border-box;
        }
        .toggle-password {
            position: absolute;
            right: 10px;
            top: 50%;
            transform: translateY(-50%);
            cursor: pointer;
            z-index: 1;
        }
        button {
            background-color: blue;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            box-sizing: border-box;
        }
        button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>

<div class="form-container">
    <h2>Registration Form</h2>
    <form id="my-form">
        <div class="form-group">
            <label for="first-name">First Name</label>
            <input type="text" id="first-name" name="first-name" required minlength="4" oninput="validateName('first-name')">
            <div class="error" id="first-name-error"></div>
        </div>
        <div class="form-group">
            <label for="last-name">Last Name</label>
            <input type="text" id="last-name" name="last-name" required minlength="6" oninput="validateName('last-name')">
            <div class="error" id="last-name-error"></div>
        </div>
        <div class="form-group">
            <label for="mobile-number">Mobile Number</label>
            <input type="tel" id="phone" name="phone" required>
            <div class="error" id="mobile-number-error"></div>
        </div>
        <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required oninput="validateEmail()">
            <div class="error" id="email-error"></div>
        </div>
        <div class="form-group">
            <label for="password">Password</label>
            <div class="password-container">
                <input type="password" id="password" name="password" required minlength="8" oninput="validatePassword()">
                <span class="toggle-password" onclick="togglePasswordVisibility()">👁️</span>
            </div>
            <div class="error" id="password-error"></div>
        </div>
        <div class="form-group">
            <label for="address">Address</label>
            <input type="text" id="address" name="address" required>
            <div class="error" id="address-error"></div>
        </div>
        <div class="form-group">
            <label for="dob">Date of Birth</label>
            <input type="date" id="dob" name="dob" required>
            <div class="error" id="dob-error"></div>
        </div>
        <div class="form-group">
            <button type="submit">Submit</button>
        </div>
    </form>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/intl-tel-input/17.0.8/js/intlTelInput.min.js"></script>
<script>
function validateName(fieldId) {
    const nameField = document.getElementById(fieldId);
    const errorField = document.getElementById(fieldId + '-error');
    let value = nameField.value;

    if (/\d/.test(value)) {
        errorField.textContent = 'Name should not contain numbers.';
    } else if (value.trim().length === 0) {
        errorField.textContent = 'Name cannot be empty.';
    } else {
        errorField.textContent = '';
    }

    // Capitalize the first letter
    if (value.length > 0 && !/\d/.test(value)) {
        value = value.charAt(0).toUpperCase() + value.slice(1);
        nameField.value = value;
    }
}

function validateEmail() {
    const emailField = document.getElementById('email');
    const errorField = document.getElementById('email-error');
    const value = emailField.value;
    const parts = value.split('@');

    if (parts.length === 2 && /\d/.test(parts[1])) {
        errorField.textContent = 'Email should not contain numbers after the @ symbol.';
    } else {
        errorField.textContent = '';
    }
}

const phoneInputField = document.querySelector("#phone");
const phoneInput = window.intlTelInput(phoneInputField, {
    utilsScript: "https://cdnjs.cloudflare.com/ajax/libs/intl-tel-input/17.0.8/js/utils.js",
});

phoneInputField.addEventListener('blur', function() {
    const errorField = document.getElementById('mobile-number-error');
    if (!phoneInput.isValidNumber()) {
        errorField.textContent = 'Invalid mobile number.';
    } else {
        errorField.textContent = '';
    }
});

function validatePassword() {
    const passwordField = document.getElementById('password');
    const errorField = document.getElementById('password-error');
    const value = passwordField.value;

    if (/\s/.test(value)) {
        errorField.textContent = 'Password should not contain spaces.';
    } else if (!/\d/.test(value)) {
        errorField.textContent = 'Password must contain at least one number.';
    } else if (!/[!@#$%^&*(),.?":{}|<>]/.test(value)) {
        errorField.textContent = 'Password must contain at least one special character.';
    } else {
        errorField.textContent = '';
    }
}

function togglePasswordVisibility() {
    const passwordField = document.getElementById('password');
    const type = passwordField.getAttribute('type') === 'password' ? 'text' : 'password';
    passwordField.setAttribute('type', type);
}
</script>

</body>
</html>
