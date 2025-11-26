PasswordStrengthChecker/
│
├── index.html            → Home page
├── strength.html         → Password checker UI
├── feedback.html         → Rating + feedback submission
│
├── style/
│   ├── main.css
│   ├── home.css
│   ├── strength.css
│   └── feedback.css
│
├── scripts/
│   ├── main.js           → Real-time strength logic & UI binding
│   ├── strength.js       → Password scoring logic
│   ├── policy.js         → Rule validation (length, uppercase, etc.)
│   ├── breachCheck.js    → HaveIBeenPwned API checker
│   ├── entropyCrack.js   → Entropy & crack time calculation
│   ├── generator.js      → Random password generator
│   └── meterAndTips.js   → Canvas meter + improvement tips
└── images/               → Icons / assets (if any)
