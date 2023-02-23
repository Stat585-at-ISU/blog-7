
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![Frontmatter
check](../../workflows/check-yaml.yaml/badge.svg)](../../workflows/check-yaml.yaml)
[![Render
rmarkdown](../../workflows/render-rmarkdown.yaml/badge.svg)](../../workflows/render-rmarkdown.yaml)
<!-- badges: end -->

In Blog 5 you had the first exposure to Github Actions. We just checked
frontmatter compliance (as we do for this round). You see that we have
added a second action - here, we are converting the Rmarkdown document
to a markdown file by running `render_rmarkdown` on Github. This action
passes successfully for this document. We want to do something similar
for blog \#4.

Now start reading …

Read the vignette [Introduction to
renv](https://rstudio.github.io/renv/articles/renv.html) for the `renv`
R package by Kevin Ushey.

Then do:

1.  **Install the R package `renv` on your local machine.**

2.  **In the project for blog 4, initialize the workflow used by the
    `renv` package.**

3.  **Add all dependencies to the environment (implicitly by installing
    all the depepndencies or explicilty by listing dependencies in a
    DESCRIPTION file).**

4.  **Add the `renv` folder to your blog 4 repository, and push the
    changes.**

5.  **Is the github action working? Read any potential error messages in
    the workflow and try to fix things. Make sure to check stackoverflow
    for help, don’t forget our Discussion board!**

Write a blog post addressing the following questions:

1.  **What is the idea of the renv package?**

2.  **In 50 to 100 words describe your experience working with `renv`.
    What went well? What did not go so well?**

Submit this blog post to your blog-6 repo.
