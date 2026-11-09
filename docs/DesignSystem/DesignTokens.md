# Plant Management – Design Tokens

**Version:** 0.2  
**Status:** Proposed  
**Design Direction:** Vibrant Botanical / Modern Nature  
**Layout Direction:** RTL  
**Platforms:** Web & Mobile  
**Theme:** Light First, Dark Mode Ready

---

# 1. Design Philosophy

The visual identity combines nature-inspired colors with modern SaaS interface patterns.

Core principles:

- Fresh, vibrant and professional.
- Modern rather than rustic or traditional.
- Clean and bright surfaces.
- Multiple controlled accent colors.
- Clear information hierarchy.
- Consistent visual language across Web and Mobile.
- Color diversity without visual noise.

The interface should feel like a modern plant-management platform, not a traditional gardening application.

---

# 2. Color System

## 2.1 Brand Colors

| Token | HEX | Usage |
|---|---|---|
| Primary | #176B50 | Main actions, active navigation |
| Primary Hover | #12563F | Hover and pressed states |
| Primary Light | #DDF1E5 | Selected backgrounds |
| Primary Soft | #F0F7F2 | Subtle surfaces |
| Primary Dark | #123D32 | Dark surfaces |
| Secondary | #26966F | Secondary actions |
| Accent | #A8D94E | Highlights and botanical accents |

## 2.2 Complementary Colors

Complementary colors provide visual diversity and semantic grouping.

| Token | HEX | Usage |
|---|---|---|
| Terracotta | #D98755 | Soil, materials, organic processes |
| Teal | #3999A5 | Water, environmental data |
| Lavender | #8972C5 | Experiments and laboratory data |
| Amber | #E7B64C | Attention and highlighted information |
| Blue | #548BC0 | Scientific and informational elements |
| Coral | #DB746A | Important warnings and selected alerts |

Rules:
- Complementary colors should be used selectively.
- Do not use all accent colors in a single component.
- Accent colors may identify functional categories.
- Brand identity must remain recognizable through Primary colors.

---

# 3. Background & Surface Colors

| Token | HEX | Usage |
|---|---|---|
| Background | #F5F8F5 | Main application background |
| Surface | #FFFFFF | Cards and standard containers |
| Surface Elevated | #FFFFFF | Dialogs and popovers |
| Surface Muted | #F0F4F0 | Secondary containers |
| Surface Green | #EAF4EB | Botanical information |
| Surface Blue | #EDF3F5 | Informational sections |
| Surface Warm | #FBF3EC | Organic and material sections |

Rules:
- Prefer neutral and bright backgrounds.
- Avoid using cream as the dominant background.
- Colored backgrounds should have sufficient contrast.
- Cards should be visually distinguishable without heavy shadows.

---

# 4. Text Colors

| Token | HEX | Usage |
|---|---|---|
| Text Primary | #1F3029 | Main text |
| Text Secondary | #65756C | Secondary text |
| Text Muted | #89958D | Hints and placeholders |
| Text Inverse | #FFFFFF | Text on dark backgrounds |
| Text Link | #176B50 | Links and interactive text |
| Text Disabled | #AAB3AD | Disabled content |

---

# 5. Border Colors

| Token | HEX | Usage |
|---|---|---|
| Border Default | #E3EAE4 | Standard borders |
| Border Strong | #CFDAD1 | Emphasized borders |
| Border Focus | #26966F | Focused controls |
| Border Selected | #176B50 | Selected components |

---

# 6. Semantic Status Colors

| Status | Foreground | Background | Usage |
|---|---|---|---|
| Success | #237548 | #E3F3E8 | Completed, successful |
| Warning | #98620C | #FFF2D8 | Pending, needs attention |
| Danger | #B84242 | #FCE8E7 | Failed, rejected, critical |
| Info | #356F9D | #E5F0FA | Informational |
| Neutral | #68756E | #EDF0ED | Draft, inactive, unknown |

Rules:
- Status must never be communicated using color alone.
- Always display a text label.
- Use icons where appropriate.
- Business status and technical status must remain separate.
- Semantic status colors must not be replaced with decorative accent colors.

---

# 7. Functional Category Colors

Use category colors consistently for information grouping.

| Category | Foreground | Background |
|---|---|---|
| Plant / Botanical | #237548 | #E3F3E8 |
| Propagation / Production | #176B50 | #DDF1E5 |
| Soil / Materials | #B36A36 | #FBEEE3 |
| Environment | #287E8C | #E1F1F3 |
| Experiments | #7962B4 | #EFEAFA |
| Measurements | #487FAE | #E8F0F8 |

Rules:
- Each category must retain its color across pages.
- Category colors are not business statuses.
- Use category colors in icons, chips, small indicators and charts.
- Avoid coloring entire large cards unnecessarily.

---

# 8. Typography

## 8.1 Font Families

Persian:
- Primary: Vazirmatn
- Fallback: Tahoma, sans-serif

English:
- Primary: Inter
- Fallback: Arial, sans-serif

## 8.2 Font Sizes

| Token | Size | Usage |
|---|---:|---|
| Display | 32px | Dashboard highlights |
| H1 | 28px | Page titles |
| H2 | 24px | Main sections |
| H3 | 20px | Card headings |
| H4 | 18px | Subsections |
| Body Large | 16px | Important content |
| Body | 14px | Standard text |
| Body Small | 13px | Secondary information |
| Caption | 12px | Hints and metadata |

