---
title: 'POINT: Pipeline for Offline Conversion and Integration of Geocodes and Neighborhood
  Data'
authors:
- Kevin Guo
- Allison B. McCoy
- Thomas J. Reese
- Adam Wright
- Samuel Trent Rosenbloom
- Siru Liu
- Elise M. Russo
- Bryan D. Steitz
date: '2023-10-01'
publishDate: '2024-02-20T22:32:19.463801Z'
publication_types:
- article-journal
publication: '*Applied Clinical Informatics*'
doi: 10.1055/a-2148-6414
abstract: "OBJECTIVES: Geocoding, the process of converting addresses into precise
  geographic coordinates, allows researchers and health systems to obtain neighborhood-level
  estimates of social determinants of health. This information supports opportunities
  to personalize care and interventions for individual patients based on the environments
  where they live. We developed an integrated offline geocoding pipeline to streamline
  the process of obtaining address-based variables, which can be integrated into existing
  data processing pipelines. METHODS: POINT is a web-based, containerized, application
  for geocoding addresses that can be deployed offline and made available to multiple
  users across an organization. Our application supports use through both a graphical
  user interface and application programming interface to query geographic variables,
  by census tract, without exposing sensitive patient data. We evaluated our application's
  performance using two datasets: one consisting of 1 million nationally representative
  addresses sampled from Open Addresses, and the other consisting of 3,096 previously
  geocoded patient addresses. RESULTS: A total of 99.4 and 99.8% of addresses in the
  Open Addresses and patient addresses datasets, respectively, were geocoded successfully.
  Census tract assignment was concordant with reference in greater than 90% of addresses
  for both datasets. Among successful geocodes, median (interquartile range) distances
  from reference coordinates were 52.5 (26.5-119.4) and 14.5 (10.9-24.6) m for the
  two datasets. CONCLUSION: POINT successfully geocodes more addresses and yields
  similar accuracy to existing solutions, including the U.S. Census Bureau's official
  geocoder. Addresses are considered protected health information and cannot be shared
  with common online geocoding services. POINT is an offline solution that enables
  scalability to multiple users and integrates downstream mapping to neighborhood-level
  variables with a pipeline that allows users to incorporate additional datasets as
  they become available. As health systems and researchers continue to explore and
  improve health equity, it is essential to quickly and accurately obtain neighborhood
  variables in a Health Insurance Portability and Accountability Act (HIPAA)-compliant
  way."
tags:
- Geographic Information Systems
- Geographic Mapping
- Humans
- Residence Characteristics
- Software
---
