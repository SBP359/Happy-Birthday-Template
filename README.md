# Happy Birthday Website

A delightful and interactive single-page website to celebrate a special someone's birthday.

## Features

- Personalized countdown timer
- Vibrant animations (balloons, shimmer, cake GIF)
- Interactive photo gallery
- Heartfelt poem/message section
- Optional background music
- Confetti and emoji bursts
- Fully responsive for all devices

---

## Customization Guide

All customization happens inside `birthday-website.html` in the section:

    // ======= CUSTOMIZABLE VARIABLES =======

---

## Images

### Cover Image

Replace `cover-image.png` with your own file and update:

    const coverImagePath = "cover-image.png";

### Gallery Images

Add your images (img3.jpg, img4.jpg, etc.) in the same directory and edit:

    const galleryImages = [
        "img2.jpg",
        "img3.jpg",
        "img4.jpg",
        "img5.jpg",
        "img6.jpg",
        "img7.jpg"
    ];

### Cake GIF

Ensure your GIF is named `cake.gif`:

    cakeImg.src = "cake.gif";

---

## Music

Default background track: “Blue” by Yung Kai (2024).  
Replace the audio file with your own if you want custom music.

---

## Notes

- Keep all assets in the same folder as `birthday-website.html`
- Filenames must match exactly or they won’t load
