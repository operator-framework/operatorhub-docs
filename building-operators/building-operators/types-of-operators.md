# Types of Operators

## Types of Operators

The business logic for an Operator – all of your expert knowledge – can be implemented in several pieces of technology. Each has its own SDK.

### Go

Ideal for traditional software development teams that want to get to a fully auto-pilot Operator. Ability to leverage the same Kubernetes libraries the upstream projects use under the hood. [Go Getting Started guide](https://github.com/operator-framework/operator-sdk/blob/master/doc/user-guide.md).

### Ansible

Useful for infrastructure-focused teams that have investment in Ansible modules, but want to use them in a Kubernetes-native way. Also useful for using Ansible to configure off-cluster objects like hardware load balancers. [Ansible Getting Started guide](https://github.com/operator-framework/operator-sdk/blob/master/doc/ansible/user-guide.md).

### Helm

Easiest way to get started. Useful for running Helm charts in a more secure way \(no Tiller\) that doesn’t rely on manual invocation of Helm to reconfigure your apps. [Helm Getting Started guide](https://github.com/operator-framework/operator-sdk/blob/master/doc/helm/user-guide.md).

### Other Languages

Operators have been built in many languages, including Python and Java, but no SDKs exist for these.

### Operator Maturity Model

The level of sophistication of the management logic encapsulated within an Operator may vary. This logic is also in general highly dependent on the type of the service represented by the Operator. One can however generalize the scale of the maturity of an operator’s encapsulated operations for certain set of capabilities that most operators can include. To this end, we have defined an Operator Maturity model which defines 5 phases of maturity for generic day-2 operations of an operator as illustrated by the diagram below. The diagram also shows how these capabilities can best be developed through the Operator Framework’s Helm, Go, and Ansible capabilities.

[![](https://camo.githubusercontent.com/16ea0293a57ce84cc382ce09f6b3dd702a6208f1/68747470733a2f2f6c68342e676f6f676c6575736572636f6e74656e742e636f6d2f767138547667505f2d4c423246575736387166436f72656b43302d496459695237533948643279595379612d546a384f6a785274567a4a516c54647875637265425a7645336451454b4756584f71636f44347934316c435277734b5434574e3843436a6955444b524379627a564f5376567465324a6457466469326f423243746171623342516f76)](https://camo.githubusercontent.com/16ea0293a57ce84cc382ce09f6b3dd702a6208f1/68747470733a2f2f6c68342e676f6f676c6575736572636f6e74656e742e636f6d2f767138547667505f2d4c423246575736387166436f72656b43302d496459695237533948643279595379612d546a384f6a785274567a4a516c54647875637265425a7645336451454b4756584f71636f44347934316c435277734b5434574e3843436a6955444b524379627a564f5376567465324a6457466469326f423243746171623342516f76)

[![](https://camo.githubusercontent.com/1ec936fc341597560f05e159b350bebac90caaa4/68747470733a2f2f6c68362e676f6f676c6575736572636f6e74656e742e636f6d2f373962754a64715a41746269645348534430704945503241676b6a573075474e4275666d6a396d51434a73716847484b4a5639756866506338786755707766476b343732544579654e6b4257534a637a686e4a5157326c4164764e6167426655304f794e6c4374723558763677675569554a574e7565347677734b6f6c374e5970644e41534d7457)](https://camo.githubusercontent.com/1ec936fc341597560f05e159b350bebac90caaa4/68747470733a2f2f6c68362e676f6f676c6575736572636f6e74656e742e636f6d2f373962754a64715a41746269645348534430704945503241676b6a573075474e4275666d6a396d51434a73716847484b4a5639756866506338786755707766476b343732544579654e6b4257534a637a686e4a5157326c4164764e6167426655304f794e6c4374723558763677675569554a574e7565347677734b6f6c374e5970644e41534d7457)

[https://github.com/operator-framework/operator-sdk/blob/master/doc/images/Operator-Maturity-Model.png](https://github.com/operator-framework/operator-sdk/blob/master/doc/images/Operator-Maturity-Model.png)

