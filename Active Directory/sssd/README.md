sssd configuration file that I run on my Linux servers.

Changes were done to:

  fallback_homedir

  use_fully_qualified_names

In fallback_homedir, I removed "@%d" so the home directory doesn't get created with the domain name.

In use_fully_qualified_names, it was set to False so you don't have to include the domain name when trying to log-in.
