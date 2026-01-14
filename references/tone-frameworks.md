# Tone Frameworks for UX Writing

## Understanding Tone vs Voice

**Voice** = Your brand's consistent personality (e.g., professional, friendly, witty)
**Tone** = How voice adapts to context and user emotion

Think of voice as who you are; tone is how you adjust your communication based on the situation.

## The Four Tone Dimensions

### 1. Humor
**Spectrum:** Serious ←→ Funny

**When to be serious:**
- Error messages
- Legal/compliance content
- Financial transactions
- Security warnings
- Data loss scenarios

**When to be playful:**
- Onboarding flows
- Empty states (when appropriate)
- Gamification elements
- Celebration moments
- Non-critical updates

**Example transformations:**
- Serious: "Your payment has been processed"
- Playful: "Woohoo! Your payment went through ✨"

### 2. Formality
**Spectrum:** Formal ←→ Casual

**When to be formal:**
- B2B/enterprise products
- Healthcare applications
- Financial services
- Legal documentation

**When to be casual:**
- Consumer apps
- Social platforms
- Creative tools
- Returning user interactions
- Internal team tools

**Example transformations:**
- Formal: "Your request has been submitted successfully"
- Casual: "Got it! We'll get back to you soon"

### 3. Respectfulness
**Spectrum:** Irreverent ←→ Respectful

