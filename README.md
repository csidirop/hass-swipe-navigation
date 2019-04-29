# Lovelace Swipe Navigation
Swipe through Lovelace views on mobile.<br>
Original idea & [project](https://github.com/themoffatt/lovelace-swiper) by [@themoffatt](https://github.com/themoffatt) <br><br>
<a href="https://www.buymeacoffee.com/FgwNR2l" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/black_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a><br>

# Installation:
Follow only one of these installation methods.

### Manual installation:
1. Copy `lovelace-swipe-navigation.js` into `/www/lovelace-swipe-navigation/`

2. Add the resource in `ui-lovelace.yaml` or by using the "Raw Config Editor".

```yaml
resources:
  # increase this version number at end of URL after each update
  - url: /local/lovelace-swipe-navigation.js?v=1.0.0
    type: js
```

3. Refresh the page.

4. That's it, nothing to configure and no card to add.


### Installation and tracking with custom_updater:

1. Make sure the [custom_updater](https://github.com/custom-components/custom_updater) component is installed and working.

2. Configure Lovelace to load the card.

```yaml
resources:
  - url: /customcards/github/maykar/lovelace-swipe-navigation.js?track=true
    type: js
```

3. Run the service `custom_updater.check_all` or click the "CHECK" button if you use the tracker-card.

4. Refresh the page.
