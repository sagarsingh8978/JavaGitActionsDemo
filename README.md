# JavaGitActionsDemo
this repo is to run basic git actions pipeline for my learning
[ JOB 1: BUILD, TEST, ANALYZE ]
├── Compile Spring Boot app
├── Run unit tests & Sonar analysis
└── Create production executable .jar file
│
▼  (upload-artifact)
☁️  GitHub Temporary Storage (Safely holds your app file)
│
▼  (download-artifact)
[ JOB 2: PACKAGE & LAUNCH ]
├── Spin up a completely fresh runner environment
├── Download production executable .jar file
└── Run Spring Boot app locally ("java -jar ...")