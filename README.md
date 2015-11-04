# ESDSWG Search Relevance Working Group 

<img src="https://earthdata.nasa.gov/img/earthdata-fb-image.jpg" align="right" width="300" />

## Introduction
This is the repo for the <a href="https://wiki.earthdata.nasa.gov/display/ESDSWG/Search+Relevance+Working+Group">Earth Science Data Systems Working Groups Search Relevance Working Group</a> (WG).

Issue tracking is disabled in this repo. If you have comments on anything you see here, please send mail to <a href="mailto:esdswg-search@lists.nasa.gov">esdswg-search@lists.nasa.gov</a> [<a href="https://lists.nasa.gov/mailman/private/esdswg-search/">archive</a>]
(members of the WG should use the regular <a href="mailto:esdswg-search@lists.nasa.gov">WG mailing list</a>.

The repo includes editors' drafts of the deliverables and notes of the Working Group. Take a look at the <a href="https://wiki.earthdata.nasa.gov/display/ESDSWG/Search+Relevance+Working+Group#SearchRelevanceWorkingGroup-WGProposalsandActionPlans">WG Proposals and Action Plans</a> for more details and the complete list of deliverables of the WG. 

To see action, visit https://lewismc.github.io/esdswg_sr

The chairs of the group are <a href="https://www.linkedin.com/pub/ed-armstrong/56/69a/613">Ed Armstrong</a> and <a href="https://www.linkedin.com/in/lmcgibbney">Lewis John McGibbney</a>.

## Contributing

In order to keep everything synced and updated, these steps are recommended to configure a remote repository for your fork.

**Configuring upstream**

Run `$ git remote -v` to list the current remote repository.

If there is only the `origin` repository configured, it's necessary to specify a new remote *upstream* that will be synced with the fork.

```$ git remote add upstream https://github.com/lewismc/esdswg_sr.git```

After that, the upstream will be listed on the remote list.

This is a one-time setup procedure.

**Keeping the repository synced**

    $ git fetch upstream
    $ git checkout gh-pages
    $ git merge upstream/gh-pages
