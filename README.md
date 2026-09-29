# IRCODE

IRCODE identifies specific images. Show it a picture, poster, painting, product
shot or ad, and it tells you which registered image it is and what information
is known about it: the title, creator, links and details.

IRCODE's database grows every day, and if something isn't recognized yet, you
can add it yourself. Register an image and anyone who points a phone at it, or
asks their assistant about it, gets the title and link you attached. There is no
QR code or overlay; the picture itself becomes the code. Sign in to make your
registrations permanent and manage them on ircode.app, and even register a video
so every part of it is recognizable.

## Things to ask

- "Ask IRCODE what this is" with a link to an image, or a photo sent through the
  in-chat picker
- "Use IRCODE to make this image scannable and link it to my site"

## What's in the plugin

- **The IRCODE connector**, a remote MCP server at `https://api.ircode.app/mcp`
  with three tools: identify an image, look up an IRCODE by its link or ID, and
  register an image.
- **Two skills**, `identify-image` and `make-image-scannable`, that tell the
  assistant which requests those tools answer and how to use them.

The plugin runs nothing on your computer.

## What it sends

Pictures you ask it to identify or register go to IRCODE, along with what you
give a registration, such as its title and link. A lookup sends the IRCODE link
or ID you gave it. A match is recorded in that image's scan history, and its
owner may be notified. Registrations are public; made without signing in, they
delete themselves after 24 hours. Signing in, needed only to keep a registration
or register a video, happens on ircode.app and gives IRCODE permission to act on
your IRCODE account, and nothing else about you. The
[privacy notice](https://ircode.com/privacy) has the details.

## Links

- Help: https://api.ircode.app/mcp#help
- Privacy: https://ircode.com/privacy
- Terms: https://ircode.com/terms
- Website: https://ircode.com
