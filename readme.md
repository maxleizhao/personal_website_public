# Personal Website

I build a modern, responsive personal website with CV and blog functionality from scratch. This application allows you to showcase your professional experience and share blog posts with your audience.

My personal website can be found [here](https://maxleizhao.online).

## Features
- CV Management: Create, edit, and organize your CV entries by category
- Blog System: Write, publish, and manage blog posts with support for attachments
- Responsive Design: Looks great on all devices, from mobile to desktop
- Admin Panel: Secure admin interface for content management
- Authentication: JWT-based authentication system with auto-logout for security
- Hero Section: Customizable hero section to showcase your name and tagline
## Technology Stack
- Frontend: React, React Router, Axios
- Backend: Node.js, Express
- Database: SQLite (easy to set up, no external dependencies)
- Authentication: JWT (JSON Web Tokens)
- Styling: CSS with variables for easy customization

## Prerequisites
- Ubuntu server (20.04 LTS or later)
- SSH access with a key (e.g., `ssh-key-2025-03-12.key`)
- GitHub repository: `git@github.com:yourusername/personal-website.git`
- Domain name or public IP address (e.g., `158.179.27.125`)
- Node.js 14+ and npm 6+
- If using a private GitHub repository: GitHub access credentials (SSH key or Personal Access Token)

### Regular Updates
```bash
# Keep system updated
sudo apt update && sudo apt upgrade -y

# Update Node.js dependencies periodically
npm audit fix
```

### Database Security
- Ensure database file is not accessible via web
- Implement regular backups
- Consider database encryption for sensitive data

---

For questions or issues, contact the repository maintainer.
