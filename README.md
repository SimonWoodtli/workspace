# Container Workspace Environment for Development

This image is a customized workspace that includes all the tools I need for my
terminal-centric workflow and gets updated and rebuild daily. This not only
allows me to set up and maintain an up-to-date workspace, but it also helps me
keep track of my personalized installation data. Moreover, a GitHub Action is
set up to update packages and rebuild the image on a daily basis, ensuring that
I have access to the latest features and enhancements. The ultimate goal of
this setup is to provide a seamless and cloud-native UNIX terminal experience
that can be used in conjunction with a dotfile manager for
a zero-configuration, 'it just works' experience out of the box.

Not only can this image be used as a standalone on any machine that has
docker/podman installed, but it also seamlessly integrates with [my
cloud-native desktop][silverblue-os] setup, providing an even more
comprehensive experience.

Related:

* <https://github.com/ublue-os>
* <https://github.com/rwxrob/workspace>
