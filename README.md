# ansible-inclusion

This repository is used for requests to include new collections into the `ansible` package.

We use GitHub [Discussions](https://github.com/ansible-collections/ansible-inclusion/discussions) feature to track these requests.

Regular community reviewers will be offered to join the [Ansible Community Steering Committee](https://docs.ansible.com/ansible/devel/community/steering/community_steering_committee.html).

See the [Collection inclusion policy](https://docs.ansible.com/ansible/devel/community/steering/community_steering_committee.html#collection-inclusion-requests-workflow) to learn how the collection inclusion process works.

## Timeline

New collections can be included in every minor release of the `ansible` package. These happen roughly every three weeks.

For new major releases (X.0.0), new collections have to be added before the feature freeze. If they miss feature freeze, they have to wait for the next minor release (X.1.0). Deadlines for the `ansible` package can be found in the [ansible roadmaps](https://docs.ansible.com/ansible/devel/roadmap/ansible_roadmap_index.html).

[The Ansible docsite](https://docs.ansible.com/ansible/devel/collections/community/index.html), the `devel` version, will refer to a collection's documentation within a day after the collection inclusion is done. The `latest` version will show the references after the following Ansible release.

## Existing request

* [New collection reviews](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/new-collection-reviews)
* [Second review needed](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/second-review-needed)
* [Resolved requests](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/resolved-reviews)

## Submission process

All new collections submitted for inclusion MUST satisfy the [Collection Requirements](https://github.com/ansible-collections/overview/blob/main/collection_requirements.rst). Before submitting, please appreciate the time of volunteer reviewers by making sure your collection satisfies the requirements.

If there are any questions, feel free to ask for clarifications in the discussion described below and/or in the `#ansible-community` [Matrix/IRC channel](https://docs.ansible.com/ansible/latest/community/communication.html#real-time-chat).

1. Review one of the collections submitted for inclusion by other developers in the following categories:
  * [second review needed](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/second-review-needed)
  * [new collection reviews](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/new-collection-reviews)

This step is **optional** but it can significantly reduces the time for your collection to get in (finally it will depend on your collection's quality) because:
  * You will gain experience when reviewing someone else's collection. It will allow you to make your collection better before submitting it and will save your and reviewer's time and effort as there will probably be fewer issues to fix.
  * The Steering Committee will handle your request with a higher priority.

You can also offer your help with reviewing other's requests after you submit your collection.

2. Start a GitHub Discussion in the [new collection review category](https://github.com/ansible-collections/ansible-inclusion/discussions/new?category=new-collection-reviews).  Please copy the following into your initial message (only after you carefully read and make your collection satisfying the [Collection Requirements](https://github.com/ansible-collections/overview/blob/main/collection_requirements.rst)):
```
Two or three sentence description of your collection.

Ansible Galaxy: https://galaxy.ansible.com/NAMESPACE/COLLECTION
GitHub: https://github.com/ORG/REPONAME
Issues Tracker: https://github.com/ORG/REPONAME/issues
GitHub Handles: 
Is the collection part of Automation Hub: Yes/Soon/No
We meet [Collection Requirements](https://github.com/ansible-collections/overview/blob/main/collection_requirements.rst): Yes/No
```
In case the repository is not on GitHub, please provide email addresses.

If you reviewed someone else's collection, please specify it too.

3. Ensure any other maintainers of the collection are `@mentioned` in the discussion so they will receive updates.
4. Promptly reply to any questions.

## Review process

1. Choose a review request from the [New collection reviews](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/new-collection-reviews) or [Second review needed](https://github.com/ansible-collections/ansible-inclusion/discussions/categories/second-review-needed) categories. Give a much higher priority to collections whose maintainers reviewed someone else's collection (see discussion descriptions for this information).
2. Copy the [Review checklist](https://github.com/ansible-collections/overview/blob/main/collection_checklist.md) into the request.
3. Go through the checklist:
  * Mark bullet points as complete when a collection satisfies the requirements.
  * If the collection does not satisfy a requirement, add `MUST FIX:` below the corresponding bullet point + an action needed from collection maintainers.
  * If the collection satisfies a requirement but the implementation can be improved, add `SHOULD FIX:` + an action needed.
  * If you have questions to maintainers, add `COMMENT: ` + your question.

See the [complete example](https://github.com/ansible-collections/ansible-inclusion/discussions/24#discussioncomment-1485070).
