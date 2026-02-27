---
icon: lucide/info
---

# Overview

The CLOG Documentation project aims to provide everything a developer might need to build successful applications with the *Common Lisp Ominificent GUI framework*. This section provides everything that you need to know about the how and why of the documentation project including ***Markdown Examples*** and ***Markdown in 5 min*** that will give you 90% of what you need to know to get you started editing and writing documentation.

## The key goals of this documentation project

Documentation isn't static. It is an ongoing effort that needs to keep up with developers at speed and with accuracy. In order to build the best possible foundation for this project, we set the following goals for the project. 

- **MARKUP** - The markup syntax must be a simple as possible and no simpler..
- **TECHNOLOGY** - The software must publish beautiful documentation with the easiest to run solution with *just enough* features and plugins for flexibility. 
- **LICENSING** - The solution must be FOSS licensed.
- **SUPPORT** - An adequate community of users and developers should exist.
- **FUTURE PROOFING** - The solution needs to have a reasonable horizon for growth and development.

## Our documentation platform - Zensical

We are always open to discovering new documentation platforms and approaches, nothing is set in stone. For now, we chose Zensical as our documentation platform. It integrates nicely with Github Pages and currently meets all of the goals we were looking for.

### Why Zensical and not Material for MkDocs?

Material for MkDocs is a theme for MkDocs. MkDocs development continues but the development of Material for MkDocs stopped as of Nov 17, 2025.  The developers of the project moved on to build Zensical whose goal is to fully cover all MkDocs features and build out beyond where MkDocs leaves off

### Why not other solutions like Docusaurus, Jekyll, Hugo or similar? 

In testing, either the platforms were too powerful or required to technical expertice that would prevent the average contributor to setup their own local instance or they were not able to publish documentation with a default look and feel that did not require substantial customization and configuration. MkDocs by default is pretty good and probably adequate for our needs but the Zensical default theme requires less configuration out of the box.

### Missing features.

The one feature that we are looking for that we are not exactly happy with is maintenance of documentation versions. Material for MkDocs uses a Python module called Mike to manage documentation versioning. The Zensical roadmap indicates that they are going to build this feature in the future so we can revisit this issue at that point. This is a wishlist item and not a hard requirement.

### What about a CLOG based solution in the future?

Projects already exist aiming to build out competitive solutions. When they are ready we will review and compare at that time.

### I want to contribute, how do I start?

Great! The simplest way is to read the [**Markdown Examples**](markdown-examples.md) and [**Markdown in 5min**](markdown-in-5min.md) to get started. Then, just fork this repo, edit and submit a pull request!  We will provide detailed instructions on installation of Zensical and workflow suggestions in the near future.





