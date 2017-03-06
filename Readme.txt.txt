#
# SOCIALAPP
#
#Copyright (c) 2017, Konstantinos Tsiamis
#All rights reserved.
#
#----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Dateiname: README.txt
#Version:   1.0
#Projekt:   socialapp 
#Erstellt:  Konstantinos Tsiamis <4tsiamis@informatik.uni-hamburg.de>
#Funktion:
#Bemerkung:
#-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#

#
#-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Modifikationen:
#
#

#-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Beschreibung: Bei dem Eclipse-Projekt handelt es sich um eine RESTful Web Services API mit JERSEY framework. 
# Diser Service ermöglicht plattformunabhängige Datenaustausch zwischen Systemen.
# Es dient als Schnittstelle für den externen Zugriff der mobilen App und anderen WebApplikationen.
#-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Die Haftung
#Die Installation des RESTful Web Services API geschieht auf eigene Gefahr. Für potenzielle Probleme nach der Installation wird keine Haftung übernommen. 

#Es gibt keine Garantie für Bug-Freiheit!
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Die Kompatibilität: 
#Für die Installation ist ein MySQL Server, Eclipse, ein Apache Tomcat Server und die Datenbank sozialraum_db_neu erforderlich
#Bemerkung: Im Ordner befindet sich die Dumpdatei der Datenbank. Diese Datei kann in MySql Workbench importiert werden.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 
#Die Installation:
#Die Installation erfolgt über zwei Wege. 
#Der erste Weg: 1. Gehen Sie auf die Seite http://ltannotation.informatik.uni-hamburg.de/
#2.Klicken Sie auf "manager webapp" und geben sie ihren Benutzernamen und ihr Passwort ein.
#3.Klicken Sie Durchsuchen im Menü "Deploy" bei dem Unterpunkt "WAR file to deploy" und suchen sie in dem Ordner die socialapp.war file und laden sie hoch.
#4.Klicken Sie auf Deploy
#Hinweis: Sie müssen schauen, ob eventuell eine datei die den selben Namen hat erstmal auf undeploy klicken, damit sie die socialapp.war file hochladen koennen.
#
#Der zweite Weg: 1.Öffnen Sie ihr Eclipse und klicken sie unter Menüpunkt "File" die Option "Open Projects from File System" und suchen nach der ZIP-Datei socialapp und klicken sie auf öffnen
#2.Anschließend erscheint das Projekt "socialapp" , klicken mit der rechten Maustaste auf das Projekt, wählen sie das "Run as" und dann "Run on Server".
#3.Waehlen sie ihren Tomcat Server aus und klicken sie auf ok.
#4.Ihr Projekt ist dem Server verbunden.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Die Deinstallation:
#Wenn sie den ersten Weg genommen haben, gehen in dem Feld, wo sich die socialapp befindet und klicken auf "undeploy".
#Für den zweiten klicken mit der rechten Maustaste auf das Projekte und dann auf "delete".
-------------------------------------------------------------------------------------- 
#Die Lizenz
#Der Entwickler der SOCIALAPP räumt jedem Nutzer uneingeschränkte Benutzung, Vervielfältigung und Weitergabe dieses Projektes ein.
#Dieses Projekt verwendet keine urheberrechtlich geschützten Materialien, die ohne Kenntnis des Besitzers integriert worden sind.
#Was nicht gestattet wird:
# Namensänderung und die folgende Veröffentlichung der SOCIALAPP oder einer Abart der SOCIALAPP.
# Editieren oder entfernen des Entwicklers aus den Dateien oder dem Installationsprogramm.
# Modifikation der SOCIALAPP ohne Kenntnis der Entwickler mit anschließender Veröffentlichung.
#Was gestattet wird:
#Sie können an dem Inhalte der SOCIALAPP Veränderungen vornehmen, vorausgesetzt, der ursprüngliche Entwickler und Rechteinhaber erhebt keinen Einspruch.



