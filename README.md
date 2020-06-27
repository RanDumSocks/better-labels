# Better Default GitHub Labels
Don't like the default github labels? Me neither, so this is a template for a better labeling system based off of [this article](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63) (with some differences and additions).

Use this [GitHub label manager](http://www.dorukdestan.com/github-label-manager/) for easy label copy/paste between repositories.

## Label Categories
There are three main types of labels; each one _should occur once_, and only once:
- Priority
  - Tells the importance of each issue.
- Status
  - Shows the state of the issue.
- Type 1
  - Should be shortened just to 'Type'. Tells what the issue itself is about.

There is one optional label:
- Type 2
  - Better thought as 'Location'
  - Better narrows down the issue type.

## Specific Label Definitions

### Priority Labels
- ![Priority: Low]
  - Issue dealing more with polish rather than functionality
- ![Priority: Medium]
  - Average priority
  - Default, go-to priority with a significant impact on functionality
- ![Priority: High]
  - Significant, possibly build breaking issue
- ![Priority: Critical]
  - Typically used for an important hot-fix issue
  - Main functionality depends on this issue being solved

### Status Labels
- ![Status: Pending]
  - New issues, not reviewed by someone on the developer team for a proper status label.
- ![Status: Available]
  - Approved as a valid issue but has not yet been assigned.
- ![Status: Accepted]
  - Issue is assigned to a developer but is not currently being worked on.
- ![Status: In Progress]
  - Issue is actively being worked on.
- ![Status: Completed]
  - Issue has been solved and committed.
  - This issue will be closed if live on the master branch, else it will be open with this label.
    - Do not close an issue if it has not been merged with master, simply change the status label to this.
- ![Status: On Hold]
  - These typically mark stretch-goals.
- ![Status: Revision Needed]
  - Is an issue not documented enough or doesn't make sense?
  - Also used for issues that may need more questions asked about how they should be implemented.
- ![Status: Duplicate]
  - As title suggests, another issue already exists that is similar to or exactly this issue.
- ![Status: Abandoned]
  - Issues that are completely disregarded. It probably didn't work out well or is irrelevant to the project.

### Type 1 Labels
- ![Type 1: Bug]
  - Self-explanatory, thar be a bug.
- ![Type 1: Maintenance]
  - Maintenance issues don't typically have a direct visual impact on the live version of the project.
  - These refer to anything related to organization or code refactoring.
- ![Type 1: Question]
  - Anything that does not affect the code is probably a question.
- ![Type 1: Enhancement]
  - If the issue does not fall into any other Type 1 category, it falls into an Enhancement.
  - Enhancements are general changes to the visual aspect of the project. They can be adding or removing features, or changes to existing features.
- ![Type 1: Wiki]
  - Anything that needs to be added to the GitHub wiki page.
  - This label is special because it doesn't specifically deal with development, but documenting development.

### Type 2 Labels
These do not need to be listed individually, because the use is quite literally on the title itself. These are 'location' labels, and should be used to narrow down the issue to a specific area of work. These are optional, but encouraged to use for organization with filters.

[Priority: Critical]: https://user-images.githubusercontent.com/23219465/67315247-05825500-f4bb-11e9-8a9f-5bbd8c326f17.png "Priority: Critical"
[Priority: Low]: https://user-images.githubusercontent.com/23219465/67315264-0fa45380-f4bb-11e9-8eb8-5de25d8cf801.png "Priority: Low"
[Priority: Medium]: https://user-images.githubusercontent.com/23219465/67315293-1df26f80-f4bb-11e9-8ded-f4153438dc82.png "Priority: Medium"
[Priority: High]: https://user-images.githubusercontent.com/23219465/67315312-29de3180-f4bb-11e9-9224-6fa603fa2a78.png "Priority: High"
[Status: Pending]: https://user-images.githubusercontent.com/23219465/67315328-34003000-f4bb-11e9-99e4-addff86caee8.png "Status: Pending"
[Status: Available]: https://user-images.githubusercontent.com/23219465/67315354-40848880-f4bb-11e9-882a-12b3d3eac76c.png "Status: Available"
[Status: Accepted]: https://user-images.githubusercontent.com/23219465/67315375-4b3f1d80-f4bb-11e9-92c3-c1a6f54a258d.png "Status: Accepted"
[Status: In Progress]: https://user-images.githubusercontent.com/23219465/67315405-5b56fd00-f4bb-11e9-9213-d1da9fa33a47.png "Status: In Progress"
[Status: Completed]: https://user-images.githubusercontent.com/23219465/67315425-690c8280-f4bb-11e9-8581-d1ae4abb4f36.png "Status: Completed"
[Status: On Hold]: https://user-images.githubusercontent.com/23219465/67314332-598c3a00-f4b9-11e9-91d0-0ec3c701c1e8.png "Status: On Hold"
[Status: Revision Needed]: https://user-images.githubusercontent.com/23219465/67314731-14b4d300-f4ba-11e9-9f08-c44a9f65522d.png "Status: Revision Needed"
[Status: Duplicate]: https://user-images.githubusercontent.com/23219465/67314818-2e561a80-f4ba-11e9-9dfd-75247b127cd5.png "Status: Duplicate"
[Status: Abandoned]: https://user-images.githubusercontent.com/23219465/67314922-66f5f400-f4ba-11e9-8a25-a09a0902f185.png "Status: Abandoned"
[Type 1: Wiki]: https://user-images.githubusercontent.com/23219465/67315052-a0c6fa80-f4ba-11e9-9614-24eef83b61e6.png "Type 1: Wiki"
[Type 1: Bug]: https://user-images.githubusercontent.com/23219465/67315451-775a9e80-f4bb-11e9-8bb4-e417e175e640.png "Type 1: Bug"
[Type 1: Enhancement]: https://user-images.githubusercontent.com/23219465/67315471-817c9d00-f4bb-11e9-9196-e079a9dc855f.png "Type 1: Enhancement"
[Type 1: Maintenance]: https://user-images.githubusercontent.com/23219465/67315493-8d685f00-f4bb-11e9-8089-f83b2bcfa1ed.png "Type 1: Maintenance"
[Type 1: Question]: https://user-images.githubusercontent.com/23219465/67315521-978a5d80-f4bb-11e9-89bd-21b7d9744f23.png "Type 1: Question"
