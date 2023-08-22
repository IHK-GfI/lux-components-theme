# Version 15.1.0

## New

- **allgemein**: Falsche Schriftart in der lux-table korrigiert. [Issue 354](https://github.com/IHK-GfI/lux-components/issues/354)
- **lux-chips-ac**: Neue Property luxHideBorder eingeführt. [Issue 351](https://github.com/IHK-GfI/lux-components/issues/351)
- **lux-master-detail-ac**: FxLayout wurde durch css ersetzt. [Issue 350](https://github.com/IHK-GfI/lux-components/issues/350)
- **lux-list-ac**: Der Keyboard-Focus wurde überarbeitet. [Issue 350](https://github.com/IHK-GfI/lux-components/issues/350)

## Bug Fixes

- **lux-app-header-ac**: Das Selected-Nav-Item wurde neue Positioniert. [Issue 349](https://github.com/IHK-GfI/lux-components/issues/349)

# Version 15.0.0

## New

- **Blue-Theme**: Das Theme wurde zugunsten des Authentic-Themes gelöscht. [Issue 316](https://github.com/IHK-GfI/lux-components/issues/316)
- **lux-icon**: Material- und FA-Icons entfernt. [Issue 322](https://github.com/IHK-GfI/lux-components/issues/322)
- **lux-icon**: luxIconSize nimmt jetzt auch px oder em-Werte an. [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-button**: luxIconSize und fontsize im Label angepasst, Focus-Indicator mit 1px Offset versehen (Theme-authentic). [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-menu**: luxIconSize in lux-menu-items und lux-menu-trigger angepasst. lux-menu-trigger default-height angepasst [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-tile-ac**: luxIconSize angepasst. [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-input-ac**: luxIconSize in lux-input-ac-prefix/-suffix angepasst. [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-file-input**, **lux-file-list**, **lux-file-upload**: luxIconSize angepasst.[Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-app-header**: luxIconSize und Button-Height für Theme Green angepasst. [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-app-footer**: Default-Height für Buttons auf die Werte von Theme-Authentic gesetzt. [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-tab**: luxIconSize in lux-tab-item angepasst (Theme Authentic). [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)
- **lux-card**: luxIconSize in lux-card angepasst. [Issue 323](https://github.com/IHK-GfI/lux-components/issues/323)

# Version 14.7.0

## New

- **lux-button, lux-menu-item, lux-app-header-ac-nav-menu-item**: Neue Properties luxButtonBadge, luxButtonBadgeColor eingeführt. [Issue 305](https://github.com/IHK-GfI/lux-components/issues/305)

## Bug Fixes

- **lux-master-detail-ac**: In der mobilen Ansicht wird initial die Detailansicht anstatt der Liste angezeigt. [Issue 338](https://github.com/IHK-GfI/lux-components/issues/338)

# Version 14.6.0

## New

- **lux-textbox**: Neue Komponente "lux-textbox" hinzugefügt. [Issue 292](https://github.com/IHK-GfI/lux-components/issues/292)

## Bug Fixes

- **lux-menu**: Lange Labels im Menu-Panel werden automatisch mit "Text-overflow: ellipsis" gekürzt. [Issue 312](https://github.com/IHK-GfI/lux-components/issues/312)

# Version 14.5.0

## New

- **lux-link-plain**: Neue Property "luxCustomClass" hinzugefügt, hover-color für blue- und green-Theme angepasst. [Issue 284](https://github.com/IHK-GfI/lux-components/issues/284)
- **lux-form-controls-ac**: Neue Property "luxDense" für alle AC-Formular-Komponenten eingeführt. [Issue 288](https://github.com/IHK-GfI/lux-components/issues/288).
- **lux-table**: AC-Formular-Komponenten werden innerhalb der Tabelle mit der geringeren Höhe angezeigt. (Nur im Theme Authentic) [Issue 288](https://github.com/IHK-GfI/lux-components/issues/288).
- **lux-checkbox-container**: Neue Komponente lux-checkbox-container erstellt. [Issue 297](https://github.com/IHK-GfI/lux-components/issues/297)

# Version 14.4.0

## New

- **lux-form-controls-ac**: Theming für das Green-Theme für alle Formcontrols und die Lookup-Komponenten erstellt. [Issue 280](https://github.com/IHK-GfI/lux-components/issues/280)
- **lux-datepicker-ac**, **lux-datetimepicker-ac**: hover für den mat-datepicker-toggle in Blue-Theme angepasst. [Issue 280](https://github.com/IHK-GfI/lux-components/issues/280)
- **lux-card**: Hover-Effekt der LUX-Cards ohne luxCardActions im Theme-Authentic anpassen. [Issue 287](https://github.com/IHK-GfI/lux-components/issues/287)

# Version 14.3.0

## New

- **allgemein**: Die Webfonts werden nun über lux-components-icons-and-fonts eingebunden. [Issue 277](https://github.com/IHK-GfI/lux-components/issues/277)

# Version 14.2.0

## New

- **lux-app-header-ac**: Icon-Buttons im Header wurden neu zentriert [Issue 32](https://github.com/IHK-GfI/lux-components-theme/issues/32), Styleanpassungen für das neue Appicon und Brandlogo. [Issue 269](https://github.com/IHK-GfI/lux-components/issues/269)

## Bug Fixes

- **lux-select-ac**, **lux-lookup-combobox-ac**: Auswahlbox bei lux-select-ac im Theme authentic ungünstig positioniert. [Issue 271](https://github.com/IHK-GfI/lux-components/issues/271)

# Version 14.1.0

## New

- **allgemein**: Verbesserungen fürs Authentic-Themes.
- **lux-file-input**: Dateifehlermeldungen (z.B. Überschreitung der erlaubten Dateigröße) können über einen Button entfernt werden. [Issue 247](https://github.com/IHK-GfI/lux-components/issues/247)
- **lux-file-list**: Dateifehlermeldungen (z.B. Überschreitung der erlaubten Dateigröße) können über einen Button entfernt werden. [Issue 247](https://github.com/IHK-GfI/lux-components/issues/247)

# Version 14.0.0

## New

- **allgemein**: Update auf Angular 14
- **allgemein**: Umstellung auf das neue Modulsystem von Sass. [Issue 30](https://github.com/IHK-GfI/lux-components-theme/issues/30)

# Version 13.0.0

## New

-**allgemein**: die Version für @angular/material und sass, analog zu denen der Lux-Components aktualisiert. [Issue 28](https://github.com/IHK-GfI/lux-components-theme/issues/28)

# Version 11.13.0

## New

- **chips**: Vorschlagsliste soll so breit wie die Chips-Komponente sein. [Issue 20](https://github.com/IHK-GfI/lux-components-theme/issues/20)
- **stepper-large**: Farben und Hover-Effekte ändern. [Issue 22](https://github.com/IHK-GfI/lux-components-theme/issues/22)
- **lux-autocomplete**, **lux-chips**, **lux-lookup-autocomplete**: Mehrzeilige Mat-Option im Dropdown-Menü eingeführt. [Issue 177](https://github.com/IHK-GfI/lux-components/issues/177)

## New - Theme "green"

- **select**: Schriftfarbe anpasse. [Issue 21](https://github.com/IHK-GfI/lux-components-theme/issues/21)

# Version 11.12.0

- **file-upload**: Styles für die neue Dateiupload-Komponente (lux-file-upload) entwickeln. [Issue 19](https://github.com/IHK-GfI/lux-components-theme/issues/19)

# Version 11.11.0

- **allgemein**: Die Font Awesome- und Material-Icons sollen nicht über die Server von Google und Font Awesome direkt importiert werden. [Issue 17](https://github.com/IHK-GfI/lux-components-theme/issues/17)
- **stepper-large**: lux-stepper-larger - Der Inhaltscontainer soll sich automatisch der Größe seines Containers anpassen. [Issue 18](https://github.com/IHK-GfI/lux-components-theme/issues/18)

# Version 11.10.0

## New - Theme "green"

- **stepper-large**: Styles für den neuen Stepper (lux-stepper-large) entwickeln. [Issue 16](https://github.com/IHK-GfI/lux-components-theme/issues/16)

# Version 11.9.0

- **allgemein**: Die folgenden neuen CSS-Klassen wurden eingeführt: [Issue 15](https://github.com/IHK-GfI/lux-components-theme/issues/15)
  - lux-display-none-important
  - lux-hidden-important

# Version 11.8.0

## New - Theme "green"

- **tabs**: Die Schrift der Tablabels soll auf die Schrift "Korb (700) 22px" umgestellt werden. [Issue 14](https://github.com/IHK-GfI/lux-components-theme/issues/14)
- **tabs**: Die Hover- und Active-Farbe soll auf den Wert "E3EBF5" eingestellt werden. [Issue 14](https://github.com/IHK-GfI/lux-components-theme/issues/14)

# Version 11.7.1

## Bug Fixes - Theme "green"

- **checkbox**: Deaktivierte Checkbox wird nicht angezeigt. [Issue 13](https://github.com/IHK-GfI/lux-components-theme/issues/13)

# Version 11.7.0

## New

- **allgemein**: Die folgenden neuen CSS-Variablen wurden eingeführt: [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- `--lux-theme-form-control-default-height-not-scalable`
- `--lux-theme-form-control-height`
- `--lux-theme-form-control-height-small`
- `--lux-theme-form-control-font-size`
- `--lux-theme-form-control-font-size-small`

## New - Theme "green"

- **checkbox**: Checkboxen abgerundet darstellen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **radio**: Aktivierte Radio-Buttons mit Haken-Icon darstellen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **form-fields**: Eingabefelder mit abgerundetem Rahmen und Label darstellen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **table**: Die Zeilenhintergrundfarbe alternierend in Weiß und Hellgrau darstellen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **table**: Den Tabellenheader in Grün darstellen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **datepicker**: Überschriften (Wochentage) mit zwei Buchstaben darstellen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **datepicker**: Tagehintergrund in hellblauen Kästchen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **datepicker**: Selektierter Tag als dunkelblaues Kästchen. [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)
- **datepicker**: Monatsname unterhalb der Tagesspaltenköpfe soll entfallen (falls möglich). [Issue 12](https://github.com/IHK-GfI/lux-components-theme/issues/12)

# Version 11.6.1

## Bug Fixes

- **table**: Falsche Fokusdarstellung bei den Tabellenzellen (td-Tags) [Issue 11](https://github.com/IHK-GfI/lux-components-theme/issues/11)

# Version 11.6.0

## New

- **badge-notification**: Accent-Farbe noch ans Theme anpassen [Issue 7](https://github.com/IHK-GfI/lux-components-theme/issues/7)
- **allgemein**: Themefarben auch als Css-Variablen zur Verfügung stellen [Issue 8](https://github.com/IHK-GfI/lux-components-theme/issues/8)

# Version 11.5.0

## New

- **green**: Die Buttons und Schriften im Theme "green" überarbeiten. [Issue 6](https://github.com/IHK-GfI/lux-components-theme/issues/6)

## Bug Fixes

- **button**: Unterschiedliche Buttonhöhen (mit/ohne Icons) korrigieren [Issue 5](https://github.com/IHK-GfI/lux-components-theme/issues/5)

# Version 11.4.0

## New

- **lux-datetimepicker**: Styles für den neuen Datetimepicker inklusive Uhrzeit bereitstellen. [Issue 4](https://github.com/IHK-GfI/lux-components/issues/4)

# Version 11.3.0

## New

- **green**: Theme "green" vollständig überarbeiten. [Issue 3](https://github.com/IHK-GfI/lux-components-theme/issues/3)

# Version 11.2.1

## Bug Fixes

- **tab-notification**: "Tab Notification"-Icons haben fälschlicherweise einen roten Rand. [Issue 2](https://github.com/IHK-GfI/lux-components-theme/issues/2)

# Version 11.2.0

## New

- **tooltip**: Schriftgröße erhöhen. [Issue 1](https://github.com/IHK-GfI/lux-components-theme/issues/1)
