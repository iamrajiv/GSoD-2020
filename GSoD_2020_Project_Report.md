<div align="center">
<img src="assets/gsod-2020.svg" height="auto" width="400" />
<br />
<h1>gRPC-Gateway</h1>
<h3>
Refactoring the Existing Docs Site of gRPC-Gateway
<br />
Project Report
</h3>
</div>

## Introduction

This is the project report for **Refactoring the Existing Docs Site of gRPC-Gateway** which was completed during Google Season of Docs 2020. The status of the project can be regarded as complete due to the fact that all pull requests have been merged and all the initial premises of the project have been fulfilled.

Final Work Product: [https://grpc-ecosystem.github.io/grpc-gateway/](https://grpc-ecosystem.github.io/grpc-gateway/)

## Work Summary

#### Community Bonding (August 17 - September 13, 2020):

- Bi-weekly meeting schedule agreed.
- gRPC-Gateway slack channel invite was arranged.
- Focus in the first three weeks before the start of the project was on:
  - Working through existing documentation and note gaps areas.
  - Putting together a timeline for the three months of the project, with weekly milestones.

### Doc Development Phase

#### Week 1 (September 14 - September 20, 2020):

- Gone through all the documentation-based Jekyll themes across various sites.
- Made a document with a comparison between different themes considered.
- Selected the Jekyll theme which suits the best for gRPC-Gateway.

#### Week 2 (September 21 - September 27, 2020)

- Deployed the theme to my gRPC-Gateway fork.

#### Week 3 (September 28 - October 4, 2020):

- Imported all the existing contents of the old website to the new website.
- Made the first draft of the Landing Page.

#### Week 4 (October 5 - October 11, 2020):

- Added contents on the Landing page.
- Added section for Release Notes and Changelog.
- Added Commenting System.

#### Week 5 (October 12 - October 18, 2020):

- Added a script to generate the Changelog file automatically from the gRPC-Gateway repository.
- Made a basic gRPC-Gateway installation with a Go backend server ready.

#### Week 6 (October 19 - October 25, 2020):

- Created a basic arithmetic gRPC server frontend that uses gRPC-Gateway.
- Added notes to the new Installation guide in the process of learning and installing.

#### Week 7 (October 26 - November 1, 2020):

- Deployed the basic arithmetic gRPC server online.
- Imported new contents from the main gRPC-Gateway repository to my gRPC-Gateway fork after the merge of branch v2 to master.

#### Week 8 (November 2 - November 8, 2020):

- Created a new Tutorials directory.
- Added documentation about generating gRPC stub via both `buf` and `protoc` in the tutorials directory and made sure that all the commands required to generate basic protobuf files are present.
- Added documentation on creating the basic protos with HTTP annotations and included a lot of links of [https://google.aip.dev/127](https://google.aip.dev/127).

#### Week 9 (November 9 - November 15, 2020):

- Created a hello world program that uses gRPC-Gateway.
- Made an empty `main.go` that has enough to run the binary.
- Made an HTTP server. Added a `net/http` handler that renders the word `hello world`.
- Installed the gRPC-Gateway handler in the HTTP handler. Tested the server by giving a single cURL command to view it.

#### Week 10 (November 16 - November 22, 2020):

- Added documentation in Tutorials directory on hello world program and how to use gRPC-Gateway in it.

#### Week 11 (November 23 - November 29, 2020):

- Added more FAQ entries.
- Added new architecture introduction diagram and removing the old one.
- Checked and fixed indentations, grammatical errors, typographical errors, and broken links across all the files including both previous and new documentations.

### Project Finalization Phase

#### Week 12 (September 30 - December 5, 2020):

- Finalized the project deliverables and refactor the code if any, based on the feedback.
- Made the project report and requested mentors to review the project report.
- Finalized and submitted the project report.
- Submitted the evaluation of the project and the experience working with the mentors.

## Pull Requests Merged

My mentors suggested me to work on my gRPC-Gateway fork and make all the changes there and make pull request after I got a large number of changes rather than making a separate pull request for every change.

These are my pull request which holds all my project deliverables:

|                               Link                                |                                                                                                  Description                                                                                                  |
| :---------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [#1786](https://github.com/grpc-ecosystem/grpc-gateway/pull/1786) |                                 This pull request holds work from week 1 to week 5 which is based on the new Jekyll theme added to the documentation website of gRPC-Gateway.                                 |
| [#1829](https://github.com/grpc-ecosystem/grpc-gateway/pull/1829) | This pull request holds work from week 6 to week 10 which is based on the new Tutorials directory of gRPC-Gateway which is made on basis of the hello world program and basic arithmetic gRPC server program. |
| [#1844](https://github.com/grpc-ecosystem/grpc-gateway/pull/1844) |                                                                       This pull request holds work of week 11 which is on FAQ entries.                                                                        |
| [#1845](https://github.com/grpc-ecosystem/grpc-gateway/pull/1845) |                                                          This pull request holds work of week 11 which is on the architecture introduction diagram.                                                           |
| [#1851](https://github.com/grpc-ecosystem/grpc-gateway/pull/1851) |                                                           This pull request holds work of week 11 which is on refactoring the documentation files.                                                            |

Works that are not yet added or not sure to be added are:

- Adding section for Release Notes and Changelog.
- Adding Commenting System.
- Adding a script to generate the Changelog file automatically from the gRPC-Gateway repository.

## Meetings Details

| Meeting No. |                Date and Time                |
| :---------: | :-----------------------------------------: |
|      1      |   Saturday, August 22, 2020⋅8:30 – 9:00pm   |
|      2      | Saturday, September 12, 2020⋅9:00 – 9:30pm  |
|      3      | Saturday, September 26, 2020⋅9:00 – 9:30pm  |
|      4      |  Saturday, October 10, 2020⋅9:00 – 9:30pm   |
|      5      |  Saturday, October 24, 2020⋅9:00 – 9:30pm   |
|      6      | Saturday, November 7, 2020⋅10:00 – 10:30pm  |
|      7      | Saturday, November 14, 2020⋅10:00 – 10:30pm |
|      8      | Saturday, November 21, 2020⋅10:00 – 10:30pm |
|      9      | Saturday, November 28, 2020⋅10:00 – 10:30pm |
|     10      | Saturday, December 5, 2020⋅10:00 – 10:30pm  |

All dates and times are in Indian Standard Time (IST) with a time offset of UTC+05:30.

## Future Works

- Improving the contributor’s guide
- Solving [documentation related issues](https://github.com/grpc-ecosystem/grpc-gateway/issues?q=is%3Aopen+is%3Aissue+label%3Adocumentation).

## Learnings

I am very glad that I had the opportunity to take part in the Google Season of Docs program project. Participating in this program has helped me to:

- Got involved with an amazing community i.e. gRPC-Gateway.
- Learned about gRPC and gRPC-Gateway.
- Learned a lot of tools like Docker, Postman and Swagger UI, etc.
- Worked on Go server and protobuf files.

## Acknowledgments

I am deeply grateful to my mentors [Johan Brandhorst-Satzkorn](https://github.com/johanbrandhorst) and [Andrew Z Allen](https://github.com/achew22), who guided me patiently through the project and was always ready to help, review work in progress, gave feedback regarding the overall shape of the project and the feasibility of certain solutions, and maintained a very friendly, supportive, and stimulating atmosphere on the team. They devoted a lot of time to this project and led the fortnightly video meetings in a well-organized, yet non-stressful manner. Their support and positivity helped me through this project and made me enjoy every bit of it. The project could not be completed without the generous feedback and help from the team. Last but not least, I would like to thank Google and Google Season of Docs organizers for this initiative.
