## [object Object]

[object Object]

### CI/CD with GitHub Actions

* [object-Object/objectobject.ca](https://github.com/object-Object/objectobject.ca):
  * Cloudflare DNS for https://objectobject.ca via [CDKTF](https://developer.hashicorp.com/terraform/cdktf)
  * Common resources used by other workflows (including OIDC, IAM, and S3) via [AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/home.html)
* [object-Object/hexxy.media](https://github.com/object-Object/hexxy.media):
  * Cloudflare DNS for https://hexxy.media via [CDKTF](https://developer.hashicorp.com/terraform/cdktf)
  * Deploying https://hexxy.media/api/v0/docs to a VPS via [CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html), with automated health checks and rollbacks
  * Provisioning CodeDeploy resources via [AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/home.html)
* [object-Object/HexBug](https://github.com/object-Object/HexBug):
  * Deploying HexBug (a Discord bot) to a VPS via [CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html), with automated health checks and rollbacks
  * Provisioning CodeDeploy resources via [AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/home.html)
* [hexdoc-dev/hexdoc](https://github.com/hexdoc-dev/hexdoc):
  * Automated builds and unit/integration testing for every commit and PR
  * PyPI releases for https://pypi.org/project/hexdoc/
  * Building and deploying https://hexdoc.hexxy.media to GitHub Pages
  * Reusable workflows used by other hexdoc projects for CI/CD
* [hexdoc-dev/minecraft-render-py](https://github.com/hexdoc-dev/minecraft-render-py):
  * Automated builds for every commit
  * PyPI releases for https://pypi.org/project/minecraft-render/
  * NPM releases for https://www.npmjs.com/package/@leftsquarebracket/minecraft-render
* Other projects with PyPI release workflows:
  * [hexdoc-dev/hatch-gradle-version](https://github.com/hexdoc-dev/hatch-gradle-version) (https://pypi.org/project/hatch-gradle-version)
  * [hexdoc-dev/hexdoc-minecraft](https://github.com/hexdoc-dev/hexdoc-minecraft) (https://pypi.org/project/hexdoc-minecraft)
  * [hexdoc-dev/hexdoc-latex](https://github.com/hexdoc-dev/hexdoc-latex) (https://pypi.org/project/hexdoc-latex)
