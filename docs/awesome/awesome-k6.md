<div class="github-widget" data-repo="k6io/awesome-k6"></div>

<div align="center">
  <a href="https://k6.io/">
    <img src="https://raw.githubusercontent.com/k6io/awesome-k6/master/assets/bert.png" alt="k6 mascot" width="300px">
  </a>

<!--lint disable awesome-heading-->
## Awesome k6 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint enable awesome-heading-->

</div>

开源的、以开发人员为中心的性能监控和负载测试解决方案， <a href="https://k6.io/">k6</a> .


想帮助改进这个列表吗？ 耶，太棒了！ 在开始之前，请先看看我们 [code of conduct](https://github.com/k6io/awesome-k6/blob/master/code_of_conduct.md) 和 [contribution guidelines](https://github.com/k6io/awesome-k6/blob/master/contributing.md).



## Extensions
- [GitHub Topic: xk6](https://github.com/topics/xk6) - 探索带有 xk6 标签的 k6 扩展.

## Articles

- [Beginner's guide to load testing with k6](https://link.medium.com/npI9sjDyyjb) - 几个部分的介绍指南，帮助您开始使用 k6.
- [Load Testing with k6](https://medium.com/@dan.ryan.emmons/qa-load-testing-with-k6-io-c11c2afced04) - k6 特性和功能的简要概述.
- [Integrating k6 with Apache Kafka](https://mostafa.dev/blog/integrating-k6-with-apache-kafka) - 将输出从 k6 发送到 Apache Kafka.
- [Test and visualize with InfluxDB, Grafana and K6](https://medium.com/@naoko.reeves/load-test-with-k6-and-visualize-with-influxdb-and-grafana-c6097a6f6d0a) - 使用 grafana 仪表板设置负载测试并对其进行可视化.
- [Open source load testing tool review 2020](https://k6.io/blog/comparing-best-open-source-load-testing-tools) - 最流行的开源负载测试工具的详细比较.
- [Load Testing Your API with Swagger/OpenAPI and k6](https://mostafa.dev/blog/load-testing-your-api-with-swagger-openapi-and-k6) - 根据 OpenAPI 规范生成 k6 负载测试脚本.
- [Load Testing Your API with Postman](https://mostafa.dev/blog/load-testing-your-api-with-postman) - 如何使用 Postman 集合对您的 API 进行负载测试.
- [Load Testing & Black Friday capacity planning](https://medium.com/back-market-engineering/how-back-market-sres-prepared-for-black-friday-5f017f343408) - Back Market 如何通过基于 k6 的负载测试为黑色星期五做好准备.
- [Load Testing SQL Databases with k6](https://k6.io/blog/load-testing-sql-databases-with-k6/) - 如何使用xk6-sql扩展直接测试SQL数据库. 
- [Introducing TestRail in your K6 tests](https://dev.to/kwidera/introducing-testrail-in-you-k6-tests-eck) - 向 TestRail 报告 k6 输出. 
- [Beautiful Load Testing With K6 and Docker Compose](https://medium.com/swlh/beautiful-load-testing-with-k6-and-docker-compose-4454edb3a2e3) - 如何使用 Docker Compose、K6、InfluxDB 和 Grafana 的出色组合运行负载测试.
- [Load Testing with Azure DevOps and k6](https://medium.com/microsoftazure/load-testing-with-azure-devops-and-k6-839be039b68a) - 如何设置 Azure DevOps 以使用 k6、handleCallback 和 JUnit 执行自动负载测试.
- [K6 — Custom Slack Integration: Metrics are the Magic of Tests](https://medium.com/geekculture/k6-custom-slack-integration-metrics-are-the-magic-of-tests-527aaf613595) - 如何使用 handleSummary 回调将 k6 输出结果发送到 Slack.

## Videos

- [Website Performance + Load Testing with K6 (k6.io) in 5 MINUTES!](https://www.youtube.com/watch?v=brasMBAezJY) - k6 的介绍性概述，展示了如何从 HAR 文件创建测试.
- [Performance Testing your web app with k6](https://www.youtube.com/watch?v=Hu1K2ZGJ_K4) - 开源负载和性能回归测试工具 k6 的演练，以及如何对您的 API 和网站进行负载测试.

## Reference Projects

- [k6-circleci-example](https://github.com/loadimpact/k6-circleci-example) - 作为 CircleCI 构建的一部分运行 k6 负载测试.
- [k6-jenkins-example](https://github.com/loadimpact/k6-jenkins-example) - 作为 Jenkins 构建的一部分运行 k6 负载测试.
- [k6-github-actions-example](https://github.com/loadimpact/k6-github-actions-example) - 运行 k6 负载测试作为 GitHub Actions 构建的一部分.
- [k6-azure-pipelines-example](https://github.com/loadimpact/k6-azure-pipelines-example) - 作为 Azure DevOps 管道的一部分运行 k6 负载测试.
- [k6-bitbucket-pipelines-example](https://github.com/poponuts/k6-boilerplate) - 作为 Bitbucket Pipeline 构建的一部分运行 k6 负载测试.
- [k6-performance-test-websocket](https://github.com/Julianhm9612/k6-performance-test-websocket) - 使用 k6 对 websocket 进行性能测试的示例.
- [k6-typescript-template](https://github.com/k6io/template-typescript) - 在 k6 中使用 TypeScript 的模板.
- [k6-es6](https://github.com/MStoykov/k6-es6) - 使用 Webpack、Babel 和 Browserify 使大多数 ES6 代码在 k6 中工作的示例项目.
- [example-data-generation](https://github.com/k6io/example-data-generation) - 使用 faker 为 k6 生成真实数据.
- [bounded-disturbances](https://github.com/bjartwolf/bounded-disturbances)  - .NET 混沌工程研讨会. 使用 Simmy 和 k6.
- [continuous-k6k8s](https://github.com/lreimer/continuous-k6k8s) - 使用 cronjobs 在 Kubernetes 中持续运行 k6 测试.
- [k6-multiscenario-template](https://github.com/SwissLife-OSS/K6-MultiScenario-template) - 使用 K6 实现多场景模板.
- [docker-k6-grafana-influxdb](https://github.com/luketn/docker-k6-grafana-influxdb) - 演示如何使用 K6、Grafana 和 InfluxDB 的容器化实例运行负载测试.

## Tools

- [k6-to-junit](https://github.com/Mattihew/k6-to-junit) - 用于将 k6 输出转换为 JUnit XML 以便与 CI 一起使用的工具.
- [k6-reporter](https://github.com/benc-uk/k6-reporter) - 将 k6 输出转换为 HTML 报告的工具.
- [k6-reporter](https://github.com/szboynono/k6-html-reporter) - 用于生成 k6 HTML 报告的工具.
- [har-to-k6](https://github.com/loadimpact/har-to-k6) - 将 HAR 录音转换为 k6 测试脚本的工具.
- [postman-to-k6](https://github.com/loadimpact/postman-to-k6) - 将 Postman 集合转换为 k6 测试脚本的工具.
- [k6 generator](https://github.com/OpenAPITools/openapi-generator) - 用于将 Swagger/OpenAPI 规范转换为 k6 测试脚本的工具.
- [jmeter-to-k6](https://github.com/loadimpact/jmeter-to-k6) - 将 JMeter 测试用例转换为 k6 测试脚本的工具.
- [jslib.k6.io](https://jslib.k6.io/) - 用于 k6 脚本的有用实用程序库.
- [k6 for visual studio code](https://marketplace.visualstudio.com/items?itemName=k6.k6&ssr=false#overview) - 用于直接从您的 IDE 运行 k6 的市场扩展.


## CI
- [k6 for GitHub actions](https://github.com/marketplace/actions/k6-load-test) - 在 GitHub Actions 中运行 k6 的市场操作.
- [k6 for Azure DevOps Pipelines](https://marketplace.visualstudio.com/items?itemName=k6.k6-load-test) - 用于在 Azure Devops 管道中运行 k6 的市场扩展.
- [k6 CircleCI Orb](https://circleci.com/developer/orbs/orb/k6io/test)  - k6 Orb 用于在 CircleCI 中运行 k6. 支持在 CircleCI runner 和 k6 云 SaaS 服务中运行测试.

## Stacks

- [CloudPosse's Load Testing Stack](https://github.com/cloudposse/load-testing) - 使用 k6、Grafana 和 InfluxDB 的负载测试堆栈.
- [Load Impact's OSS Load Testing Stack](https://github.com/loadimpact/open-source-load-testing-stack) - 开源堆栈，适用于运行负载测试、存储结果和在仪表板中可视化这些结果.
