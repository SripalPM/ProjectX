# Google Login System

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/SripalPM/ProjectX.git
   cd ProjectX
   ```

2. **Install dependencies**:
   Make sure you have Node.js installed, then run:
   ```bash
   npm install
   ```

3. **Create Google API Credentials**:
   - Go to the [Google Developers Console](https://console.developers.google.com/).
   - Create a new project.
   - Navigate to "Credentials" and click on "Create Credentials".
   - Select "OAuth 2.0 Client IDs".
   - Configure the consent screen and specify the redirect URI.
   - Download the credentials JSON file.

4. **Set up environment variables**:
   Create a `.env` file in the root directory and include:
   ```env
   GOOGLE_CLIENT_ID=your_client_id
   GOOGLE_CLIENT_SECRET=your_client_secret
   REDIRECT_URI=your_redirect_uri
   ```

## Deployment Instructions
1. **Build the project**:
   ```bash
   npm run build
   ```

2. **Deploy to your desired hosting service**:
   You can use services like Heroku, Vercel, or AWS. Ensure the environment variables are configured in your hosting service as well.

3. **Start the application**:
   ```bash
   npm start
   ```

## Additional Resources
- [Google OAuth 2.0 Documentation](https://developers.google.com/identity/protocols/oauth2)
- [Node.js Express Guide](https://expressjs.com/en/starter/installing.html)

Feel free to contribute or raise issues if you face any problems!