---
title: "Additional Considerations"
type: open-source-licences-in-business
order: 03
permalink: /open-source-licences-in-business/additional-considerations
---
#### This information is for general guidance and is NOT legal advice

## Strong Licences and Internal Distribution

A question commonly asked is whether a [larger work]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work), which incorporates a [strongly]({% link _open-source-licences-in-business/06-strong-licence-examples.md %}) licensed [third-party work]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-work), must have its [source code]({% link _open-source-licences-in-business/07-definitions.md %}#source) made publically available. In the case of a [larger work]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work) subject to the [GNU General Public License 3.0](https://www.opensource.org/licenses/gpl-v3.0), if it is [kept private or distributed internally](https://www.gnu.org/licenses/gpl-faq.html#InternalDistribution) (i.e. it is only distributed within the company and staff do **not** have permission to distribute it outside of the company) then the company is only making copies for itself and it does not need to extend access to the [source code]({% link _open-source-licences-in-business/07-definitions.md %}#source) beyond its own confines. However, once it is distributed to other organizations or individuals then the rights provided by [copyleft](https://en.wikipedia.org/wiki/Copyleft) must be passed on to them.

## Remote Usage Provisions

Some [strong]({% link _open-source-licences-in-business/06-strong-licence-examples.md %}) [third-party licences]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-licence), most notably the [GNU Affero General Public License 3.0](https://www.opensource.org/licenses/agpl-v3), have additional provisions that explicitly extend [copyleft](https://en.wikipedia.org/wiki/Copyleft) to any individuals who make use of licensed works over a network (e.g. as web applications). In some special cases, such provisions [are also implicit to the GNU General Public License 3.0](https://www.gnu.org/licenses/gpl-faq.html#UnreleasedMods). Again, when access is kept private or only provided internally, then it is regarded as internal distribution and there is no obligation to provide access to the [source code]({% link _open-source-licences-in-business/07-definitions.md %}#source). However, the risk of non-compliance is greatly increased if the licensed work (or a derivative of it) is ever likely to be used externally. This risk is compounded in agile development environments where software components are generally regarded as reusable in any [larger work]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work) , including those to be made externally available.

## Common Non-FOSS licences

Though not defined as [Free](https://www.fsf.org)/[Open Source](https://www.opensource.org) Software (FOSS) licences, the following are also worth categorizing for the sake of completeness:

* [Code Project Open License](https://www.codeproject.com/info/cpol10.aspx)
* [Creative](https://creativecommons.org/licenses/by/3.0) [Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0)
* [Creative Commons Attribution-Share Alike 3.0 Unported License](https://creativecommons.org/licenses/by-sa/3.0)
* and [Public Domain](https://creativecommons.org/publicdomain)

## Unclear Licensing

In situations where the nature of a [third-party licence]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-licence) is unclear, this does not absolve a developer of responsibility for determining the conditions of use. Since copyright is an automatic and enforceable right for an author of a qualifying work, in all cases the initial assumption should be that such [third-party works]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-work) are not available for use in [larger works]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work) until it can be confirmed otherwise.

## Third-Party Licence Compatibility

Finally, when using a combination of components or libraries, with different [third-party licences]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-licence), it should be confirmed whether their terms and conditions are mutually compatible. This tends to be more of an issue with [strong]({% link _open-source-licences-in-business/06-strong-licence-examples.md %}) [third-party licences]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-licence) licences, which require that all [source code]({% link _open-source-licences-in-business/07-definitions.md %}#source) for the [larger work]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work) be covered by the same license. For example:

*   Neither the [GNU General Public License 3.0](https://www.opensource.org/licenses/gpl-v3.0) nor the [GNU Affero General Public License 3.0](https://www.opensource.org/licenses/agpl-v3) can be used in conjunction with any other licences (apart from each other)
*   In some cases the [GNU General Public License 2.0](https://www.opensource.org/licenses/gpl-v2.0) [may or may not be compatible with later versions of itself](https://www.gnu.org/licenses/gpl-faq.html#AllCompatibility)

In cases where two or more components or libraries are licensed under mutually incompatible [third-party licences]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-licence), then they **cannot** be used together as part of a [larger work]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work). This relates specifically to the issue of resolving multiple [third-party licences]({% link _open-source-licences-in-business/07-definitions.md %}#third-party-licence) that have been combined into the same [larger work]({% link _open-source-licences-in-business/07-definitions.md %}#larger-work), and **not** the common practice of [multi-licensing](https://en.wikipedia.org/wiki/Multi-licensing), where software is made available under two or more different licences, and recipients can choose the licence under which they would prefer to use it.