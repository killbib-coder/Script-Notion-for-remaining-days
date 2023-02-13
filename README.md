# Script-Notion-for-remaining-days
Here is a script to display the remaining days in the Notion calendar 

```if(prop("📈 Status") == "Fait", "👏 Bravo !", if(prop("Jour retard") > 0, "🚨 " + format(prop("Jour retard")) + " jours de retards", "⏳ " + format(prop("Jours restants")) + " jours restants"))```
