# AWS Storage Options

AWS re:Invent 2023 -  AWS Storage - The backbone for your data-driven business (STG227)

    Stories on how AWS Storage solutions work for different usecases.
    Work on improving Durability, Security, Availability and Performance

EBS - EBS earlier hosted on harddrive - from 2008 - 2012.
EBS - Later introduced recent writes ofloaded to SSD's - SSD's where expensive back that time
      Approach to use the SSD efficiently - Async write to SSD on __write__ operation from application.
      Since most of the operation