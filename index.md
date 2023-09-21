**Check out [COMPOST](https://compost.digital), a magazine about the digital commons, telling stories about people building the web as a shared resource.** COMPOST is published to the web and [DWeb](https://getdweb.net) using the [Distributed Press API](https://github.com/hyphacoop/api.distributed.press).

![](img/2021-03-06-one-brave-ipns.png)
_COMPOST magazine viewed over IPFS on the Brave Browser with Web Monetization extension._

---

**Distributed Press** is an open source publishing tool for the World Wide Web and [DWeb](https://getdweb.net). It automates publishing and hosting content to the WWW that it seeds to [Hypercore](https://hypercore-protocol.org/) and [IPFS](https://ipfs.io). 

In addition to seeding content, the [Distributed Press API](https://github.com/hyphacoop/api.distributed.press) also seeds other project data over DWeb protocols. For example, the current Monetization API integrates with Ethereum and Open Collective to provide real-time project funding information. In the future, these APIs will support content verification and social messaging across DWeb ecosystems.

Distributed Press is currently alpha software. This is the list of current projects using the tool.

| Domain                  | Description |
|:------------------------|:------------|
| staging.compost.digital | Example website for Distributed Press |
| one.compost.digital     | Website of [COMPOST magazine Issue O1](https://one.compost.digital) |
| hypha.coop              | Website of [Hypha Worker Co-operative](https://hypha.coop) |
| sutty.ml                | Experimental website mirror of [Sutty](https://sutty.nl/en/) |

---

## Our Vision

We are building the _Distributed Press_ — a beginner friendly, open-source publishing tool for the distributed web. Aiming to empower authors, _Distributed Press_ utilizes the distributed web to amplify free expression worldwide, while exposing sources of misinformation.

We all have a sense of the wide-ranging and complex issues facing publishing today: political censorship, disinformation, walled gardens, and the [decline of independent media][decline of independent media]. Yet the solutions to these challenges remain unclear. Working with authors, audiences, and distributed web communities, we hope to co-develop new tools, in order to make publishing fair, democratic, and dignified for all.

Our approach is to engage and learn from broader communities who actively research the issues outlined above and those that practice alternative publishing models. With them, we wish to investigate if and how the distributed web can better serve the publishing ecosystem. As a means to this end, we are launching a journal for and by the citizens of the distributed web, and test its resilience against the challenges facing publishing today.

This journal is our sandbox, our lab bench, and the seed that will eventually become the _Distributed Press_ publishing tool for anyone to use.

[decline of independent media]: https://www.cima.ned.org/publication/confronting-the-crisis-in-independent-media/

## Today, centralized platforms wield disproportionate power

![distributed-press-0](img/distributed-press-0.svg)

Of the [3.9 billion Internet users worldwide][3.9 billion Internet users worldwide],

>Facebook now boasts 2.7 billion monthly users across its family of apps.
>
> -- Mariel Soto Reyes, _[Scandals and teen dropoff weren't enough to stop Facebook's growth][Scandals and teen dropoff weren't enough to stop Facebook's growth]_

Facebook, Tencent, and Google now mediate a majority of global public discourse. As recent history shows, such extreme power consolidation can be readily abused to [influence political outcomes][influence political outcomes], [censor citizens][censor citizens], and create an [anti-competitive market][anti-competitive market].

[3.9 billion Internet users worldwide]: https://www.statista.com/topics/1145/internet-usage-worldwide/
[Scandals and teen dropoff weren't enough to stop Facebook's growth]: https://www.businessinsider.com/facebook-grew-monthly-average-users-in-q1-2019-4
[censor citizens]: https://citizenlab.ca/tag/wechat/
[influence political outcomes]: https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal
[anti-competitive market]: https://ec.europa.eu/commission/presscorner/detail/en/IP_19_1770

## The distributed web presents emerging alternatives

![distributed-press-1](img/distributed-press-1.svg)

The promise of the Distributed Web (DWeb) is that it gives everyone the ability to control their digital networks and platforms. In distributed networks, the underlying code, data, and network infrastructure are managed by many. 

## We are trapped by network effects

Centralized platforms with large networks like Facebook and Medium are still unmatched for promoting and discovering new content.

Content authors and audiences who are attracted to the promise of the distributed web are compelled to maintain a presence on centralized platforms in order to access wider viewership and content.

With the inherently fragmented nature of the distributed web, content dissemination and discovery is a recognized challenge. However, initiatives such as [IndieWeb][IndieWeb]'s syndication model and [Micro.blog][Micro.blog]'s decoupling of the timeline from post storage have shown us an encouraging path forward.

[IndieWeb]: https://indieweb.org
[Micro.blog]: https://micro.blog

## Verifiable sources in a fragmented ecosystem

Imagine if authors published content in their entirety rather than as a hyperlink, directly to your favourite social networks or the aggregation sites where discussions happen. It would be important for the authenticity of the content to be verifiable to prevent replication and piracy, irrespective of an origin website that serves as a single source of truth.

To establish authenticity, we can disseminate content along with digital signatures by the author, publisher, or other fact-checking bodies, such as organizations like [Civil][Civil] that aims to uphold journalistic ethics.

Signed messages also allow authors to distribute peer-to-peer payments in order to crowdfund their work. Crowdfunded public interest publications like [Ricochet][Ricochet] and digital currency supported [Popula][Popula], exemplify this concept.

[Civil]: https://civil.co
[Ricochet]: https://ricochet.media
[Popula]: https://popula.com

## Censorship resistant content dissemination

Distributed web technologies [claim to resist centralized censors][claim to resist centralized censors]. But even the most distributed technologies have [chokepoints that can be exploited][chokepoints that can be exploited] by private or state actors to undermine people's free expression. As a result, circumventing censorship [necessitates particular practices][necessitates particular practices].

We plan to utilize tools such as the [OONI Probe][OONI Probe] to measure worldwide content dissemination and evaluate compatibility of distributed web protocols with independently operated network infrastructure, such as [offline mesh networks][offline mesh networks] where packets travel through channels out of reach from state censors.

[claim to resist centralized censors]: https://ipfs.io/blog/24-uncensorable-wikipedia/
[chokepoints that can be exploited]: https://github.com/ipfs/ipfs/issues/419
[necessitates particular practices]: https://github.com/ipfs/notes/issues/281
[OONI Probe]: https://ooni.org/nettest/
[offline mesh networks]: https://edgeryders.eu/t/a-radically-new-internet-a-study-on-p2p-protocols-and-mesh-networks/9802

**Our goal over the next three years is to deploy and maintain an open source tool that authors can use to publish content to the DWeb and WWW.** The tool will streamline distribution and monetization on the DWeb, editorial and fact checking, and guide authors to establish creator owned cooperative publications. In turn, the tool will be sustained by the federation of cooperative publications it enables.

## Research will be made public for a wider community of researchers and developers

Research topics:
- Applicability of distributed web protocols for digital authorship
- Mechanisms for disintermediated content dissemination
- Economic viability of distributed publishing
- Compatibility with current alternative publishing tools and practices
- Publishing practices that resist centralized censorship

Research methods:
- Informational interviews with diverse community members and partners
- Comparative survey of publishing on the distributed web versus the World Wide Web
- Secondary research looking at existing literature
- Technical prototyping with available distributed web protocols and tools
- Co-creation activities with content authors and readers

---

## Project team
Our project team has experience in the distributed web, community networks, cooperative governance, and content publishing. 

- **Mai Sutton**  
Co-founder, Lead Editor & Community Steward, COMPOST magazine  
Associate Producer of DWeb Projects, Internet Archive  
Steward, People’s Open Network / Disaster Radio  
formerly Global Policy Analyst, Electronic Frontier Foundation  

- **Udit Vira**  
Co-founder, Product Lead, COMPOST magazine  
Founding Member, Hypha Worker Co-operative   
Strategist, studio From Later  

- **Benedict Lau**  
Co-founder, Distributed System Engineer & Technical Lead, COMPOST magazine      
Founding Member, Hypha Worker Co-operative / Toronto Mesh   
formerly Network Coordinator, DWeb Camp 2019  


## Let’s chat!
If anything here interests you, and you want to explore collaborations, get in touch with us at `hello [at] distributed.press`.
