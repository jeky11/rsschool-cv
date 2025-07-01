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
