# DMCA.com Site Alert Protocol [![DMCA API](https://images.dmca.com/Badges/dmca-badge-w200-5x1-04.png)](https://www.dmca.com)

DMCA.com Site alerts are the email notifications that get sent out when a new badge is detected on a new domain. You would get one by having a DMCA.com protection badge on your page(s).

- To manage your site alert settings, login to your dashboard at: [DMCA Sites Dashboard](https://www.dmca.com/dashboard?sites)

## How it works
- The first time a new domain is detected with a badge on it the owner of that badge ID is alerted.
   * The owner can choose to mute the alert or do nothing and receive further alerts.
   * DMCA.com will confirm the badge is actually present at that URL before sending the alert. (Default setting)
- The second time will be sent to the badge owner unless it's muted
- Same with the 3rd
- Same with the 4th
- The 5th alert will be sent with opt in requirement. You need to click the link that says "I want to keep receiving these alerts" or you wont receive any more alerts.
- The reason we have to disable the alerts after 5 is to prevent spam. We need to make sure what happening is deliberate.

### Known Issues
* We are working on a way to better validate the alert is legitimate
* We are working a better ways manage the difference in sensitivity between alerts
* We are working better ways to prevent abuse on this feature.
* We are working on a higher sensitivity for the alerts.


### Coming Soon
* SMS alerts
