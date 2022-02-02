# ansible-inclusion
Requests to include new collections into the `ansible` package.

We use GitHub's Discussion feature to track these requests.

## Timeline

New collections can be included in every minor release of the `ansible` package. These happen roughly every three weeks.

For new major releases (X.0.0), new collections have to be added before the feature freeze. If they miss feature freeze, they have to wait for the next minor release (X.1.0). Deadlines for the `ansible` package can be found in the [`ansible` roadmaps](https://docs.ansible.com/ansible/devel/roadmap/ansible_roadmap_index.html).

## Existing request

* [New Collection reviews](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/new-collection-reviews)
* [Resolved requests](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/resolved-reviews)

## Process

All new collections submitted for inclusion MUST satisfy the [Collection Requirements](https://github.com/ansible-collections/overview/blob/main/collection_requirements.rst).
If there are any questions, feel free to ask for clarifications in the discussion described below and / or in the `#ansible-community` IRC channel.

1. Start a GitHub Discussion in the [new collection review category](https://github.com/ansible-collections/ansible-inclusion/discussions/new?category=new-collection-reviews).  Please copy the following into your initial message:
```
Two or three sentence description of your collection

Ansible Galaxy: https://galaxy.ansible.com/NAMESPACE/COLLECTION
GitHub: https://github.com/ORG/REPONAME
Issues Tracker: https://github.com/ORG/REPONAME/issues
GitHub Handles: 
Is the collection part of Automation Hub: Yes/Soon/No
We meet [Collection Requirements](https://github.com/ansible-collections/overview/blob/main/collection_requirements.rst): Yes/No
```
In case the repository is not on GitHub, please provide email addresses.

2. Ensure any other maintainers of the collection are `@mentioned` in the discussion so they will receive update.
3. Promptly reply to any questions.

