mopidy
=========

Installs and configures mopidy, iris and (optionally) mopidy-spotify.

Requirements
------------

For `mopidy-spotify`: A Spotify Premium account.

Role Variables
--------------


| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`mopidy_spotify_enabled` | "false" | Whether to enable Spotify plugin
`mopidy_spotify_username` | "changeme" | Username for Spotify
`mopidy_spotify_password` | "changeme" | Password for Spotify
`mopidy_spotify_client_id` | "changeme" | Client ID for Spotify
`mopidy_spotify_client_secret` | "changeme" | Client Secret for Spotify

Dependencies
------------

None.

To expose mopify I recommend using my `nginx` role.

Example Playbook
----------------

See `molecule/default/playbook.yml`.

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
