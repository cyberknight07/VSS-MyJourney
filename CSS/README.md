## INLINE TO EXTERNAL CSS

### INLINE CSS

<body
    style="
      margin: 0;
      padding: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: black;
    "
  >
    <!-- Background -->
    <div
      style="
        width: 100%;
        height: 100vh;
        background: linear-gradient(
            to top,
            rgba(0, 0, 0, 0.8),
            rgba(0, 0, 0, 0.8)
          ),
          #111;
        background-size: cover;
        display: flex;
        flex-direction: column;
      "
    >
      <!-- Header -->
      <div style="padding: 25px 50px">
        <svg
          width="150"
          height="50"
          viewBox="0 0 150 50"
          xmlns="http://www.w3.org/2000/svg"
        >
          <!-- Dark background -->
          <rect x="0" y="0" width="150" height="50" fill="#221F1F" rx="4" />

          <!-- NETFLIX text in bold red -->
          <text
            x="75"
            y="36"
            font-family="Arial, sans-serif"
            font-size="32"
            font-weight="900"
            fill="#E50914"
            text-anchor="middle"
            letter-spacing="0.5"
          >
            NETFLIX
          </text>
        </svg>
      </div>

      <!-- Signup Box -->
      <div
        style="
          flex: 1;
          display: flex;
          justify-content: center;
          align-items: center;
        "
      >
        <div
          style="
            width: 380px;
            background: rgba(0, 0, 0, 0.75);
            padding: 60px;
            color: white;
            border-radius: 4px;
          "
        >
          <h1
            style="
              margin: 0 0 28px 0;
              font-size: 32px;
              color: white;
              font-family: Arial, Helvetica, sans-serif;
            "
          >
            Create Your Account
          </h1>

          <!-- First Name Input -->
          <input
            type="text"
            placeholder="First Name"
            style="
              width: 100%;
              padding: 14px;
              margin-bottom: 16px;
              background: #333;
              border: none;
              border-radius: 4px;
              color: white;
              font-size: 16px;
              box-sizing: border-box;
            "
          />

          <!-- Last Name Input -->
          <input
            type="text"
            placeholder="Last Name"
            style="
              width: 100%;
              padding: 14px;
              margin-bottom: 16px;
              background: #333;
              border: none;
              border-radius: 4px;
              color: white;
              font-size: 16px;
              box-sizing: border-box;
            "
          />

          <!-- Email Input -->
          <input
            type="email"
            placeholder="Email address"
            style="
              width: 100%;
              padding: 14px;
              margin-bottom: 16px;
              background: #333;
              border: none;
              border-radius: 4px;
              color: white;
              font-size: 16px;
              box-sizing: border-box;
            "
          />

          <!-- Password Input -->
          <input
            type="password"
            placeholder="Password"
            style="
              width: 100%;
              padding: 14px;
              margin-bottom: 16px;
              background: #333;
              border: none;
              border-radius: 4px;
              color: white;
              font-size: 16px;
              box-sizing: border-box;
            "
          />

          <!-- Confirm Password Input -->
          <input
            type="password"
            placeholder="Confirm Password"
            style="
              width: 100%;
              padding: 14px;
              margin-bottom: 20px;
              background: #333;
              border: none;
              border-radius: 4px;
              color: white;
              font-size: 16px;
              box-sizing: border-box;
            "
          />

          <!-- Terms Agreement -->
          <div
            style="
              display: flex;
              align-items: flex-start;
              margin-bottom: 20px;
              font-size: 13px;
              color: #b3b3b3;
            "
          >
            <input
              type="checkbox"
              style="margin-right: 10px; margin-top: 3px"
            />
            <span
              >I agree to the Netflix
              <span style="color: #e50914; cursor: pointer">Terms of Use</span>
              and
              <span style="color: #e50914; cursor: pointer"
                >Privacy Policy</span
              ></span
            >
          </div>

          <!-- Sign Up Button -->
          <button
            style="
              width: 100%;
              padding: 14px;
              background: #e50914;
              border: none;
              border-radius: 4px;
              color: white;
              font-size: 16px;
              font-weight: bold;
              cursor: pointer;
              margin-bottom: 20px;
            "
          >
            Create Account
          </button>

          <!-- Already have account section -->
          <div
            style="
              display: flex;
              justify-content: center;
              align-items: center;
              font-size: 14px;
              color: #b3b3b3;
            "
          >
            Already have an account?
            <span style="color: #e50914; cursor: pointer; margin-left: 8px">
              Sign In</span
            >
          </div>

          <!-- Contact Info -->
          <div
            style="
              display: flex;
              justify-content: center;
              margin-top: 25px;
              font-size: 13px;
              color: #737373;
            "
          >
            Need help?
            <span style="color: #e50914; cursor: pointer; margin-left: 8px"
              >Contact Support</span
            >
          </div>

          <!-- reCAPTCHA notice -->
          <div
            style="
              margin-top: 25px;
              font-size: 11px;
              color: #8c8c8c;
              text-align: center;
              padding-top: 15px;
              border-top: 1px solid #333;
            "
          >
            This page is protected by Google reCAPTCHA to ensure you're not a
            bot. <span style="color: #e50914; cursor: pointer">Learn more</span>

