![Banner saying: build your own feature flag infrastructure](/profile/assets/banner.jpg)

# 👉 What is it all about?

➡️ **Let's revolutionize the way we work with feature flags.**

Key aspects:

- 👨‍👩‍👧 Accessible for everyone for any budget!
- ✅ Availability first. Never worry about third party service outages!
- 🛡️ Own your data, control the data flow! Bye, bye, PII concerns!
- 💎 Intuitive UI. Usable by everyone.
- 🧩 Fits in your stack. Storage agnostic. Pluggable UI.
- 👉 It's your choice: The toolkit that doesn't care how you would like to do things!

# 📖 Table of contents

<!-- TOC -->
* [👉 What is it all about?](#-what-is-it-all-about)
* [📖 Table of contents](#-table-of-contents)
* [📂️ Repositories](#-repositories)
* [⭐️ The vision](#-the-vision)
* [🤩 Say hello to](#-say-hello-to)
* [👋 Say goodbye to](#-say-goodbye-to)
* [🗺️ Roadmap](#-roadmap)
* [🔭 Future ideas](#-future-ideas)
* [🙆‍♂️ Author](#-author)
<!-- TOC -->

# 📂️ Repositories

- [JavaScript/TypeScript SDK 🔗](https://github.com/Loli-Feature-Flags/loli-sdk)
- [Pluggable Management UI 🔗](https://github.com/Loli-Feature-Flags/loli-ui)

# ⭐️ The vision

You shall be able to add a powerful feature flag tooling to your own
infrastructure/tech stack. To build your own. With low costs. And low effort.

# 🤩 Say hello to

- 🤑 Low costs
- 🔐 PII sensitive tooling
- ⚡️ Low latency
- 💻 Intuitive management UI
- 📶 No third party service outages

# 👋 Say goodbye to

- 💸 High costs.
- 👩 PII data leaving your system.
- ⏳ High latency due to calls to third parties.
- 🖥️ Unintuitive management UIs.
- 🚨 Third party service outages.

# 🗺️ Roadmap

| Milestone     | Project                                 | Status           | Description                                                                                                              |
|---------------|-----------------------------------------|------------------|--------------------------------------------------------------------------------------------------------------------------|
|               | JS/TS SDK                               | Building 🟡      | A library that defines the Loli Spec schema, validates it, and can evaluate feature flags.                               |
|               | Management UI                           | Building 🟡      | A pluggable management UI that makes it easy to manage the Loli Spec and can be integrated into any website/web-app.     |
| Alpha version |                                         | Working on it 🟡 | A state where Loli can be used in a JS/TS environment using your own storage for the Loli Spec. Requires tech expertise. |
|               | Extensive documentation for developers  | Planned 📝       |                                                                                                                          |
|               | Extensive documentation for non-techies | Planned 📝       |                                                                                                                          |
|               | Tutorial videos for developers          | Planned 📝       |                                                                                                                          |
|               | Tutorial videos for non-techies         | Planned 📝       |                                                                                                                          |
| Beta version  |                                         | Planned 📝       | A state where Loli comes with docs and tutorial videos.                                                                  |
|               | OpenFeature JS/TS Adapter               | Planned 📝       |                                                                                                                          |
|               | Automated testing for management UI     | Planned 📝       |                                                                                                                          |
|               | Website                                 | Planned 📝       |                                                                                                                          |
|               | Community support (e.g. Discord Server) | Planned 📝       |                                                                                                                          |
| Version 1     |                                         | Planned 📝       | A state where Loli looks like a real project, has full test coverage, and offers an OpenFeature adapter.                 |

# 🔭 Future ideas

| Milestone | Project                                                                                | Probability | Description                                                                                                                                                                                                       |
|-----------|----------------------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|           | Diffing UI                                                                             | medium      | A pluggable UI that lets you render differences between two Loli Specs. Can be used for comparing audit log changes.                                                                                              |
|           | Loli Service                                                                           | high        | Loli UI as a service. Manage users with different rights. Audit logs. But still – own the storage by using integrations/adapters (such as Vercel Edge Config, REST, Redis, ...). Self hosted and/or as-a-service. |
|           | JSON schema based validation                                                           | low         |                                                                                                                                                                                                                   |
|           | SDKs for other languages (Java, Go, Rust, C#, ...)                                     | low         |                                                                                                                                                                                                                   |
|           | Loli server/docker image + simplified SDKs for other languages speaking to Loli Server | medium      | Keep the JS/TS SDK as the single source of truth regarding evaluation, but offer a bundled Loli server and client SDKs for other languages.                                                                       |
|           | OpenFeature adapters for other languages (Java, Go, Rust, C#, ...)                     | medium      | Possible OpenFeature adapters for the server <> client scenario (one row above).                                                                                                                                  |

# 🙆‍♂️ Author

Hey, I am Peter Kuhmann! 👋

My social profiles:

- [GitHub Profile 🔗](https://github.com/peter-kuhmann/)
- [X / Twitter 🔗](https://twitter.com/squirrel_pierre)
- [LinkedIn 🔗](https://www.linkedin.com/in/peter-kuhmann/)
