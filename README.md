# Abraham.ai Wireframes

**Date**: October 25, 2025
**Purpose**: UI/UX wireframes for Abraham's Covenant launch
**For**: Gene, Henry, and team

## Links

- **Live Wireframes**: https://abraham-wireframes-md4rfiuqo-edenprojects.vercel.app
- **GitHub Repo**: https://github.com/brightseth/abraham-wireframes
- **Vercel Project**: https://vercel.com/edenprojects/abraham-wireframes

## What's Included

Four main wireframe views for Abraham's Covenant:

### View 1: Daily View (Sunday-Friday)
- Image-first layout (60-70% of screen)
- Day counter: "Day X of 4,074" reinforces 13-year commitment
- Countdown to next Saturday auction
- Creation title and story below image
- Minimal header: logo + About link

### View 2: Auction Day (Saturday - 7th Day)
- 7-day grid showing full week cycle
- Sunday-Friday: 6 creations on auction
- Saturday: rest day (visually distinct, no bid info)
- Real-time bid updates and countdown
- All pieces start at 0.1 ETH minimum

### View 3: Archive
- Week-based navigation to maintain covenant structure
- Browse all past weeks and auction results
- Previous/Next week controls
- Shows sold prices for completed auctions

### View 4: My Collection
- Personal gallery of won pieces
- Shows purchase price and day number
- Only visible when wallet connected

## Key Design Decisions

**✓ Implemented:**
- Image-first daily view
- Day counter reinforcing 13-year commitment
- Simplified navigation (logo = home, About = info)
- 7-day auction grid with Saturday rest day
- Week-based archive structure

**→ Future Enhancements:**
- High bidder indicator (green border)
- Easy bid increment (one-click raise)
- Sealed bids (set max bid, auto-increment)
- List view toggle
- Collection filters and stats
- Archive search

## Technical Details

- **Single-file HTML**: `index.html` (26.9 KB)
- **Framework**: Vanilla HTML/CSS/JS
- **Hosting**: Vercel
- **Responsive**: Mobile-friendly grid layouts
- **Navigation**: Anchor links with smooth scroll

## Immediate Priorities (Pre-Launch)

1. **Auction functionality** - Bidding, claiming, refunds
2. **Content reading** - IPFS vs onchain metadata display
3. **Responsive design** - Test grid layouts on mobile/tablet
4. **Saturday placeholder** - Abraham logo or rest day visual
5. **Navigation clarity** - Finalize Archive link behavior

## Open Questions

- Should clicking auction day images go to individual work page or stay in modal?
- Do we need calendar/list toggle or just one browsing mode?
- Should "My Collection" be in nav or via wallet dropdown?
- What happens to the covenant text - in About page or remain on homepage?

## Session Notes

**Created**: Oct 25, 2025
**Time**: ~10 minutes
**Tools**: Single HTML file with embedded CSS

Quickly prototyped wireframes based on design session feedback. Focused on:
- Image-first approach (art is primary)
- Week-based structure (covenant lore)
- Streamlined navigation (minimal friction)
- Clear auction mechanics (7-day cycle with rest day)

**Deployment**: Vercel auto-deploy from GitHub
**Access**: Public repo for Gene/Henry to review and modify
