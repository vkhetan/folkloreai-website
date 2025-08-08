# FolkLore AI - Project Context for Claude

## 🎯 Project Overview

**Company**: FolkLore AI  
**Product**: Chrome extension for persistent web annotations and AI-powered knowledge management  
**Mission**: Transform scattered web research into connected, compounding intelligence  
**Tagline**: "Threads for your thoughts"

### Core Problem We Solve
Knowledge workers lose dozens of insights daily when closing browser tabs. Our brains weren't designed for the fragmented nature of web browsing. FolkLore ensures that every brilliant connection, every "aha" moment, and every perfect quote persists exactly where you found it.

### Target Audience
- Knowledge workers and researchers
- Students and academics
- Product managers and strategists
- Anyone who does extensive research on web or across various apps

## 🛠 Technical Stack

- **Frontend**: Pure HTML/CSS/JavaScript (no frameworks)
- **Hosting**: Vercel (automatic deployment on git push)
- **Architecture**: Static site with blog
- **Dependencies**: None (vanilla implementation)
- **Font**: Inter (Google Fonts)
- **Local Dev**: `python3 -m http.server 8000`

## 🎨 Brand & Design System

### Color Palette
```css
--primary: #7B3FF2      /* Main purple */
--primary-dark: #6B2FE2 /* Darker purple */
--secondary: #9333EA    /* Secondary purple */
--accent: #06b6d4       /* Cyan accent */
--light-purple: #F3E8FF /* Light purple background */
--purple-glow: rgba(123, 63, 242, 0.2)
--ink: #0a0a0a          /* Main text */
--smoke: #64748b        /* Secondary text */
--whisper: #94a3b8      /* Tertiary text */
--paper: #FFFFFF        /* White */
--dawn: #FAFBFC         /* Light gray background */
```

### Design Philosophy
- **Minimal and elegant**: Clean interfaces with generous white space
- **Purple accents**: Used sparingly for emphasis
- **Subtle animations**: Floating thoughts, fade-ins, gentle hovers
- **Typography-first**: Large, bold headlines (clamp(2.5rem, 5vw, 3.5rem))
- **Mobile-responsive**: Breakpoints at 768px and 1024px

### Visual Elements
- Floating "lost thoughts" animation in hero
- Connection graphs and network visualizations
- Animated product preview panels
- Gradient text effects on key messaging
- Subtle shadows and borders (never heavy)

## 📝 Content Strategy

### Voice & Tone
- **Philosophical**: Deep thinking about knowledge and cognition
- **Empathetic**: Understanding the frustration of lost insights
- **Visionary**: Painting a picture of collective intelligence
- **Conversational**: Accessible, not academic
- **Storytelling**: Use narratives to explain concepts

### Key Messaging Themes
1. **Digital Amnesia**: "Your browser history is an archive of forgotten brilliance"
2. **Threading Thoughts**: "Connect scattered ideas across time and tabs"
3. **Compounding Knowledge**: "Every session builds on the last"
4. **Collective Intelligence**: "The knowledge layer for 1 billion connected minds"

### Blog Post Topics
- Neuroscience of context switching
- Psychology of digital organization
- Future of AI-enhanced note-taking
- Building collective intelligence
- The shoebox problem of browser tabs

## 🚀 Product Features

### Three Core Modes
1. **📝 Annotate**
   - Highlight text on any webpage
   - Add personal notes and tags
   - Annotations persist across sessions

2. **💡 Insights**
   - AI surfaces patterns across your research
   - Connects disparate ideas automatically
   - Reveals hidden themes in your thinking

3. **💭 Brainstorm**
   - Conversational AI personas
   - Adaptive to your thinking style
   - Explore ideas through dialogue

### Unique Value Propositions
- **Persistence**: Your annotations stay on webpages forever
- **Continuity**: Pick up exactly where you left off
- **Connection**: AI threads related ideas together
- **Compounding**: Knowledge grows richer over time

## 📁 File Structure

```
folkloreai-website/
├── index.html                 # Landing page (hero, features, testimonials)
├── blog.html                  # Blog listing page
├── posts/                     # Individual blog posts
│   ├── folklore-blog-motivation.html      # Founding story
│   ├── folklore-blog-shoebox.html        # The shoebox problem
│   ├── folklore-blog-context-collapse.html # Neuroscience angle
│   ├── future-of-note-taking.html        # AI vision
│   └── folklore-north-star.html          # Collective intelligence vision
├── _internal/                 # Drafts and internal notes
│   ├── notes.txt             # Blog post ordering
│   └── ideas.html            # Future features brainstorm
├── privacy-policy.html
├── terms.html
├── 404.html
├── robots.txt
├── sitemap.xml
├── vercel.json               # Vercel configuration
└── .claude/                  # Claude-specific configs
    └── settings.local.json
```

