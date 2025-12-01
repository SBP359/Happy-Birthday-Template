# Happy Birthday Website

A delightful and interactive single-page website to celebrate a special someone's birthday! This website features:

- **Personalized Countdown:** A dynamic countdown timer leading up to the celebration.
- **Vibrant Animations:** Floating balloons, shimmering effects, and a festive cake GIF.
- **Interactive Photo Gallery:** A stylish gallery to showcase cherished memories.
- **Heartfelt Poem Section:** A dedicated space for a personalized birthday message.
- **Background Music:** An option to play background music for a complete celebratory experience.
- **Confetti and Emoji Bursts:** Engaging visual effects to add to the festive atmosphere.
- **Responsive Design:** Optimized for various screen sizes, from desktops to mobile devices.

Easily customizable with recipient's name, sender's name, personalized messages, and your own images and music!

## Customization

You can easily personalize this website by modifying the `birthday-website.html` file. Look for the `// ======= CUSTOMIZABLE VARIABLES =======` section within the `<script>` tag.

### Images

- **Cover Image:**
  - Replace `cover-image.png` with your desired cover image. Update the `coverImagePath` variable in `birthday-website.html` if the filename changes.
  - ```578:578:birthday-website.html
            const coverImagePath = "cover-image.png"; // Changed from "/api/placeholder/800/600"
  ```
- **Gallery Images:**
  - Add your image files (e.g., `img3.jpg`, `img4.jpg`) to the same directory as `birthday-website.html`.
  - Update the `galleryImages` array in `birthday-website.html` with the filenames of your desired images.
  - ```581:588:birthday-website.html
        const galleryImages = [
            "img2.jpg",
            "img3.jpg",
            "img4.jpg",
            "img5.jpg",
            "img6.jpg",
            "img7.jpg"
        ];
  ```
- **Cake GIF:**
  - Ensure your cake GIF is named `cake.gif` and placed in the same directory.
  - ```823:823:birthday-website.html
            cakeImg.src = 'cake.gif'; // Make sure your cake GIF is named 'cake.gif'
  ```
