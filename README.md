Generate a full-stack project called **Care4U** – a Digital Psychological Intervention System for students.  

Requirements:  

1. **Frontend (React + Tailwind CSS)**  
   - Clean, modern, and responsive UI with nice colors, icons, and illustrations.  
   - Mood Tracker: users select mood (happy, sad, stressed, anxious, relaxed, angry) with emojis/pictures.  
   - Daily Self-Test: 5 simple multiple-choice questions → show a score + feedback.  
   - Dashboard: show latest mood, last test score, and a simple 7-day report (line chart/bar chart).  
   - Resource Hub with:  
     - **YourDost website link (https://yourdost.com/)**.  
     - YouTube videos for stress relief, meditation, and motivation.  
     - Verified Indian mental health helpline numbers.  
   - Authentication: signup/login/logout with simple forms.  
   - Attractive home page with a welcome banner and motivational images.  

2. **Backend (Node.js + Express)**  
   - API endpoints for:  
     - User authentication (signup/login).  
     - Mood tracking (add mood, get moods).  
     - Daily self-test (submit & fetch result).  
     - Reports (generate last 7-day report).  
     - Resources (return YouTube links, helplines, and YourDost link).  
   - Use MongoDB for storage.  
   - Enable CORS for frontend-backend connection.  

3. **Database (MongoDB)**  
   - Users: { username, email, password }  
   - Moods: { userId, mood, timestamp }  
   - Tests: { userId, score, date }  
   - Resources: { title, type, link }  

4. **Preloaded Resource Data (must be added):**  
   - YourDost: "Talk to experts" → https://yourdost.com/  
   - Helplines:  
     - Vandrevala Foundation Helpline: 1860 266 2345 / 1800 233 3330  
     - AASRA Helpline (24x7): +91-9820466726 / +91-9820466727  
     - Snehi Helpline: +91-9582208181  
   - YouTube:  
     - "Guided Meditation for Stress Relief" – https://www.youtube.com/watch?v=inpok4MKVLM  
     - "Motivational Video for Students" – https://www.youtube.com/watch?v=mgmVOuLgFB0  
     - "How to Control Anxiety" – https://www.youtube.com/watch?v=WWloIAQpMcQ  

5. **Other requirements**  
   - Include **package.json** and working **server.js**.  
   - Provide a complete **README.md** with description, features, tech stack, setup steps.  
   - Code should run with minimal setup (`npm install && npm start`).  




