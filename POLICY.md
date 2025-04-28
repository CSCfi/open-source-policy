# CSC open source policy

CSC - IT Center for Science Ltd. embraces free and open source throughout its operations and development. Open source software, open data and open interfaces are considered to be the essential building blocks of sustainable digital ecosystems. The purpose of the company open source policy is to codify current de facto practices and to encourage employees to use and produce open source software. CSC believes that improved collaboration is the greatest benefit that open source can provide and for that reason this policy is written with emphasis on practices that encourage collaboration.

The policy aims to be concise and practical, giving suggestions that align well with commonly accepted principles of the open source community. For getting started quickly please have a look at the attached practical guidelines for licensing and publishing open source software at CSC (at the end of this document).

## 1. Use open source

When possible, use open source tools, libraries, modules and frameworks in your projects.

Check for license compatibility when integrating copyleft licensed code (GPL, AGPL or EUPL).

## 2. Contribute to open source

If you make patches or improvements to other projects, you are allowed and encouraged to contribute them back.

If you are required to submit a Contributor License Agreement, you can do so. In case a company signature is needed, it needs to be done by the procuration holders (directors).

## 3. Our software can be open sourced

You are allowed and encouraged to release your code into open source. Smaller projects can be just pushed to GitHub or a similar repository. For projects worth more than a person week please check with your supervisor first.

The exceptions for releasing source code are:

Code that contains or might contain internal security information about our infrastructure, personal data or other confidential information. If you are not sure, consult your senior colleagues or head of security.

If the work is paid by a customer then open sourcing needs to be agreed with the customer.

If parts of the source code cannot be released, it is recommended to organise your code so that the main part can be released and restricted modules kept closed.

## 4. Use a standard license for software

Both permissive and copyleft licenses can be used. It is often best to go with community standards when choosing the licensing model. If the software is part of some open source product family, then it is best to use a matching license.

Use only proper open source licenses approved by OSI (https://opensource.org/licenses). Funny or empty licenses are a pain for anyone who would like to use your code. Established licenses also contain some safeguards for patent traps and liabilities. Do not use a Creative Commons license alone for software. If needed, use dual licensing.

### 4.1. Permissive: MIT license

Unless there are specific reasons to choose otherwise, use the permissive MIT license. This license can be used for all projects and software owned by CSC. It allows people to do anything they want with your code as long as they provide attribution back.

The MIT license is also compatible with the GNU General Public License, meaning that MIT licensed software can be integrated into GPL software, but not the other way around (https://en.wikipedia.org/wiki/MIT_License).

### 4.2. Copyleft: GPL license

In some communities using a copyleft license is the standard practice and in that case, it is best to follow that practice. Copyleft licenses include a condition that requires projects using the licenced code to also distribute their own code under the same copyleft license. This guarantees that further contributions by others are also open sourced.

If your customer wants to use a copyleft license, CSC recommends using the GPL license. To avoid version incompatibilities between GPL versions, the recommended clause is: "distributed under the terms of GNU General Public License (GPL) v3 or later".

When considering a copyleft license, remember that combining pieces of software under copyleft licenses can be harder than assumed. This is especially true when multiple copyleft licenses need to be mixed. Extra attention is needed when considering a copyleft license other than the GPL, including the AGPL and the EUPL. For more information on license compatibility, see: https://en.wikipedia.org/wiki/License_compatibility#Compatibility_of_FOSS_licenses

## 5. Publish your software together with the license

Unless there are reasons to choose otherwise, use the established GitHub repository to release and host code. Attach your project to the company organisation at GitHub (https://github.com/cscfi). Customers might have their own repositories to use so please check with them first.

The license file should be attached and displayed following the practices set up by the repository. In addition to the license file, you should put a license and copyright notice at the start of each source file, stating what license it carries and who holds the copyright. This lessens the risk of the code getting disconnected from its license and reduces ambiguity when there are large programs and multiple releases.

## 6. Note the copyright owner and original authors

The copyright owner should be recorded when publishing software. Most licenses have a place to indicate the copyright owner and furthermore, it should be noted in all source code files. When development work is paid by a customer who will own the copyright over the results, the copyright owner for the software should be recorded in the contract and noted accordingly in both code and content.

The authors who have contributed to the code base should be noted unless they wish to remain anonymous. Recognising original authors regardless of who owns the copyright allows programmers to gain reputation in the open source community and is also a public way of saying thank you to external collaborators.

## 7. Use Creative Commons license for non-software

Unless there are specific reasons to choose otherwise, use the permissive Creative Commons BY 4.0 license (https://creativecommons.org/licenses/by/4.0/) for non-software, such as documentation, illustrations and data. This is the recommendation for public administration in Finland (https://www.avoindata.fi/data/fi/dataset/jhs189).

For releasing and hosting the content, use established international repositories that are most relevant to your case. Small files are often best stored next to code in GitHub.

## 8. Accept and encourage contributions

Outside contributions are one of the great benefits of open source, so you should accept and encourage them. Care is needed when accepting contributions, though. Sometimes so-called Contributor License Agreements (CLA's) are used to prevent copyrights from scattering and contributors from withdrawing their contributions at a later stage. However, CLA's are not trivial to implement and will discourage some people from contributing. Often the best solution is to use the permissive MIT license in your projects, so you will have wide rights to use external contributions.

If you use a copyleft license (GPL, AGPL or EUPL) or otherwise need more control over the source code, it is good to consider requiring CLA's from your contributors. Apache Software Foundation CLA can be used as a model.

## Attachment: Practical guidelines for licensing and publishing

1. Within your project and team, you should:
1. Decide on a license (default: MIT)
1. Determine the copyright holder (default: CSC)
1. Add your project to GitHub (default organisation: CSCfi)
1. Add the license file to the root of your repository (https://opensource.org/licenses/MIT)
1. Check that the license is identified by GitHub (is machine readable)
1. Consider adding two elements to each source file of your program
   1. copyright notice stating who owns the copyright
   1. statement that the program is distributed under the terms of the chosen license

Support for open sourcing your project is available from supervisors and contract management.

_Accepted 28.9.2018. Revised 12.7.2019, 22.2.2019 and 28.4.2025_
