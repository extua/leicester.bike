This repository contains the source files for building https://leicester.bike/ with AWS Amplify.

#### To Do


- [ ] CI/CD build process on AWS Amplify.
- [X] Add CSP, with exception for data.leicester.gov.uk and other standard security stuff (DNSSEC/CAA).
- [X] Pre-connect to data.leicester.gov.uk to speed up connection.
- [ ] Setup proper www redirect -> then add HSTS preloading.
- [ ] Rewrite javascript as single shadow DOM function.
- [ ] Logic to catch when a station has zero bicycles available and get the next nearest one instead.
- [ ] Use Swagger v2 API instead of v1. (is this done?)
- [ ] Investigate rate limits, and/or api errors in general?
- [ ] Add web workers to allow offline functionality?
