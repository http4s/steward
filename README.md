# http4s Steward

Runs the [scala-steward-action](https://github.com/scala-steward-org/scala-steward-action) daily to update the dependencies of http4s projects.  Pull requests are opened by the [http4s-steward app](https://github.com/organizations/http4s/settings/apps/http4s-steward).

## Adding a repo

Edit the [repos.md](https://github.com/http4s/steward/edit/main/repos.md) file.  This action uses a GitHub token for the http4s installation of http4s-steward and will only work on projects in the http4s org.  For external projects, see [diy-steward](https://github.com/armanbilge/diy-steward/).
