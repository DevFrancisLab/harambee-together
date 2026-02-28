

# Harambee Wallet — Implementation Plan

## 1. PWA Setup & Design System
- Install `vite-plugin-pwa`, configure manifest with app name "Harambee Wallet", icons, and theme color
- Set up the custom color palette (Trust Blue #1D4ED8, Hope Green #22C55E, Warm Sand #F7F4ED, Gold #F59E0B, Dark #111827, Gray #6B7280)
- Configure friendly rounded sans-serif typography (Inter or Nunito) with large readable sizes
- Define reusable rounded card, soft shadow, and warm UI component styles

## 2. Welcome Screen
- Split layout with community illustration/imagery (helping hands, family support)
- Headline: "Raise Together. Help Faster." with subtext
- Login with Google button (mock), Instant Wallet Creation messaging
- PWA Install App button
- Warm, minimal, emotionally inviting design

## 3. Dashboard Screen
- Greeting header ("Welcome back, [Name]")
- Summary cards: My Fundraisers, Community Contributions, Wallet Balance
- Quick "Create Harambee" floating action button
- Campaign card list showing title, raised/goal amounts, progress bar, contributor count
- Large readable cards with soft shadows, mobile-money-familiar feel

## 4. Create Harambee Screen
- Simple form: Title, Story (textarea), Goal Amount, Category picker (Medical, School Fees, Community, Emergency), optional image upload
- "Create Harambee" button with reassurance message about automatic secure wallet creation
- Clean, minimal, step-by-step feel

## 5. Fundraiser Detail Screen
- Hero layout with large progress bar (raised vs goal)
- Organizer name, story, contributor list with human avatars
- Transparency badge icon
- "Donate" and "Share Link" action buttons
- Emotionally optimistic, large friendly layout

## 6. Donate Screen
- Simple amount input with quick-select preset amounts (e.g. 100, 500, 1000)
- "Confirm Contribution" button
- Success animation with "Contribution successful!" message
- No crypto jargon visible

## 7. Transparency Ledger Screen
- Clean table/list of contributions: name, amount, time, verification badge
- Blockchain proof icon (subtle, non-technical)
- Mobile-readable, trust-oriented layout

## 8. Profile Screen
- User info with auto-created wallet (minimal blockchain exposure)
- Tabs/sections: My Contributions, My Fundraisers, Settings
- Clean and simple

## 9. Navigation & Responsiveness
- Bottom tab navigation on mobile (Home, Create, Ledger, Profile)
- Sidebar navigation on desktop
- Cards stack vertically on mobile, grid on desktop
- Offline indicator bar
- All data is mock/demo data for MVP

