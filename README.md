### 🛠️ Run Instructions for `Empowering-Local-Youth-Through-Mentorship-Server`

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd Empowering-Local-Youth-Through-Mentorship-Server
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

   (or `yarn install` if the project uses yarn)

3. **Set up environment variables**
   Create a `.env` file in the root directory and add values like:
   ```env
   PORT=5000
   DATABASE_URL=mongodb://127.0.0.1:27017/mentorship
   JWT_SECRET=your-secret-key
   ```

4. **Run the server**

   * For normal start:

     ```bash
     npm start
     ```
   * For development with auto-restart (if using `nodemon`):

     ```bash
     npm run dev
     ```

5. **Verify server is running**
   Open your browser or use Postman:

   ```
   http://localhost:5000/
   ```

   You should see a response like `"Server is running"` or API endpoints working.

---


