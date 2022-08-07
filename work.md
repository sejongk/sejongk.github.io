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
    - title: Support Containerization of Web Application Firewall (WAF) Product
      image:
        src: https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/2880px-Docker_%28container_engine%29_logo.svg.png
        alt: container
      description: I researched essential technologies for a new network engine in the WAF product. There were some problems in the legacy engine, one of which was that it had strong dependencies on a specific device and environment. I proposed a new network engine design that enables providing necessary network functionalities and accelerating packet processing with less dependencies in Kubernetes. 
    - title: Product License Management Agent in Cloud
      image:
        src: https://upload.wikimedia.org/wikipedia/commons/5/59/Empty.png
        alt: empty
      description: There was a requirement for each product to be integrated with the license policy server, which provides a license file and meters time-based usage. I invented a new standard license format that replaced what each product seperately used with. Based on the format, I also designed a standard license API for the policy server, and developed an python agent dealing with the product's license management.
  - category: Open Source Software Contribution
    projects:
    - title: Contour (Kubernetes Ingress Controller)
      image:
        src: https://pbs.twimg.com/profile_images/1092808662429642752/NThJo60y_400x400.jpg
        alt: contour
      description: At that time, Contour was implementing Gateway API, which is a standard kubernetes gateway interface replacing Ingress API. I added support for the RequestMirror HTTPRoute filter type at the rule level in Gateway API (<a href='https://github.com/projectcontour/contour/pull/4557'>Pull Request 4557</a>). I also tried to add thorough testings for this feature by adding an E2E test code which reads the mirror server's logs and find the particular log related to the mirrored request.
---
Displaying my work, my interests, and my projects.
<br />
<br />
