Thank you for attending the Moneyball session at Data Saturday Munich 2024. Below you will find some further documentation and resources which were mentioned or used in the presentation.

### 👨‍💻 Get In Touch
- Email: abhi.jayanty@quorum.co.uk
- LinkedIn: https://www.linkedin.com/in/abhinav-j-06253714b
- Sessionize: https://sessionize.com/abhi-jayanty/

---
###  📊 Demo Content

**Azure Data Explorer clusters can be created for free, without an Azure subscription!** I would HIGHLY recommend doing this to start experimenting with ADX and KQL: https://learn.microsoft.com/en-us/azure/data-explorer/start-for-free-web-ui

You will be able to run the Monza23.kql queries against a Kusto DB created within Synapse Real-Time Analytics in Fabric or an Azure Data Explorer cluster, with local file ingestion used with the CSV provided. 
- Information on how to do this can be found here: https://learn.microsoft.com/en-us/azure/data-explorer/get-data-file

The queries for Entra ID log analysis have been provided under EntraID.kql, however the associated data is not available as this contains logs from a private tenant provided for private use. Entra ID logs can be extracted from your own tenant and used with the queries provided, so long as the table name which you have given your Kusto/ADX DB is amended. 
- Information on how to extract Entra ID sign-in logs can be found here: https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-download-logs

I have included the .pbix file for the example PowerBI telemetry dashboard which I showed in the demo.

---

## 📖 Further Resources & Reading:

- 📈 F1 Telemetry with ADX - Microsoft:
  - https://techcommunity.microsoft.com/t5/azure-data-explorer-blog/f1-telemetry-analysis-with-azure-data-explorer-adx/ba-p/3283911
  - This blog post written by Anshul Sharma details how you can set up an export of F1 data from the game and use the PaaS Azure Data Explorer product to ingest the data and output to Grafana for real-time visualisation.
 
- 🏎️ Faster data, faster car: How BWT Alpine F1 Team aims to lead the Formula 1 tech race - Microsoft:
  - https://news.microsoft.com/source/features/digital-transformation/faster-data-faster-car-how-bwt-alpine-f1-team-lead-formula-1-tech-race/
  - This post details how Microsoft's partnership with the Alpine F1 Team helps the team gain the edge and quickly make crucial decisions during an F1 race using data in real-time.
 
- 🥇 Kusto Detective Agency:
  - https://detective.kusto.io/
  - A resource for learning Kusto Query Language through challenges and problem solving

- 📚 ADX-in-a-day:
  - https://github.com/Azure/ADX-in-a-Day
  - Free workshop materials on how to use ADX and KQL to analyse example log data
 
- 😻 Fabric CAT team demos:
  - https://github.com/microsoft/FabricCAT
  - Content built for the community by the Customer Advisory Team at Microsoft for Fabric Real-Time Analytics
 
- ⚽ "Farewell James Milner, Liverpool's Mr Everything" - The Athletic (paywalled article):
  - https://theathletic.com/4531487/2023/05/24/james-milner-liverpool-mr-everything/
  - This article by The Athletic uses the Opta visuals shown on James Milner to show his effectiveness on the pitch while playing for Liverpool

- ⚽ "Johan Cruyff: The Tactical Masters" - The Coach's Voice:
  - https://www.coachesvoice.com/johan-cruyff-barcelona-coach-tactics-pep-guardiola
  - Analysis on Johan Cruyff's tactical formations as a football manager

- ⚽ "StatsBomb Icons: Johan Cruyff" - StatsBomb:  
  - https://statsbomb.com/articles/soccer/statsbomb-icons-johan-cruyff/
  - Further analysis on Johan Cruyff as a player (not mentioned in presentation at DS Munchen)
