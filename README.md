# Julkalendern: dashboard widget

This folder is published with GitHub Pages and shown on the Azure DevOps dashboard.

- `index.html` is the widget. It shows the countdown, today's doors, the next door, and who opened today's door.
- `julkalender-status.json` tells the widget which doors have been opened. Replace it after each morning's draw.
- `robots.txt` asks search engines not to index the site.

## Daily update

1. In the calendar on the TV computer, go to Inställningar → Säkerhetskopia → Spara säkerhetskopia.
2. In this repository on GitHub, open `julkalender-status.json`, choose Edit, replace all text with the contents of the backup file, and commit.
3. The widget picks up the change within about five minutes.
