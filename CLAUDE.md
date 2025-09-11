# AI Visual Magic - Design System

## Project Overview
This project creates a glassmorphic tile-based interface for an AI document processing system with dynamic tile interactions.

## Design Principles

### Apple Liquid Glass Aesthetic
- **Enhanced Glassmorphism**: Strong backdrop blur (25px+) with layered transparency
- **Refined Lighting**: Top-left light source with realistic highlight and shadow gradients
- **Smooth Animations**: Cubic-bezier transitions (0.25, 0.46, 0.45, 0.94) for natural feel
- **Layered Depth**: Multiple shadow layers for depth perception
- **Color Harmony**: Subtle color variations with consistent opacity levels

### Visual Hierarchy
- **Base tiles**: 140x140px with 28px border radius
- **Icon sizing**: 40px with color-coded drop shadows
- **Typography**: 11px uppercase labels with 0.8px letter spacing
- **Spacing**: 30px gaps between tiles for clean layout

### Color System
- **Upload**: Green (#22c55e) - Start of process
- **Preprocessing**: Amber (#fbbf24) - Data preparation
- **A.I. Analysis**: Blue (#a4e0ff) - Core AI processing
- **Review**: Purple (#a855f7) - Human validation
- **Operate**: Red (#ef4444) - Final action

### Icon Framework
- **Phosphor Icons**: Duotone and Bold variants
- **CDN Links**: 
  - `https://cdn.jsdelivr.net/npm/@phosphor-icons/web@2.1.2/src/duotone/style.css`
  - `https://cdn.jsdelivr.net/npm/@phosphor-icons/web@2.1.2/src/bold/style.css`

## System Flow Concepts
1. **Upload** (`ph-upload-simple`) - File upload interface
2. **Preprocessing** (`ph-gear-six`) - Data transformation
3. **A.I. Analysis** (`ph-brain`) - AI processing (bold variant)
4. **Review** (`ph-magnifying-glass`) - Human review step
5. **Operate** (`ph-play-circle`) - Execute final actions

## Interactive Elements
- **Trigger Tile**: First tile activates dynamic tile expansion
- **Connection Lines**: Animated lines show data flow
- **Dynamic Tiles**: Appear with staggered animations
- **Hover Effects**: Subtle scale and shadow enhancements

## Technical Implementation
- **Backdrop Filter**: Use both `-webkit-backdrop-filter` and `backdrop-filter`
- **CSS Masking**: For precise border gradients
- **Mix Blend Modes**: `overlay` and `soft-light` for realistic lighting
- **Transform Origins**: Proper anchoring for animations

## File Structure
- `tiles.html` - Main tile interface with dynamic interactions
- `example.html` - Phosphor icon reference and examples

## Development Notes
- Maintain 5-tile system layout
- Preserve Apple liquid glass lighting effects
- Use Phosphor icons for consistency
- Keep color-coded system for visual flow indication