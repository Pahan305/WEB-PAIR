<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PAIR CODE</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      background-color: #141414;
      background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                        url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><rect width="100" height="100" fill="%231a1a1a"/><path d="M0 0L100 100" stroke="%23200" stroke-width="1"/><path d="M100 0L0 100" stroke="%23200" stroke-width="1"/></svg>');
      background-repeat: repeat;
      font-family: 'Arial', sans-serif;
      color: #fff;
      padding: 20px;
      box-sizing: border-box;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 100%;
    }

    .box {
      width: 100%;
      max-width: 340px;
      padding: 25px;
      text-align: center;
      background: linear-gradient(145deg, #a20000, #8a0000);
      border-radius: 12px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.6);
      position: relative;
      overflow: hidden;
    }

    .box::before {
      content: '';
      position: absolute;
      top: -10px;
      left: -10px;
      right: -10px;
      bottom: -10px;
      background: linear-gradient(45deg, #ff0000, #ff5e00, #ff0000);
      z-index: -1;
      filter: blur(20px);
      opacity: 0.3;
    }

    #text {
      color: #ffffff;
      position: relative;
      z-index: 1;
    }

    .centered-text {
      color: #ffffff;
      margin-top: 0;
      margin-bottom: 15px;
    }

    .subtitle {
      color: #ffcccc;
      font-size: 0.85rem;
      margin-bottom: 20px;
      line-height: 1.4;
    }

    .input-container {
      display: flex;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 4px;
      gap: 4px;
      width: 100%;
      margin-bottom: 15px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }

    .input-container input {
      border-radius: 10px 0 0 10px;
      background: #000000;
      width: 100%;
      flex-basis: 70%;
      padding: 14px;
      border: none;
      border-left: 2px solid #25d366;
      color: #ecf0f1;
      font-size: 14px;
      transition: all 0.3s ease;
    }

    .input-container input:focus {
      border-left: 3px solid #25d366;
      outline: none;
      box-shadow: inset 5px 5px 8px #000000, inset -5px -5px 8px #1a1a1a;
    }

    .input-container button {
      flex-basis: 30%;
      padding: 14px;
      background: #25d366;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: white;
      border: none;
      border-radius: 0 10px 10px 0;
      cursor: pointer;
      transition: all 0.3s ease;
      font-size: 12px;
    }

    .input-container button:hover {
      background: #20bd5c;
      transform: translateY(-2px);
    }

    .input-container button:active {
      transform: translateY(0);
    }

    #waiting-message {
      color: #ffffff;
      margin-top: 10px;
    }

    #pair {
      min-height: 60px;
      margin-top: 15px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .code-display {
      background: rgba(0, 0, 0, 0.3);
      padding: 12px 20px;
      border-radius: 8px;
      cursor: pointer;
      transition: all 0.3s ease;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }

    .code-display:hover {
      background: rgba(0, 0, 0, 0.5);
      transform: scale(1.02);
    }

    #copy {
      font-size: 18px;
      font-weight: bold;
      color: white;
    }

    #copy span {
      color: #25d366;
      font-size: 20px;
    }

    /* Loading spinner */
    #loading-spinner {
      display: none;
      color: white;
      margin: 15px 0;
      flex-direction: column;
      align-items: center;
    }

    .spinner-text {
      margin-top: 8px;
      font-size: 14px;
      color: #ccc;
    }

    .fa-spinner {
      animation: spin 1.5s linear infinite;
      font-size: 24px;
    }

    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    .error-message {
      color: #ff6b6b;
      font-weight: bold;
      background: rgba(0, 0, 0, 0.3);
      padding: 10px;
      border-radius: 6px;
      border-left: 3px solid #ff6b6b;
    }

    .success-message {
      color: #25d366;
      font-weight: bold;
    }

    @media (max-width: 500px) {
      .input-container {
        flex-direction: column;
      }

      .input-container input {
        border-radius: 10px;
        margin-bottom: 4px;
      }

      .input-container button {
        padding: 12px;
        border-radius: 10px;
        width: 100%;
      }
      
      .box {
        padding: 20px 15px;
      }
    }

    .logo {
      font-size: 24px;
      margin-bottom: 15px;
      color: white;
    }

    .logo i {
      margin-right: 8px;
      color: #25d366;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="main">
      <div class="box" id="box">
        <div class="logo">
          <i class="fab fa-whatsapp"></i> ROBIN WEB PAIR
        </div>
        <div id="text">
          <h3 class="centered-text">Link Robin with phone number</h3>
          <p class="subtitle">🔢 Enter your number with country code to generate pairing code</p>
          <div class="input-container">
            <input placeholder="+94701234567" type="tel" id="number" name="number">
            <button id="submit">Submit</button>
          </div>
          <!-- Loading spinner -->
          <div id="loading-spinner">
            <i class="fas fa-spinner fa-spin"></i>
            <div class="spinner-text">Generating code...</div>
          </div>
          <main id="pair"></main>
        </div>
      </div>
    </div>
  </div>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/1.0.0-alpha.1/axios.min.js"></script>
  <script>
    let a = document.getElementById("pair");
    let b = document.getElementById("submit");
    let c = document.getElementById("number");
    let box = document.getElementById("box");
    let loadingSpinner = document.getElementById("loading-spinner");

    // Format phone number as user types
    c.addEventListener('input', function (e) {
      let input = e.target.value.replace(/\D/g, '').substring(0, 15);
      let formattedInput = '';
      
      if (input.length > 0) {
        formattedInput = '+' + input;
      }
      
      e.target.value = formattedInput;
    });

    async function Copy() {
      let text = document.getElementById("copy").innerText;
      let obj = document.getElementById("copy");
      let code = obj.querySelector('span').innerText;
      
      try {
        await navigator.clipboard.writeText(code);
        obj.innerHTML = "✔️ COPIED";
        obj.className = "success-message";
        
        setTimeout(() => {
          obj.innerHTML = `CODE: <span>${code}</span>`;
          obj.className = "";
        }, 2000);
      } catch (err) {
        alert('Failed to copy: ' + err);
      }
    }

    b.addEventListener("click", async (e) => {
      e.preventDefault();
      
      // Clear previous messages
      a.innerHTML = '';
      
      if (!c.value) {
        a.innerHTML = '<div class="error-message">❗ Please enter your WhatsApp number with country code.</div>';
        return;
      }
      
      // Remove any non-digit characters except leading +
      const phoneNumber = c.value.replace(/[^0-9+]/g, '');
      
      // Validate phone number (basic validation)
      if (!phoneNumber.startsWith('+') || phoneNumber.length < 10 || phoneNumber.length > 16) {
        a.innerHTML = '<div class="error-message">❗ Invalid number format. Please include country code (e.g. +94701234567).</div>';
        return;
      }
      
      // Show loading spinner
      loadingSpinner.style.display = "flex";
      b.disabled = true;
      
      try {
        // Simulate API call (replace with your actual endpoint)
        // In a real scenario, you would use: await axios(`/code?number=${phoneNumber.replace('+', '')}`)
        await new Promise(resolve => setTimeout(resolve, 2000)); // Simulate network delay
        
        // For demo purposes - generating a random 6-digit code
        const randomCode = Math.floor(100000 + Math.random() * 900000);
        
        a.innerHTML = `
          <div class="code-display" id="copy" onclick="Copy()">
            CODE: <span>${randomCode}</span>
          </div>
          <p class="subtitle">Click the code to copy it</p>
        `;
      } catch (error) {
        a.innerHTML = '<div class="error-message">❗ Service unavailable. Please try again later.</div>';
        console.error('Error:', error);
      } finally {
        // Hide loading spinner
        loadingSpinner.style.display = "none";
        b.disabled = false;
      }
    });
  </script>
</body>
</html>
