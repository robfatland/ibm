# ibm

* IBM has a full cloud stack, two terms 'Infrastructure' and 'Platform'
    * Infrastructure cloud
        * compute, storage, networking 
        * "Build" paradigm
    * Platform cloud
        * Services
    * See the profusion through the IBM Cloud Catalog
    
* Console resembles others
    * LHS: Pricing plan: *Lite* is a free tier. *free* is "services that are always free".
    * Term "cloud foundry"?
    * Term "Discovery" NLP service has a 1000 document limit in Lite tier, 30 day timeout.
    * Term "Resource Group" sounds like same in Azure; or Projects in GCP. to do True?
        * Within Resource Group create Access Group with permissions

* Invite people to an Access Group within Resource Group, not to the Account
* API is compartmentalized; so ML goes under `ibm_watson`
* VM start up
    * VPC per usual; always choose Virtual Server for VPC to start off on the right security foot
    * root volume is 100GB by default
    * add a floating ip to get a public ip address (to do is this persistent through stop/start?)
