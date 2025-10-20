# 🎨 Interactive Welcome Dashboard - Customization Guide

This guide will help you customize your new interactive GitHub profile README!

## ✨ What's Included

Your new interactive README template includes:

### 🎬 Animated Components
1. **Waving Header Banner** - Animated gradient header with your name
2. **Typing Animation** - Dynamic text that types out your introduction
3. **Contribution Snake** - Snake animation that eats your GitHub contributions
4. **Animated Footer** - Waving footer banner

### 📊 Dynamic Widgets
1. **Profile View Counter** - Tracks how many people visit your profile
2. **GitHub Stats Card** - Shows your GitHub statistics
3. **Streak Stats** - Displays your contribution streak
4. **Top Languages** - Shows your most used programming languages
5. **Activity Graph** - 365-day contribution activity graph
6. **GitHub Trophies** - Achievement badges for your accomplishments
7. **Quote of the Day** - Dynamic inspirational quote
8. **WakaTime Stats** - Coding time tracking (requires setup)
9. **Spotify Widget** - Now playing on Spotify (requires setup)

### 📝 Sections to Fill In
1. **About Me** - Personal information in YAML format
2. **Tech Stack & Tools** - Technology badges
3. **Pinned Projects** - Showcase your best repositories
4. **Social Links** - Links to your social media profiles
5. **Professional Summary** - Brief bio
6. **Current Focus & Goals** - What you're working on
7. **Recent Blog Posts** - Your latest articles

---

## 🚀 Quick Start Customization

### Step 1: Basic Information

Replace these placeholders in the header section:

```markdown
text=YOUR%20NAME%20HERE  →  text=John%20Doe
desc=Your%20Tagline%20Here  →  desc=Full%20Stack%20Developer
```

**Note:** Use `%20` for spaces in URLs!

### Step 2: Update Username

Find and replace all instances of `andrewprasetya-k` with your actual GitHub username throughout the README.

You can do this with a text editor's find-and-replace feature:
- Find: `andrewprasetya-k`
- Replace: `your-github-username`

### Step 3: Fill in About Me Section

Update the YAML block with your information:

```yaml
name: "Your Full Name"
location: "City, Country"
current_role: "Your Current Role/Title"
company: "Your Company/Organization"
interests:
  - Interest 1
  - Interest 2
  - Interest 3
experience: "X years in software development"
```

Replace the bullet points below it with your actual information.

### Step 4: Customize Tech Stack