## 💡 Vision & Philosophy

### Short-term Vision (Now)
Personal knowledge management layer for web browsing. Help individuals capture, connect, and continue their thinking across browsing sessions.

### Long-term Vision (Future)
**"The Knowledge Layer for 1 Billion Connected Minds"**
- Team knowledge that compounds across projects
- Organizational intelligence that persists
- Cross-platform thought threading
- The connective tissue for the internet's collective intelligence

### Core Beliefs
- The internet should be an extension of your mind, not a library you visit
- Your thinking shouldn't restart with every new browser session
- Knowledge compounds when properly connected
- Collective intelligence emerges from connected individual insights

## 👨‍💻 Development Guidelines

### Code Style
- **HTML**: Semantic, accessible markup
- **CSS**: Use CSS variables for all colors
- **JavaScript**: Vanilla JS, no frameworks
- **Comments**: Minimal, code should be self-documenting
- **Formatting**: 4-space indentation

### Performance Priorities
1. Fast initial load (< 2s)
2. Smooth animations (60fps)
3. Mobile-first responsive design
4. Minimal external dependencies
5. Optimized images and assets

### SEO Considerations
- Clean URLs (no .html extensions in production)
- Proper meta descriptions
- Open Graph tags for social sharing
- Maintained sitemap.xml
- Semantic HTML structure

## 🔗 Important URLs

- **Production Site**: https://folkloreai.com
- **Blog**: https://folkloreai.com/blog
- **Chrome Extension**: https://chromewebstore.google.com/detail/folklore-ai/dhhdghiloajikefeigbjckfiogpdpmen
- **Email**: hello@folkloreai.com

## 📋 Common Tasks

### Local Development
```bash
# Start local server
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Git Workflow
```bash
# Check status
git status

# Stage changes
git add .

# Commit with descriptive message
git commit -m "Update: [feature/fix/content] - description"

# Push (auto-deploys to Vercel)
git push origin main
```

### Content Updates
1. Blog posts go in `/posts/` directory
2. Update `blog.html` to list new posts
3. Follow existing HTML structure and styling
4. Test on mobile (768px) and tablet (1024px)

## ✏️ Writing Guidelines

### Headlines
- Use emotional, impactful language
- Focus on the problem, not just the solution
- Examples:
  - ✅ "Your best ideas are buried in yesterday's tabs"
  - ❌ "FolkLore saves your annotations"

### Product Descriptions
- Start with the user's pain
- Paint a picture of the solution
- Use concrete examples
- Emphasize the magical moment of rediscovery

### Call-to-Actions
- Primary: "Add to Chrome - It's Free"
- Secondary: "Start your FolkLore"
- Philosophical: "Never lose a brilliant insight again"

## 🔮 Future Roadmap

### Near-term Features
- Team workspaces
- PDF annotation support
- Mobile app (iOS/Android)
- Browser extensions (Firefox, Safari)
- Export to Notion/Obsidian
- A single workplace connecting the sessions from FolkLoRE and various other apps of yours 

### Long-term Features
- AI research assistants
- Cross-app intelligence layer
- Collaborative brainstorming spaces
- API for developers

## 🎯 When Working on This Project

### Do's
- ✅ Maintain the elegant, minimal aesthetic
- ✅ Use purple sparingly as an accent
- ✅ Focus on user emotions and pain points
- ✅ Keep animations subtle and purposeful
- ✅ Test on multiple screen sizes
- ✅ Write in a thoughtful, philosophical tone

### Don'ts
- ❌ Add heavy backgrounds or overwhelming colors
- ❌ Use technical jargon without explanation
- ❌ Create features without clear user value
- ❌ Ignore mobile responsiveness
- ❌ Write in a salesy or pushy tone

## 📊 Success Metrics

- Retention: Users returning to old annotations and for new reserach 
- Growth: New Chrome extension installs
- Connection: Number of cross-session threads created
- Value: User testimonials about rediscovered insights

## 🤝 Collaboration Notes

When assisting with this project:
1. Always consider the philosophical underpinning of features
2. Maintain consistency with the existing design language
3. Focus on the emotional journey of users losing and finding insights
4. Remember we're building for the long-term vision of collective intelligence
5. Every feature should support the core promise: "Never lose a brilliant insight again"

---

*Last Updated: August 2025*  
*This document is the source of truth for FolkLore AI development and should be updated as the project evolves.*