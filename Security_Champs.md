## Security Champions: An integral part of modern Software Development teams


### State of Security

In a perfectly mature software development world setup, teams would have dedicated infosec guys lying around helping software engineers and developers build more effective, usable and secure applications. A huge development team would ideally have security people helping them review secure code, understand vulnerabilities reported by automated security scanners, review security design solutions, review security requirements against business requirements for the application, go through user stories against evil stories, and train engineers to write code securely. Unfortunately, not every organization has the huge resources of Fortune 500 companies to have this perfect setup. We can all dream about it. Well, even most of the Fortune 500 companies don't have this scenario that was just mentioned; instead, they usually have a development team, QA team, and product or sales team. Security comes last on the list - and may not even make the list of priorities for most of them! The cyber threat landscape is a fast moving world and keeping up with threats would overwhelm developers considering their main roles building software.

For most companies, product development of an application is the most important part of building software as it is the one that brings revenue. When they get some spare money to burn they start looking at security for either a bunch of reasons: the investor insists, industry regulations, paranoia about security breaches, attract more investors and clients, and last which is the least is security consciousness. 

Now you want to look at security but you don't have the means to hire the top AppSec talents. And even if you have the resources you might be looking at the wrong skill sets needed by your organization. How do you deal with this dilemma? This is where Security Champions come in play. 


### Security Champions

Security Champions are traditionally AppSec engineers who had experience and expertise to bring and incorporate security practices in an organization's development process. These days the definition of this term has evolved not only AppSec engineers, but mainly Software Developers who are interested in application security but do not have the skills are the ones being groomed to be Security Champions. In a development team usually due to some constraints and skills gap in AppSec, organizations tend to look for Security Champions internally and support him to lead learning and teaching others secure development practices. Security Champions could be coming from Devs, QA, DevOps, Architects, Managers, Engineers, Designers, or anyone interested in security really! Ideally, a Security Champion is someone who has knowledge of project internals which makes the transition of security practices smoother for the team as he will be the team's security single point of contact. Because your security champion speaks the language of developers and is intimately involved in the project, he or she can communicate security issues in a way that the development team will understand and embrace. The best part of this is by increasing the security quality of code at the development stage, you’ll reduce bottlenecks at the security review stage, giving your security team more time to work on high-value tasks. They are mostly volunteers who are interested in learning and doing security and should not be appointed - keep this in mind as we will go back to this point later. 


A perfect analogy I came up with describing Security Champions would be this scenario... Let's say AppSec Engineers speak only German language, Software Developers speak only Italian language. They are both speaking different languages, now somewhere along the population (company of 100 employees), there is a 1% of the population who is the Security Champion that can speak both German and Italian languages. He then takes the reports the AppSec Engineers (written and spoken in German) and interprets it, goes to the Software Developers (to translate the German words to Italian words so that Devs will be able to digest it). They are the bridge between two different groups of people.   

`[An illustration would be funny for this] [Insert some funny sketch/cartoon here AppSec Engineer -> Security Champion -> Devs) and then (AppSec Engineer <- Security Champion <- Devs)]`

### Roles and Responsibilities of Security Champions

Now that the organization has identified a Security Champion, what's next and what would he do? Defining the roles of the Security Champion would be the next step after noticing his gravity towards security. Since there are not much good Application Security Engineers around, the Security Champion can help scale security through multiple teams as the AppSec Engineer mentors him. Same principle as how a Green Berets as force multipliers who train foreign rebel soldiers in the military. He would be involved in a lot of activities aside from his main role, unless the organization is kind enough to shift him totally to this role and focus on security things, then it will be the best thing for him, else he will have to juggle with his mail role and being a security champion. He would be helping his team initially and then later on other dev teams configure DAST, SAST, IAST and SCA tools, participate in threat modeling, triage security tools results, bug fixing, review user-stories in the backlog for "evil stories/abuse cases", guard security best practices, monitor/review vulnerabilities found by tools/scanners in your environment, share security knowledge, etc.

As you can see, Security Champions could be all by themselves vs. a million of security problems as mentioned, so companies must set realistic expectations from them. Oftentimes, Security Champions would be learning security as the same time with the company, but they help the company incorporate it faster and better instead of no one leading and guiding the way. Security Champions don't need to be security pros, rather they just need to act as the security conscience of the team. I am not a fan of blaming developers for every software and security flaw happening. It is not their fault always (sometimes there are lazy ones, but they are a very small fraction of software developers out there). The truth is, a good developer cares about his code and would want to fix it instead of building faulty software; they basically want to do some cool stuff with or without knowing that there could be security implications for every vulnerability found on their code. So now that the organization has an identified and working Security Champion, should companies get rid of AppSec Engineers? The answer to that is no. While Security Champions will handle the low hanging fruit and security at a code level, AppSec Engineers still take care of manual pentesting, threat modeling, identifying harder and more complex vulnerabilities, and of course grooming of Security Champions to be like them in some way or another. 

### At the end of the Day

Enable for this security endeavor of the company and the Security Champion to work there would be a few factors that are needed. Firstly, support from the organization and management must be there because without it this whole endeavor falls apart. There could be security conscious software engineers who want their applications tested but don't know how to make it more secure, thus they reach out to the management for help but if the management doesn't care then it is moot. It should be noted that business people have a huge different with engineers in the way how they view security and by talking to their language, that's how a Security Champion will do his impact into these two groups. Business people care mainly about the impact of a security issue to the company or business while developers care about fixing problems. Ultimately, security fails when business does not care, people lack knowledge, apathy, and whenever security is put always at the back burner of list of priorities to do. The cost of fixing security bugs in a business' software is exponential over time. If companies would catch security issues during early stages of development, then it is cheaper than when it is already launched and in production where hundreds of thousands to millions of users which would be affected by those security issues. As such, Security Champions help lower this cost as time goes on. 


### Related Links and Further Reading


"Definition of Security Champions":
  - https://owasp.org/www-pdf-archive/OWASP_Bucharest_2017_Antukh.pdf
  - https://resources.infosecinstitute.com/what-is-a-security-champion-definition-necessity-and-employee-empowerment/#gref
  - https://hella-secure.com/security-champions/
  
"9 Things Application Security Champions Need to Succeed": 
  - https://www.darkreading.com/careers-and-people/9-things-application-security-champions-need-to-succeed/d/d-id/1336827

"How to Turn Developers into Security Champions": 
  - https://www.veracode.com/sites/default/files/pdf/resources/ipapers/how-to-turn-developers-into-security-champions/index.html




