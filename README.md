A work-in-progress project. Ultimately, the goal is to create a bot that will:

1. Perform a GET request on a given URL
   1. Custom headers maybe too
   1. Session control?
1. Parse the data from the response
   1. HTML/XML/JSON/PDF/?
1. Store as a snapshot
1. Compare to previous snapshot
1. If different, send an alert
   1. Email/push notification/webhook

With the following features:

* Run change checks at user-provided intervals, customizable per URL
* Run change checks manually
