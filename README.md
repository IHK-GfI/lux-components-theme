## Theme
- [Allgemein](#allgemein)
- [Styles](#styles)
  - [Allgemeine Style Classes](#allgemeine-style-classes)
  - [Style Classes aus der Farbpalette](#style-classes-aus-der-farbpalette)

### Installation
```bash
npm install @ihk-gfi/lux-components-theme
```

### Styles
#### Allgemeine Style Classes
- lux-app-header-bg
- lux-app-content-bg
- lux-app-footer-bg
- lux-app-data-bg
- lux-highlight-section
- lux-highlight-section-label
- lux-color-dark-primary-text
- lux-color-dark-secondary-text
- lux-color-dark-disabled-text
- lux-color-dark-focused
- lux-color-light-primary-text
- lux-color-light-secondary-text
- lux-color-light-disabled-text
- lux-color-light-focused
- lux-selected-bg
- lux-hover-bg
- lux-hover-dark-bg
- lux-color-dark-divider
- lux-color-light-divider
- lux-outline-color-light
- lux-outline-color-dark
- lux-outline-width
- lux-outline-style
- lux-outline-light
- lux-outline-dark

#### Style Classes aus der Farbpalette
Das LUX-Components-Theme besteht aus den folgenden Farbpaletten:
- lux-palette_primary
- lux-palette_accent
- lux-palette_warn

Beispiel der Farbpalette `lux-palette_primary`:
```
$lux-palette_primary: (
50 : #e7ebf0,
100 : #c6d1dc,
200 : #99aec2,
300 : #708daa,
400 : #527497,
500 : #335c85,
600 : #2e547d,
700 : #274a72,
800 : #204168,
900 : #143055,
A100 : #b5d5e8,
A200 : #4d9dca,
A400 : #0073b3,
A700 : #00569a,
contrast: (
50 : #000000,
100 : #000000,
200 : #000000,
300 : #000000,
400 : #000000,
500 : #ffffff,
600 : #ffffff,
700 : #ffffff,
800 : #ffffff,
900 : #ffffff,
A100 : #000000,
A200 : #000000,
A400 : #000000,
A700 : #000000,
)
);
```

Zu jedem Eintrag (z.B. 50, 100, 200,..., A100, A200,...) aus der Farbpalette gibt es im LUX-Theme entsprechende Style Classes.

Beispiel der Farbpalette `lux-palette_primary` für den Eintrat `50`:
- lux-color-primary-50
- lux-color-primary-50-contrast
- lux-bg-color-primary-50
- lux-bg-color-primary-50-contrast
- lux-border-color-primary-50
- lux-border-color-primary-50-contrast
- lux-outline-color-primary-50
- lux-outline-color-primary-50-contrast
- lux-text-decoration-primary-color-50
- lux-text-decoration-primary-color-50-contrast
- lux-column-rule-color-primary-50
- lux-column-rule-color-primary-50-contrast
- lux-color-accent-50
- lux-color-accent-50-contrast
- lux-bg-color-accent
- lux-bg-color-accent-50-contrast
- lux-border-color-accent-50
- lux-border-color-accent-50-contrast
- lux-outline-color-accent-50
- lux-outline-color-accent-50-contrast
- lux-text-decoration-accent-color-50
- lux-text-decoration-accent-color-50-contrast
- lux-column-rule-color-accent-50
- lux-column-rule-color-accent-50-contrast
- lux-color-warn-50
- lux-color-warn-50-contrast
- lux-bg-color-warn-50
- lux-bg-color-warn-50-contrast
- lux-border-color-warn-50
- lux-border-color-warn-50-contrast
- lux-outline-color-warn-50
- lux-outline-color-warn-50-contrast
- lux-text-decoration-warn-color-50
- lux-text-decoration-warn-color-50-contrast
- lux-column-rule-color-warn-50
- lux-column-rule-color-warn-50-contrast
