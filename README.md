<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a id="readme-top"></a>

<!--
*** Thanks for checking out the KIZO Organization Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/kizo-org">
    <img src="https://avatars.githubusercontent.com/u/234577620?s=400&u=a60b2a5e1b517fc583f069800ec9203d096c61dc&v=4" alt="KIZO Logo" width="80" height="80">
  </a>

  <h3 align="center">KIZO Organization</h3>

  <p align="center">
    Your platform for amazing events and workshops!
    <br />
    <a href="https://github.com/kizo-org"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://kizo-app.vercel.app">View Demo</a>
    &middot;
    <a href="https://github.com/kizo-org/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/kizo-org/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Key Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#environment-setup">Environment Setup</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

![KIZO Event Platform Screenshot](/images/screenshot.png)

KIZO is a comprehensive event management platform designed to simplify the process of creating, organizing, and attending events. Whether you're organizing workshops, conferences, meetups, or social gatherings, KIZO provides all the tools you need in one place.

Here's why KIZO stands out:

- 🎯 **Focus on Event Creation**: Easy-to-use tools for event organizers
- 🚀 **Modern Technology Stack**: Built with Next.js, Supabase, and Tailwind CSS
- 🔥 **Real-time Updates**: Live event updates and notifications
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile
- 🎨 **Beautiful UI**: Clean, modern interface with dark/light theme support
- 🔒 **Secure Authentication**: Robust user management and admin controls

### Key Features

- **Event Management**: Create, edit, and manage events with detailed information
- **User Registration**: Secure authentication system with email verification
- **Admin Dashboard**: Comprehensive admin panel for event management
- **Event Discovery**: Search and filter events by type, location, and keywords
- **Responsive Calendar**: Interactive calendar view for better event planning
- **Dark Theme Support**: Modern UI with theme switching capabilities
- **Real-time Analytics**: Track event performance and user engagement

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project is built with modern web technologies to ensure performance, scalability, and developer experience.

- [![Next.js][Next.js]][Next-url]
- [![React][React.js]][React-url]
- [![TypeScript][TypeScript]][TypeScript-url]
- [![Tailwind CSS][TailwindCSS]][TailwindCSS-url]
- [![Supabase][Supabase]][Supabase-url]
- [![Vercel][Vercel]][Vercel-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later)
- npm or yarn
- Git

```sh
# Check Node.js version
node --version

# Check npm version
npm --version
```

### Installation

1. Clone the repository

   ```sh
   git clone https://github.com/kizo-org/[project-name].git
   cd [project-name]
   ```

2. Install dependencies

   ```sh
   npm install
   # or
   yarn install
   ```

3. Set up environment variables

   ```sh
   cp .env.example .env.local
   ```

4. Configure your environment variables (see Environment Setup)

5. Run the development server

   ```sh
   npm run dev
   # or
   yarn dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser

### Environment Setup

Create a `.env.local` file with the following variables:

```env
# Supabase Configuration
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key

# Database Configuration
DATABASE_URL=your_database_url

# Optional: Email Configuration
SMTP_HOST=your_smtp_host
SMTP_PORT=587
SMTP_USER=your_email
SMTP_PASSWORD=your_password

# Optional: Analytics
NEXT_PUBLIC_GA_ID=your_google_analytics_id
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

KIZO can be used for various event management scenarios:

### For Event Organizers

- Create detailed event pages with rich descriptions
- Manage attendee registrations
- Send automated confirmations and reminders
- Track event analytics and engagement

### For Attendees

- Browse and search for events
- Register for multiple events
- Receive calendar invitations
- Get updates about event changes

### For Organizations

- Centralized event management
- Brand customization
- Advanced reporting and analytics
- Multi-admin support

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Basic event creation and management
- [x] User authentication and authorization
- [x] Event discovery and search
- [x] Admin dashboard
- [x] Responsive design with theme support
- [ ] Advanced reporting and analytics
- [ ] Email marketing integration
- [ ] Multi-language support
- [ ] Mobile app (React Nasifcation)
- [ ] Payment integration
- [ ] Video streaming integration
- [ ] Calendar synchronization
- [ ] Social media integration

See the [open issues](https://github.com/kizo-org/[project-name]/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow the existing code style
- Write tests for new features
- Update documentation as needed
- Ensure responsive design compliance
- Test across different browsers

### Top contributors:

<a href="https://github.com/kizo-org/[project-name]/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kizo-org/[project-name]" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

**KIZO Organization** - [@kizo_org](https://twitter.com/kizo_org) - contact@kizo.org

🏢 **Organization Link**: [https://github.com/kizo-org](https://github.com/kizo-org)
🌐 **Website**: [https://kizo-app.vercel.app](https://kizo-app.vercel.app)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

This project was built with the help of these amazing resources and communities:

- [Next.js Documentation](https://nextjs.org/docs) - Amazing React Framework
- [Supabase Documentation](https://supabase.com/docs) - Open Source Firebase Alternative
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [Lucide React](https://lucide.dev) - Beautiful & consistent icon toolkit
- [shadcn/ui](https://ui.shadcn.com) - Beautiful and accessible React components
- [Vercel](https://vercel.com) - Deploy Next.js applications
- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- Shields -->

[contributors-shield]: https://img.shields.io/github/contributors/kizo-org/[repository].svg?style=for-the-badge&color=blue
[contributors-url]: https://github.com/kizo-org/[repository]/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/kizo-org/[repository].svg?style=for-the-badge&color=green
[forks-url]: https://github.com/kizo-org/[repository]/network/members
[stars-shield]: https://img.shields.io/github/stars/kizo-org/[repository].svg?style=for-the-badge&color=yellow
[stars-url]: https://github.com/kizo-org/[repository]/stargazers
[issues-shield]: https://img.shields.io/github/issues/kizo-org/[repository].svg?style=for-the-badge&color=red
[issues-url]: https://github.com/kizo-org/[repository]/issues
[license-shield]: https://img.shields.io/github/license/kizo-org/[repository].svg?style=for-the-badge&color=purple
[license-url]: https://github.com/kizo-org/[repository]/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kizo-org

<!-- Screenshots -->

[product-screenshot]: https://via.placeholder.com/800x400/1f2937/ffffff?text=KIZO+Event+Platform

<!-- Technology Badges -->

[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[TypeScript]: https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org/
[TailwindCSS]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[TailwindCSS-url]: https://tailwindcss.com/
[Supabase]: https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white
[Supabase-url]: https://supabase.com/
[Vercel]: https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white
[Vercel-url]: https://vercel.com/
