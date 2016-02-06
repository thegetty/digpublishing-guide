## Updates and Revisions

For updates and revisions to digital books, Getty Publications follows something like a traditional book publication model. Updates are made in regulated, formal batches as new editions and are always thoroughly documented in the publications' repositories, as well as in the published Revision History included in each of the books. In this way, readers can be comfortable citing these digital publications, knowing that citation will be verifiable in the future. And internally, this policy helps us to manage the workflow on the book, avoiding a cycle of making continual updates to the books with each new desired correction.

### Version Control

All Getty Publications digital publication files are hosted on GitHub, or a similar version control service. The repositories of all books that are published open access or Creative Commons licensed are made public at the time of publication if not before.

The `master` branch of a book's repository is protected and always to reflect the current published version.

Any `revisions` branches will show corrections and updates currently under consideration, or those made and subsequently merged into the `master` branch as a new edition.

 Revisions branches are named as `second-edition-revisions`, `third-edition-revisions`, etc.

### Publishing the Revisions History

All digital books are published with a Revisions History listing on the Copyright or About page, as in the example below. This history is updated with each new edition, and should communicate the primary changes made. The list of changes need be only an overview, as complete details are always available in the code repository for the publication.

> Any revisions or corrections made to this publication after the first edition date will be listed here and in the project repository at [https://github.com/gettypubs/...](https://github.com/gettypubs/), where a more detailed version history is available. The revisions branch of the project repository, when present, will also show any changes currently under consideration but not yet published here.

> **January 31, 2016**

> First edition

> **May 1, 2017**

> Second edition<br />
> • Minor text corrections<br />
> • Revised bibliographic info on Cats. 1–3<br />
> • Updated backend coding for interactive map

### Policy on How Revisions are Made

All new suggested content corrections—whether from public submission, author request, or internally—are reviewed by the book's original project editor or the Editor-in-Chief. When approved, changes are entered by them or the digital publications team on the appropriate `revisions` branch. This is an ongoing process, and changes should be made with commit messages specific enough for public understanding.

When a significant quantity or quality of corrections accumulate, as determined by the editor, the current `revisions` branch is merged into the `master` branch to create a new edition of the book. A corresponding update to the Revision History published in the book should also be made at this time.

Digital Publications team then ensures the new edition is deployed to the live site, and distributed to the appropriate vendors as needed.

ISBNs and other identifiers are not changed with these revised editions. Only in cases of significant content changes or overhauls will we re-release the book with a new ISBN. And in these cases, the original edition will be maintained as a separate publication, not simply updated or overwritten.

### Code Updates

Along with content corrections, there may also occasionally be need to make updates to the code underlying a book. These are done by the Digital Publications team, separate from any active `revisions` branches, with consultation to the project editor. Unless there are changes the content or front-end structure of the book that would effect readers citation of the book, or reading of it's content, these updates will not be recorded in the Revisions History as such, but only in the project repository.