### EXTERNAL CSS

- {
  margin: 0;
  padding: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: black;
  }

.mainContainer {
width: 100%;
height: 100vh;
background: linear-gradient(to top, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
#111;
background-size: cover;
display: flex;
flex-direction: column;
}

.header {
padding: 25px 50px;
}

.signup {
flex: 1;
display: flex;
justify-content: center;
align-items: center;
}

#signup-container {
width: 380px;
background: rgba(0, 0, 0, 0.75);
padding: 60px;
color: white;
border-radius: 4px;
}

#signup-container > h1 {
margin: 0 0 28px 0;
font-size: 32px;
}

#input-box {
width: 100%;
padding: 14px;
margin-bottom: 16px;
background: #333;
border: none;
border-radius: 4px;
color: white;
font-size: 16px;
box-sizing: border-box;
}

.terms {
display: flex;
align-items: flex-start;
margin-bottom: 20px;
font-size: 13px;
color: #b3b3b3;
}

.terms > input {
margin-right: 10px;
margin-top: 3px;
}

.terms > span {
color: #e50914;
cursor: pointer;
}

.button {
width: 100%;
padding: 14px;
background: #e50914;
border: none;
border-radius: 4px;
color: white;
font-size: 16px;
font-weight: bold;
cursor: pointer;
margin-bottom: 20px;
}

.account {
display: flex;
justify-content: center;
align-items: center;
font-size: 14px;
color: #b3b3b3;
}

#spanbox {
color: #e50914;
cursor: pointer;
margin-left: 8px;
}

.contact {
display: flex;
justify-content: center;
margin-top: 25px;
font-size: 13px;
color: #737373;
}

.recaptcha {
margin-top: 25px;
font-size: 11px;
color: #8c8c8c;
text-align: center;
padding-top: 15px;
border-top: 1px solid #333;
}

### Animation of Color moving over text from left to right

  <h1 style="
    font-size:60px;
    font-family:Arial, sans-serif;
    background: linear-gradient(80deg, rgb(244, 78, 78), orange, yellow, green, cyan, blue, violet);
    background-size: 200% auto;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: colorMove 5s linear infinite;
  ">
    Animated Heading
  </h1>

  <style>
    @keyframes colorMove {
      from { background-position: 0% center; }
      to   { background-position: 200% center; }
    }
  </style>

#### We can use different color-gradient for animation

> radial-gradient(outward-color-animation)
> background: conic-gradient(red, yellow, green, blue); -> For Circular color coding
> @keyframes spinColors {

            from { background-position: 0% 0%; }
            to   { background-position: 100% 100%; }
        }

> repeating-radial-gradient(circle, red 0%, orange 10%, yellow 20%);
> @keyframes pulseColors {

          from { background-position: 0% 0%; }
          to   { background-position: 100% 100%; }
        }

### Thank you for going through my repository
