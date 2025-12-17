# Fairplay Moving - Interaction Design

## Core Interactive Components

### 1. Get Free Quote Modal
- **Trigger**: Always-accessible button in header (desktop) and floating action button (mobile)
- **Form Fields**:
  - Move date (date picker)
  - Move size dropdown:
    - Studio apartment
    - 1 bedroom apartment
    - 2 bedroom apartment
    - 3 bedroom apartment
    - 4+ bedroom apartment
    - Small house (1-2 bedrooms)
    - Medium house (3-4 bedrooms)
    - Large house (5+ bedrooms)
    - Storage unit (5x5, 5x10, 10x10, 10x15, 10x20)
  - Full name (required)
  - Email (required, validation)
  - Phone (required, format validation)
  - From ZIP code (required, Chicago area validation)
  - To ZIP code (required)
  - How did you hear about us? (dropdown)
  - Additional comments (optional)
- **Captcha**: Simple math question or checkbox
- **Submission**: AJAX form with success/error handling

### 2. Moving Cost Calculator
- **Location**: Services page
- **Interactive Elements**:
  - Distance calculator (from/to ZIP)
  - Size selector with visual icons
  - Additional services checkboxes (packing, storage, etc.)
  - Real-time estimate display
  - "Get Detailed Quote" button leading to modal

### 3. Service Area Map
- **Location**: About/Services page
- **Features**:
  - Interactive map of Chicago area coverage
  - Highlighted service zones
  - Clickable area markers
  - Distance/time estimates to popular destinations

### 4. Review System Integration
- **Google Reviews Display**:
  - Star ratings with animated counters
  - Recent review carousel
  - "Leave Review" button linking to Google
  - Review filtering and sorting options

## User Journey Flow

### Desktop Experience
1. **Landing**: Hero section with clear value proposition
2. **Explore**: Service cards with hover effects
3. **Calculate**: Interactive cost estimator
4. **Quote**: Modal form with progress indicator
5. **Follow-up**: Confirmation with next steps

### Mobile Experience
1. **Landing**: Streamlined hero with prominent quote button
2. **Navigate**: Collapsible menu with thumb-friendly targets
3. **Quote**: Always-accessible floating quote button
4. **Form**: Step-by-step mobile-optimized form
5. **Contact**: One-tap phone/email integration

## Accessibility Features
- Keyboard navigation for all interactive elements
- Screen reader compatible form labels
- High contrast mode support
- Focus indicators on all clickable elements
- Alternative text for all images
- Semantic HTML structure

## Performance Considerations
- Lazy loading for images and heavy components
- Progressive enhancement for JavaScript features
- Fast loading quote modal (pre-loaded)
- Optimized form validation
- Minimal external dependencies