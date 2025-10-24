# Biostatech Branding Guide

## Overview

This OpenClinica installation has been customized with Biostatech branding to reflect its use by **Biostatech - Advice, Training & Innovation in Biostatistics, S.L.**

## Company Information

**Biostatech** is a specialized consultancy firm providing expert services in:
- Biostatistics
- Clinical Data Management
- Clinical Trial Design
- Regulatory Affairs
- Statistical Analysis
- Training and Innovation in Clinical Research

## Brand Identity

### Color Palette

The Biostatech brand uses a professional blue-green gradient that represents trust, innovation, and scientific excellence:

- **Teal**: `#14A6A1` - Innovation and freshness
- **Blue**: `#0075A9` - Trust and professionalism
- **Dark Blue**: `#003F7F` - Stability and expertise

### Logo Variations

Multiple logo formats are available in `/web/src/main/webapp/images/biostatech/`:

1. **biostatech-logo.svg** - Full color gradient logo (primary)
2. **biostatech-logo-white.svg** - White logo for dark backgrounds
3. Additional formats include stacked and compact versions

The logo features the distinctive "BIOSTATECH" wordmark with mathematical symbols (∫ and Σ) representing the statistical and analytical nature of the company's work.

## Implementation Details

### Files Modified

#### Visual Branding (Logos)

The following JSP files have been updated to display the Biostatech logo:

1. `/web/src/main/webapp/WEB-INF/jsp/login-include/login-header.jsp` - Login page header
2. `/web/src/main/webapp/WEB-INF/jsp/include/home-header.jsp` - Home page header
3. `/web/src/main/webapp/WEB-INF/jsp/include/admin-header.jsp` - Admin section header
4. `/web/src/main/webapp/WEB-INF/jsp/include/submit-header.jsp` - Data submission header
5. `/web/src/main/webapp/WEB-INF/jsp/include/managestudy-header.jsp` - Study management header
6. `/web/src/main/webapp/WEB-INF/jsp/include/extract-header.jsp` - Data extraction header
7. `/web/src/main/webapp/decorator.jsp` - Main page decorator

All logo references changed from:
```html
<img src="images/Logo.gif">
```

To:
```html
<img src="images/biostatech/biostatech-logo.svg" alt="Biostatech - OpenClinica" style="height: 60px; margin: 10px 0;">
```

#### Custom Styling

**New File**: `/web/src/main/webapp/includes/biostatech-branding.css`

This comprehensive CSS file includes:
- Biostatech color scheme variables
- Custom header styling with gradient backgrounds
- Branded buttons and links
- Custom table styling
- Form elements with brand colors
- Responsive design adjustments
- Print-friendly styles

The CSS is included in all major headers:
- Login header
- Admin header
- Home header
- Study management header
- Data submission header
- Extract header

#### Footer Branding

**Modified**: `/web/src/main/webapp/WEB-INF/jsp/include/footer.jsp`

Added Biostatech attribution:
```html
<span style="margin-left: 10px; color: #0075A9; font-weight: 600;">| Customized by Biostatech</span>
```

#### Documentation

**Modified**: `/README.md`
- Updated welcome message to include Biostatech branding
- Added company information section
- Added contact information footer
- Included reference to professional management by Biostatech

**New Files**:
- `/BRANDING.md` - This comprehensive branding guide
- Logo files in `/web/src/main/webapp/images/biostatech/`

## Visual Elements

### Header

The application header now features:
- Biostatech gradient background (teal to blue to dark blue)
- Biostatech logo prominently displayed (60px height)
- Professional rounded corner design
- White background for logo area with subtle transparency

### Buttons and Interactive Elements

- Primary actions use the Biostatech gradient
- Hover effects with color inversion and subtle shadow
- Smooth transitions for professional feel
- Consistent color scheme throughout

### Tables and Data Display

- Header rows use Biostatech gradient background
- Selected/active items highlighted with teal accent
- Professional typography and spacing

### Forms

- Input fields with teal focus borders
- Subtle shadow effects on focus
- Consistent padding and border radius

## Usage Guidelines

### When to Use the Logo

1. **Always Use**: On all main pages, headers, and official documentation
2. **Size Guidelines**: Maintain minimum height of 40px for readability
3. **Clear Space**: Maintain adequate white space around logo
4. **Background**: Works best on white or very light backgrounds

### Color Usage

1. **Primary Actions**: Use gradient or teal for main CTAs
2. **Links**: Use blue (#0075A9) for standard links
3. **Highlights**: Use teal (#14A6A1) for important information
4. **Status Indicators**: Maintain existing OpenClinica conventions but with brand colors

### Typography

- Maintain existing OpenClinica fonts for consistency
- Use brand colors for headings and emphasis
- Ensure good contrast for accessibility

## Technical Notes

### CSS Cascade Order

The Biostatech branding CSS is loaded after the main OpenClinica styles:
```html
<link rel="stylesheet" href="includes/styles.css" type="text/css">
<link rel="stylesheet" href="includes/biostatech-branding.css" type="text/css">
```

This ensures:
- Original OpenClinica functionality is preserved
- Biostatech styles override where appropriate
- Easy maintenance and updates

### Responsive Design

The branding adapts to different screen sizes:
- **Desktop**: Full logo at 60px height
- **Tablet/Mobile**: Logo scales to 40px height
- **Print**: Grayscale logo for professional appearance

### Browser Compatibility

All branding elements are tested and compatible with:
- Modern browsers (Chrome, Firefox, Safari, Edge)
- IE11 (with graceful degradation)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Maintenance

### Updating the Logo

To update the Biostatech logo:
1. Place new logo file in `/web/src/main/webapp/images/biostatech/`
2. Update references in header JSP files
3. Test across all main pages
4. Clear browser cache

### Modifying Colors

To change brand colors:
1. Edit CSS variables in `/web/src/main/webapp/includes/biostatech-branding.css`
2. Update the `:root` section at the top of the file
3. Changes will cascade throughout the application

### Adding New Branded Pages

For new pages requiring Biostatech branding:
1. Include `biostatech-branding.css` in page header
2. Use appropriate header JSP include file
3. Follow color guidelines for new UI elements
4. Test visual consistency with existing pages

## Support

For questions about Biostatech branding or customization:
- Review this guide first
- Check existing implementations in JSP files
- Refer to `/web/src/main/webapp/includes/biostatech-branding.css` for styling patterns

## Version History

- **2024-10-24**: Initial Biostatech branding implementation
  - Added logo files (SVG format)
  - Created custom CSS stylesheet
  - Updated all main headers
  - Modified footer with attribution
  - Updated README.md
  - Created comprehensive branding guide

## License

The Biostatech brand elements (logo, colors, name) are proprietary to Biostatech, S.L. The OpenClinica application remains under its original GNU LGPL license. This branding customization does not affect the OpenClinica license terms.

---

**Biostatech - Advice, Training & Innovation in Biostatistics, S.L.**

*Professional Clinical Data Management Solutions*
