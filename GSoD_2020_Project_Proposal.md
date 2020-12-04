<div align="center">
<img src="assets/logo.svg" />
<br />
<h1>gRPC-Gateway</h1>
<h3 align="center">
Refactoring the Existing Docs Site of gRPC-Gateway
<br />
Project Proposal
</h3>
</div>

## ABSTRACT:

The user docs site is designed to assist end-users to use a product or service. The good user docs site is very important because it provides an avenue for users to learn how to use the software, its features, tips, tricks and also resolve common problems encountered when using the software. It also reduces support cost and is part of the corporate identity of the product. The good user docs site is a sign of healthiness of the product, the developer team. Without good user docs site, a user may not know how to do the above things effectively and efficiently. User docs site can play a pivotal role in ensuring a product's success because great communication is and will always be at the heart of any business or product and great documentation just takes that communication and puts it in a manageable framework that everyone can access for success.

At the time of this writing, the gRPC-Gateway repository has been forked by approximate 1200 times and 184 people have contributed to this repository this shows that a lot of people all over the world use the gRPC-Gateway and may want to read its user documentation for guidance on how to use the gRPC-Gateway. However, the gRPC-Gateway user documentation and docs site is currently outdated and incomplete and the gRPC-Gateway community wants to use this project to refactor the existing docs site improve its docs site to enable end-users to have a seamless experience when using the gRPC-Gateway.

## CURRENT STATE:

Currently, the gRPC-Gateway docs site have two major problems:-

- The first problem is bad and outdated docs website that is the styling and structure of site and theme used is obsolete, incomplete, hard to navigate or find information, does not cover many features of good docs website. Refactoring the Existing Docs Site of gRPC-Gateway will include styling of the website, adding features such as document search etc, improving UI of website, organising tutorials and examples in a proper sidebar and updating the existing flowcharts and images by designing a new one etc. This will be my primary goal and my work will be more based on styling and restructuring of existing Docs site.

- The second problem, there is a need to refactor the existing documentation, tutorials and examples etc of gRPC-Gateway which can be done by removing typographical and grammatical mistakes across the files, making proper alignment of Go snippets and refactoring Go snippets according to Gofmt formats. Also, if so we can add more documentation, tutorials and examples if need or we can reuse the existing files after refactoring it. This is my secondary goal and will do this after I complete my primary goal i.e. styling and restructuring of existing Docs site.

## WHY IS MY PROPOSED DOCS SITE AN IMPROVEMENT OVER THE CURRENT ONE?

The proposed user docs website will be structured to improve and ensure efficiency, consistency, and peace of mind for an end-user. It will give a better look and UI with well-stylized sections and features contain written guides and its associated flowcharts and images.

gRPC-Gateway documentation provides a good description of the method and example. But it is still using old Jekyll theme and modern days we have better SSG (Static Site Generator) Jekyll themes. Also, there is a need for restructuring of pages and making it more useful for users by adding new examples and tutorials and update and rewriting the previous contents.

## STRUCTURE AND ROADMAP OF THE PROPOSED GOALS AND IDEAS:

### PRIMARY GOAL OF THIS PROJECT:-

The above goals and ideas can be implemented in the following ways:-

Shifting the Current Jekyll theme to better and robust theme. The reason for using Jekyll themes again is that it will be easy for maintainers to contribute and understand the workflow of the project since they are already aware of existing Jekyll framework and theme which is similar to new Jekyll theme.

After going through different Jekyll themes across the internet I found this https://idratherbewriting.com/documentation-theme-jekyll/ themes suite best for gRPC-Gateway docs site because of the following feature:

- Markdown:-
  So that technical writers don't have to worry about installation. They can write simply in the .md file. Anyone can click on edit button shown on the website (new feature) and contribute (edit/suggest changes for the page in GitHub) to make it better. This will engage users to add new content or edit content to improve it.

- Documentation Search:-
  User should be having a search box so that they can easily and quickly find out relevant contents.

- Comments Section:-
  User may have the option to comment and share their views on posts and tutorials. They can able to read other people views on project documentation.

- New Release Notes and Blogs:-
  The website should be updated with new blog posts and news about current development and roadmap. So kind of blogging should be present on the landing page.

- Fast Development:-
  Most of the SSG (Static Site Generator) frameworks are running in server and changes in file reflects immediately in UI. Also deploy and build process should be easy.
  In future, if we want to change the framework, we use. Then it should be easy. Most of the frameworks support Markdown writing so just moving the .md files and few changes should be enough.

Here I am splitting the existing website pages into new website sections and pages :

- Landing Page:-

Landing page should point out the major features of gRPC-Gateway.

- Getting started with gRPC-Gateway (redirect to the user guide)
- Simple Installation instructions (brief commands)
- Why use gRPC-Gateway
- Project using gRPC-Gateway

So the basic idea is rather than writing long description, display main points in landing page and provide the link to go for details.

- gRPC-Gateway User Guide Page:-

- Installation guide.
- Quick start with gRPC-Gateway.

- gRPC-Gateway Developer Guide Page:-

Development Guide, Contribution guide, Git setup, Code of Conduct, Documentation setup, Development workflow etc are pointing to similar pages inside. So refactoring and rearranging all the files are needed. Main Development page should contain all these pages and the hyperlink will be created in each step.

- About gRPC-Gateway Page:-

List of all the contributors should be present in team sections
Quick links and release notes, latest blogs will be added to engage the user to make them read about the current gRPC-Gateway news.

- Blogs, Release Notes and Tutorials Page:-

I feel that website should have a blogging option. So news and releases can be communicated easily. The tutorial page will contain some popular talks and articles that clarify gRPC-Gateway APIs and concepts. Contributors can add their tutorial links in the tutorial page.

After completing the above task update the same changes in the v2 branch and making even with the master branch of gRPC-Gateway.

### SECONDARY GOAL OF THIS PROJECT:-

Other changes need to be done to make gRPC-Gateway documentation more robust and readable:-

- Fixing grammatical, Typographical errors and organising and aligning of link and posts in the site across all the existing files of gRPC-Gateway.

- Adding more documentation and content if needed in gRPC-Gateway as most of the features have very short documentation like in Documentation section of the site on AWS, Background and Usage etc.

- Refactoring Go snippets gRPC-Gateway as according to Gofmt formats

After completing the above task update the same changes in the v2 branch and making even with the master branch of gRPC-Gateway.

## WHY AM I THE RIGHT PERSON FOR THIS PROJECT:

I believe I am the right person for this project because:-

- I have past experience in improving the documentation of organizations and I can use any version control system, so carrying out commands on GitHub will not be a problem.
- Moreover, what drives me is working on projects that create value for people.
  I believe that If you want someone to do something in the most efficient way possible, you document it. By documenting your processes, you ensure efficiency, consistency, and peace of mind for anyone involved.
- I am familiar with the workflow and the codebase of gRPC-Gateway since I am contributing to gRPC-Gateway from last two months and got 11 PR merged.
