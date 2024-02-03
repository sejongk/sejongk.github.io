---
layout: work
title: Work
slug: /work
items:
  - category: Penta Security System
    projects:
    - title: Kubernetes Operator for Security Products
      image:
        src: https://raw.githubusercontent.com/kubernetes/kubernetes/985c9202ccd250a5fe22c01faf0d8f83d804b9f3/logo/logo.svg
        alt: kubernetes
      description: I designed and developed a Kubernetes operator for the security products. The operator has a domain-specific knowledge about the products and enables the products to be seamlessly integrated with Kubernetes. Specifically, It provides dynamic configuration via custom resources and service discovery, and operational automation ranging from error remediation, blue-green deployment and dynamic scaling on load. 
  - category: Open Source Software Contribution
    projects:
    - title: Contour (Kubernetes Ingress Controller)
      image:
        src: https://pbs.twimg.com/profile_images/1092808662429642752/NThJo60y_400x400.jpg
        alt: contour
      description: At that time, Contour was implementing Gateway API, which is a standard kubernetes gateway interface replacing Ingress API. I added support for the RequestMirror HTTPRoute filter type at the rule level in Gateway API (<a href='https://github.com/projectcontour/contour/pull/4557'>Pull Request 4557</a>). I also tried to add thorough testings. For instance, I added an E2E test code which reads the mirror server's logs, and searches the particular logs related to the mirrored request to check if Contour mirrors successfully the request.
---
Displaying my work, my interests, and my projects.
<br />
<br />
