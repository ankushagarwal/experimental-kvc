我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# Volume Controller for Kubernetes (VCK)

[![CircleCI](https://circleci.com/gh/IntelAI/vck.svg?style=svg)](https://circleci.com/gh/IntelAI/vck)
## Overview

This project provides basic volume and data management in Kubernetes v1.9+
using [custom resource definitions][crd] (CRDs), custom controllers,
[volumes][vols] and [volume sources][volsources]. It also 
establishes a relationship between volumes and data and provides a way to
abstract the details away from the user. When using VCK, users 
are expected to only interact with [custom resources][cr] (CRs).

![VCK overview figure](./docs/images/vck.png)

## Further Reading

- [Architecture][arch-doc]
- [Developer Manual][dev-doc]
- [Operator Manual][ops-doc]
- [User Manual][user-doc]
- [Best Practices][best-practices-doc]
- [FAQs][faqs-doc]

[arch-doc]: docs/arch.md
[dev-doc]: docs/dev.md
[ops-doc]: docs/ops.md
[user-doc]: docs/user.md
[faqs-doc]: docs/faq.md
[best-practices-doc]: docs/best-practices.md
[crd]: https://kubernetes.io/docs/tasks/access-kubernetes-api/extend-api-custom-resource-definitions/
[cr]: https://kubernetes.io/docs/concepts/api-extension/custom-resources/
[vols]: https://kubernetes.io/docs/concepts/storage/volumes/
[volsources]: https://github.com/kubernetes/api/blob/master/core/v1/types.go#L250
