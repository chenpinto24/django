MY HALF PAGER ON THE BONUS
first i forked the django repo and activated branch protection, merge request approved with one minumum reviewer approval, all checks to pass, and all conversations to be
resolved.built a ci pipeline that runs pylint for code analysis warning,built a docker for testing, ran testing using pytest then pushed the reports and the docker image to s3 bucket.
created a cd pipeline to run when a pr is merged to main branch,repeated the ci steps, increased the version and pushed a tag with version name, built the repo as distribution package and published as release on github.
