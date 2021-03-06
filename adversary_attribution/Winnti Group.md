# Winnti Group
## Description
[[Group/G0044|Winnti Group]] is a threat group with Chinese origins that has been active since at least 2010. The group has heavily targeted the gaming industry, but it has also expanded the scope of its targeting. Though both this group and [[Group/G0001|Axiom]] use the malware [[Software/S0141|Winnti]], the two groups appear to be distinct based on differences in reporting on the groups' TTPs and targeting.[[CiteRef::Kaspersky Winnti April 2013]][[CiteRef::Kaspersky Winnti June 2015]][[CiteRef::Novetta Winnti April 2015]]
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Defense Evasion |                  Rootkit            |  |         [[Group/G0044 Winnti Group]] used a rootkit to modify typical server functionality.[[CiteRef::Kaspersky Winnti April 2013]] |                                                      
| Persistence Privilege Escalation | New Service        |   Winnti | [[Software/S0141 Winnti]] sets its DLL file as a new service in the Registry to establish persistence.[[CiteRef::Microsoft Winnti Jan 2017]] |                                     
| Discovery |                        Process Discovery  |  |         [[Group/G0044 Winnti Group]] looked for a specific process running on infected servers.[[CiteRef::Kaspersky Winnti April 2013]] |                                                  
| Defense Evasion Execution |        Rundll32           |   Winnti | The [[Software/S0141 Winnti]] installer loads a DLL using rundll32.[[CiteRef::Microsoft Winnti Jan 2017]] |                                                                        
| Defense Evasion |                  Code Signing       |  |         [[Group/G0044 Winnti Group]] used stolen certificates to sign its malware.[[CiteRef::Kaspersky Winnti April 2013]] |                                                               
| Defense Evasion |                  Masquerading       |   Winnti | A [[Software/S0141 Winnti]] implant file was named ASPNET_FILTER.DLL, mimicking the legitimate ASP.NET ISAPI filter DLL with the same name.[[CiteRef::Microsoft Winnti Jan 2017]] |



