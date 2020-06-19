> # This blog is part of the **[Cloudyman Mentorship Program](https://t.co/78sRvCvYiO?amp=1)** under the mentorship of *[Mustafa Saifee](https://www.linkedin.com/in/saifeemustafaq/)*

## Date: June 18, 2020

## What is a region pair?

- An Azure Region Pair is a relationship between 2 Azure Regions within the same geographic region for disaster recovery purposes. If one of the regions were to experience a disaster or failure, then the services in that region will automatically failover to that regions secondary region in the pair. For example, North Central US region’s pair is South Central US.

![](https://i1.wp.com/build5nines.com/wp-content/uploads/2017/01/azureregionpairgeography.png?w=1080&ssl=1)

- Almost all the Azure Regions are located within the same geographic region as at least 1 other Azure Region; it’s Region Pair. The only exception to this rule is the Brazil South region, which is the only Azure Region in Brazil, so it’s Region Pair is South Central US in a one-way pairing connection, as South Central US’s pair is North Central US. I know this sounds confusing, but this is the only Azure Region who’s pair is outside it’s geographic region.

- The Azure Region Pairs are more than just a visual concept to think about with Azure Regions. The Azure Region pairs are connected directly together and offer multiple benefits when utilized together in the same distributed or redundant system. Before we get into these benefits of Azure Region Pairs, let’s first discuss the Azure Regions and Datacenters in further details.

## Geography	     =              Paired regions

Asia               =       East Asia | Southeast Asia

Australia	         =       Australia East | Australia Southeast

Australia	         =       Australia Central | Australia Central 2

Brazil	           =       Brazil South (1) | South Central US

Canada	           =       Canada Central | Canada East

China	             =       China North | China East

China	             =       China North 2 | China East 2

Europe	           =       North Europe (Ireland) | West Europe (Netherlands)

France	           =       France Central | France South

Germany	           =       Germany Central | Germany Northeast

India	             =       Central India | South India

India	             =       West India | South India

Japan	             =       Japan East | Japan West

Korea	             =       Korea Central | Korea South

North America	     =       East US | West US

North America	     =       East US 2 | Central US

North America	     =       North Central US | South Central US

North America	     =       West US 2 | West Central US

South Africa	     =       South Africa North | South Africa West

UK	               =       UK West | UK South

United Arab Emirates	 =   UAE North | UAE Central

US Department of Defense =	US DoD East | US DoD Central

US Government	     =       US Gov Arizona | US Gov Texas

US Government	     =       US Gov Iowa | US Gov Virginia

US Government	     =       US Gov Virginia | US Gov Texas
