# OpenCollab 🚀

### Real-time Collaborative Code Editor for Technical Interviews & Pair Programming


[![Node](https://img.shields.io/badge/node-%3E%3D16.0.0-green)](package.json)
[![Firebase](https://img.shields.io/badge/firebase-realtime-orange)](https://firebase.google.com)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/humancto/CollabCode)
[![Version](https://img.shields.io/badge/version-1.0.0-blue)](package.json)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/humancto/CollabCode)


<p align="center">
  <strong>A secure, production-ready platform for conducting technical interviews and pair programming sessions.</strong><br>
  Built with Node.js, Firebase, and vanilla JavaScript for maximum performance and simplicity.
</p>

<p align="center">
  <a href="#-live-demo">Live Demo</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-features">Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## 🎯 Why OpenCollab?

<table>
  <tr>
    <td>✅ <strong>Zero Setup</strong><br>No accounts needed for candidates</td>
    <td>⚡ <strong>Real-time Sync</strong><br>See changes instantly across all participants</td>
    <td>🌍 <strong>16+ Languages</strong><br>JavaScript, Python, Java, C++, Go, Ruby, and more</td>
  </tr>
  <tr>
    <td>▶️ <strong>Live Execution</strong><br>Run code directly in the browser</td>
    <td>📊 <strong>Interview Analytics</strong><br>Track candidate behavior and performance</td>
    <td>💬 <strong>Slack Integration</strong><br>Export results directly to your team</td>
  </tr>
</table>

## 🚀 Live Demo

### 🎬 See It In Action

<p align="center">
  <!-- Add demo GIF here: docs/screenshots/demo.gif -->
<img src="docs/screenshots/demo.gif" alt="OpenCollab Demo" width="100%">
</p>

**Try it now:** [OpenCollab Live Demo](https://opencollab-demo.vercel.app)

### 📸 Screenshots

<details open>
<summary><b>Beautiful Landing Page</b></summary>
<img src="docs/screenshots/landing-page.png" alt="Landing Page" width="100%">

- Animated code particles background
- Clear role selection (Interviewer vs Candidate)
- Feature highlights at a glance
</details>

<details>
<summary><b>Interviewer Login</b></summary>
<img src="docs/screenshots/interviewer-login2.png" alt="Interviewer Login" width="100%">

- Secure JWT authentication
- Clean, professional interface
- Password reset functionality
</details>

<details>
<summary><b>Admin Dashboard - Session Management</b></summary>
<img src="docs/screenshots/admin-dashboard.png" alt="Admin Dashboard" width="100%">

- View all active/ended sessions
- Real-time session statistics
- Quick actions for each session
- Export capabilities
</details>

<details>
<summary><b>Live Coding Session</b></summary>
<img src="docs/screenshots/coding-session.png" alt="Coding Session" width="100%">

- Real-time collaborative editor
- Multiple language support
- Live code execution
- Participant presence indicators
</details>

<details>
<summary><b>Interview Notes & Feedback (Feature)</b></summary>

**Advanced note-taking features:**
- Structured feedback forms
- Real-time note synchronization
- Rating system for different skills
- Hiring recommendations
- Export to Slack/Email
- Markdown support for formatting
- Timestamped observations
- Code snippet references
</details>

<details>
<summary><b>Session Analytics (Feature)</b></summary>

- Activity timeline
- Code changes history
- Time spent analysis
- Candidate behavior tracking
- Tab switch detection
- Copy/paste monitoring
</details>

## ⚡ Quick Start

### One-Click Deploy

Deploy your own instance in seconds:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/humancto/CollabCode&env=ADMIN_EMAIL,ADMIN_PASSWORD_HASH,JWT_SECRET,FIREBASE_PROJECT_ID)

### Local Development

```bash
# Clone the repository
git clone https://github.com/treonix.in/CollabCode.git
cd CollabCode

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Generate admin password hash
node generate-password-hash.js "YourSecurePassword123!"

# Start development server
npm run dev

# Open http://localhost:3000
```

**Setup time: Under 3 minutes! ⏱️**

## 🎨 Features

### For Interviewers

<details>
<summary><b>📋 Admin Dashboard</b></summary>

- Create unlimited interview sessions
- Manage active sessions in real-time
- View candidate activity and metrics
- Export session data to Slack/CSV
- Session recording and playback

</details>

<details>
<summary><b>📝 Interview Notes & Feedback System</b></summary>

**Comprehensive note-taking during interviews:**
- **Real-time Notes:** Take notes while watching candidates code
- **Structured Feedback:** Pre-defined categories for consistent evaluation
- **Skill Ratings:** Rate candidates on technical skills, problem-solving, communication
- **Hiring Recommendations:** Clear yes/no/maybe with justification
- **Code Annotations:** Reference specific code snippets in your notes
- **Timestamp Tracking:** Automatic timestamps for observations
- **Markdown Support:** Format notes with headings, lists, code blocks
- **Template System:** Use predefined interview question templates
- **Collaborative Notes:** Multiple interviewers can add notes simultaneously
- **Export Options:** Send to Slack, email, or download as PDF/JSON

</details>

<details>
<summary><b>📊 Analytics & Insights</b></summary>

- Real-time activity tracking
- Code change history
- Time spent per problem
- Candidate behavior patterns
- Performance metrics
- Tab switch detection
- Copy/paste monitoring
- Typing speed analysis

</details>

<details>
<summary><b>🔒 Security Features</b></summary>

- JWT-based authentication
- Encrypted session data
- Role-based access control
- Session isolation
- Automatic cleanup
- IP tracking for audit logs

</details>

### For Candidates

<details>
<summary><b>💻 Professional Editor</b></summary>

- Syntax highlighting for 16+ languages
- Auto-completion and IntelliSense
- Multiple themes (Monokai, GitHub, Solarized, etc.)
- Customizable editor settings
- Vim/Emacs key bindings

</details>

<details>
<summary><b>🚀 Code Execution</b></summary>

- Run code in real-time
- Support for multiple languages
- Input/output handling
- Error highlighting
- Performance metrics

</details>

<details>
<summary><b>🤝 Collaboration Tools</b></summary>

- Real-time cursor tracking
- Live code synchronization
- Built-in chat (coming soon)
- Screen sharing (coming soon)
- Voice/video calls (coming soon)

</details>

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
  <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase" alt="Firebase">
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express">
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT">
  <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
</p>

- **Frontend:** Vanilla JavaScript, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **Database:** Firebase Realtime Database
- **Editor:** ACE Editor with Firepad
- **Authentication:** JWT + bcrypt
- **Deployment:** Vercel (serverless functions)
- **Code Execution:** Piston API

## 📦 Project Structure

```
OpenCollab/
├── 📁 api/                 # Serverless API endpoints
│   ├── auth/              # Authentication endpoints
│   └── sessions/          # Session management
├── 📁 scripts/            # Client-side JavaScript
│   ├── app.js            # Main application logic
│   └── auth-api.js       # Authentication handling
├── 📁 styles/             # CSS styles
├── 📁 lib/                # Libraries and SDKs
├── 📄 index.html          # Landing page
├── 📄 app.html            # Main application
└── 📄 package.json        # Dependencies
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file with the following variables:

```env
# Admin Credentials
ADMIN_EMAIL=admin@yourcompany.com
ADMIN_PASSWORD_HASH=<generated_hash>
JWT_SECRET=<random_secret_key>

# Firebase Configuration
FIREBASE_PROJECT_ID=your-project-id
FIREBASE_CLIENT_EMAIL=firebase-adminsdk@your-project.iam.gserviceaccount.com
FIREBASE_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\n...\n-----END PRIVATE KEY-----"

# Optional
SLACK_WEBHOOK_URL=https://hooks.slack.com/services/YOUR/WEBHOOK
APP_DOMAIN=https://your-domain.com
```

### Firebase Setup

1. Create a new Firebase project
2. Enable Realtime Database
3. Add security rules from `database.rules.secure.json`
4. Generate service account key
5. Update `lib/firebase-sdk.js` with your config

## 🙏 Acknowledgments

- [ACE Editor](https://ace.c9.io/) - The high performance code editor
- [Firebase](https://firebase.google.com/) - Real-time database and hosting
- [Piston](https://github.com/engineer-man/piston) - Code execution engine
- [Vercel](https://vercel.com/) - Deployment and serverless functions


<p align="center">
  <a href="#opencollab-">Back to top ⬆️</a>
</p>
