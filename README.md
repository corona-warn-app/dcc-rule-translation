<h1 align="center">
  Digital COVID Certificates: Booster Notification Rules - Translation
</h1>

<p align="center">
    <a href="#about-this-repository">About this Repository</a> •
    <a href="#how-to-maintain-texts">How to maintain texts</a> •
    <a href="#support-and-feedback">Support and Feedback</a> •
    <a href="#how-to-contribute">How to Contribute</a> •
    <a href="#licensing">Licensing</a>
</p>

## About this Repository
This repository contains the description texts for the booster notification rules to be displayed in the Corona-Warn-App. From here, the translation can be triggered automatically into the languages supported by the Corona-Warn-App and later transferred to the corresponding repositories in which these rules are maintained.

## How to Maintain Texts

Only description texts for booster notification rules are maintained in this repository. The texts are maintained as German texts in the file [./i18n/de/strings.xml](./i18n/de/strings.xml).

Between the xml tag `<resources> </resources>`, the description text for a rule can be maintained as follows:

```xml
 <!-- XTXT: Booster Notification Rule: <Rule Id>, <Short Text>  -->
 <string name="Rule Id">"Long Description Text"</string>
```

Line breaks inside the **Long Description Text** must be indicated by `\n`.

## Support and Feedback

The following channels are available for discussions, feedback, and support requests:

| Type                     | Channel                                                |
| ------------------------ | ------------------------------------------------------ |
| **General discussion, issues, bugs**   | <a href="https://github.com/corona-warn-app/dcc-rule-translation/issues/new/choose" title="General Discussion"><img src="https://img.shields.io/github/issues/corona-warn-app/dcc-rule-translation/question.svg?style=flat-square"></a> </a>   |
| **Other requests**    | <a href="mailto:corona-warn-app.opensource@sap.com" title="Email CWA Team"><img src="https://img.shields.io/badge/email-CWA%20team-green?logo=mail.ru&style=flat-square&logoColor=white"></a> |

## How to Contribute

Contribution and feedback are encouraged and always welcome. For more information about how to contribute, the project structure, as well as additional contribution information, see our [Contribution Guidelines](./CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](./CODE_OF_CONDUCT.md) at all times.

## Contributors

The German government has asked SAP and Deutsche Telekom to develop the Corona-Warn-App for Germany as open source software. Deutsche Telekom is providing the network and mobile technology and will operate and run the backend for the app in a safe, scalable and stable manner. SAP is responsible for the app development, its framework and the underlying platform. Therefore, development teams of SAP and Deutsche Telekom are contributing to this project. At the same time our commitment to open source means that we are enabling -in fact encouraging- all interested parties to contribute and become part of its developer community.

## Repositories

A list of all public repositories from the Corona-Warn-App can be found [here](https://github.com/corona-warn-app/cwa-documentation/blob/master/README.md#repositories).

## Licensing

Copyright (c) 2020-2022 SAP SE or an SAP affiliate company.

Licensed under the **Apache License, Version 2.0** (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License from [here](./LICENSE).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the [LICENSE](./LICENSE) for the specific language governing permissions and limitations under the License.

