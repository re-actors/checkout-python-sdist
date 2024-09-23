# `re-actors/checkout-python-sdist@release/v1`

A GitHub Action to unpack a source distribution package
(tarball / `.tar.gz`) into the current workspace.


## Options

This action only has two inputs — `source-tarball-name` (default:
`*.tar.gz`) and `workflow-artifact-name` (default:
`python-package-distributions`). It downloads the latter and works with
the sdist matching the former glob to make its contents available in the
current working directory.


## Any users?

At the moment, it is used by [@aio-libs], [@CherryPy], [pip-api],
[some Ansible projects], with more to come.


## License

The contents of this project is released under the
[BSD 3-clause license].


[BSD 3-clause license]: LICENSE
[@aio-libs]: https://github.com/aio-libs
[@CherryPy]: https://github.com/cherrypy
[pip-api]: https://github.com/di/pip-api
[some Ansible projects]:
https://github.com/search?q=org%3Aansible+%22uses%3A+re-actors%2Fcheckout-python-sdist%22+path%3A.github%2Fworkflows%2F&type=code
