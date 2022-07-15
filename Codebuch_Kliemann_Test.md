# Datensatz Kliemann #
Codebuch Stand 2022-07
erstellt von dj032, ha022, fu009, sp103, tk164 

## Inhalt

- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Wir haben den Datensatz aus diversen Internetartikeln erstellt.

  
**Beziehungsnetzwerk business** 

Das Edge-Attribut *relationship* beschreibt die Art der Geschäftsbeziehung: Firmeninhaber, Kooperation oder Investoren/Gesellschafter.



**Umgang mit fehlgenden Werten**

Fehlende Werte werden nicht erfasst.

# EDGE-Attribute

**id**  

(eindeutige Codierung des Knoten)   
entspricht dem Gekürzten Namen der Firmen/Kooperationspartner 

**from**

von Person zu Firma oder von Person zu Person

**to**

zur Firma oder Person

**weight**  

Anzahl der Jahre der Kooperation
Eine 2022 begonnene Kooperation/Firma besizt den weight = 1
Eine 2021 begonnene Kooperation/ Firma besitzt den weight =2
usw.

**relation**

Art der Beziehung:
1 steht für die eigenen Firmen, 2 für einen Kooperationspartner, 3 für einen Investor, 4 für einen Gesellschafter.


# NODE-Attribute  
  
**id**  

Identische ID wie aus der edgelist zur Identifikation der Knoten. 

**name**

Name der Knoten

**periodstart**

Anfang der Kooperationszeit/Investition bzw. Firmengründung seiner eigenen Unternehmen

**periodend**

Ende der Kooperationszeit

**location**

Wohnort der Person oder Standort der Firma

**sex**

Geschlecht der Personen
1=männlich
2=weiblich
3=divers

##
