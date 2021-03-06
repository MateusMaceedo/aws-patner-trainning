<h1 align="center">
<img src="https://keybe.ai/en/wp-content/uploads/2020/01/download.png" width="350" height="230">
 <br>
 AWS Trainning
</h1>

![Build Status](https://codebuild.us-west-2.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiSkJibVVQVEpvUms1cmw3YVlnU1hSdkpBQ0c5SFgyTkJXMFBFdEU2SWtySHREcUlUVlRhbW4zMEd3NlhsOWIzUWgvRkxhUWVSSTFPZGNNakNHRVNLalY0PSIsIml2UGFyYW1ldGVyU3BlYyI6IlV0QjBRZXRvS0F5dE5vbTciLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master)

Links and materials made available as additional content for studies in AWS training. The information entered here is maintained by myself, and does not express any official information on the part of AWS; even though most of them are official articles and blog posts from Amazon Web Services.

### Certificações

- [X] Escolha sua [carreira de certificações](https://aws.amazon.com/certification/) e organize o seu [roteiro de aprendizado](https://aws.amazon.com/training/learning-paths/)
- [X] Revise o arquivo [_Exam Guide_](https://aws.amazon.com/certification/certification-prep/) do respectivo exame de certificação
- [X] Defina uma estratégia eficiente de estudos. Há algumas técnicas bem interessantes como o [_Retrieval_](https://aws.amazon.com/blogs/training-and-certification/using-retrieval-practice-techniques-to-improve-learning/), [_Spaced_](https://aws.amazon.com/blogs/training-and-certification/use-spaced-practice-to-increase-learning-retention/) e o [_Elaboration_](https://aws.amazon.com/blogs/training-and-certification/cognitive-science-post-3-using-elaboration-to-reinforce-your-understanding-of-concepts/)
- [X] Faça um treinamento presencial oficial da AWS em [aws.training](https://www.aws.training/)
- [X] Faça laboratórios e ganhe experiência prática
- [X] Revise o arquivo de **_Sample Questions_** do respectivo exame de certificação
- [X] Revise os _whitepapers_ e **FAQs** dos serviços que estão no escopo do exame de certificação
- [X] Assista os vídeos da série [_"This is My Architecture"_](https://aws.amazon.com/this-is-my-architecture/), com exemplos de casos reais dos clientes AWS
- [X] Faça um treinamento oficial da AWS com foco na preparação do exame; através dos cursos **_Exam Readiness_**
- [X] Acompanhe [nossos eventos e webinars da comunidade AWS em LATAM](https://aws.amazon.com/pt/training/events), pois sempre temos conteúdo muito bom pra ajudar nos estudos
- [X] Faça um **_Practice Exam_** oficial (simulado)
- [X] Agende seu [exame de certificação](https://www.aws.training/Certification) na **PSI** ou **Person Vue**
- [X] Adicione [30 minutos a mais](https://www.linkedin.com/pulse/30-minute-extension-your-aws-certification-exam-garcia-lozano/) em seu exame com o **_ESL +30 MINUTES_** (disponível para não-nativos de língua inglesa) 
- [X] Seja um certificado AWS!
- [X] Aproveite os [benefícios](https://aws.amazon.com/certification/benefits/) concedidos só a quem tem certificações AWS

### AWS Categories
- Practitioner
- Solutions Architect Associate
- Developer Associate
- SysOps Administrator
- Devops Engineer Professional
- Solutions Architect Professional
- Advanced Networking Speciality
- Security Speciality
- Database Speciality
- Data Analytics Speciality
- Machine Learning Speciality
- Alexa Skill builder Speciality

Steps to build Standard 5.0 image

* Run `git clone https://github.com/MateusMaceedo/aws-patner-trainning.git` to download this repository to your local machine
* Run `cd ubuntu/standard/5.0` to change the directory in your local workspace. This is the location of the Standard 5.0 Dockerfile with Ubuntu base.
* Run `docker build -t aws/codebuild/standard:5.0 .` to build Docker image locally

To poke around in the image interactively, build it and run:
`docker run -it --entrypoint sh aws/codebuild/standard:5.0 -c bash`

To let the Docker daemon start up in the container, build it and run:
`docker run -it --privileged aws/codebuild/standard:5.0 bash`

```
$ git clone https://github.com/MateusMaceedo/aws-patner-trainning.git
$ cd aws-codebuild-docker-images
$ cd ubuntu/standard/5.0
$ docker build -t aws/codebuild/standard:5.0 .
$ docker run -it --entrypoint sh aws/codebuild/standard:5.0 -c bash
```

<h1 align="center">
<img src="https://github.com/MateusMaceedo/aws-patner-trainning/blob/main/img/Amazon.png?raw=true" width="1160" height="554">
 <br>
 AWS (Sem Vercel)
</h1>
