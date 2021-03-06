# use-UPL-not-MIT

use the UPL-1.0 license and not the MIT License 

![](https://img.shields.io/badge/license-upl--1.0-black)

```
![](https://img.shields.io/badge/license-upl--1.0-black)
```

> [source, https://oss.oracle.com/licenses/upl/](https://oss.oracle.com/licenses/upl)

- [spdx https://spdx.org/licenses/UPL-1.0.html](https://spdx.org/licenses/UPL-1.0.html)


## Readme Section:

<pre>
 ## License
 
 Licensed under either of

 * Universal Permissive License 1.0
   ([LICENSE-UPL](LICENSE-UPL) or https://opensource.org/licenses/UPL)

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 
 at your option.

 ### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Universal Permissive License v 1.0 
license, shall be dual licensed as above, without any additional terms or conditions.
</pre>


# Universal Permissive License FAQ

> Excerpt
> This page provides a copy of and also attempts to answer some frequently asked questions about the Universal Permissive License version 1.0.  The UPL was first drafted by Oracle in the Spring of 2014, was revised several times after extensive consultation with the Java Community Process Executive Committee and through the Open Source Initiative review process, and was finally approved by the Open Source Initiative in February 2015.


## The Universal Permissive License (UPL), Version 1.0

This page provides a copy of and also attempts to answer some frequently asked questions about the Universal Permissive License version 1.0. The UPL was first drafted by Oracle in the Spring of 2014, was revised several times after extensive consultation with the Java Community Process Executive Committee and through the Open Source Initiative review process, and was finally approved by the Open Source Initiative in February 2015.

To begin with, this is the final approved text of the Universal Permissive License v 1.0:

```
Copyright (c) [year] [copyright holders]

The Universal Permissive License (UPL), Version 1.0

Subject to the condition set forth below, permission is hereby granted to any
person obtaining a copy of this software, associated documentation and/or data
(collectively the "Software"), free of charge and under any and all copyright
rights in the Software, and any and all patent rights owned or freely
licensable by each licensor hereunder covering either (i) the unmodified
Software as contributed to or provided by such licensor, or (ii) the Larger
Works (as defined below), to deal in both

(a) the Software, and
(b) any piece of software and/or hardware listed in the lrgrwrks.txt file if
one is included with the Software (each a "Larger Work" to which the Software
is contributed by such licensors),

without restriction, including without limitation the rights to copy, create
derivative works of, display, perform, and distribute the Software and make,
use, sell, offer for sale, import, export, have made, and have sold the
Software and the Larger Work(s), and to sublicense the foregoing rights on
either these or other terms.

This license is subject to the following condition:
The above copyright notice and either this complete permission notice or at
a minimum a reference to the UPL must be included in all copies or
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

When referring to the license, you may link to it at [https://oss.oracle.com/licenses/upl](https://oss.oracle.com/licenses/upl) or you may also find a copy on the Open Source Initiative web site at [https://opensource.org/licenses/UPL](https://opensource.org/licenses/UPL).

## Frequently Asked Questions

1.  [What is the UPL and why did you create it?](https://oss.oracle.com/licenses/upl/#faq-1)
2.  [What are the most important features of the UPL?](https://oss.oracle.com/licenses/upl/#faq-2)
3.  [Can you point to some concrete problems the UPL solves that you could not have addressed with the MIT, BSD or Apache licenses?](https://oss.oracle.com/licenses/upl/#faq-3)
4.  [So why is the absence of an express patent license in the MIT or BSD licenses a problem - isn't the implied license enough?](https://oss.oracle.com/licenses/upl/#faq-4)
5.  [Why didn't you include a defensive patent termination provision?](https://oss.oracle.com/licenses/upl/#faq-5)
6.  [I heard this licenses our entire patent portfolio to Oracle, is that right?](https://oss.oracle.com/licenses/upl/#faq-6)
7.  [How should I apply the UPL to my code?](https://oss.oracle.com/licenses/upl/#faq-7)
8.  [What goes in the Larger Works file and what should it look like?](https://oss.oracle.com/licenses/upl/#faq-8)
9.  [Can someone else change my Larger Works file and license my patents for other things?](https://oss.oracle.com/licenses/upl/#faq-9)

### What is the UPL and why did you create it?

The UPL is a highly permissive license, including both copyright and patent licenses, which permits use and relicensing under both copyleft and commercial terms, and also facilitates use as a contributor license agreement.

It was originally borne out of a discussion in the Java Community Process around what it would take to permit collaboration on JSR reference implementations in open source forges without the necessity of collaborators signing the JSPA or an Oracle Contributor Agreement. In order to accommodate the broadest possible use case, the license needed to include an express patent license and to be broadly agreed to be GPLv2, GPLv2+Classpath Exception, CDDL, and commercial license compatible, including the ability to cut and paste code between modules, and while it is almost universally agreed among those knowledgeable in FOSS licensing that license proliferation is something to be avoided without good cause, since a license meeting these relatively simple and obvious criteria did not exist, it was decided to draft one.

Drafting started with the MIT license, and after a lot of discussion with other open source lawyers, developers, members of the Java Community Process Executive Committee, and reviewers and board members of the Open Source Initiative, and several rounds of revision, finally arrived at the vetted license text you see here. The license was approved by the OSI as conforming with the Open Source Definition and non-duplicative of existing permissive licenses in February 2015.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### What are the most important features of the UPL?

The most important features and things to understand about the UPL are the following:

-   **Clear patent protection**. The UPL is a broad permissive license including both a copyright license and an express patent license, covering at least a version licensed by someone under the license (for example a distributor) and/or a version someone contributed to even if they never distribute the whole. (The reason the latter is needed is discussed below.) By virtue of the unambiguous patent license, the UPL is materially clearer with respect to the rights licensed and likely broader than either the MIT or BSD licenses.
-   **Clear & simplified relicensing**. The UPL expressly permits sublicensing under either the UPL or under other terms, which clearly allows someone to relicense code received under the UPL either on copyleft terms, on proprietary terms, or otherwise, thus permitting maximum flexibility in reuse.
-   **Reduced overhead in source files**. The UPL expressly permits use of the license without including a full copy of the text, which is useful for JavaScript or other cases where minimizing space consumed by licenses is desired - see below for our recommendation of how to apply the license or include proper attribution without the full text.
-   **It can be used as a contributor agreement**. Finally, the UPL may be used as a contributor license agreement licensing both the software itself and also contributor patents for use in one or more "Larger Works." The Larger Works licensed in this fashion are designated by the use of a separate file accompanying the license, akin to the NOTICE file that accompanies the Apache License, Version 2.0. The Larger Works file can be used to control for both contributions to other works (for example, we could specify MySQL in a Larger Works file for a work, which would then license contributor patents for MySQL as well as the contribution), to set patent license scope for specific versions (for example, we could specify the approved reference implementation of JSR-xxx including Maintenance Releases to ensure that all contributors to an RI are licensing both the final version of the RI and qualified updates under the JCP program), or both.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### Can you point to some concrete problems the UPL solves that you could not have addressed with the MIT, BSD or Apache licenses?

The most important problem the UPL solves is the inclusion of an express patent license in a license that is both broadly agreed to be uniformly copyleft compatible and also permits the software to be freely used in commercially licensed software (i.e., without concerns about reciprocal license obligations).

The MIT and BSD licenses do not include express patent licenses, and while many argue that there is an implied patent license, there is nontrivial debate about the existence & scope of any such implied license. This is addressed in some more detail below. The Apache license, on the other hand, is argued by some not to be GPLv2 compatible, which makes it tricky to use in connection with GPLv2 licensed code - the GPLv2 is still by far the most popular open source license, and unambiguous, undisputed GPL compatibility was a crucial qualifier for any license considered for use in the JCP. (Even the BSD license has been argued not to be GPL compatible - while this need not be addressed here, and it is not the conclusion of the FSF or most others, by virtue of expressly permitting relicensing on other terms, the UPL is definitively and fully GPLv2 compatible.)

Another problem solved with the UPL, which seems like a small thing but adds compliance and clarity, is that licensors and distributors are expressly permitted to reference the UPL rather than including a complete copy of the text in each item. What is the license solving for here? The MIT and BSD licenses expressly require that you include a complete copy of the license in each piece of source code. This means that if you have 50 different JavaScript files being downloaded from a page, each one should be giving you a complete copy of the license - you may be using as much bandwidth for licenses as you do for the actual code! And if you do not include a complete copy of the license, as some folks do not, merely referring to the license by URL or name, then you are not really applying the license in the intended manner and are in fact suggesting that downstream recipients not strictly follow those terms either.

Finally, the inclusion of the Larger Works concept facilitates use as a contributor license agreement (CLA), with contributors granting a patent license to the works to which they're contributing, and therefore creating a common & safe platform for collaboration where no one is going to assert infringement by the same project in which they're an active participant.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### So why is the absence of an express patent license in the MIT or BSD licenses a problem - isn't the implied license enough?

Some authorities think it _is_ enough, but not everyone agrees on this point. To begin with, it has been suggested that in some jurisdictions there may be no implied license at all, or only a license to people to whom a licensor directly distributed the software.

But even if one were to take the position that a patent license covering any contribution is implied, and further that it covers the entirety of a work you distribute, in our world of cloud offerings, many contributors may never distribute the entirety of the work at all. This may reduce the likelihood that a court would find them to have granted an implied license for the whole of the work.

The UPL attempts to solve these problems by having each party that either contributes to the project or distributes it under the UPL expressly license all patents that they own or can freely license that cover the work - thus, e.g., licensing the whole even from contributors who never distribute the whole.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### Why isn't there a defensive patent termination provision?

A defensive patent termination provision may sound like a great idea at first, especially for a pure open source project, but does not really work for contributions to software that is also licensed on commercial terms.

Why? A company that takes on commercial obligations with respect to a piece of code needs to retain the ability to keep supporting and shipping that code. A defensive patent termination provision allows someone who makes a contribution and then breaches the project license to the project to then potentially effectively block infringement suits against them, even when they have willfully and flagrantly disregarded community norms and IP rights in the project. Such a provision is therefore in reality as much of a sword as it is a shield.

Say, for example, that a fictional company WidgetCo were to make a contribution to fictional company GadgetCo's product GadgetX under a license with a patent termination provision. Now, WidgetCo decides to violate GadgetCo's terms and distribute GadgetX without a license. GadgetCo's options for stopping the violation would ordinarily include both copyright and also patent infringement claims for any patents covering GadgetX. If, on the other hand, WidgetCo has made patent covered contributions under an agreement with a so-called defensive termination clause, GadgetCo's ability to stop WidgetCo from violating the license may be significantly compromised because it can no longer bring patent claims without risking losing its own license to the patents on the contributions, which therefore might require it to stop shipping GadgetX immediately and stop supporting versions that customers are relying on.

As a commercial distributor of software, GadgetCo's customers rely on it to have the rights it needs to be able to continue to deliver and support the software, and defensive patent termination rights in contributions are inconsistent with those obligations. Defensive patent termination only helps someone who may be subject to infringement litigation by someone who is using the code - it won't stop patent trolls, who aren't normally using the code to begin with. So who does it stop, in reality? Someone who is using the code but has IP rights that someone else using the code is infringing. Now, it may be reasonable to tell someone who has no relationship to a community that they cannot simultaneously expect to be able to use the code and also sue for its use - thus making such provisions at least not entirely crazy for a pure FOSS project that no one is signing up to develop or support on a commercial basis, and which is rarely if ever going to need to enforce its rights anyway. But for anyone who both actually expects to need to enforce its license and also wants to take contributions, this makes no sense - you need to be able to enforce your rights in the project without needing to stop shipping or using it, and accepting contributions under terms with a patent termination provision does not satisfy this basic need.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### I heard this licenses our entire patent portfolio to Oracle, is that right?

No, it is not, this is simply untrue except in odd and contrived circumstances that would apply to other FOSS licenses as well. If your entire patent portfolio happens to read on a UPL licensed project that you have distributed on those terms or contributed to, or its designated Larger Works, then yes, it would all be licensed for use in that Software and those specified Larger Works, not just to Oracle but to all licensees under the UPL, just as it would all be licensed for a project under the Apache Software License or Eclipse Public License if your entire portfolio read on a project under the ASL or EPL. Patents that do not read on the project as you contributed to or distributed it or the specified Larger Works are not licensed, there is no magic here.

The patent scope is not really all that complicated. It covers your contributions, the project you contributed to in the state it existed when you contributed, and anything specified in the Larger Works file (which may be another application, it may be other or later versions, it may be a piece of hardware, or any combination of those things - or, just as importantly, it may be none of those things, since many projects may have no Larger Works file at all, in which case the patent license is little different than the express patent license in the Apache license, only without the so-called defensive termination provision).

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### How should I apply the UPL to my code?

It is best to insert a copyright notice and a copy of the license at the top of each source file, and if there is a package of numerous files, to also insert a LICENSE file including a copy of the UPL in the root of the distribution. Here is an example:

```
/*
** MyWidget version 1.0.
**
** Copyright (c) 2015 WidgetCo, Inc.
**
** The Universal Permissive License (UPL), Version 1.0
**
** Subject to the condition set forth below, permission is hereby granted to any
** person obtaining a copy of this software, associated documentation and/or data
** (collectively the "Software"), free of charge and under any and all copyright
** rights in the Software, and any and all patent rights owned or freely
** licensable by each licensor hereunder covering either (i) the unmodified
** Software as contributed to or provided by such licensor, or (ii) the Larger
** Works (as defined below), to deal in both
** 
** (a) the Software, and
** (b) any piece of software and/or hardware listed in the lrgrwrks.txt file if
** one is included with the Software (each a "Larger Work" to which the Software
** is contributed by such licensors),
** 
** without restriction, including without limitation the rights to copy, create
** derivative works of, display, perform, and distribute the Software and make,
** use, sell, offer for sale, import, export, have made, and have sold the
** Software and the Larger Work(s), and to sublicense the foregoing rights on
** either these or other terms.
** 
** This license is subject to the following condition:
** The above copyright notice and either this complete permission notice or at
** a minimum a reference to the UPL must be included in all copies or
** substantial portions of the Software.
** 
** THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
** IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
** FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
** AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
** LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
** OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
** SOFTWARE.
*/

```

If using the UPL for JavaScript or other circumstances in which space is at a premium, you may use a reference to the license rather than a full copy (though a full copy is always preferred if there's room and you won't be transmitting a bunch of copies to the same user). If you want to use just a short reference, you should still insert a copyright notice, and along with it, a statement that the file is licensed under the UPL, and may link to it at [https://oss.oracle.com/licenses/upl](https://oss.oracle.com/licenses/upl) or on the Open Source Initiative web site at [https://opensource.org/licenses/UPL](https://opensource.org/licenses/UPL).

Here is an example header with a short reference for use in source code:

```
/*
** MyWidget version 1.0.
**
** Copyright (c) 2015 WidgetCo, Inc.
** Licensed under the Universal Permissive License v 1.0 as shown at https://oss.oracle.com/licenses/upl/
*/

```

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### What goes in the Larger Works file and what should it look like?

To begin with, we should note that the Larger Works concept will be irrelevant to many people and to be clear, there is no need to license any Larger Works at all in order to use the UPL on your code - this is still advantageous versus other permissive licenses because licensees can count on a patent license of unambiguous scope from each contributor, can freely relicense the code as necessary for their needs, and can abbreviate the license notice if appropriate.

The purpose of the Larger Works addition to the license is to allow you to use the UPL as a contributor license agreement, commonly referred to as a CLA, licensing patents for a specified larger work or set of works with which contributions may be used. If you desire to use the UPL as a CLA, in addition to including the UPL and/or references to it in your source, you should insert a lrgrwrks.txt file in the root of the distribution specifying the licensed Larger Works. You will name the licensed project/product there, and if appropriate, specify what versions are covered. In theory you could use a single word naming a product, which would be effective, but some slightly prettier examples are as follows.

Here is what we are hoping to use in connection with JCP Reference Implementations:

```
/* Larger Works File for JSR-xxx
** 
** Licensed Larger Works: The Reference Implementation for JSR-xxx Including Maintenance Releases
** as defined in the JCP Procedures documentation.
*/   

```

So what is the intent here? We are not expanding the scope of the licensed project beyond the RI, however, we want to make sure that the RI is fully covered such that an early contributor who stops adding new code still licenses the RI as a whole, including Maintenance Releases down the line.

A somewhat broader example is as follows:

```
/* Larger Works File for MyWidget
** 
** Larger Works: MyApp
*/

```

Here, someone has set up the Larger Works file to act as a CLA for the application MyApp. The licensors of MyWidget are also licensing their patents for use in MyApp, and because there is no version restriction, this is presumably true for future versions of MyApp as well as the current version. If they wanted to license only the current version, they could have said:

```
/* Larger Works File for MyWidget
** 
** Larger Works: MyApp 1.0
*/

```

Or if Company A wanted to use the UPL with a Larger Works file as a CLA for all of their products, they could use one of the following:

```
/* Larger Works File for Contributions to Company A Projects
** 
** Larger Works: All Software Authored or Distributed by Company A
*/

```

or

```
/* Larger Works File for Contributions to Company A Projects
** 
** Larger Works: All Company A Products and Projects
*/

```

If the Apache Software Foundation wanted to use the UPL as a CLA, they could use the following:

```
/* Larger Works File for Contributions to ASF Projects
** 
** Larger Works: All Apache Software Foundation Projects
*/

```

or even more broadly, to include dependencies that are not ASF projects:

```
/* Larger Works File for Contributions to ASF projects
**  
** Larger Works: All Apache Software Foundation projects and their dependencies
*/

```

or they could make it project specific, for single or multiple Projects:

```
/* Larger Works File for Contributions to Apache Ant & Maven
** 
** Larger Works: Apache Ant and Apache Maven and their subprojects
*/

```

or project and version specific:

```
/* Larger Works File for Contributions to Cassandra
** 
** Larger Works: Apache Cassandra 2.0.15 and updates other than major version updates
*/

```

or subject area specific:

```
/* Larger Works File for Contributions to Build Tools
** 
** Larger Works: All Apache Software Foundation projects pertaining to software builds and related processes, including without
** limitation Ant, Ant Libraries, Ivy, IvyDE, EasyAnt, Maven and other software for controlling build processes tools
*/

```

As you can see, the intent of the Larger Works file is to permit nearly infinite flexibility in what is being licensed beyond the Software itself, as every company and FOSS project has different needs. Note that while a comment format has been used for these examples, since this is not executable code, this isn't strictly necessary, it was done as a matter of habit and in case someone imports one of the files into some executable code.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

### Can someone else change my Larger Works file and license my patents for other things?

To begin with, a party who alters the Larger Works file cannot alter the scope of the license someone else granted, any more than they could alter the license text of the UPL, the GPL, or any other license and assert that the original licensors are bound by their changes. So no one can offer a broader license to your patents than the one you declared. The only power they have is to sublicense downstream recipients on different terms under whatever IP rights they have.

And on the flip side, what happens if someone simply removes the Larger Works file from a code base and then redistributes without it? Then they are sublicensing the code to a downstream recipient on other terms, without any Larger Works being licensed under their own patents, though the license from the original licensors would still survive on those terms as to people who receive the Software from other sources.

Similarly, if someone alters the Larger Works file and then distributes the code to new recipients themselves under the UPL, then that new distributor is granting a license of a different scope than the one granted by the original authors, which they are permitted to do, just as they would be permitted to grant their own license to the code under the GPL or a commercial license. However, the polite thing to do in this case would be to address the altered scope of their license in the Larger Works file while leaving intact the Larger Works designation from prior licensors. Let's say, for example, we start off with a Larger Works file that looks like this, covering all of Java:

```
/* Larger Works File for Contributions to Project X
** 
** Larger Works: All Oracle Java implementations including without limitation Oracle Java EE, Java SE, Java ME, and OpenJDK
*/

```

This would grant a license to all of Java from each contributor on those terms. Now let's say Company A only wants to license a particular JSR, not all of Java. They would ideally add separate license and Larger Works files that travel with their contributions calling out only that JSR, most effectively by placing them in a separate directly clearly demarcating what is under that license. (Separating these things out is always a trick when you try to commingle source in the same file, but if you keep files separate, this is not generally difficult.)

In the alternative, if the contributions were not easily separable from the larger project in another directory, and for some reason they could not add a separate directory just for the license either, and therefore absolutely needed a way to combine their own, distinct Larger Works designation with that from others, they could in theory also add their own declaration to the existing Larger Works file without purporting to change the license from others as follows:

```
/* Larger Works File for Contributions to Project X
** 
** Larger Works: All Oracle Java implementations including without limitation Oracle Java EE, Java SE, Java ME, and OpenJDK
**
** Exception: Company A licenses only the following Larger Works: The Reference Implementation for JSR-xxx including
** Maintenance Releases as defined in the JCP Procedures documentation
*/

```

This would therefore clearly inform a recipient that only the RI was licensed under Company A's patents, but leave intact the reference to the broader license from other contributors.

There are certainly other possibilities for accommodating multiple Larger Works scopes as well, about which your counsel can advise you.

[Return to FAQ.](https://oss.oracle.com/licenses/upl/#faq)

[Return to top.](https://oss.oracle.com/licenses/upl/#top)

