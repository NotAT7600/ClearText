# ClearText – Cognitive Personalization Engine

## Overview

ClearText is a cognitive personalization engine that adapts digital content to match a user’s cognitive preferences.

Many users experience digital overload due to dense text, complex layouts, or overwhelming instructions. ClearText reduces these barriers by transforming content into a format aligned with how an individual processes information.

This project was built during the Grizzly Hacks 24-hour hackathon.

---

## What It Does

ClearText can:

- Adapt webpages via URL
- Adapt pasted text
- Generate personalized image captions
- Adjust reading complexity
- Change structure (step-by-step, bullets, paragraph)
- Reduce emotional tone
- Limit information chunk size
- Generate executive summaries
- Extract key actions
- Explain confusing terms
- Display a cognitive load score

---

## Project Architecture

This repository contains two applications:

### ClearText Application
Folder: `ClearText-Code/`

This is the main adaptation engine built using Base44.

It:
- Accepts user content (URL, text, or image)
- Applies cognitive profile settings
- Rewrites content to match user preferences
- Displays cognitive load metrics
- Generates structured outputs

Live Demo:
https://clear-text-ai-e34fdac2.base44.app/

---

### Cognitive Profile Generator
Folder: `Profile-Generator/`

Built using MeDo (sponsor platform).

This application:
- Asks users questions about reading preferences
- Generates a structured cognitive profile
- Automatically redirects to ClearText
- Passes profile settings via URL parameters

This demonstrates sponsor integration and dynamic personalization.

---

## How They Work Together

1. User completes assessment in Profile Generator (MeDo).
2. A cognitive profile is generated.
3. The user is redirected to ClearText.
4. ClearText automatically applies the profile settings.
5. Content is adapted to match the user's preferences.

System Flow:

User → MeDo Profile Generator → URL Redirect → ClearText Engine → AI Transformation → Personalized Output

---

## 🛠 Tech Stack

- React + Vite
- TailwindCSS
- AI-powered content transformation
- Base44 deployment
- MeDo integration

---

## Hackathon Criteria Alignment

Impact & Accessibility:
ClearText reduces digital cognitive barriers and increases independence.

Functionality:
Fully working multimodal adaptation engine with dynamic profile application.

User Experience:
Accessible UI, cognitive load indicators, structured formatting options.

Innovation:
Deep-link integration between MeDo and ClearText enables automated cognitive personalization.

---

## Repository Structure
ClearText-Code/
Profile-Generator/
README.md


---

## Team

Built for Grizzly Hacks 2025.


