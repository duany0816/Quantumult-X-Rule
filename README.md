Difference between Quantumult X versions
Store version QX1.0.0 (120) JS function is unlimited, but does not support v2, does not support AlwaysOn

Store version QX1.0.1 (130) restricts keywords for script VIP types, but supports v2 and supports AlwaysOn

Store version QX1.0.2 (136) Relaxed certain keyword restrictions, but limited script remote references (script subscriptions), support for v2 and support for http and support AlwaysOn

Store version QX1.0.3 (155) Removed keyword restrictions and restored script remote references. However, the content in the remote script needs to be annotated with the device ID before it can be executed.

Store version QX1.0.4 (164) This version completely limits remote script resources, meaning that all scripts can only point to local paths.

Store version QX1.0.5 (192) Remote script resources are unavailable, but "task" script functionality is added.

Store version QX1.0.6 (212) Supports rewrite of HTTP request body, and replay of HTTP request

Store version QX1.0.7 (240) Supports TLS 1.3 for TLS based proxy protocols, and new external proxy protocol trojan.
