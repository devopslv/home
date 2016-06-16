:date: 2016-06-15
:slug: devopspro-review
:author: Marcis Veveris
:category: review
:tags: devopspro, automation, infrastructure, review
:summary: short review of 2016 devops pro conference


****************************
DevOps Pro conference review
****************************

On May 26th `DataMiner`_ hosted first DevOps centred conference in Baltic. 
From technical perspective two of the major themes was microservices and 
Infrastructure as a Code.
Although event is happening for the first time it had a 4 talks in parallel 
which made it difficult to choose which panels to visit. Nice thing was that 
organizers used color codes to distinguish 
between technical/not-so-technical/tool-introduction talks.
It included speakers from CloudBees, Uber, LayerV and Cloud66 to name a few.

I have chosen only three talks for review as these for me was most important.

***************
Panels in depth
***************


Andrey Adamovich: Patterns for Infrastructure as a Code
*******************************************************

Andrey talk was focused on Pattern - Anti-Pattern dichotomy. During his talk he pointed out pattern/anti-patterns 
for Image creating, secret storage/distribution, DSL for managing infrastructure, how to manage and apply configuration changes.

`Andreys presentation`_

Tushar Sharma: Does your configuration code smell?
**************************************************

Tushar was focused on certain anti-patterns that are most common when working configuration code. As an example he used
Puppet code examples. This presentation is an `outcome of study`_ performed by Tushar Sharma, Marios Fragkoulis and Diomidis Spinellis 
where they analyzed Puppet code repositories hosted on GitHub by utilizing Puppet-Lint tool with custom rules to 
detect implementation smells and their own tool Puppeteer for design smell detection.
You can find `list of configuration smells here`_.

`Tushars presentation`_

Tim Perry: Opening open source with DevOps
******************************************

This was inspiring talk where Tim shared his own experience as a Open source contributor wanna be.
Talk was concentrated on frustrations that are experienced when trying to contribute to the oss 
project for the first time. Key idea of his talk is that with DevOps mindset we can create oss projects
that are easier to set up, e.g., by creating Vagrant+Docker boxes with running source code so that initial 
set up is already there and newcomer can dive into software itself rather than trying to configure it manually.

`Tims presentation`_


`Check other conference presentations`_


Lately we can see that operations are adopting best practices from development - we're talking about
configuration code smell, unit and functional tests for infrastructure, keeping configuration
in source control, etc. We can even apply tools used by testers to make test scenarios - Cucumber for example.
But at the same time we can't apply every practice taken from development world - so we have
to look into establishing common practices for developing infrastructure. 


DataMiner has done good job for promoting DevOps in Batics - it is nice to see that a lot of people are interested in efficient development.
Also Dataminer is seems very serious about next years conference so it is something we should look forward to.



.. _DataMiner: http://dataminer.lt
.. _list of configuration smells here: http://www.tusharma.in/research/a-catalog-of-configuration-smells/
.. _outcome of study: http://dl.acm.org/citation.cfm?id=2901761

.. _Andreys presentation: http://www.slideshare.net/aestasit/patterns-for-infrastructure-as-code-for-devopspro-2016
.. _Tushars presentation: https://speakerdeck.com/devopspro/does-your-configuration-code-smell
.. _Tims presentation: https://speakerdeck.com/devopspro/opening-open-source-with-devops

.. _Check other conference presentations: http://devopspro.lt/conference-presentations/

