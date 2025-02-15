## **AI Image Generator**  
A web-based AI image generator powered by **Pollinations.ai** as an open API backend. It enables users to generate high-quality AI images with customizable parameters.  

### **Features:**  
- **Powered by Pollinations.ai** – Uses an open API for AI image generation.  
- **Multi-Model Support** – Choose from various AI models.  
- **Customizable Prompts** – Optimize prompts for better results.  
- **Adjustable Parameters** – Modify aspect ratio, seed values, and more.  
- **Real-Time Preview** – View generated images before finalizing.  
- **Dark Mode Support** – Switch between light and dark themes.  
- **Prompt Enhancement** – Default system prompt optimized for generating Indonesian women’s physical characteristics (constant). Feel free to modify as needed.  
- **NSFW Capabilities** – With the right combination of text and image models, NSFW content can be generated to a certain degree.  

### **How to Deploy**  

#### **Modern Deployment**  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/your-repo/ai-image-generator.git  
   cd ai-image-generator  
   ```  
2. **Install dependencies:**  
   ```sh
   npm install  
   ```  
3. **Set environment variables:**  
   - Create a `.env` file.  
   - Add your **Pollinations.ai API key** and required configurations.  
4. **Run the development server:**  
   ```sh
   npm run dev  
   ```  
5. **Build for production:**  
   ```sh
   npm run build  
   ```  
6. **Deploy using Vercel, Netlify, or Docker:**  
   - **Vercel:** `vercel deploy`  
   - **Netlify:** Connect the repo and deploy  
   - **Docker:**  
     ```sh
     docker build -t ai-image-generator .  
     docker run -p 3000:3000 ai-image-generator  
     ```  

#### **Old-School Deployment (HTML Only)**  
1. **Download html file** (the only one required file).  
2. **Place it in your web server’s root or any subfolder.**  
3. **Open the file in a browser**—and voilà, it runs! 🚀  

Now your AI Image Generator is live and ready to use! 🎨
