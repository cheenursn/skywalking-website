# Apache SkyWalking webpage
This is the repository including all source codes of `http://skywalking.incubator.apache.org` and `http://skywalking.io`.

Apache Infra deploys the webpage in branch `asf-site`, SkyWalking team governs sourse in branch `master`.

## Contribution
Please contribute the website to branch `master`

## How to generate HTMLs in asf-site
Note, branch `asf-site` don't accept pull request, all `asf-site` branch HTMLs should be generated by SkyWalking PPMC members or Robot.

Usage:
1. Git pull branch `master`
1. Entry `/jekyll-source`
1. Run `jekyll build --source jekyll-source/ --destination _site`
1. Move all files in `_site` to `/` folder, and remove `_site`.
1. Push all files to `asf-site`.