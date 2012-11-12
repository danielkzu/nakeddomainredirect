NakedDomainRedirect
===================

This repository contains the website content for nakeddomainredirect.com redirection service.

This site is uploaded statically to S3 where it's hosted as a website. Therefore, when you hit 
nakeddomainredirect.com, the site service itself is used to redirect you to the www version, which 
is actually CNAME'd to Amazon's S3 bucket.