# 🎁 Cloak Gift 

<div align="center">

*Hide your secrets in plain sight with the magic of steganography*

[🌐 Live Demo](https://cloak-gifts.netlify.app/)  | [🐛 Report Bug](https://github.com/BVPKARTHIKEYA/cloak-gift/issues) | [✨ Request Feature](https://github.com/BVPKARTHIKEYA/cloak-gift/issues)

</div>

---

## 📖 Overview

*Cloak Gift* is an interactive and secure steganography web application that transforms the way you share secrets. Using a delightful "gift box" metaphor, it allows users to hide and reveal encrypted messages within images.

- 🎁 *Wrap* your message like a gift (encryption + steganography)
- 🎀 *Tie the knot* with your secret key
- 📦 *Share* the gift box image
- 🔓 *Unwrap* to reveal the hidden message (decryption)

The result? A digital gift that only the intended recipient can open, blending fun interaction with strong cryptographic protection.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 *Interactive Interface* | Wrap and unwrap encrypted messages with a beautiful gift box animation |
| 🔐 *Advanced Encryption* | Triple-layer security: Unicode Binary → Morse Code → XOR Cipher |
| 🖼 *Image Embedding* | Securely hides encrypted data within images using steganography |
| 🔑 *Simple Decryption* | Reveals hidden content using your secret key |
| 🌐 *Browser-Based* | No installation needed — runs entirely in your browser |
| 🚀 *Zero Backend* | Complete client-side processing for maximum privacy |

---

## 🎬 Demo Gallery

<div align="center">

### The Gift Box Narrative
![WhatsApp Image 2025-10-26 at 20 21 26_874dd677](https://github.com/user-attachments/assets/e867f432-4248-4e98-9b80-f0c43f09bdea)


### Storing Message in the Gift Box
![WhatsApp Image 2025-10-26 at 20 21 54_fd4abcc0](https://github.com/user-attachments/assets/d35d7672-09d7-4beb-8680-9bc45df2ba29)

### Tying the Knot
![WhatsApp Image 2025-10-26 at 20 22 19_10b27b16](https://github.com/user-attachments/assets/d6455c6d-cf75-4710-a2df-1b8ea1b46933)


### Closing the Gift Box
![WhatsApp Image 2025-10-26 at 20 22 55_a1153ac6](https://github.com/user-attachments/assets/c43399d7-9e8c-4a87-ba63-4efe86b1f428)


### Untying and Opening the Gift Box
![WhatsApp Image 2025-10-26 at 20 24 28_12aa6b11](https://github.com/user-attachments/assets/5c18a13b-a91b-42c8-a573-e49e2b103d9e)

### Encryption Process

![WhatsApp Image 2025-10-26 at 20 25 09_57756bca](https://github.com/user-attachments/assets/d3206686-6560-4c69-be5e-d692e84d0c30)



### Decryption Process

![WhatsApp Image 2025-10-26 at 20 25 33_8a057480](https://github.com/user-attachments/assets/a89199b6-792f-4b48-8572-b1296c8eeba5)

</div>

---

## 🧠 How It Works

### 🎁 Creating a Gift Box (Encryption Process)

1. *Enter Your Secret Message* 💬
   - Type the message you want to hide

2. *Set Your Secret Key* 🔑
   - Create a unique key that only you and the recipient know

3. *Multi-Layer Encryption* 🛡
   - *Step 1*: Message converted to Unicode binary
   - *Step 2*: Secret key converted to Morse code binary
   - *Step 3*: Both combined using XOR encryption

4. *Image Embedding* 🖼
   - Upload an image to hide the encrypted data within
   - The encrypted message is invisibly embedded in the image pixels

5. *Download Your Gift* 🎉
   - Download the final gift box image
   - Share it with your recipient!

### 📦 Opening a Gift Box (Decryption Process)

1. *Upload the Gift Image* 📤
   - Load the steganographic image you received

2. *Enter the Secret Key* 🗝
   - Use the same key that was used during encryption

3. *Reveal the Message* ✨
   - Watch as the hidden message is magically revealed
   - The multi-layer decryption happens automatically

---

## 🧩 Tech Stack

| Layer | Technologies |
|-------|--------------|
| *Frontend* | HTML5, CSS3, JavaScript (ES6+) |
| *Encryption* | Unicode Binary, Morse Code, XOR Cipher |
| *Steganography* | Canvas API, Image Processing |
| *Deployment* | Netlify |
| *Design* | Custom CSS Animations, Responsive Design |

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or database required!

### Installation

1. *Clone the Repository*

   bash
   git clone https://github.com/BVPKARTHIKEYA/cloak-gift.git
   cd cloak-gift
   

2. *Open Locally*

   Simply open index.html in your browser:

   bash
   # On Windows
   start index.html

   # On macOS
   open index.html

   # On Linux
   xdg-open index.html
   

3. *Or Use Live Server*

   If you have VS Code with Live Server extension:
   - Right-click on index.html
   - Select "Open with Live Server"

### Quick Start with Live Demo

No installation needed! Just visit the [Live Demo](https://cloak-gifts.netlify.app/) and start creating gift boxes right away.

---

## 💡 Usage Guide

### Creating Your First Gift

1. Navigate to the *"Create Gift"* section
2. Type your secret message in the text area
3. Enter a memorable secret key
4. Click *"Upload Image"* to choose a cover image
5. Click *"Wrap Gift"* to encrypt and embed
6. Download your gift box image
7. Share it securely with your recipient

### Opening a Received Gift

1. Navigate to the *"Open Gift"* section
2. Upload the gift box image
3. Enter the secret key provided by the sender
4. Click *"Unwrap Gift"* to reveal the message

> 💡 *Pro Tip*: Use longer, more complex keys for better security!

---

## 🔒 Security Features

### Multi-Layer Encryption


Plain Text → Unicode Binary → Morse Binary → XOR Cipher → Steganography


1. *Unicode Binary*: Converts text to binary representation
2. *Morse Code*: Transforms the key into Morse binary
3. *XOR Encryption*: Combines message and key using XOR operation
4. *Steganography*: Hides encrypted data in image pixels

### Privacy First

- ✅ All processing happens in your browser
- ✅ No data sent to any server
- ✅ No tracking or analytics
- ✅ Messages never leave your device
- ✅ Complete offline functionality

---

## 📁 Project Structure


cloak-gift/
├── index.html              # Main HTML file
├── styles/
│   ├── main.css           # Core styles
│   └── animations.css     # Gift box animations
├── scripts/
│   ├── encryption.js      # Encryption logic
│   ├── steganography.js   # Image embedding
│   └── ui.js              # User interface handlers
├── assets/
│   ├── images/            # UI images and icons
│   └── fonts/             # Custom fonts
└── README.md              # This file


---

## 🔮 Future Enhancements

### Planned Features

- [ ] 🔐 Support for AES-256 encryption
- [ ] 📱 Mobile app version (React Native)
- [ ] 🌍 Multi-language support
- [ ] 🔔 Browser notifications
- [ ] 🎵 Audio steganography support

### Contributions Welcome!

Have an idea? Found a bug? Contributions are always welcome! See the [Contributing](#contributing) section below.

---

## 🤝 Contributing

We love contributions! Here's how you can help:

### How to Contribute

1. *Fork* the repository
2. *Create* a feature branch (git checkout -b feature/AmazingFeature)
3. *Commit* your changes (git commit -m 'Add some AmazingFeature')
4. *Push* to the branch (git push origin feature/AmazingFeature)
5. *Open* a Pull Request

### Contribution Ideas

- 🎨 Improve UI/UX design
- 🔐 Add new encryption methods
- 🐛 Fix bugs and issues
- 📝 Improve documentation
- 🌐 Add internationalization
- ♿ Enhance accessibility
- 🧪 Add unit tests

---



## 👨‍💻 Author

*Karthikeya Boddeda*

Made with ❤ and lots of ☕

- 💻 GitHub: [@BVPKARTHIKEYA](https://github.com/BVPKARTHIKEYA)
- 📧 Email: boddeda.karthikeya@gmail.com
- 💼 LinkedIn: [Karthikeya Boddeda](https://www.linkedin.com/in/boddeda-venkata-pavan-karthikeya-1a670b255/)
- 🐦 Twitter: [@karth_bodd9274](https://x.com/karth_bodd9274)

---

## 🙏 Acknowledgments

- Thanks to the open-source community for inspiration
- Special thanks to cryptography and steganography pioneers
- All contributors who help improve this project

---



## ⚠ Disclaimer

This tool is designed for educational purposes and secure personal communication. Users are responsible for complying with all applicable laws and regulations regarding encryption and data privacy in their jurisdiction.

---

## 🌟 Support

If you found Cloak Gift helpful, please consider:

- ⭐ *Starring* the repository
- 🐛 *Reporting* bugs and issues
- 💡 *Suggesting* new features
- 🤝 *Contributing* to the codebase
- 📢 *Sharing* with friends and colleagues
- ☕ *Buying me a coffee* (if you're feeling generous!)

---

<div align="center">

*🎁 Made with ❤ by Karthikeya Boddeda*

[⬆ Back to Top](#-cloak-gift)

</div>
