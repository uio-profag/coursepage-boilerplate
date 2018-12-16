# coursepage-boilerplate
Boilerplate for creating ProFag course pages

`index.md` inneholder forsiden

Resten av innholdet legges i `pages` (og underdirectories). Sider med `sidebar_link=true` kommer opp i venstremenyen. Resten må eksplisitt lenkes opp fra andre sider for å kunne navigeres til. 

Man kan legge inn enten markdown-dokumenter eller jupyter notebooks. I tilfellet jupyter notebook vil denne automatisk konverteres til markdown på travis CI før publisering av nettsiden. 

For at integreringen med github deployment skal fungere trenger man å legge til en github token i Travis. 