## 8.3 Font Weights

| Token | Weight |
|---|---:|
| Regular | 400 |
| Medium | 500 |
| SemiBold | 600 |
| Bold | 700 |

Rules:
- Default body text: 14px.
- Persian body line-height: 1.8.
- Heading line-height: 1.5.
- Use consistent typography hierarchy.
- Avoid excessive font weight variation.

---

# 9. Spacing Scale

Base unit: 4px.

| Token | Value |
|---|---:|
| Space 1 | 4px |
| Space 2 | 8px |
| Space 3 | 12px |
| Space 4 | 16px |
| Space 5 | 20px |
| Space 6 | 24px |
| Space 8 | 32px |
| Space 10 | 40px |
| Space 12 | 48px |
| Space 16 | 64px |

Rules:
- Standard component padding: 12–16px.
- Standard card padding: 16–20px.
- Standard section spacing: 24px.
- Keep spacing consistent across pages.

---

# 10. Border Radius

| Token | Value | Usage |
|---|---:|---|
| Radius XS | 4px | Small elements |
| Radius SM | 8px | Inputs and chips |
| Radius MD | 12px | Buttons and controls |
| Radius LG | 16px | Cards |
| Radius XL | 20px | Large panels |
| Radius 2XL | 24px | Dialogs |
| Radius Full | 9999px | Pills and avatars |

---

# 11. Shadows

| Token | Value | Usage |
|---|---|---|
| Shadow XS | 0 1px 2px rgba(31,48,41,0.04) | Inputs |
| Shadow SM | 0 2px 8px rgba(31,48,41,0.05) | Cards |
| Shadow MD | 0 6px 16px rgba(31,48,41,0.08) | Dropdowns |
| Shadow LG | 0 12px 28px rgba(31,48,41,0.12) | Dialogs |

Rules:
- Prefer subtle shadows.
- Use borders to establish component boundaries.
- Avoid heavy shadows and excessive depth effects.
- Floating navigation may use Shadow MD.

---

# 12. Component Dimensions

| Component | Standard Dimension |
|---|---|
| Button Height | 44px |
| Input Height | 44px |
| Select Height | 44px |
| Icon Button | 44 × 44px |
| Small Icon | 16px |
| Standard Icon | 20px |
| Large Icon | 24px |
| Avatar | 40–48px |
| Desktop Sidebar | 240px |
| Mobile Navigation | 64–72px |

Interactive elements should have a minimum touch target of 44 × 44px.

---

# 13. Motion & Transitions

| Token | Duration | Usage |
|---|---|---|
| Fast | 120ms | Hover and icons |
| Normal | 200ms | Buttons and dropdowns |
| Slow | 300ms | Panels and dialogs |

Default easing:

`cubic-bezier(0.2, 0, 0, 1)`

Rules:
- Use subtle transitions.
- Avoid unnecessary animations.
- Respect reduced-motion preferences.
- Loading states must be distinguishable.

---

# 14. Layout Principles

- Default direction: RTL.
- Desktop sidebar: Right aligned.
- Mobile navigation: Floating bottom navigation.
- Main content: Flexible width.
- Mobile layout: Single-column by default.
- Cards: Consistent padding and radius.
- Tables: Horizontal scrolling or alternative card layouts on narrow screens.
- Forms: Group related fields into logical sections.
- Preserve sufficient whitespace.
- Avoid excessive information density.

---

# 15. Visual Component Principles

## Buttons
- Primary actions use Primary.
- Secondary actions use neutral surfaces with borders.
- Destructive actions use Danger.
- Avoid multiple competing primary buttons.

## Cards
- White or subtle neutral backgrounds.
- Light borders.
- Minimal shadows.
- Category accents only when meaningful.

## Inputs
- Neutral background.
- Clear focus state.
- Consistent height and radius.
- Validation feedback using semantic colors.

## Navigation
- Active item uses Primary.
- Inactive items use Text Secondary.
- Mobile navigation should remain visually lightweight.
- Floating navigation must not obstruct page content.

## Charts
- Use distinct series colors.
- Maintain consistent category colors.
- Avoid relying on color alone.
- Keep chart backgrounds neutral.

---

# 16. Dark Mode Readiness

Dark Mode is not part of the initial implementation but all semantic tokens must support future theme mapping.

Rules:
- Components must reference semantic tokens.
- Avoid hardcoded HEX values inside component styles.
- Define separate dark-theme values when implementation begins.
- Maintain readable contrast for text, borders and interactive states.

---

# 17. Naming Convention

Use semantic token names rather than hardcoded colors.

Examples:

- color.brand.primary
- color.brand.secondary
- color.surface.default
- color.surface.elevated
- color.text.primary
- color.status.success
- color.category.experiment
- spacing.4
- radius.lg
- shadow.md
- typography.body

Components must reference semantic tokens rather than raw HEX values.

---

# 18. Design Quality Rules

1. Avoid monotonous single-color interfaces.
2. Maintain a clear distinction between brand, category and status colors.
3. Use accent colors intentionally.
4. Preserve readability and accessibility.
5. Avoid excessive gradients.
6. Prefer modern, clean and lightweight components.
7. Maintain consistency between Web and Mobile.
8. Prioritize usability over decoration.

**End of Design Tokens – Version 0.2**