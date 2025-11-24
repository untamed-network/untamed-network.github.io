# Minecraft Server Website Design Guidelines

## Design Approach
**Reference-Based + Gaming Aesthetic**: Drawing inspiration from modern gaming community sites (Hypixel, Mojang) combined with Discord's clean interface design. The Minecraft pixel aesthetic will be balanced with contemporary web design for credibility and usability.

## Core Design Principles
- **Blocky Elegance**: Incorporate Minecraft's iconic pixel/block aesthetic through subtle geometric patterns, not overwhelming retro elements
- **Community Focus**: Emphasize social proof, player engagement, and server vitality
- **Clear Hierarchy**: Gaming sites must balance excitement with information clarity

## Typography System
- **Primary Font**: "Minecraft" or "Press Start 2P" (Google Fonts) for headers and branding elements
- **Secondary Font**: Inter or Roboto for body text to maintain readability
- **Hierarchy**: 
  - H1: 3xl-4xl (hero titles, page headers)
  - H2: 2xl-3xl (section headers)
  - H3: xl-2xl (subsection titles)
  - Body: base-lg (readable paragraphs)
  - Small: sm (metadata, captions)

## Layout & Spacing System
**Spacing Units**: Tailwind 4, 6, 8, 12, 16, 24 for consistent rhythm
- Section padding: py-16 to py-24
- Component spacing: gap-6 to gap-8
- Container max-width: max-w-7xl with px-4 to px-6

## Page-Specific Layouts

### Homepage
**Hero Section** (70-80vh):
- Large background image: Dramatic Minecraft server landscape/build showcase
- Centered content: Server name, tagline, player count display
- Dual CTA buttons: "Join Server" (primary) and "View Info" (secondary) with blur background
- Floating stats cards: Online players, total members, uptime

**Feature Grid** (3 columns desktop, 1 mobile):
- Server highlights with Minecraft-style icons
- Each card: Icon, title, description
- Subtle hover lift effect

**Community Showcase**:
- Screenshot gallery (masonry or grid layout)
- Player testimonials with Discord-style avatars
- Recent server updates feed

### Information Page
**Two-Column Split**:
- Left: Navigation sidebar with anchor links to sections
- Right: Content sections (Server Features, Gameplay Modes, Rules, Getting Started)
- Icon-enhanced lists throughout
- Expandable/collapsible sections for detailed info

### Donations Page
**Tiered Layout**:
- Pricing cards in 3-4 column grid
- Each tier: Featured badge for popular option, benefits list with checkmarks, price display, donation CTA
- Benefits comparison table below tiers
- Trust indicators: Secure payment badges, donor count
- FAQ section addressing donation concerns

### Credits Page
**Team Showcase**:
- Grid layout (3-4 columns) for staff members
- Each card: Minecraft skin/avatar, name, role, description
- Separate sections: Administrators, Moderators, Developers, Contributors
- Special recognition section for major contributors

### FAQ Page
**Accordion Pattern**:
- Category tabs or sections (General, Gameplay, Technical, Donations)
- Expandable question cards with smooth animations
- Search/filter functionality placeholder
- "Still have questions?" CTA linking to Discord/support

## Component Library

### Navigation
- Sticky header with logo left, nav links center, Discord/Join buttons right
- Mobile: Hamburger menu with smooth slide-in
- Active page indicator with underline or background highlight

### Cards
- Rounded corners (rounded-lg to rounded-xl)
- Subtle shadows with hover elevation
- Border treatment with gradient accents on featured items

### Buttons
- Primary: Solid fill with hover scale (1.02-1.05)
- Secondary: Outlined with hover fill
- Icon buttons: Circular or square with icon-only
- CTA buttons on images: Backdrop blur with semi-transparent background

### Forms (Donation Page)
- Input fields with subtle borders and focus states
- Clear labels and helper text
- Success/error states with color-coded feedback

### Stats/Metrics Display
- Large numbers with labels
- Animated counters (subtle)
- Icon accompaniment

## Images Strategy

**Hero Images**: 
- Homepage: Epic server build or landscape (full-width, 70-80vh)
- Each page: Smaller hero banners (40-50vh) with relevant Minecraft imagery

**Supporting Images**:
- Gallery section: 6-8 screenshots in masonry grid
- Feature icons: Minecraft-themed custom icons or Font Awesome with pixel styling
- Team avatars: Minecraft player skins (square format)
- Background patterns: Subtle grass block textures or pixel patterns in sections

**Image Treatment**: 
- Slight gradient overlays on hero images for text readability
- Rounded corners on content images (rounded-lg)
- Subtle parallax on hero backgrounds

## Visual Enhancements
- **Animations**: Minimal - fade-in on scroll, subtle hover states, smooth page transitions
- **Patterns**: Minecraft grass/dirt block patterns as subtle background textures in specific sections
- **Gradients**: Use green-to-blue gradients on dividers, buttons accents, or section backgrounds (sparingly)
- **Shadows**: Layered shadows for depth on elevated components

## Accessibility
- Maintain WCAG AA contrast ratios for all text
- Keyboard navigation support
- Alt text for all images
- Focus indicators on interactive elements
- Readable font sizes (minimum 16px body text)

## Responsive Behavior
- Mobile: Single column, stacked navigation, touch-friendly targets (min 44px)
- Tablet: 2-column grids, condensed spacing
- Desktop: Full layouts, hover effects active
- Breakpoints: Standard Tailwind (sm, md, lg, xl)