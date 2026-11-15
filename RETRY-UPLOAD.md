# Retry upload: pins 2–40

Use **pinterest-retry-39-pins.csv** to retry the remaining 39 pins after pin 1 imported. Do not re-upload the original 40-pin file for this attempt.

- 14 pins have an empty Link field (35.9%). These are spread through the four days. Their descriptions use save-focused wording without asking people to click a missing link.
- 25 pins use unique utm_content tracking values, alongside utm_source=pinterest, utm_medium=social and utm_campaign=christmas_gnome_nov2026. Every linked URL retains the exact original Etsy product host and path.
- Images, titles, boards, keywords and the remaining publish times are unchanged. Pin 1 is excluded.
- The first remaining publish time is November 15, 2026 at 20:24 Morocco time (UTC). Upload before that time, or move elapsed timestamps into the future.

This is an upload experiment, not a verified fix for the reported first-pin-only import issue. Pinterest may normalize tracking parameters. The [official bulk-upload documentation](https://help.pinterest.com/en/business/article/bulk-upload-video-pins) lists Link as optional and does not state a requirement for unique destination URLs.
