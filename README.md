# surl
The tiniest Semantic URL framework for Coldfusion (Railo, Adobe, OpenBD). Semantic URLs are also known as User-Friendly URLs
 
# Pre-reqs
- IIS 6+
- IIS Rewrite Module http://www.iis.net/downloads/microsoft/url-rewrite
- Railo, Adobe Coldfusion, OpenBD

# Install
Copy the ``web.config`` file and the ``__engine`` folder into your root site folder

# How to use
As a test open up ``http://yoursite.com/hello/cruel/semantic/world``

By default it will show a dump of the path attempted to be accessed: ``hello/cruel/semantic/world``

From that point, based on the ``path`` found in the ``url`` scope, you can do path validation, define actions, setup controllers, etc...
