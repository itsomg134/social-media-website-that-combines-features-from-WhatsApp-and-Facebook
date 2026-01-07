# social-media-website-that-combines-features-from-WhatsApp-and-Facebook

A modern hybrid social media web application that combines the best features of WhatsApp and Facebook, built with pure HTML, CSS, and JavaScript.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 💬 Messaging (WhatsApp-inspired)
- Real-time chat interface with message bubbles
- Contact list with recent conversations
- Search functionality for messages
- Sent/received message styling
- Active status indicators
- Timestamp display

### 📱 Social Feed (Facebook-inspired)
- News feed with user posts
- Create and share posts
- Stories feature with user avatars
- Like, comment, and share actions
- User profiles with custom avatars
- Chronological post display

### 🎨 Design
- Beautiful gradient purple theme
- Responsive layout
- Smooth animations and transitions
- Modern UI/UX patterns
- Clean and intuitive interface

## 🚀 Demo

<img width="1903" height="914" alt="image" src="https://github.com/user-attachments/assets/cb3055c5-e4e5-411f-857f-940350307422" />

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/social-connect.git
```

2. Navigate to the project directory:
```bash
cd social-connect
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

That's it! No build process or dependencies required.

## 💻 Usage

### Messaging
1. Click on any contact in the left sidebar to view the conversation
2. Type your message in the input field at the bottom
3. Press Enter or click the send button to send a message
4. Use the search box to find specific conversations

### Social Feed
1. Switch to the "Feed" tab in the top-right corner
2. View stories by clicking on user avatars at the top
3. Create a new post by typing in the "What's on your mind?" field
4. Interact with posts using Like, Comment, and Share buttons

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with flexbox and gradients
- **JavaScript** - Vanilla JS for interactivity
- **No frameworks or libraries** - Pure, dependency-free code

## 📁 Project Structure

```
social-connect/
│
├── index.html          # Main HTML file with embedded CSS and JS
├── README.md           # Project documentation
└── screenshot.png      # Preview image (optional)
```

## 🎯 Key Features Explained

### Chat System
- Dynamic message rendering
- Time-based message sorting
- User avatar generation with initials
- Active/inactive status tracking

### Post System
- Real-time post creation
- User-generated content display
- Engagement metrics (likes, comments, shares)
- Story highlights

### UI/UX
- Tab-based navigation between views
- Responsive sidebar with chat list
- Smooth scrolling and transitions
- Hover effects and visual feedback

## 🔧 Customization

### Changing Colors
Edit the gradient colors in the CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adding New Contacts
Add new chat items in the HTML:
```html
<div class="chat-item" onclick="selectChat('Name')">
    <div class="avatar">NN</div>
    <div class="chat-info">
        <div class="chat-name">Name</div>
        <div class="chat-preview">Message preview</div>
    </div>
    <div class="chat-time">1m</div>
</div>
```

### Modifying Layout
Adjust the sidebar width:
```css
.sidebar {
    width: 350px; /* Change this value */
}
```

## 🌟 Future Enhancements

- [ ] User authentication
- [ ] Real-time messaging with WebSockets
- [ ] Image/file sharing
- [ ] Video calls integration
- [ ] Dark mode support
- [ ] Mobile responsive design improvements
- [ ] Notification system
- [ ] Group chats
- [ ] Message reactions
- [ ] Profile customization
- [ ] Backend integration (Node.js/Express)
- [ ] Database storage (MongoDB/PostgreSQL)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
