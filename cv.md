# Dmitrii Kholodov

## Contact Info
* **LinkedIn**: [kholodov](https://www.linkedin.com/in/kholodov/)  
* **GitHub:** [jeky11](https://github.com/jeky11)
* **Discord:** [jekyll_dk](https://discordapp.com/users/1286318206998413424)  

## About me
<p>
As a senior software engineer with more than 12 years of experience, I am passionate about software development and a commitment to doing good work. 
My expertise spans a wide array, with a particular focus on .NET and Event Sourcing, while my professional journey has centered around the e-commerce domain.
</p>
<p>
Over the years, I've honed my skills in developing both small and large distributed high-load applications and creating the necessary tools to support them. 
One of my standout achievements has been leading the migration from a legacy monolithic system to modern microservice-based architecture, 
resulting in substantial improvements in stability, scalability, and performance.
</p>

## Skills
* C#, ASP.NET, ASP.NET Core, MVC
* EventStore, MS SQL Server, Entity Framework, MongoDB, LMDB
* Microsoft Azure: Blob Storage, Key Vault, App Configuration, Feature management, Service Bus
* React, Redux, AngularJS, jQuery, JavaScript
* Event Sourcing, CQRS, DDD, TDD, TBD, Agile, Scrum
* Visual Studio, JetBrains Rider, Jira, Slack, Grafana, Kibana

## Code example
```
public string LongestCommonPrefix(string[] strs)
{
	string result = "";
	int shortestStr = strs.Min(s => s.Length);

	for (int charNumber = 0; charNumber < shortestStr; charNumber++)
	{
		char commonChar = strs[0][charNumber];
		for (byte strNumber = 1; strNumber < strs.Length; strNumber++)
		{
			if (strs[strNumber][charNumber] != commonChar)
			{
				return result;
			}
		}

		result += commonChar;
	}

	return result;
}
```

## Experience

### Linnworks
#### Senior Software Engineer
#### March 2017 - Now

* Was a key member and led team during a long-term migration project. Heavily involved in creating new core for a second version of SkuVault backend. 
Worked extensively with EventStore to integrate it and developed different tools for this integration. 
This migration increased stability, scalability, and performance.
* Developed and integrated library to work with Azure Key Vault, Azure App Configuration, and Azure Feature Management. 
This allowed maintaining private information securely in one place and releasing code more granularly and faster. 
* Developed library to work with the Azure Blob Storage and migrated a microservice from FDB to Microsoft Azure Blob Storage, 
simplifying the service and increasing supportability, and reused this library in other microservices.
* Migrated Amazon and BigCommerce integrations to new API using modern technologies and practices to increase stability and supportability. 
Developed approach will be applied to other integrations.
* Developed US GTM feature that introduced account types with different feature sets, allowing the business to enter new prices.
* Developed 3PL feature allowing clients to share inventory among each other.
* Developed Bins and Lots features that allowed our clients to better track inventory in the warehouse.

### Linnworks
#### Software Developer
#### January 2014 - March 2017

* Developed and maintained SkuVault integration with Amazon, NetworkSolutions, Volusion, 3dCart, BigCommerce, OpenCart, Shopify, ShopVisible, Teapplix.
* Worked as a full-stack developer on new features.

### INOSTUDIO
#### Software Developer
#### March 2011 - January 2014

At the Inostudio, I worked on a few small and big projects. The last project I worked on was Mojo.
* Worked on new features for the project and maintained existing code.
* Developed a system for monitoring landing pages. This system was helping us to know about problems on every landing page in time.

## Education

### Taganrog State Radio Technical University 
#### Bachelor's degree, Computer Science
#### September 2007 - February 2011

### Armavir State Engineering College
#### Software of computer and automated systems
#### September 2003 - September 2007

## Language
Russian (Native), English - Intermediate(B1)