**When to be respectful:**
- Sensitive topics (health, finance, personal data)
- Error states (don't make light of user frustration)
- Cultural or religious content
- Accessibility features
- Customer support

**When to use lighter tone:**
- Celebrations (achievements, milestones)
- Optional features
- Social interactions
- Creative exploration
- Low-stakes decisions

**Example transformations:**
- Respectful: "We understand this is frustrating. Let us help you resolve this."
- Lighter: "Looks like something went sideways. Let's fix it together."

### 4. Enthusiasm
**Spectrum:** Matter-of-fact ←→ Enthusiastic

**When to be matter-of-fact:**
- Complex technical tasks
- Data-heavy interfaces
- Frequent/routine actions
- Professional workflows
- Critical information

**When to be enthusiastic:**
- User achievements
- Onboarding completion
- Feature discovery
- Positive outcomes
- Milestone moments

**Example transformations:**
- Matter-of-fact: "Profile updated"
- Enthusiastic: "Your profile is looking great! ✓"

## Contextual Tone Matrix

| Context | Humor | Formality | Respect | Enthusiasm | Example |
|---------|-------|-----------|---------|------------|---------|
| **Critical Error** | Serious | Formal | Respectful | Low | "Payment failed. Your card was declined. Please try a different payment method." |
| **Minor Error** | Neutral | Casual | Respectful | Low | "Hmm, this email format doesn't look quite right. Try name@example.com" |
| **Success** | Light | Casual | Positive | High | "All set! Your changes are saved ✓" |
| **Onboarding** | Light | Casual | Encouraging | Medium | "Nice! You've completed your profile. Let's explore what you can do." |
| **Legal/Terms** | Serious | Formal | Respectful | Low | "By continuing, you agree to our Terms of Service and Privacy Policy." |
| **Empty State** | Light | Casual | Neutral | Medium | "Your inbox is empty. You're all caught up!" |
| **Loading** | Neutral | Neutral | Neutral | Low | "Analyzing your data (typically 30 seconds)" |
| **Permission Request** | Neutral | Casual | Respectful | Low | "Get notified when someone responds to your comments" |
| **Warning** | Serious | Semi-formal | Respectful | Low | "This action cannot be undone. Your data will be permanently deleted." |
| **Achievement** | Fun | Casual | Celebratory | High | "You're on fire! 10 tasks completed this week 🔥" |

## Tone Adaptation by User State

### First-Time User
- More helpful and explanatory
- Enthusiastic about features
- Encouraging tone
- Explicit instructions

**Example:** "Welcome! Let's get your account set up. First, add a profile photo to help your team recognize you."

### Returning User
- Concise and efficient
- Less explanation
- Assumes familiarity
- Respects their time

**Example:** "Welcome back! You have 3 new messages."

### Frustrated User (Multiple Errors)
- Empathetic and apologetic
- Extra helpful
- No humor
- Clear next steps

**Example:** "We're sorry you're having trouble. Let's get this sorted out together. Our support team is standing by to help."

### Expert/Power User
- Technical precision acceptable
- Minimal hand-holding
- Efficiency-focused
- Advanced options visible

**Example:** "Export complete. 2,847 records exported to CSV in 1.2 seconds."

## Emotional Context Mapping

### User is Likely...

**Confused:**
- Tone: Clear, patient, helpful
- Avoid: Jargon, complexity, humor
- Example: "It looks like you're trying to [action]. Here's how to do that..."

**Frustrated:**
- Tone: Empathetic, apologetic, solution-focused
- Avoid: Blame, humor, corporate speak
- Example: "This shouldn't have happened. Here's how we'll fix it..."

**Uncertain:**
- Tone: Reassuring, specific, confidence-building
- Avoid: Vagueness, passivity, doom-and-gloom
- Example: "This will take about 5 minutes. You can save your progress anytime and continue later."

**Excited:**
- Tone: Celebratory, energetic, positive
- Avoid: Being a buzzkill, over-explaining
- Example: "Congrats! You've unlocked a new achievement 🎉"

**In a rush:**
- Tone: Concise, direct, efficient
- Avoid: Long explanations, unnecessary words
- Example: "Saved ✓"

**Worried (Security/Privacy):**
- Tone: Transparent, specific, trustworthy
- Avoid: Vagueness, dismissiveness
- Example: "We encrypt all your data with industry-standard AES-256 encryption. Your information is never shared with third parties."

## Brand Voice Archetypes

Choose a baseline voice, then adapt tone by context:

### Professional (B2B, Finance, Healthcare)
- **Baseline:** Confident, competent, trustworthy
- **Key traits:** Precise language, data-driven, formal
- **Tone range:** Serious to moderately enthusiastic
- **Example:** "Your quarterly report has been generated. Review performance metrics and export data as needed."

### Friendly (Consumer Apps, E-commerce)
- **Baseline:** Approachable, helpful, warm
- **Key traits:** Conversational, encouraging, human
- **Tone range:** Casual to enthusiastic
- **Example:** "Thanks for your order! We'll email you when it ships 📦"

### Innovative (Tech, Startups)
- **Baseline:** Forward-thinking, clever, energetic
- **Key traits:** Modern language, concise, confident
- **Tone range:** Neutral to playful
- **Example:** "Your workspace is ready. Time to build something awesome."

### Authoritative (Education, News, Research)
- **Baseline:** Knowledgeable, credible, clear
- **Key traits:** Precise terminology, thorough, objective
- **Tone range:** Serious to moderately enthusiastic
- **Example:** "Your research has been saved to your library. 127 citations indexed."

### Playful (Gaming, Creative Tools, Social)
- **Baseline:** Fun, energetic, creative
- **Key traits:** Informal, expressive, bold
- **Tone range:** Casual to very enthusiastic
- **Example:** "Nice work! You just leveled up 🎮"

## Red Flags: When Tone Goes Wrong

### Tone-Deaf Error Messages
❌ "Oops! Something broke 🤷"
✅ "Payment processing failed. Please try again or contact support."

**Why:** Playful tone minimizes serious user problems.

### False Enthusiasm
❌ "Yay! Your account is locked for security! 🎉"
✅ "Your account has been locked due to suspicious activity. Reset your password to regain access."

**Why:** Enthusiasm is inappropriate for negative outcomes.

### Inappropriate Humor
❌ "404: This page is lost in the Bermuda Triangle 🌊"
✅ "Page not found. The link may be broken or the page may have been removed."

**Why:** Humor during task failure frustrates users.

### Over-Apologizing
❌ "We're terribly, deeply sorry for any inconvenience this may cause..."
✅ "We're fixing this issue now. Your data is safe."

**Why:** Excessive apologizing erodes confidence.

## Tone Guidelines Checklist

When optimizing copy, consider the following principles:

- [ ] Tone matches user's likely emotional state
- [ ] Formality level suits the product type (B2B vs consumer)
- [ ] Humor (if used) is appropriate for the context
- [ ] Respectful toward user's time and problems
- [ ] Enthusiasm level matches the action's significance
- [ ] Consistent with established brand voice
- [ ] No tone-deaf moments (playful during errors, etc.)
