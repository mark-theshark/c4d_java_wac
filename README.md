# Java workspace template for a Coder for Docker (localhost) deployment

This WAC file for Coder for Docker - uses Coder's template feature to automate and configure-as-code the parameters of a Java-related workspace ( aka development environment )

Press the button to authenticate into a Coder deployment and execute the coder.yaml

###### https://coder.com/docs/coder/latest/workspaces/workspace-templates

###### localhost:7080 embeddable button to run the template 
[![Open in Coder](https://cdn.coder.com/embed-button.svg)](http://localhost:7080/wac/build?template_oauth_service=github&template_url=git@github.com:mtm20176/c4d_java_wac.git&template_ref=main&template_filepath=.coder/coder.yaml)

###### localhost:7080 embeddable button to build a workspace for the Java image (not using a template)
[![Open in Coder](https://cdn.coder.com/embed-button.svg)](http://localhost:7080/workspaces/git?org=default&image=61b1920f-53d4154a13c2dfce7fe34a2c&tag=ubuntu&service=github&repo=git@github.com:mtm20176/c4d_java_wac.git)

###### Notes / To run this app after cloning, we recommend:

* builds a Coder workspace container

* injects Coder's code-server open-source project to run VS Code in a browser

* installs VS Code extensions for Java development

* clones a GitHub Java Helo World repository