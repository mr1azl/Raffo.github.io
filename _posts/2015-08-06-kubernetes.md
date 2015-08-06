---
layout: post
title: Kubernetes and Google's Cloud Strategy
---

We all know that Google was struggling a lot in the last year to get some users
to switch from AWS to Google Cloud Engine as most of the startups and companies
that decided to use cloud services were currently using Amazon AWS. Google
tried hard in the past to be a relevant player in the PaaS offering with Google
App Engine, but this was more about fighting Heroku than AWS and while they
were so busy making this, they wasted years during which Amazon got the whole
market of IaaS.

We can easily say that Google is a late player in the IaaS market, at least
from the consumer perspective, even if they have probably the biggest
infrastructure ever in terms of number of nodes and scale. Even if this is
true, it is widely known that Google was a precursors in containerization of
workloads, but their work was not available for customers external to their
organization. 

Google soon realized that no matter the way they were fighting, there was no
way to win the IaaS "war", at least not in the short term and definitely not in an easy way. 
Nonetheless, Google was still able to find a solution to all their problems: they changed the objective, 
deciding to become one of the biggest players in Open Source Container orchestration, 
using all the buzz around Docker. 

This resulted to be extremely intelligent, given the  fact that, for some reason, 
Amazon was weak in this area and was following the old Microsoft style approach with AWS: 
their cloud is very closed source, everything kept for themselves and everything offered as a (paid) service, 
apart from the SDKs. Google is now following a completely different approach: 
they want to open everything about [Kubernetes](http://kubernetes.io/), their answer to cloud orchestration, 
and use it as the basis of their future cloud solutions while giving it to a [foundation](https://cncf.io/) 
and making developers a big part of it. Google knows that Open Source is the only way to win in the cloud market, 
no matter what other competitors are doing... and they are going in the right direction.


