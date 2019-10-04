# API-DOS_POC

The most common type of Layer 7 attacks is so-called HTTP floods, which send seemingly legitimate requests in too large numbers. They are particularly effective when they target resource-hungry elements of the web application, such as large file downloads or form submissions.

![HTTP Flood Attack](https://security.syafiqhadzir.dev/assets/images/http-flood-attack.webp)

When flooding, the attacker wants to submerge the target server under many requests, to saturate its computing resources. Flooding works best when the server allocates a lot of resources in response to a single request.

Since POST requests include parameters, they usually trigger relatively complex processing on the server (e.g. database accesses), which are more expensive for the server than serving a much simpler GET. Thus, POST-based flooding tends to be more effective than GET-based flooding (it takes fewer requests to drown the server if the requests are POST). On the other hand, GET requests being much more common, it is often way easier for the attacker to enlist (involuntary) help in the flooding effort when GET-flooding.
