<div align="center">
<img src="assets/gsod-2020.svg" height="auto" width="400" />
<br />
<h1>gRPC-Gateway</h1>
<h3>
Refactoring the Existing Docs Site of gRPC-Gateway
<br />
Project Timeline
</h3>
</div>

### Community Bonding (August 17 - September 13, 2020):

- Bi-weekly meeting schedule agreed.
- gRPC-Gateway slack channel invite has been arranged.
- Focus in the first three weeks before the start of the project will be on:
  - Working through existing documentation and note gaps areas.
  - Putting together a timeline for the three months of the project, with weekly milestones.

## Doc Development Phase

### Week 1 (September 14 - September 20, 2020):

- Going through all the documentation-based Jekyll themes across various sites.
- Making a document with a comparison between different themes considered.
- Selecting the Jekyll theme which suits the best for gRPC-Gateway.

### Week 2 (September 21 - September 27, 2020)

- Deploying the theme to my gRPC-Gateway fork.

### Week 3 (September 28 - October 4, 2020):

- Importing all the existing contents of the old website to the new website.
- Making the first draft of the Landing Page.

### Week 4 (October 5 - October 11, 2020):

- Adding content on the Landing page.
- Adding section for Release Notes and Changelog.
- Adding Commenting System.

### Week 5 (October 12 - October 18, 2020):

- Adding a script to generate the Changelog file automatically from the gRPC-Gateway repository.
- Making a basic gRPC-Gateway installation with a Go backend server ready.

### Week 6 (October 19 - October 25, 2020):

- Creating a basic arithmetic gRPC server frontend that uses gRPC-Gateway.
- Adding notes to the new Installation guide in the process of learning and installing.

### Week 7 (October 26 - November 1, 2020):

- Deploying the basic arithmetic gRPC server online.
- Importing new contents from the main gRPC-Gateway repository to my gRPC-Gateway fork after the merge of branch v2 to master.

### Week 8 (November 2 - November 8, 2020):

- Creating a new Tutorials directory.
- Adding documentation about generating gRPC stub via both `buf` and `protoc` in the tutorials directory and making sure that all the commands required to generate basic protobuf files are present.
- Adding documentation on creating the basic protos with HTTP annotations and including a lot of links of [https://google.aip.dev/127](https://google.aip.dev/127).

### Week 9 (November 9 - November 15, 2020):

- Creating a hello world program that uses gRPC-Gateway.
- Making an empty `main.go` that has enough to run the binary.
- Making an HTTP server. Adding a `net/http` handler that renders the word `hello world`.
- Installing the gRPC-Gateway handler in the HTTP handler. Testing the server by giving a single cURL command to view it.

### Week 10 (November 16 - November 22, 2020):

- Adding documentation in Tutorials directory on hello world program and how to use gRPC-Gateway in it.

### Week 11 (November 23 - November 29, 2020):

- Adding more FAQ entries.
- Adding a new architecture introduction diagram and removing the old one.
- Checking and fixing indentations, grammatical errors, typographical errors, and broken links across all the files including both previous and new documentations.

## Project Finalization Phase

### Week 12 (September 30 - December 5, 2020):

- Finalizing the project deliverables and refactor the code if any, based on the feedback.
- Making the project report and requesting mentors to review the project report.
- Finalizing and submitting the project report.
- Submitting the evaluation of the project and the experience working with the mentors.
