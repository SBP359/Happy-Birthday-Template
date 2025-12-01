# Happy Birthday Website

A delightful and interactive single-page website to celebrate a special someone's birthday!

This project includes:

- **Personalized Countdown:** A dynamic timer leading up to the celebration.
- **Vibrant Animations:** Floating balloons, shimmering effects, and a festive cake GIF.
- **Interactive Photo Gallery:** A stylish gallery to showcase cherished memories.
- **Heartfelt Poem Section:** A dedicated space for a personalized birthday message.
- **Background Music:** Optional background audio for a full celebratory vibe.
- **Confetti and Emoji Bursts:** Engaging visual effects for added fun.
- **Responsive Design:** Optimized for all screen sizes, from desktops to mobile devices.

Easily customizable with the recipient's name, sender's name, personalized messages, and your own images and music.

---

## Customization

You can personalize the website by editing the `birthday-website.html` file.  
Look for the `// ======= CUSTOMIZABLE VARIABLES =======` section inside the `<script>` tag.

---

## Images

### Cover Image
Replace `cover-image.png` with your desired cover image.  
Update the `coverImagePath` variable if the filename changes.

**Snippet:**  
\`\`\`js  
const coverImagePath = "cover-image.png";  
\`\`\`

### Gallery Images
Add your own images (e.g. `img3.jpg`, `img4.jpg`) to the same folder and update the array:

**Snippet:**  
\`\`\`js  
const galleryImages = [  
  "img2.jpg",  
  "img3.jpg",  
  "img4.jpg",  
  "img5.jpg",  
  "img6.jpg",  
  "img7.jpg"  
];  
\`\`\`

### Cake GIF
Make sure your cake GIF is named `cake.gif`.

**Snippet:**  
\`\`\`js  
cakeImg.src = "cake.gif";  
\`\`\`

---

## Music

The background music used in this project is **"Blue" by Yung Kai" (2024)**.  
Replace the audio file with your own if needed.
