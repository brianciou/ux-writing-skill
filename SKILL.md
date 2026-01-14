---
name: ux-writing
description: UX writing guidelines for reviewing and optimizing interface copy. Use when the user asks to review, improve, or rewrite UI text including button labels, error messages, onboarding flows, or any interface copy. Apply when auditing microcopy for web apps, mobile apps, or any digital product requiring clear, user-centered communication.
---

# UX Writing

## Overview

UX writing creates clear, concise interface text that guides users through digital products. This skill provides battle-tested principles and patterns for microcopy—buttons, labels, errors, CTAs, and notifications—that reduce friction, build trust, and improve conversion.

## Core Principles

Apply these principles to all interface copy:

### 1. Be Concise
Remove every unnecessary word. Users scan rather than read.

- Edit ruthlessly: delete words until meaning changes
- Use verbs over noun phrases: "Log in to comment" not "You must log in before you can write a comment"
- Front-load objectives: "To see item properties, tap its name" not "Tap the item to see its properties"

**Example transformation:**
- Before: "Create your account to start exploring our powerful analytics platform"
- After: "Create your account"

### 2. Speak the User's Language
Eliminate jargon, acronyms, and internal terminology.

- Use present tense and active voice: "Message sent" beats "Message has been sent"
- Avoid double negatives
- Use plain, everyday language

**Bad:** "Verification failed"  
**Good:** "This email format doesn't look quite right"

### 3. Be Consistent
Uniform terminology reduces cognitive load and signals professionalism.

- If one screen says "Log in," all screens say "Log in" (not "Sign in")
- Align capitalization, punctuation, and tone across the product
- Decide on contractions, person (first/second), and how you address users

**Example:** Use "Checkout" consistently, not mixed with "Payment" or "Proceed to pay"

### 4. Use Specific, Action-Oriented CTAs
Buttons should state exactly what happens when clicked.

- Structure: verb + object
- Generic CTAs like "Next" or "Submit" cause hesitation
- Include secondary clarifying text when helpful

**Examples:**
- "Download report" (not "Continue")
- "Send invoice" (not "Submit")
- "Add to cart" (not "OK")
- "Continue to payment" + "We'll email your client a copy"

### 5. Lead with Important Information
Users decide within seconds whether to continue.

- Place the key action or benefit first
- Use headings and subheadings to guide scanning
- Apply progressive disclosure: show essential info upfront, offer "Learn more" for details
- Structure messages: goal → action, not action → goal

**Bad:** "To continue, please click the Subscribe button"  
**Good:** "Click Subscribe to continue"

### 6. Write in Active Voice
Active voice is direct, clear, and engaging.

**Passive:** "Your order has been confirmed by the system"  
**Active:** "We've confirmed your order"

Active voice makes messages clearer and more actionable by showing who does what.

### 7. Be Specific About What Happens
Give exact information to reduce uncertainty.

**Vague:** "Try again later"  
**Specific:** "System maintenance in progress. Please retry in 10 minutes"

Concrete details eliminate guesswork and build confidence.

### 8. Adopt a Conversational Tone
Write like a human, not a machine.

- Use natural, everyday language
- Vary formality based on context: playful in onboarding, empathetic in errors, professional in critical actions
- Respect user emotions: be celebratory after success, supportive during problems
- Avoid slang, idioms, or cultural references that could alienate users

**Examples by context:**
- Onboarding: "Nice! You've completed your profile"
- Error: "Something went wrong on our end. We're working on it. Please try again in a few minutes"
- Critical action: "Delete this project? This action cannot be undone"

### 9. Never Blame the User
Help users recover from errors gracefully.

Structure helpful error messages:
1. Identify what went wrong
2. Explain why (if needed)
3. Offer a clear fix

**Bad:** "Your card is invalid"  
**Good:** "Your card number is incomplete. Please re-enter all digits"

**Additional guidelines:**
- Highlight problematic fields
- Provide links to support when appropriate
- Ensure error text is associated with form fields (accessibility)
- Don't rely on color alone to convey errors

### 10. Design for Accessibility and Scanning
Make copy work for everyone.

- Use high contrast and legible fonts
- Label fields clearly—don't rely only on placeholder text
- Break long text into short paragraphs or bullet lists
- Use numerals to speed reading
- Refer to interface elements by label: "Click **Save**" not "click the button above"
- Provide alt text for icons and images

Following accessibility guidelines reduces friction for all users, not just those with disabilities.

## Practical Application Patterns

### Button CTAs by Context

**E-commerce:**
- "Add to cart" (not "Buy now" at product level)
- "Continue to payment" (not "Next")
- "Place order" (not "Submit")

**Forms:**
- "Save changes" (not "OK")
- "Send message" (not "Submit")
- "Create account" (not "Sign up")

**Confirmations:**
- "Delete project" (not "OK")
- "Cancel subscription" (not "Confirm")
- Consider the full context including modal title when writing button CTAs

### Error Message Formula

```
[What went wrong] + [Why it matters/happened] + [How to fix]
```

**Examples:**
- "Payment declined. Your bank flagged this as suspicious. Please contact your bank or try a different card."
- "File size exceeds 10MB. Compress your image or choose a smaller file."
- "This username is taken. Try adding numbers or using your email address."

### Empty State Copy

Explain what users can do, not what's missing.

**Bad:** "No data available"
**Good:** "Add your first project to get started" + [CTA: "Create project"]

### Loading & Wait States

Set expectations with specific information.

**Bad:** "Loading..."
**Good:** "Analyzing your data (typically takes 30 seconds)"

### Success Confirmation

Acknowledge completion and suggest next steps.

**Example:** "Invoice sent to client ✓" + "View in sent folder"

## UX Writing Checklist

When optimizing copy, verify the following key points:

- [ ] Every word earns its place (no redundancy)
- [ ] No jargon or internal terminology
- [ ] Consistent with existing vocabulary
- [ ] CTAs use verb + object structure
- [ ] Most important info comes first
- [ ] Active voice used (unless passive is clearer)
- [ ] Specific about what happens
- [ ] Tone matches context (playful/professional/empathetic)
- [ ] Identify the problem and provide clear solutions in error messages
- [ ] Accessible (labels, alt text, no color-only indicators)

## Resources

When you need more specific guidance on tone adaptation:

- **`references/tone-frameworks.md`** - Use when you need to adjust tone based on context (user emotion, product type, brand voice) or understand how to adapt language for different situations and emotional states