Edit the tech stack badges to match the technologies you actually use. You can:
- Remove badges you don't use
- Add new badges from these sources:
  - [shields.io](https://shields.io)
  - [Markdown Badges Collection](https://github.com/Ileriayo/markdown-badges)

### Step 5: Update Social Links

Replace the placeholder URLs in the "Connect With Me" section:

```markdown
[LinkedIn](https://linkedin.com/in/your-username)  →  [LinkedIn](https://linkedin.com/in/johndoe)
[Twitter](https://twitter.com/your-username)  →  [Twitter](https://twitter.com/johndoe)
```

---

## 🎯 Advanced Customization

### Changing Color Themes

All the GitHub stats widgets use the `tokyonight` theme by default. You can change this by replacing `theme=tokyonight` with any of these themes:

- `dark`
- `radical`
- `merko`
- `gruvbox`
- `onedark`
- `cobalt`
- `synthwave`
- `highcontrast`
- `dracula`

Example:
```markdown
theme=tokyonight  →  theme=dracula
```

### Customizing the Typing Animation

Edit the typing animation by modifying the URL parameters:

```
lines=Welcome+to+my+GitHub+Profile!+%F0%9F%91%8B;Full+Stack+Developer+%7C+Tech+Enthusiast
```

Each line is separated by a semicolon (`;`). Add or modify lines as needed.

Parameters you can adjust:
- `size=22` - Font size
- `duration=3000` - Time to type each line (milliseconds)
- `pause=1000` - Pause between lines (milliseconds)
- `color=2E9EF7` - Text color (hex without #)

### Updating Pinned Projects

Replace the placeholder project names with your actual repository names:

```markdown
repo=project-1  →  repo=awesome-app
repo=project-2  →  repo=cool-website
```

If the repository doesn't exist yet, the card will show an error. You can remove these sections or add more pinned project cards.

---

## 🐍 Setting Up the Snake Animation

The snake animation is already configured! Here's what happens:

1. **Automatic Generation**: The GitHub Action (`.github/workflows/snake.yml`) runs every 12 hours
2. **Manual Trigger**: You can manually trigger it from the Actions tab
3. **Output Branch**: The animation is saved to an `output` branch

### First-Time Setup

After you push this code to your repository:

1. Go to your repository on GitHub
2. Click on "Actions" tab
3. Click on "Generate Snake Animation" workflow
4. Click "Run workflow" button
5. Wait for it to complete (takes about 1 minute)

The snake will now appear in your README!

### Troubleshooting Snake Animation

If the snake doesn't show up:
- Make sure the workflow has run at least once
- Check that the `output` branch was created
- Verify the workflow has write permissions (should be automatic)

---

## 🎵 Optional: Setting Up Spotify Widget

To show what you're currently playing on Spotify:

1. Visit [Novatorem](https://github.com/novatorem/novatorem)
2. Follow their setup instructions
3. Deploy to Vercel
4. Update the URL in your README

---

## ⏱️ Optional: Setting Up WakaTime Stats

To show your coding time statistics:

1. Sign up at [WakaTime](https://wakatime.com)
2. Install WakaTime plugin in your code editor
3. Get your WakaTime username
4. Replace `andrewprasetya-k` with your WakaTime username in the stats URL

---

## 📝 Optional: Auto-Update Blog Posts

To automatically show your latest blog posts:

1. Create a file `.github/workflows/blog-post-workflow.yml`
2. Use the [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow) action
3. Add your blog RSS feed URL
4. The workflow will automatically update your README with new posts

Example workflow:

```yaml
name: Latest blog post workflow
on:
  schedule:
    - cron: '0 */6 * * *'
  workflow_dispatch:

jobs:
  update-readme-with-blog:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          feed_list: "https://your-blog.com/feed.xml"
```

---

## 🎨 Color Customization Reference

### Header & Footer Banner Colors

The header and footer use `customColorList=6,11,20`. These numbers correspond to:
- 6, 11, 20 = Blue-Purple gradient

You can change these numbers (0-30) to get different color combinations.

### Custom Color Schemes

For consistent theming, here are matching color combinations:

**Dark Blue Theme:**
- Background: `0D1117`
- Title: `58A6FF`
- Text: `C9D1D9`
- Accent: `1F6FEB`

**Purple Theme:**
- Background: `1a1b27`
- Title: `bb9af7`
- Text: `a9b1d6`
- Accent: `7aa2f7`

**Green Theme:**
- Background: `0d1117`
- Title: `39d353`
- Text: `c9d1d9`
- Accent: `238636`

---

## 📋 Checklist: Final Steps

After customizing, go through this checklist:

- [ ] Updated name in header
- [ ] Updated tagline in header
- [ ] Replaced all instances of username
- [ ] Filled in "About Me" section
- [ ] Customized tech stack badges
- [ ] Updated social media links
- [ ] Added real pinned project names (or removed section)
- [ ] Updated professional summary
- [ ] Filled in current focus & goals
- [ ] Ran snake animation workflow at least once
- [ ] Removed/updated blog posts section
- [ ] Tested all links
- [ ] Removed the "Customization Guide" section from README (optional)
- [ ] Deleted this CUSTOMIZATION_GUIDE.md file (optional)

---

## 💡 Tips & Tricks

1. **Keep it Updated**: Regularly update your "Current Focus & Goals" section
2. **Quality Over Quantity**: Don't add every possible widget - choose what represents you best
3. **Test on Mobile**: View your profile on mobile to ensure it looks good
4. **Consistent Theme**: Use the same color theme across all widgets for a cohesive look
5. **Real Projects**: Only showcase projects you're proud of
6. **Active Social Links**: Only include social media you actually use

---

## 🆘 Common Issues & Solutions

### Stats Cards Not Showing
- **Issue**: GitHub stats card shows an error
- **Solution**: Make sure your profile is public and you have some commits

### Snake Animation Not Appearing
- **Issue**: Snake shows 404 error
- **Solution**: Run the workflow manually from Actions tab first

### Badges Not Displaying
- **Issue**: Tech stack badges don't show up
- **Solution**: Check that the badge URLs are correct (no typos)

### Profile Views Counter Not Working
- **Issue**: View counter doesn't increment
- **Solution**: This is normal - it only counts external views, not your own

---

## 📚 Additional Resources

- [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [Shields.io Badge Guide](https://shields.io)
- [Markdown Badges Collection](https://github.com/Ileriayo/markdown-badges)
- [GitHub Stats Card](https://github.com/anuraghazra/github-readme-stats)

---

## 🎉 You're All Set!

Your interactive GitHub profile README is ready to impress! Remember to:
1. Save and commit your changes
2. Push to your GitHub profile repository
3. View your profile to see the result
4. Share it with the world! 🚀

**Happy Coding!** ☕️💻
