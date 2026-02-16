# 🎬 Rick and Morty Code Snippets

Add these snippets to your VS Code for even more interdimensional fun!

## 📝 How to Add Snippets

1. Open VS Code
2. `Cmd+Shift+P` / `Ctrl+Shift+P` → "Configure User Snippets"
3. Select your language (JavaScript, Python, etc.)
4. Copy the snippets below!

---

## 🔬 JavaScript / TypeScript Snippets

```json
{
  "Wubba Lubba Dub Dub Comment": {
    "prefix": "wubba",
    "body": [
      "// Wubba Lubba Dub Dub! - ${1:comment}",
      "$0"
    ],
    "description": "Rick's signature comment"
  },
  
  "Portal Gun Function": {
    "prefix": "portal",
    "body": [
      "/**",
      " * Opens a portal to dimension ${1:C-137}",
      " * @param {string} dimension - Target dimension",
      " * @returns {Portal} portal instance",
      " */",
      "function openPortal(dimension = '${1:C-137}') {",
      "  console.log(`🌀 Opening portal to ${dimension}...`);",
      "  ${2:// Portal logic here}",
      "  return new Portal(dimension);",
      "}",
      "$0"
    ],
    "description": "Create a portal gun function"
  },
  
  "Mr. Meeseeks Helper": {
    "prefix": "meeseeks",
    "body": [
      "const summonMeeseeks = (task) => {",
      "  console.log(\"I'm Mr. Meeseeks, look at me!\");",
      "  console.log(`Task: ${task}`);",
      "  ${1:// Complete the task}",
      "  console.log(\"Can do! ✅\");",
      "};",
      "$0"
    ],
    "description": "Summon a Mr. Meeseeks helper function"
  },
  
  "Rick's Try-Catch": {
    "prefix": "ricktry",
    "body": [
      "try {",
      "  ${1:// Risky science experiment}",
      "} catch (error) {",
      "  console.error('Aw jeez Rick, something went wrong:', error);",
      "  ${2:// Handle the disaster}",
      "}",
      "$0"
    ],
    "description": "Try-catch with Rick and Morty flair"
  },
  
  "Plumbus Class": {
    "prefix": "plumbus",
    "body": [
      "class Plumbus {",
      "  constructor() {",
      "    this.fleeb = 'rubbed';",
      "    this.schleem = 'repurposed';",
      "    this.grumbo = 'cleaned';",
      "  }",
      "  ",
      "  manufacture() {",
      "    ${1:// Everyone has a plumbus in their home}",
      "    return this;",
      "  }",
      "}",
      "$0"
    ],
    "description": "Create a Plumbus class (everyone has one)"
  },
  
  "Dimension Array": {
    "prefix": "dimensions",
    "body": [
      "const dimensions = [",
      "  'C-137',  // Rick's home dimension",
      "  'C-131',  // Doofus Rick's dimension",
      "  'C-132',  // Evil Morty's dimension",
      "  ${1:'C-???'}  // Unknown dimension",
      "];",
      "$0"
    ],
    "description": "Array of dimensions"
  },
  
  "Get Schwifty Loop": {
    "prefix": "schwifty",
    "body": [
      "// Time to get schwifty!",
      "for (let i = 0; i < ${1:10}; i++) {",
      "  console.log(`🎵 Shit on the floor! Step ${i + 1}`);",
      "  ${2:// Get schwifty logic}",
      "}",
      "$0"
    ],
    "description": "Get schwifty loop"
  },
  
  "Pickle Rick Transform": {
    "prefix": "pickle",
    "body": [
      "const pickleRick = {",
      "  scientist: 'Rick',",
      "  form: 'pickle',",
      "  reason: 'therapy avoidance',",
      "  funnyLevel: Infinity,",
      "  ",
      "  transform() {",
      "    console.log(\"I'm Pickle Rick! 🥒\");",
      "    ${1:// Funniest shit you've ever seen}",
      "  }",
      "};",
      "$0"
    ],
    "description": "Pickle Rick object"
  },
  
  "Interdimensional Cable": {
    "prefix": "cable",
    "body": [
      "const interdimensionalCable = {",
      "  channel: Math.floor(Math.random() * 137),",
      "  ",
      "  broadcast(show) {",
      "    console.log(`📺 Now showing: ${show}`);",
      "    ${1:// Random interdimensional content}",
      "  }",
      "};",
      "$0"
    ],
    "description": "Interdimensional Cable object"
  },
  
  "Council of Ricks": {
    "prefix": "council",
    "body": [
      "class CouncilOfRicks {",
      "  constructor() {",
      "    this.members = [];",
      "    this.decisions = [];",
      "  }",
      "  ",
      "  vote(proposal) {",
      "    console.log('🏛️ Council voting on:', proposal);",
      "    ${1:// Democracy for Ricks}",
      "  }",
      "}",
      "$0"
    ],
    "description": "Council of Ricks class"
  }
}
```

