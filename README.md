# 🚀 Hacktoberfest Meetup Phagwara 2026

<p align="center">
  <img src="https://img.shields.io/badge/Hacktoberfest-2026-orange?style=for-the-badge" alt="Hacktoberfest 2026" />
  <img src="https://img.shields.io/badge/Open%20Source-For%20Everyone-blue?style=for-the-badge" alt="Open Source for Everyone" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge" alt="Contributions Welcome" />
</p>

<p align="center">
  The official website and community contribution hub for Hacktoberfest Meetup Phagwara, hosted by AWS Student Builder Group at Lovely Professional University.
</p>

<p align="center">
  <a href="https://hacktoberfest-phagwara.vercel.app/"><strong>🌐 Visit the Website</strong></a>
  ·
  <a href="https://github.com/shashankpandey04/hacktoberfest-meetup-phagwara/issues">Explore Issues</a>
  ·
  <a href="CONTRIBUTING.md">Contributing Guide</a>
</p>

---

## 🌱 About the Project

Hacktoberfest Meetup Phagwara brings students, developers, and open-source enthusiasts together to learn, build, collaborate, and explore the world of open source.

This repository powers our official event website and provides a place for the community to contribute.

Whether you're an experienced developer or making your first pull request, you're welcome here!

**Our goal is simple: make open source more accessible, one contribution at a time.**

## 🎯 What's Inside?

- **Event Website:** The official online home for Hacktoberfest Meetup Phagwara.
- **Event Information:** Details about the meetup, sessions, speakers, and activities.
- **Attendee Wall:** A community showcase featuring contributors who add their profiles to the repository.
- **Open-Source Contributions:** An opportunity to experience the real-world GitHub workflow by contributing to a community project.

## 👥 Join the Attendee Wall

Want to become part of our community showcase?

Add your profile to the attendee directory and let the world know you contributed to the project!

Every accepted contribution can add another face to our growing community.

### How to Add Your Profile

1. **Fork** this repository.
2. Create a JSON file inside `app/attendees/`.
3. Name the file after your GitHub username, such as `octocat.json`.
4. Add your profile information using the format below.
5. Commit your changes and push them to your fork.
6. Open a pull request to this repository.
7. Wait for the organizers to review your contribution.

### Profile Format

Create a file such as `app/attendees/octocat.json`:

```json
{
  "fullName": "Your Full Name",
  "githubUsername": "octocat",
  "pfpUrl": "https://github.com/octocat.png"
}
```

Replace the example values with your own information.

**Contribution guidelines:**
- Add only your own profile.
- Use your actual GitHub username as the filename.
- Follow the JSON format shown above.
- Do not modify another contributor's profile.
- Check that your profile doesn't already exist.
- Keep your pull request focused on your contribution.

For detailed instructions, read [CONTRIBUTING.md](CONTRIBUTING.md).

> Your profile will be eligible to appear on the live website after your pull request is reviewed and merged, provided the attendee showcase is configured to load it.

## 🛠️ Tech Stack

The current application is built with:

- **Next.js 16** — App Router and server-rendered pages
- **React 19** — UI components
- **TypeScript 5** — typed application code
- **Tailwind CSS 4** — styling
- **ESLint 9** — code-quality checks
- **Vercel** — production hosting

## 💻 Local Development

Want to run the website locally or help improve it?

### Prerequisites

- Git
- Node.js 20.9 or newer
- npm (included with Node.js)

### Setup

Clone the repository:

```bash
git clone https://github.com/shashankpandey04/hacktoberfest-meetup-phagwara.git
cd hacktoberfest-meetup-phagwara
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL printed by Next.js (usually `http://localhost:3000`).

### Available checks

```bash
npm run lint
npm run build
```

Run the lint check before opening a pull request. The production build also catches route, TypeScript, and bundling errors.

## 🤝 Contributing

We welcome contributions from developers of all experience levels!

You can help by:

- Adding your profile to the attendee wall.
- Improving the website's design and accessibility.
- Fixing bugs and improving existing features.
- Enhancing documentation.
- Suggesting new ideas for the community.

Before contributing, please read our [Contributing Guide](CONTRIBUTING.md).

For bugs or feature requests, open an issue in the repository.

Please keep contributions relevant, useful, and respectful of the community.

## 💙 About the Organizers

Hacktoberfest Meetup Phagwara is hosted by **AWS Student Builder Group at Lovely Professional University**.

We bring developers together through community events, technical sessions, hands-on learning, and opportunities to build with modern technologies.

Learn more about our community:

- 🌐 Website: [awslpu.in](https://awslpu.in/)
- 📢 WhatsApp Channel: [Join our community](https://whatsapp.com/channel/0029Vb92tww0lwghsnwSlQ3A)
- 💻 GitHub: [Explore this repository](https://github.com/shashankpandey04/hacktoberfest-meetup-phagwara)

## 📜 License

This project is open source. Refer to the repository's `LICENSE` file for the applicable license and permissions.

If you're contributing, please ensure that your contributions can be distributed under the project's license.

---

<p align="center">
  Built with 💙 by the community, for the community.
  <br />
  <strong>Learn. Build. Collaborate. Contribute.</strong>
</p>
