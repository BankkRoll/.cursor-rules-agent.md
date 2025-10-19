# .cursor/rules/AGENTS.md

This repository contains a **Cursor `AGENTS.md` rules file** for **Next.js + ShadCN + Tailwind + Motion** development.

**About `AGENTS.md`:**  
Cursor supports custom development agents via an `AGENTS.md` file inside your `.cursor/rules` folder.  
Learn more here: [https://cursor.com/docs/context/rules#agentsmd](https://cursor.com/docs/context/rules#agentsmd)

---

### Usage

1. Copy the [`AGENTS.md`](./AGENTS.md) file from this repo.  
2. Paste it into your local project at:

```
.cursor/rules/AGENTS.md
```

3. Start coding.

#### Easy Copy-Paste Method

You can download and place the file directly into your project using one command:

**Using `curl`:**

```
mkdir -p .cursor/rules
curl -L https://raw.githubusercontent.com/BankkRoll/.cursor-rules-agent.md/main/AGENTS.md -o .cursor/rules/AGENTS.md
```

**Using `wget`:**

```
mkdir -p .cursor/rules
wget https://raw.githubusercontent.com/BankkRoll/.cursor-rules-agent.md/main/AGENTS.md -O .cursor/rules/AGENTS.md
```

This ensures the `AGENTS.md` file is in the correct location and ready for Cursor to use.

---

### About This Agent

This agent defines high-quality coding and design rules covering:

- **Next.js** implementation standards  
- **shadcn/ui** component conventions  
- **Tailwind CSS** tokens and layout structure  
- **Motion (via `motion/react`)** animation rules and restrictions  
- **UI/UX accessibility**, focus, and performance guidelines  
- **“Always Works™”** reliability and testing principles  

Use this as a solid base for maintaining a clean, production-grade development environment in Cursor.

## Contributing

Contributions are welcome! Here’s how you can help:

1. **Fork the repository** and create a new branch for your changes.
2. **Update or add rules** in `AGENTS.md` following the existing structure and conventions.
3. **Test your changes** in a local Cursor project to ensure they behave as expected.
4. **Submit a Pull Request** with a clear description of your changes.

### Guidelines

- Follow the coding, animation, and UI/UX rules defined in the current `AGENTS.md`.
- Ensure all changes are **production-ready**, tested, and maintain consistency with existing rules.
- Focus on clarity, maintainability, and performance.
- Always document any new rules or changes with clear comments.

Thank you for helping improve this development agent!

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
