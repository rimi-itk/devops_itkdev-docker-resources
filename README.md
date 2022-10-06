# ITK-dev docker setup resources

Configuration files for [ITK-dev docker
setup](https://github.com/itk-dev/devops_itkdev-docker)

## SSH config

[`ssh/config.d/`](ssh/config.d/) contains default SSH config files for ITK
Development servers and can be included in your
[`~/.ssh/config`](https://man7.org/linux/man-pages/man5/ssh_config.5.html) file
(see “Include” in <https://man7.org/linux/man-pages/man5/ssh_config.5.html> for
details).

Run `./bin/ssh-config-helper`(./bin/ssh-config-helper) to get started.

**Note**: Your ssh version (`ssh -V`) must be `7.3p1` or newer for this to work.
