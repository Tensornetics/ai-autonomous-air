

ai-autonomous-air
├── README.md
├── LICENSE
├── docs
│   ├── architecture.md  
│   ├── design.md 
│   ├── installation.md  
│   ├── usage.md 
│   ├── troubleshooting.md 
│   ├── security_best_practices.md 
│   ├── biometric_authentication.md 
│   └── regulatory_compliance.md
├── server
│   ├── index.js (entry point for the Node.js backend)
│   ├── routes (folder for routing the API endpoints)
│   │   └── api.js (API endpoint file)
│   ├── controllers (folder for handling API requests)
│   │   └── controller.js (controller file)
│   ├── models (folder for handling database models)
│   │   └── model.js (database model file)
│   ├── utils (folder for utility functions)
│   │   └── helper.js (utility function file)
│   ├── tests (folder for tests)
│   │   └── test.js (test file)
│   ├── package.json (npm package manager file)
│   └── .env (environment variables file)
├── client
│   ├── app
│   │   ├── index.js (entry point for the React Native front-end)
│   │   ├── components (folder for React components)
│   │   ├── screens (folder for React screens)
│   │   └── assets (folder for project assets)
│   ├── package.json (npm package manager file)
│   └── .env (environment variables file)
├── infra
│   ├── terraform (folder for Terraform code)
│   │   ├── main.tf (Terraform main configuration file)
│   │   ├── variables.tf (Terraform variable file)
│   │   └── outputs.tf (Terraform output file)
│   └── docker (folder for Docker related files)
│       ├── Dockerfile (Docker file for building the app)
│       └── docker-compose.yml (Docker Compose file for the app services)
├── ci-cd (folder for CI/CD pipeline files)
│   ├── .travis.yml (Travis CI file)
│   └── Jenkinsfile (Jenkins pipeline file)
└── tests (folder for project tests)
    └── test.js (test file)
