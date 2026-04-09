# Vaultr Style Guide

## Brand Identity
- **Name**: Vaultr
- **Tagline**: Wealth Intelligence Platform
- **Personality**: Precise, institutional, zero-emotion, premium

## Color Palette
- **Primary Gold**: `#c9a84c` (accent, CTAs, highlights)
- **Background**: `#0a0a0f` (near-black)
- **Text Primary**: `rgba(255,255,255,0.9)`
- **Text Secondary**: `rgba(255,255,255,0.6)`
- **Text Muted**: `rgba(255,255,255,0.4)`
- **Profit**: `#34d399` (emerald-400)
- **Loss**: `#f87171` (red-400)
- **Warning**: `#fbbf24` (yellow-400)

## Glassmorphism System
```css
.glass {
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(20px);
  border-radius: 1rem;
}

.glass-subtle {
  background: rgba(255, 255, 255, 0.02);
  border: 1px solid rgba(255, 255, 255, 0.05);
  backdrop-filter: blur(10px);
  border-radius: 0.75rem;
}
```

## Typography
- **Font**: Inter (sans-serif)
- **Mono**: JetBrains Mono (code, numbers)
- **Headings**: Bold (700), white
- **Body**: Regular (400), white/60-90
- **Labels**: Semi-bold (600), white/50, uppercase tracking-wider

## Animations
- `fade-in-up`: 0.5s ease-out, translate + opacity
- `pulse-ring`: 2s ease-out infinite, expanding ring
- `glow-pulse`: 3s ease-in-out infinite, gold box-shadow
- `scroll`: 30s linear infinite, horizontal ticker

## Component Patterns
1. **Cards**: Always use `.glass` variant
2. **Inputs**: Dark bg, white/10 border, gold focus ring
3. **Buttons**: Gold gradient primary, ghost secondary
4. **Icons**: Lucide React, 16-24px, white/40 default
5. **Spacing**: 4px grid system (p-4, gap-4, space-y-4)

## Responsive Breakpoints
- Mobile: < 640px (single column)
- Tablet: 640-1024px (2 columns)
- Desktop: 1024-1440px (sidebar + content)
- Wide: > 1440px (max-w-7xl centered)

## Private Banking (Secret Tier)
- Gold shimmer border animation
- Ambient glow effects
- Crown icon branding
- Premium typography sizing
- Encrypted label badges
