# How to Set Up KrisuAI/Pinaka Public Repository

This folder contains **ALL FILES** needed for https://github.com/KrisuAI/Pinaka

## 📁 What's in This Folder

```
UPLOAD_TO_PUBLIC_REPO/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml           ← Bug report form
│   │   ├── feature_request.yml      ← Feature request form
│   │   └── config.yml                ← Issue template config
│   ├── DISCUSSION_TEMPLATE/
│   │   ├── 01_announcements.yml     ← Announcement template
│   │   ├── 02_ideas.yml             ← Ideas template
│   │   └── 03_show_and_tell.yml     ← Showcase template
│   ├── CODE_OF_CONDUCT.md           ← Community rules
│   ├── CONTRIBUTING.md              ← How to contribute
│   ├── SECURITY.md                  ← Security policy
│   └── SUPPORT.md                   ← Getting help
└── README.md                        ← Main page (installation guide)
```

## 🚀 Upload Everything to GitHub

### Option 1: Via Git (FASTEST - 2 minutes)

```bash
# Clone the public repo
git clone https://github.com/KrisuAI/Pinaka.git
cd Pinaka

# Copy everything from this folder
cp -r "D:\Apps\SessionReplayTester\visual-test-builder\UPLOAD_TO_PUBLIC_REPO\*" .

# Commit and push
git add .
git commit -m "Add community templates and documentation"
git push origin main
```

### Option 2: Via GitHub Web UI (10 minutes)

1. Go to https://github.com/KrisuAI/Pinaka
2. Upload each file/folder using "Add file" → "Upload files"
3. Drag the entire `.github` folder
4. Drag `README.md`
5. Commit changes

## ⚙️ After Upload - Enable Features

### Step 1: Enable Discussions

1. **Go to:** https://github.com/KrisuAI/Pinaka/settings
2. **Scroll to "Features"**
3. **Check:** ✅ Discussions
4. **Click:** "Set up discussions"

### Step 2: Create Discussion Categories

1. **Go to:** https://github.com/KrisuAI/Pinaka/discussions
2. **Click:** "Categories" (top right)
3. **Create these 5 categories:**

#### Category 1: Announcements
- **Click "New category"**
- Name: `Announcements`
- Emoji: `📢`
- Description: `Official updates and release notes from the KrisuAI team`
- Format: **Announcement** (only maintainers can post)
- Click "Create"

#### Category 2: Q&A
- Name: `Q&A`
- Emoji: `🙏`
- Description: `Ask questions and get help from the community`
- Format: **Q&A** (allows marking answers as solutions)
- Click "Create"

#### Category 3: Ideas
- Name: `Ideas`
- Emoji: `💡`
- Description: `Share feature suggestions and improvements`
- Format: **Discussion** (open to all)
- Click "Create"

#### Category 4: Show and Tell
- Name: `Show and Tell`
- Emoji: `🎉`
- Description: `Share your test automation success stories`
- Format: **Discussion** (open to all)
- Click "Create"

#### Category 5: Tutorials
- Name: `Tutorials`
- Emoji: `📚`
- Description: `Community guides, tips, and tutorials`
- Format: **Discussion** (open to all)
- Click "Create"

### Step 3: Create Welcome Post

1. **Go to:** https://github.com/KrisuAI/Pinaka/discussions/new
2. **Category:** Announcements
3. **Title:** `Welcome to KrisuAI Pinaka Community! 🎉`
4. **Copy this:**

```markdown
Welcome to the KrisuAI Pinaka community!

We're excited to have you here. This is the place to:
- 🙏 **Ask questions** and get help
- 💡 **Share ideas** for improvements
- 🎉 **Show off** your test automation success
- 📢 **Stay updated** with announcements

## Getting Started

**New to Pinaka?**
- Install from [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=krisuai.krisuai-pinaka)
- Read the [README](https://github.com/KrisuAI/Pinaka#quick-start)

**Need Help?**
- Visit [Q&A](https://github.com/KrisuAI/Pinaka/discussions/categories/q-a)
- Check [Documentation](https://github.com/KrisuAI/Pinaka#documentation)

**Have an Idea?**
- Share in [Ideas](https://github.com/KrisuAI/Pinaka/discussions/categories/ideas)

## Community Guidelines
Please read our [Code of Conduct](https://github.com/KrisuAI/Pinaka/blob/main/.github/CODE_OF_CONDUCT.md)

Happy testing! 🚀

**KrisuAI Team**
```

5. **Click "Start discussion"**
6. **Pin it:** Click "..." menu → "Pin discussion"

### Step 4: Update Repository Settings

1. **Go to:** https://github.com/KrisuAI/Pinaka/settings
2. **Under "About" (right sidebar on main page):**
   - Description: `Visual AI Test Generation - Click to Test. That Simple.`
   - Website: `https://krisuai.com`
   - Topics: `vscode-extension`, `playwright`, `test-automation`, `visual-testing`, `no-code`
3. **Click "Save changes"**

## ✅ Verify Everything Works

Check these URLs:

1. **Bug Report:** https://github.com/KrisuAI/Pinaka/issues/new?template=bug_report.yml
2. **Feature Request:** https://github.com/KrisuAI/Pinaka/issues/new?template=feature_request.yml
3. **Discussions:** https://github.com/KrisuAI/Pinaka/discussions
4. **Q&A:** https://github.com/KrisuAI/Pinaka/discussions/categories/q-a
5. **Security:** https://github.com/KrisuAI/Pinaka/blob/main/.github/SECURITY.md

## 🎯 What Users Will See

When users visit https://github.com/KrisuAI/Pinaka:

1. **Main page** - Installation and quick start (README.md)
2. **Issues tab** - Bug reports and feature requests with templates
3. **Discussions tab** - Q&A, ideas, announcements, showcases
4. **Community files** - Code of conduct, contributing guide, security policy

## 📊 Maintenance

**Weekly:**
- Check new discussions in Q&A
- Respond to issues
- Post announcements for updates

**Per Release:**
- Create GitHub release
- Post announcement in Discussions
- Update README if needed

---

## ✨ You're Done!

Users can now:
- ✅ Report bugs with guided templates
- ✅ Request features
- ✅ Ask questions in Discussions
- ✅ Share success stories
- ✅ See community guidelines

**Total setup time:** 15-20 minutes
**Last updated:** 2025-11-16
