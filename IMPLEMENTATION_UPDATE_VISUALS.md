# Implementation Plan: Premium Visual Updates for Autonova Landing Page

This plan outlines the visual enhancements for the Autonova landing page (`index.html`) to transform it into a premium, modern, and highly-interactive B2B AI Automation Lead Gen Landing Page. 

The update focuses on:
* **Premium Color Palette & Typography**: Polishing the gold/charcoal theme, incorporating Outfit/Inter font pairing, and ensuring consistent type scales.
* **Glassmorphism**: Enhancing the navigation and cards with blurred backdrops and subtle borders.
* **Dynamic Animations**: Adding floating background blobs, card lift effects, and micro-interactions.
* **Progress Tracking**: Including a cross-agent tracking checklist for coordinated development.

---

## Proposed Changes

### Core Styles & Layout

#### [MODIFY] [index.html](file:///Users/charlie/Github/B2B-AI-Automation-Lead-Gen-Landing-Page/index.html)
* **Design Tokens & Variable Overhaul**:
  * Fine-tune HSL colors for gradients: `--gold-primary: hsl(40, 65%, 48%)`, `--gold-accent: hsl(40, 75%, 58%)`, and deep slate/charcoal colors.
  * Integrate font-family `'Outfit', sans-serif` for headers and `'Inter', sans-serif` for body text.
* **Hero Section enhancements**:
  * Adjust radial-gradients for the background blobs to ensure subtle and smooth animated movement.
  * Elevate the visual weight of the primary header and CTA button with premium border-image gradients.
* **Component Improvements**:
  * Apply glassmorphism styling (`backdrop-filter`, `border: 1px solid rgba(255, 255, 255, 0.05)`) to cards in the "Who This Is For" and "How It Works" sections.
  * Modernize the lead generation form inputs with smooth transition scaling and animated validation states.

---

## Walkthrough Checklist

Use the checklist below to track progress across development turns and AI agents.

### Phase 1: Setup & Design Verification
- [ ] Verify Vite local development environment runs properly (`npm run dev`)
- [ ] Review current layout spacing, media queries, and responsive breaks
- [ ] Back up the original `index.html` file

### Phase 2: Color System & Glassmorphism
- [ ] Update CSS variables to use premium HSL palette with satin metallic tones
- [ ] Apply glassmorphism styling to the sticky `.nav` header
- [ ] Add glassmorphism to cards in the `.for-section` and `.how-section`
- [ ] Customize scrollbar styling to match the dark/gold theme

### Phase 3: Animations & Micro-Interactions
- [ ] Implement smooth drifting animations for the backdrop blur blobs
- [ ] Add transition states (magnetic lift + border glow) to all buttons and cards
- [ ] Enhance checklist hover states and check/uncheck transitions
- [ ] Add subtle pulse indicators for input fields on focus

### Phase 4: Verification & Polish
- [ ] Verify styling on mobile and desktop layout sizes
- [ ] Check cross-browser rendering compatibility of backdrop-filters
- [ ] Verify form validation flow works as expected

---

## Verification Plan

### Automated Verification
* Run Vite build command (`npm run build`) to ensure there are no compilation errors.

### Manual Verification
* Run local dev server (`npm run dev`) and test page visually:
  * Verify glassmorphic elements blur background properly.
  * Ensure drifting blobs run at 60fps without causing stutter.
  * Confirm responsive layout sizes.
