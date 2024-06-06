# kuberTENes
Kubernetes Birthday Bash - A trip down memory lane

- [Kubernetes History Blog Article - Brenden Burns](https://kubernetes.io/blog/2018/07/20/the-history-of-kubernetes-the-community-behind-it/)
- [Run K8s v1.0 in the browser](https://github.com/spurin/kubernetes-v1.0-lab)
- [Kubernetes Movie - PART 1](https://youtu.be/BE77h7dmoQU?si=5Zhw5KPi8az4Ma3L)
- [Kubernetes Movie - PART 2](https://youtu.be/318elIq37PE?si=ydjwmRdUHzGGnwtW)
- [Kubernetes Website in 2014](https://web.archive.org/web/20141114180626/http://kubernetes.io/)
- [K8s First Demo - Google I/O 2014 - Brendan Burns](https://youtu.be/tsk0pWf4ipw?si=u7Zpq4n7lwRQl4vI)
- [Kubernetes Origins Podcast with Craig McLuckie](https://softwareengineeringdaily.com/2016/07/20/kubernetes-origins-with-craig-mcluckie/)
- [YT Playlist from 2015 Kubernetes Gathering](https://youtube.com/playlist?list=PL69nYSiGNLP2FBVvSLHpJE8_6hRHW8Kxe&si=7wThb73UGJaRffD7)
- [Original Borg Papers](https://www.cse.ust.hk/~weiwa/teaching/Fall16-COMP6611B/reading_list/Borg.pdf)
- [K8s Origin Story - Blog by Craig McLuckie](https://cloud.google.com/blog/products/containers-kubernetes/from-google-to-the-world-the-kubernetes-origin-story)
- [First blog post on Kubernetes.io - Welcome to the Kubernetes Blog](https://kubernetes.io/blog/2015/03/welcome-to-kubernetes-blog/)
- [HBD K8s PARTY YouTube Stream](https://www.youtube.com/live/jYjEWlnY25M?si=8V3B43rl3C1pi8w2)
- [CNCF Landscape game](https://landscape.cncf.io/games)
- [Contributor Card](https://contribcard.clotributor.dev/)


## Kubernetes Trivia

### Firsts
Who demoed the first Kubernetes on youtube?
Google I/O 2014 - Containerizing the Cloud with Docker on Google Cloud Platform

Which image or application was used in the first demo of Kubernetes?
nginx

Who committed the first Kubernetes commit, what was the date?
Joe Beda June 6th 2014

What was the first semantic version of Kubernetes and when?
v0.4.1

What was the first version of Kubernetes in 2015?
v0.8.0

How many Kubernetes releases were done in 2014?
17 

When did Kubernetes reach its 1.0 release?
July 21, 2015

Who are the original authors of Kubernetes?
Joe Beda, Brendan Burns, and Craig McLuckie

What is the name of the mascot for Kubernetes?
Phippy

When was Kubernetes donated to the CNCF?
July 2015

When did Kubernetes become the first CNCF project to graduate?
March 6, 2018

What is the name of the first Kubernetes certification program?
Certified Kubernetes Administrator (CKA)

Which year did the first KubeCon take place?
November 9th 2015 in SF https://kubecon2015.sched.com/ 

### Ecosystem
Who did the first commit of Minikube and when?
Dan Lorenc April 18 2016

When or what version of Kubernetes minikube released, which OSs were supported?
Minikube 1.0.0. May 30th 2016, Linux and MacOS

When or what version of Kubernetes kind CLI downloadable, which versions of kubernetes supported?
v0.3.0 - May 17th 2017 (k8s 1.11, 1.12, 1.13, 1.14)

When or what version of Kubernetes kubeadm released?

When or what version of Kubernetes was Containerd v1.0.0 first supported?
v1.9.0 - December 2017

What is the significance of the number 7 in the Kubernetes logo?
It represents the seven spokes on the steering wheel, symbolizing its role as a helmsman

Which major tech companies are part of the Kubernetes Steering Committee?
Google, Red Hat, IBM, and VMware

When did K8s switch its release cycle from four times per year to three times per year?
August 2020 with 1.19 release

What company developed both etcd and the operator framework?
CoreOS

What was the first version of etcd and when was it released?
V0.1.0 was released by CoreOS on July 16, 2013

When was the Operator Framework first introduced and why?
Introduced by CoreOS in June 2016 to extend Kubernetes’ capabilities by automating the management of complex, stateful applications.

When did Kubernetes first support Windows nodes?
K8s v1.14 - March 2019

When was the first version of Helm released?
November 2015 by Deis, Inc. (Deis was aquired by Microsoft in April 2017, and Gabriel Monroy came over as a Principal Program Manager for Azure)


### Major API Features

When or what version of Kubernetes was Secret first supported?
Always supported part of core

When or what version of Kubernetes was Ingress first supported?
v1.2.0 - March 2016

When or what version of Kubernetes was Job first supported?
v1.2.0 - March 2016

When or what version of Kubernetes was ConfigMap first supported?
v1.2.0 - March 2016

When or what version of Kubernetes was Deployment first supported?
v1.2.0 - March 2016

What API feature did Deployments replace?
ReplicationController

When or what version of Kubernetes was DaemonSet first supported?
v1.2.0 - March 2016

When or what version of Kubernetes was ReplicaSet first supported?
v1.2.0 - March 2016

When or what version of Kubernetes was StorageClass first supported?
v1.4.0 - September 2016

When or what version of Kubernetes was NetworkPolicy first supported?
v1.3.0 - July 2016

When or what version of Kubernetes was CSIDriver first supported?
v1.14.0 - March 2019

When or what version of Kubernetes was CustomResourceDefinition (CRD) v1 supported?
v1.16.0 - October 2019

When did Kubernetes add support for CRI (Container Runtime Interface)?
K8s v1.5 (Dec 2016)

When did Kubernetes change the API location for Ingress from extensions/v1beta1 to networking.k8s.io/v1?
With Kubernetes 1.19 in August 2020

When did Kubernetes introduce the StatefulSet object?
With Kubernetes 1.5 in December 2016

What were StatefulSets called before they were StatefulSet?
PetSet

When was Horizontal Pod Autoscaler first introduced?
With v1.1 in November 2015

When was Docker shim removed from Kubernetes?
With v1.24 in May 2022

When was the Container Storage Interface (CSI) introduced in Kubernetes?
With v1.9 in December 2017

When did the Container Storage Interface (CSI) reach GA?
K8s v1.13 - December 2018

What were the primary components shipped with Kubernetes v1.0?
API server, etcd, controller manager, scheduler, kubelet, kubectl, kube-proxy

What were the only API features were available with Kubernetes v1.0?
Pods, replicationController, services, labels and selectors, namespaces, endpoints, nodes, events

