# Update the presence of a Zoom user based upon an inbound interaction

This Genesys Cloud Developer Blueprint explains how to set up Genesys Cloud and Zoom to update a Genesys Cloud agent's presence in Zoom at the start and end of an inbound Genesys Cloud voice interaction.

When an Architect workflow receives an inbound interaction, a Zoom API call is sent to the Zoom user that is associated with the Genesys Cloud agent who is assigned to the interaction. The Zoom user's presence is set to "Do Not Disturb" when the voice interaction begins. When the interaction ends, the Zoom user's presence is set to "Available."

The following illustration shows the presence solution from an agent’s point of view.

![Zoom presence update from an agent's point of view](images/zoom-workflow.png "Zoom presence update from an agent's point of view")

The following shows the end-to-end agent experience that this solution enables.

![End-to-end agent experience](images/ZoomGCPresenceSyncBlueprint.gif "End-to-end agent experience")

To trigger Zoom presence updates from Genesys Cloud, you use several public APIs that are available from Genesys Cloud and Zoom. The following illustration shows the API calls between Genesys Cloud and Zoom.

![The API calls between Genesys Cloud and Zoom](images/zoom-architect.png "The API calls between Genesys Cloud and Zoom")

> View the full [Update the presence of a Zoom user based upon an inbound interaction ](https://developer.genesys.cloud/blueprints/update-zoom-presence-from-inbound-interaction-trigger-blueprint) in the Genesys Cloud Developer Center.