---

## 🐍 Python Snippets

```json
{
  "Wubba Lubba Dub Dub Comment": {
    "prefix": "wubba",
    "body": [
      "# Wubba Lubba Dub Dub! - ${1:comment}",
      "$0"
    ],
    "description": "Rick's signature comment"
  },
  
  "Portal Gun Function": {
    "prefix": "portal",
    "body": [
      "def open_portal(dimension: str = 'C-137') -> 'Portal':",
      "    \"\"\"",
      "    Opens a portal to the specified dimension",
      "    ",
      "    Args:",
      "        dimension: Target dimension (default: C-137)",
      "    ",
      "    Returns:",
      "        Portal instance",
      "    \"\"\"",
      "    print(f'🌀 Opening portal to {dimension}...')",
      "    ${1:# Portal logic here}",
      "    return Portal(dimension)",
      "$0"
    ],
    "description": "Create a portal gun function"
  },
  
  "Mr. Meeseeks Class": {
    "prefix": "meeseeks",
    "body": [
      "class MrMeeseeks:",
      "    \"\"\"I'm Mr. Meeseeks, look at me!\"\"\"",
      "    ",
      "    def __init__(self, task: str):",
      "        self.task = task",
      "        self.is_done = False",
      "        print(\"I'm Mr. Meeseeks, look at me!\")",
      "    ",
      "    def complete_task(self) -> bool:",
      "        \"\"\"Complete the assigned task\"\"\"",
      "        ${1:# Task completion logic}",
      "        self.is_done = True",
      "        print('Can do! ✅')",
      "        return True",
      "$0"
    ],
    "description": "Mr. Meeseeks helper class"
  },
  
  "Rick's Try-Except": {
    "prefix": "ricktry",
    "body": [
      "try:",
      "    ${1:# Risky science experiment}",
      "except Exception as error:",
      "    print(f'Aw jeez Rick, something went wrong: {error}')",
      "    ${2:# Handle the disaster}",
      "$0"
    ],
    "description": "Try-except with Rick and Morty flair"
  },
  
  "Plumbus Class": {
    "prefix": "plumbus",
    "body": [
      "class Plumbus:",
      "    \"\"\"Everyone has a plumbus in their home\"\"\"",
      "    ",
      "    def __init__(self):",
      "        self.fleeb = 'rubbed'",
      "        self.schleem = 'repurposed'",
      "        self.grumbo = 'cleaned'",
      "    ",
      "    def manufacture(self) -> 'Plumbus':",
      "        ${1:# Manufacturing process}",
      "        return self",
      "$0"
    ],
    "description": "Create a Plumbus class"
  },
  
  "Dimension List": {
    "prefix": "dimensions",
    "body": [
      "dimensions = [",
      "    'C-137',  # Rick's home dimension",
      "    'C-131',  # Doofus Rick's dimension",
      "    'C-132',  # Evil Morty's dimension",
      "    ${1:'C-???'}  # Unknown dimension",
      "]",
      "$0"
    ],
    "description": "List of dimensions"
  },
  
  "Pickle Rick Decorator": {
    "prefix": "pickle",
    "body": [
      "def pickle_rick(func):",
      "    \"\"\"I'm Pickle Rick! 🥒\"\"\"",
      "    def wrapper(*args, **kwargs):",
      "        print(\"I'm Pickle Rick!\")",
      "        result = func(*args, **kwargs)",
      "        print('Funniest shit ever!')",
      "        return result",
      "    return wrapper",
      "$0"
    ],
    "description": "Pickle Rick decorator"
  },
  
  "Council of Ricks": {
    "prefix": "council",
    "body": [
      "class CouncilOfRicks:",
      "    \"\"\"The governing body of the Citadel\"\"\"",
      "    ",
      "    def __init__(self):",
      "        self.members: list = []",
      "        self.decisions: list = []",
      "    ",
      "    def vote(self, proposal: str) -> bool:",
      "        print(f'🏛️ Council voting on: {proposal}')",
      "        ${1:# Democracy for Ricks}",
      "        return True",
      "$0"
    ],
    "description": "Council of Ricks class"
  }
}
```

