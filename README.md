# wings
The goal of wings is to build and manage opinionated CI/CD toolchains for software projects using select AWS services with minimal configuration by the user. This means you take your existing source code, write a little bit of TOML, run wings, and get a full CI/CD pipeline using native AWS tools ([Code Suite services](https://aws.amazon.com/products/developer-tools/)) that cost next to nothing. Knowledge of the underlying services is not required. Spend more time coding and less time managing your CI/CD.

# Supported AWS Services
wings knows how to model CI/CD for projects running on the following AWS services:
* [AWS Lambda](https://aws.amazon.com/lambda/) (in development)
* [AWS ECS](https://aws.amazon.com/ecs/) (planned, not yet implemented)

# Usage
```python
pip install wings

wings -h
```

# FAQs
### 1. Why the name wings?
I wanted something that represented "moving into the cloud." After checking a few names in [PyPI](https://pypi.org/), I settled on wings. Birds have wings, birds can fly into the clouds. Seemed fitting and it's nice and short :)
