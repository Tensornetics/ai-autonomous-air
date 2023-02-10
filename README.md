# AI-Autonomous Air

The AI-Autonomous Air project is an innovative solution for the development of dominant tactical autonomy for multi-ship, beyond visual range air combat missions. The project is being developed for the DARPA AIR (Autonomous Intelligent Robotics) program.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Node.js
- React Native
- Docker

### Installing

A step by step series of examples that tell you how to get a development environment running:

1. Clone the repository
```
git clone https://github.com/<your_username>/ai-autonomous-air.git
```

2. Install the dependencies
```
npm install
```

3. Start the development server
```
npm start
```

## Deployment

The project is deployed using Helm charts and Kubernetes. For more information, see the [k8s directory](k8s).

## Built With

- [React Native](https://facebook.github.io/react-native/) - The front-end framework
- [Node.js](https://nodejs.org/) - The back-end framework
- [Docker](https://www.docker.com/) - Containerization platform

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [DARPA](https://www.darpa.mil/) - For the AIR program
- [OpenAI](https://openai.com/) - For training the AI models



```
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
```
