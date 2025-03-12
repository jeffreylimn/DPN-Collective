

```markdown
# How to Contribute to DPN Collective

Thank you for your interest in building the future of decentralized computing!  
This guide will help you start contributing, even if you're new to open-source.

---

## Code Style Guidelines
- **Language**: All code and comments must be in **English**  
  (Non-English discussions are welcome in [GitHub Discussions](https://github.com/jeffreylimn/DPN-Collective/discussions))
- **Formatting**:  
  - JavaScript/TypeScript: Use [Prettier](https://prettier.io/) with default settings  
  - Solidity: Follow [Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html)
- **Naming Conventions**:  
  - Variables: `camelCase` (e.g., `userHashRate`)  
  - Functions: Verb-based names (e.g., `calculateReward()`)  
  - Constants: `UPPER_SNAKE_CASE` (e.g., `MAX_NODES`)

---

## Contribution Workflow

### 1. First-Time Setup
```bash
# Fork the repository
git clone https://github.com/your-username/DPN-Collective.git
cd DPN-Collective
npm install
```

### 2. Creating a Pull Request (PR)
1. Create a feature branch:  
   ```bash
   git checkout -b feat/your-feature-name
   ```
2. Make changes and test:  
   ```bash
   npm test  # Run test suite
   ```
3. Commit changes:  
   ```bash
   git commit -m "feat: add anti-ASIC validation module"
   ```
4. Push and create PR:  
   - Go to your fork on GitHub → Click "Pull Request"  
   - Use this PR title format: `[Type] Short description`  
     - Types: `feat|fix|docs|test|refactor`

---

## Testing Requirements
- **Unit Tests**: Required for all new logic  
  Example test file: `/test/hashRateValidator.test.js`
- **Integration Tests**: Required for protocol changes  
  ```bash
  npm run test:integration
  ```
- **Performance Tests**: For time-sensitive modules (VDF/zk-SNARKs)  
  ```bash
  npm run benchmark
  ```

---

## Community Standards
### Reward System
- **Governance Rights**:  
  Valid contributions earn governance points tracked via [Soulbound Tokens](https://vitalik.ca/general/2022/01/26/soulbound.html)
- **Badge System**:  
  ![Contributor Tier](https://img.shields.io/badge/Contributor-Bronze-gold)  
  Earn NFT badges based on contribution value (see [Badge Criteria](./BADGE_CRITERIA.md))

### Communication Channels
| Purpose                     | Channel                          |
|-----------------------------|----------------------------------|
| Technical Discussions        | GitHub Issues                   |
| Quick Questions              | [Discussions](https://github.com/jeffreylimn/DPN-Collective/discussions) |
| Security Reports             | dpnprotocol@hotmail.com (PGP)   |

---

## Good First Issues
Start with these beginner-friendly tasks:  
[🔧 Good First Issues](https://github.com/jeffreylimn/DPN-Collective/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)