---

## 🎨 CSS Snippets

```json
{
  "Portal Gun Colors": {
    "prefix": "portalcolors",
    "body": [
      ":root {",
      "  /* Portal Gun Dark Theme */",
      "  --portal-green: #5ce65c;",
      "  --meeseeks-blue: #00d4ff;",
      "  --mega-seeds-yellow: #ffd54f;",
      "  --rick-flask-red: #ff6b6b;",
      "  ",
      "  /* Citadel Light Theme */",
      "  --citadel-green: #2e7d32;",
      "  --council-blue: #0088cc;",
      "  --szechuan-sauce: #f57f17;",
      "  --evil-morty-red: #d32f2f;",
      "}",
      "$0"
    ],
    "description": "Rick and Morty color variables"
  },
  
  "Portal Animation": {
    "prefix": "portalani",
    "body": [
      "@keyframes portal-spin {",
      "  0% {",
      "    transform: rotate(0deg) scale(1);",
      "    opacity: 0.8;",
      "  }",
      "  50% {",
      "    transform: rotate(180deg) scale(1.1);",
      "    opacity: 1;",
      "  }",
      "  100% {",
      "    transform: rotate(360deg) scale(1);",
      "    opacity: 0.8;",
      "  }",
      "}",
      "",
      ".portal {",
      "  animation: portal-spin 2s infinite;",
      "  border: 3px solid var(--portal-green);",
      "  border-radius: 50%;",
      "}",
      "$0"
    ],
    "description": "Portal animation"
  }
}
```

---

## 💬 Comment Headers

Add these comment headers to your code files:

### JavaScript
```javascript
/**
 * ╔═══════════════════════════════════════════╗
 * ║  🔬 RICK'S INTERDIMENSIONAL LAB 🔬       ║
 * ║  Dimension: C-137                         ║
 * ║  Scientist: Rick Sanchez                  ║
 * ║  Status: Wubba Lubba Dub Dub!            ║
 * ╚═══════════════════════════════════════════╝
 */
```

### Python
```python
"""
╔═══════════════════════════════════════════╗
║  🔬 RICK'S INTERDIMENSIONAL LAB 🔬       ║
║  Dimension: C-137                         ║
║  Scientist: Rick Sanchez                  ║
║  Status: Wubba Lubba Dub Dub!            ║
╚═══════════════════════════════════════════╝
"""
```

---

## 🎯 Quick Console Logs

Add these fun console.log messages:

```javascript
// Portal Opening
console.log('🌀 Portal opening...');

// Mr. Meeseeks
console.log("👤 I'm Mr. Meeseeks, look at me!");

// Pickle Rick
console.log('🥒 IM PICKLE RICK!');

// Get Schwifty
console.log('🎵 Time to get schwifty! 🎵');

// Wubba Lubba Dub Dub
console.log('🔬 Wubba Lubba Dub Dub! 🔬');

// Dimension Jump
console.log('🚀 Jumping to dimension C-137...');

// Error
console.error('💥 Aw jeez Rick, something exploded!');

// Success
console.log('✅ Science accomplished!');
```

---

## 🎪 Usage Tips

1. **Type the prefix** (e.g., `wubba`) in your editor
2. **Press Tab or Enter** to expand the snippet
3. **Navigate placeholders** with Tab
4. **Customize** as needed!

---

**Remember:** *"Your boos mean nothing, I've seen what makes you cheer!"* - Rick

Now go forth and code with interdimensional power! 🔬✨
