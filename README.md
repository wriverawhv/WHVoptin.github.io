<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JNL Quantum Wireless Call Alarm SMS Opt-In</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f7fb;
      margin: 0;
      padding: 30px 20px;
    }
    .container {
      max-width: 650px;
      margin: 0 auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 6px 18px rgba(0,0,0,.08);
      padding: 30px;
    }
    h1 {
      margin-top: 0;
      font-size: 2rem;
    }
    .info-box, .notice {
      background: #eef3ff;
      border-left: 4px solid #4a67d8;
      padding: 15px;
      border-radius: 5px;
      margin: 20px 0;
    }
    label {
      display: block;
      font-weight: bold;
      margin: 15px 0 8px;
    }
    input[type="tel"] {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 16px;
    }
    .checkbox {
      display: flex;
      align-items: flex-start;
      gap: 10px;
      margin: 18px 0;
    }
    .checkbox input {
      margin-top: 4px;
    }
    a {
      color: #2d5bd7;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .cta {
      width: 100%;
      background: #4a67d8;
      color: white;
      border: none;
      padding: 14px 20px;
      font-size: 1rem;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
    }
    .cta:hover {
      background: #3957c3;
    }
    .muted {
      font-size: 0.9rem;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>JNL Quantum Wireless Call Alarm SMS Notifications</h1>

    <div class="info-box">
      <strong>What you'll receive:</strong>
      <ul>
        <li>Resident call alarm alerts</li>
        <li>Wireless nurse call station notifications</li>
        <li>System alarm updates</li>
      </ul>
    </div>

    <form>
      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" placeholder="+1 (555) 123-4567" required />

      <div class="checkbox">
        <input type="checkbox" id="consent" required />
        <label for="consent">
          I agree to receive SMS messages related to resident call alarm notifications from the JNL Quantum Wireless Call System.
        </label>
      </div>

      <div class="notice">
        Standard message and data rates may apply.
      </div>

      <div class="checkbox">
        <input type="checkbox" id="policy" required />
        <label for="policy">
          I have read and agree to the
          <a href="privacy-policy.html">Privacy Policy</a>
          and
          <a href="terms-conditions.html">Terms & Conditions</a>.
        </label>
      </div>

      <button type="submit" class="cta">Sign up for SMS alerts</button>
    </form>

    <p class="muted">
      Your phone number will remain confidential and will only be used for JNL Quantum notification services.
    </p>
  </div>
</body>
</html>
