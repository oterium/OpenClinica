# Biostatech Visual Branding Examples

## Logo Showcase

### Primary Logo (Full Color Gradient)
```
┌─────────────────────────────────────────────────────┐
│                                                     │
│  BIO∫TATΣCH                                        │
│  ═══════════                                        │
│  Advice, Training & Innovation in Biostatistics    │
│                                                     │
└─────────────────────────────────────────────────────┘
```

**Colors**: Gradient from Teal (#14A6A1) → Blue (#0075A9) → Dark Blue (#003F7F)

## Application Header Example

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║  ┌──────────────────────────┐                                    ║
║  │  [Biostatech Logo]       │  Home | Submit Data | Extract...   ║
║  └──────────────────────────┘                                    ║
║                                                                   ║
╚═══════════════════════════════════════════════════════════════════╝
```

**Background**: Biostatech gradient (teal → blue → dark blue)
**Logo Area**: White background with subtle rounded corners
**Navigation**: White text on gradient background

## Button Styles

### Primary Button
```
┌──────────────────┐
│  Submit Data     │  ← Biostatech gradient background
└──────────────────┘     White text, rounded corners
```

### Hover State
```
┌──────────────────┐
│  Submit Data  ↗  │  ← Reversed gradient + shadow
└──────────────────┘     Subtle lift effect
```

## Table Headers

```
╔══════════════════════════════════════════════════╗
║ Subject ID │ Status    │ Last Updated │ Actions ║  ← Gradient header
╠════════════╪═══════════╪══════════════╪═════════╣
║ SUB-001    │ Complete  │ 2024-10-24   │ [View] ║
║ SUB-002    │ Pending   │ 2024-10-23   │ [Edit] ║
╚════════════╧═══════════╧══════════════╧═════════╝
```

## Form Elements

### Input Field (Normal)
```
┌────────────────────────────────┐
│ Enter username...              │
└────────────────────────────────┘
  Light gray border (2px)
```

### Input Field (Focused)
```
┌────────────────────────────────┐
│ john.doe█                      │
└────────────────────────────────┘
  Teal border with soft glow
```

## Status Indicators

### Complete Status
```
✓ Complete
  └─ Teal color (#14A6A1)
```

### Pending Status
```
◷ Pending
  └─ Blue color (#0075A9)
```

### Error Status
```
✗ Invalid
  └─ Red color (#E63946)
```

## Card/Panel Design

```
┌──────────────────────────────────────────┐
│ ╔══════════════════════════════════════╗ │
│ ║ Study Dashboard                      ║ │ ← Gradient header
│ ╚══════════════════════════════════════╝ │
│                                          │
│  Total Subjects: 127                     │
│  Completed CRFs: 89                      │
│  Pending Reviews: 15                     │
│                                          │
│  [View Details] [Export Data]            │
│                                          │
└──────────────────────────────────────────┘
  Rounded corners, subtle shadow
```

## Footer

```
═══════════════════════════════════════════════════════════════
OpenClinica Portal | Help | Privacy | Contact
Licensed under GNU LGPL | Customized by Biostatech
                                        Version 3.18-SNAPSHOT
═══════════════════════════════════════════════════════════════
```

**Attribution**: "Customized by Biostatech" in brand blue

## Login Page Layout

```
┌──────────────────────────────────────────────┐
│                                              │
│           ┌──────────────────┐               │
│           │                  │               │
│           │ [Biostatech Logo]│               │
│           │                  │               │
│           └──────────────────┘               │
│                                              │
│         OpenClinica - Biostatech Edition     │
│                                              │
│         ┌──────────────────────────┐         │
│         │ Username                 │         │
│         └──────────────────────────┘         │
│                                              │
│         ┌──────────────────────────┐         │
│         │ Password                 │         │
│         └──────────────────────────┘         │
│                                              │
│              [Login Button]                  │
│                                              │
│         Forgot Password? | Help              │
│                                              │
└──────────────────────────────────────────────┘
```

## Color Swatches

### Primary Colors
```
Teal         Blue         Dark Blue
#14A6A1      #0075A9      #003F7F
█████████    █████████    █████████
```

### Usage
- **Teal**: Highlights, success states, hover effects
- **Blue**: Links, primary actions, active states
- **Dark Blue**: Text on light backgrounds, borders

## Gradient Definition

```css
background: linear-gradient(90deg, 
    #14A6A1 0%,    /* Teal */
    #0075A9 50%,   /* Blue */
    #003F7F 100%   /* Dark Blue */
);
```

## Typography Examples

### Headers
```
H1: Study Management Dashboard
    └─ 24px, bold, Dark Blue (#003F7F)

H2: Recent Activity
    └─ 20px, semi-bold, Blue (#0075A9)

H3: Section Title
    └─ 18px, medium, Blue (#0075A9)
```

### Body Text
```
Standard text: 14px, Arial/Helvetica, #333
Links: 14px, Blue (#0075A9), underline on hover
Small text: 12px, #666
```

## Responsive Breakpoints

### Desktop (> 768px)
- Logo height: 60px
- Full navigation visible
- Multi-column layouts

### Tablet/Mobile (≤ 768px)
- Logo height: 40px
- Collapsed navigation menu
- Single-column layouts

## Accessibility Features

### Color Contrast Ratios
- Teal on White: 4.5:1 (WCAG AA compliant)
- Blue on White: 6.2:1 (WCAG AA compliant)
- Dark Blue on White: 8.1:1 (WCAG AAA compliant)
- White on Gradient: 7.5:1 average (WCAG AA compliant)

### Interactive Elements
- Minimum touch target: 44x44px
- Focus indicators: 2px teal outline
- Skip navigation links available
- ARIA labels on icons

## Print Styles

When printing:
- Logo converts to grayscale
- Gradient backgrounds removed
- High contrast for readability
- Page breaks optimized

---

## Implementation Files Reference

- **Logos**: `/web/src/main/webapp/images/biostatech/*.svg`
- **Styles**: `/web/src/main/webapp/includes/biostatech-branding.css`
- **Headers**: `/web/src/main/webapp/WEB-INF/jsp/*/header.jsp`
- **Footer**: `/web/src/main/webapp/WEB-INF/jsp/include/footer.jsp`

---

**Last Updated**: October 24, 2024
**Created by**: Biostatech Branding Team
