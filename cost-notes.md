 ## Cost Awareness Note
   
   During RDS provisioning, an initial configuration (Provisioned IOPS storage, 
   oversized instance class) generated an estimated cost of $8,686.20/month. 
   
   Reviewed AWS's built-in cost estimator before launching, identified the issue, 
   and reconfigured to db.t3.micro with General Purpose (gp2) storage — bringing 
   the estimate down to a free-tier-eligible ~$14.71/month.
   
   Lesson: always check the "Estimated monthly costs" panel before clicking 
   Create — AWS defaults are not always cost-conscious.
