# MLFlow with proxied artifact storage

This repository is forked from [Tomasz Dłuski](https://github.com/Toumash/mlflow-docker) who provided a MLflow setup with MINIO. For my master's thesis and teaching efforts I adapted Thomasz project to leverage MLflows ability to proxy artifacts. The docker-compose setup corresponds to the version I run on my VPS and for local development. We further ran MLflow with proxied artifact storage on a on-prem Kubernetes cluster for teaching. I will add the corresponding configuration to deploy with Helm soon.  


### Licensing

Copyright (c) 2022 Alina Mailach
Copyright (c) 2021 Tomasz Dłuski

Licensed under the MIT License (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License by reviewing the file [LICENSE](./LICENSE) in the repository.