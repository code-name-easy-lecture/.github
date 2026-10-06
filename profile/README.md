# Easy Lecture

Easy Lecture transcribes a lecture and answers questions about it. Every answer cites the timestamp where the point came up, so you can jump to that moment and check it against what the professor said.

It uses retrieval augmented generation (RAG). The system finds the relevant stretch of the transcript first, then asks Claude Haiku 4.5 to answer from what it found.

## The team

Juan ([@jbalderas-pgit](https://github.com/jbalderas-pgit)) builds the front end and CI/CD and runs the repo. Preston ([@prestonimus](https://github.com/prestonimus)) owns retrieval. Derek ([@EnterBluey](https://github.com/EnterBluey)) handles AWS and the speech to text pipeline. We sync weekly and post notes in Discussions.

## Where things stand

We start building on October 8, 2026. The repo, issue tracker and project board are set up, and the first planning issues are open.

The web app is Next.js with TypeScript. The retrieval service is Python 3.12 and will run on AWS Lambda.

Our first target is a working MVP by December 11. A pilot follows on February 12, 2027, and we plan to launch on April 2, 2027.
## Follow along

The code is in [easy-lecture](https://github.com/code-name-easy-lecture/easy-lecture), and the plan is on the [project board](https://github.com/orgs/code-name-easy-lecture/projects/1/views/1).
