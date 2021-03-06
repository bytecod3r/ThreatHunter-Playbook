# Winnti Group
## Description
[[Group/G0044|Winnti Group]] is a threat group with Chinese origins that has been active since at least 2010. The group has heavily targeted the gaming industry, but it has also expanded the scope of its targeting. Though both this group and [[Group/G0001|Axiom]] use the malware [[Software/S0141|Winnti]], the two groups appear to be distinct based on differences in reporting on the groups' TTPs and targeting.Kaspersky Winnti April 2013Kaspersky Winnti June 2015Novetta Winnti April 2015
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Defense Evasion |                  Rootkit            |  |         [[Winnti Group]] used a rootkit to modify typical server functionality.Kaspersky Winnti April 2013 |                                                   
| Persistence Privilege Escalation | New Service        |   Winnti | [[Winnti]] sets its DLL file as a new service in the Registry to establish persistence.Microsoft Winnti Jan 2017 |                                     
| Discovery |                        Process Discovery  |  |         [[Winnti Group]] looked for a specific process running on infected servers.Kaspersky Winnti April 2013 |                                               
| Defense Evasion Execution |        Rundll32           |   Winnti | The [[Winnti]] installer loads a DLL using rundll32.Microsoft Winnti Jan 2017 |                                                                        
| Defense Evasion |                  Code Signing       |  |         [[Winnti Group]] used stolen certificates to sign its malware.Kaspersky Winnti April 2013 |                                                            
| Defense Evasion |                  Masquerading       |   Winnti | A [[Winnti]] implant file was named ASPNET_FILTER.DLL, mimicking the legitimate ASP.NET ISAPI filter DLL with the same name.Microsoft Winnti Jan 2017 |



