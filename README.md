# open-memorial
Open Memorial is an open source, federated platform for sharing memories about our loved ones.

Key features to build:
* It is cloud-native, modular, repeatable, and shareable.
* Open Memorial uses identities, geolocation, and historical data to build Memorial records.
* Users can add Memories to Memorials, logging in with a federated identity.
* Users are respected. Geo fencing is anonymous and user data is not shared, other than Memories.
* Memories are shared publicly, and can contain a photo and a block of text.
* Privately-run federated servers can be set up, to enable local moderation, hosting, and sharing of Memories, as in for a memorial service or a cemetery walk.
* Memories are shared between federated servers, so anonymous users can browse all Memories.

Technologies needed:
* Geolocation of fixed points (graves, memorials, other points as needed)
* Geo fencing for clients (no trackers, anonymous)
* Social/sharing platform (text upload, photo upload, federated ID/OIDC, no trackers, anonymous browsing mode). Likely ActivityPub compliant. Check out this list: https://codeberg.org/fediverse/delightful-fediverse-apps#user-content-social-networks-microblog-apps.
* Payment processing, to reduce bots and cover cloud hosting costs for public instance (someday, maybe)
