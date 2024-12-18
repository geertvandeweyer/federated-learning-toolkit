---
title: Editors checklist
summary: Checklist for editors before approving and merging a pull request (PR).
---

## Before approving and merging a pull request (PR), the editors must check that

1. The page layout in the preview looks correct.
2. The new page is linked in the appropriate [sidebar]({{site.REPO}}/tree/master/_data/sidebars) menu, in the same
   branch of the PR.
3. The contributors' names are listed in the [CONTRIBUTORS file]({{site.REPO}}/blob/master/_data/CONTRIBUTORS.yaml), in
   the same branch of the PR. Advice to have at least one contributor per page having its contact information in
   this  [CONTRIBUTORS file]({{site.REPO}}/blob/master/_data/CONTRIBUTORS.yaml).
4. All relevant metadata fields in a specific page are correctly filled in (see the [page metadata](page_metadata) and
   the [Editorial board guide](editorial_board_guide)). Some critical ones are listed below.
    * unique `page_id` ([List of page IDs](website_overview))
    * `contributors`
    * `related_pages` ([Related pages](editorial_board_guide.html#related-pages))
    * `training`
    * `search_exclude` must be deleted
    * `description`
    * `affiliations`
    * `coordinators`(only used in national pages + they must be listed as `contributors` as well)
    * `resources`
5. Make sure that listed tools or resources are tagged in the text with the [correct snippet](tool_resource_update) +
   that its metadata is described in
   the [tool_and_resource_list.yml]({{site.REPO}}/blob/master/_data/tool_and_resource_list.yml)
   file.
6. The content conforms to FLkit's scope, [style](style_guide) and templates.
7. There are no [copyright](copyright) issues related to the content of the page.
8. The contributors implemented the requested changes.
9. When a new page is added, a news item is added to
   the [news.yml file]({{site.REPO}}/blob/master/_data/news.yml), in the same branch of the
   PR.
10. The contributors are acknowledged for their efforts and informed about the publication of their content.
11. The PR is linked to related issues and can be merged into the main branch with no conflicts.
